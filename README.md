# Working-on-Images:

## WORKING ON IMAGES :
### NAME : Keerthana S
### REG NO : 212222230066

## INSTRUCTION :
1. The image should be a plant, Tree, flower or building.

2. The filename should be username.jpg.

3.The image should be Converted to gray scale and HSV

4. Display the H, S and V planes

## PROGRAM :
```
import cv2
image=cv2.imread('flower.jpg',1)
image=cv2.resize(image,(400,250))
cv2.imshow('pic',image)
cv2.waitKey(0)
```

### The image should be Converted to gray scale :
```
import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2GRAY)
cv2. imshow('gray_scale', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
The image should be Converted to HSV :

import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2HSV)
cv2. imshow('my_img', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
Display the H, S and V planes :

import cv2
image=cv2.imread("flower.jpg",1)
image= cv2.resize(image,(400,250))
image=cv2.cvtColor(image,cv2.COLOR_RGB2HSV)
H,S,V=cv2.split(image)
cv2.imshow('Hue',H)
cv2.imshow('Saturation',S)
cv2.imshow('Value',V)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
OUTPUT :
IMAGE :
![pic](https://github.com/Keerthanasampathkumar/Working-on-Images/assets/119477890/962fe6f3-25ef-4d96-b1ff-a3052b9eb079)


GRAY SCALE :
![gray_scale](https://github.com/Keerthanasampathkumar/Working-on-Images/assets/119477890/638a766f-8bb6-490c-b29b-4154245eaefa)


HSV :
![my_img](https://github.com/Keerthanasampathkumar/Working-on-Images/assets/119477890/3208854a-3c52-475d-9205-20705d59b22b)


HUE :
![Hue](https://github.com/Keerthanasampathkumar/Working-on-Images/assets/119477890/9089f1b6-d001-4eb9-a27a-c64668270f71)


VALUE :
![Value](https://github.com/Keerthanasampathkumar/Working-on-Images/assets/119477890/620ca594-b46a-4317-9375-abfc392e3cad)


SATURATION :
![Saturation](https://github.com/Keerthanasampathkumar/Working-on-Images/assets/119477890/c8ea2904-429c-49dd-9d04-99e19ed39453)


RESULT :
Therefore working on images has been successfully implemented.
