all: static_block dynamic_block

clean:
	rm -rf bin/

program.o: program.c
	cc -c program.c -o program.o

block.o: source/block.c
	cc -fPIC -c source/block.c -o block.o

static_block: program.o libstatic.a
	cc -o static_block program.o libstatic.a

dynamic_block: program.o libshared.so
	cc program.o libshared.so -o dynamic_block -Wl,-rpath .

libstatic.a: block.o
	ar -qc libstatic.a block.o
	
libshared.so: block.o
	cc -shared -o libshared.so block.o