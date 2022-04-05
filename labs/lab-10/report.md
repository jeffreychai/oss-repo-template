# Lab 10 - Databases

## Checkpoint 0

I decided to analyze the incident with the Faker.js and Color.js libraries.

Link to blog entry: https://github.com/jeffreychai/oss-repo-template/wiki/Open-Source-Attack-(Week-10)

## Checkpoint 1: Install CouchDB

Localhost Message:
![image](check1.PNG)

Now we know that the database is working properly on the local machine.

## Checkpoint 2: Quick Tour

Need to login:

![image](fauxton-prelogin.PNG)

![image](fauxton-login.PNG)

Curl Example (Terminal):

![image](check2.PNG)

![image](first-document.PNG)

![image](first-query.PNG)

Query 1

![image](1998-query.PNG)

Query 2

![image](second-query.PNG)

Start to Duplicate

![image](replication-schedule.PNG)

Fully Duplicated:

![image](replication-same-size.PNG)

## Checkpoint 3: API Tutorial

Server

![image](check-server.PNG)

Albums-Backup

![image](check3-albums-backup.PNG)

Add First Document:

![image](check3-latest-revision-number.PNG)

Database & Revisions:

![image](database_revision.PNG)

Documents in Detail:

![image](database_add.PNG)

Attachments:

![image](attachment.PNG)

Visit URL on Browser:

![image](artwork-screenshot.PNG)

Albums-Replica (Replication):

![image](album-replica-works.PNG)

![image](access_again.PNG)

## Checkpoint 4

### 4.1 - Year Query

![image](check4_1.PNG)

### 4.2 - Title Query

![image](check4_2.PNG)

### 4.3 - New Index

![image](check4_3.PNG)

### 4.4 - Run Title Query Again

![image](check4_4.PNG)

For this part, I adapted the given command to create an index, and then reran the query.
Thus, there is no longer a warning since the query is optimized.
