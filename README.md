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

<img width="1448" height="416" alt="image" src="https://github.com/user-attachments/assets/39be5c67-1e8e-4960-b4b8-39eb8ea5fff0" />
<img width="1257" height="281" alt="Screenshot 2025-11-13 154846" src="https://github.com/user-attachments/assets/8b1678a3-5838-496a-a096-a4c6a979e1ad" />
<img width="1371" height="350" alt="image" src="https://github.com/user-attachments/assets/55d855bd-28a6-4f21-b5fa-ae41cd934439" />
<img width="1251" height="370" alt="image" src="https://github.com/user-attachments/assets/fde554ff-fae2-403a-a418-2d4c84759bda" />


