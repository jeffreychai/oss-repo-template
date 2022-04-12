# Lab 11 Report - TensorFlow

## Checkpoint 1

Screenshot of pop-up:

![check1_img](check1.PNG)

## Checkpoint 2

Screenshot of plot:

![check2_img](check2.PNG)

## Checkpoint 3

In order to perform the operations of grayscale, rescaling to 28 x 28, inverting, and scale between 0 and 1, I used the libraries of Image, ImageOps from PIL. I applied these operations to each image.

Original Image #1:

![clothes1](clothes1.png)

Transformed Image #1 (Grayscale):

![transformed_clothes1](grey_clothes1.PNG)

Transformed Image #1 (All):

![transformed_clothes1](after_clothes1.PNG)

Original Image #2:

![clothes2](clothes2.png)

Transformed Image #2 (Grayscale):

![transformed_clothes2](grey_clothes2.PNG)

Transformed Image #2 (All):

![transformed_clothes2](after_clothes2.PNG)

Original Image #3:

![clothes3](clothes3.png)

Transformed Image #3 (Grayscale):

![transformed_clothes3](grey_clothes3.PNG)

Transformed Image #3 (All):

![transformed_clothes3](after_clothes3.PNG)

Test Prediction Accuracy (Grayscale):

![check3_img](results.PNG)

Test Prediction Accuracy (All):

![check3_img](results2.PNG)

Conclusion:

#1 is a dress shirt, but it was classified as coat.
#2 is a shoe, but it was classified as bag.
#3 is pants, but it was classified as trouser.

Therefore, there are inaccuracies. 
