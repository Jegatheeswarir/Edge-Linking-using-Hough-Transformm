# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.

## Output

### Input image and grayscale image

<img width="454" height="331" alt="image" src="https://github.com/user-attachments/assets/656a03ab-1035-4b3f-b692-90fd4404ee13" />

### Canny Edge detector output

<img width="521" height="348" alt="image" src="https://github.com/user-attachments/assets/e287b906-2296-44d2-9ec7-46c923b58fb7" />

### Display the result of Hough transform

<img width="458" height="339" alt="image" src="https://github.com/user-attachments/assets/ebfc82b5-7198-42b5-9d22-0157f842e191" />
