# DIPT-workshop-1:
## WORKING ON IMAGES :
#### NAME : S.JAIGANESH
#### REG NO : 212222240037

## AIM:
   To convert the given image into grayscale and HSV.

## INSTRUCTIONS  :
1. The image should be a plant, Tree, flower or building.

2. The filename should be username.jpg.

3. The image should be Converted to gray scale and HSV

4. Display the H, S and V planes

## PROGRAM :

```
import cv2
image=cv2.imread('Jais.jpg',1)
image=cv2.resize(image,(400,250))
cv2.imshow('pic',image)
cv2.waitKey(0)

```
***The image should be Converted to gray scale :***
```
import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2GRAY)
cv2. imshow('gray_scale', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
***The image should be Converted to HSV :***
```
import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2HSV)
cv2. imshow('my_img', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
***Display the H, S and V planes :***
```
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
## OUTPUT :
#### IMAGE :
![Screenshot 2024-02-27 104038](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/ab37b8c7-13cd-4ed5-85a7-fe0b5d279a15)

#### GRAY SCALE :
![Screenshot 2024-02-27 104057](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/6cfbd822-f332-43a0-b74e-b8897e475c8c)


#### HSV :
![Screenshot 2024-02-27 104105](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/b1aff30e-b6ed-41e9-a298-f6953b70f3e3)


#### HUE :
![Screenshot 2024-02-27 104113](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/dac43204-eae2-4862-ab79-7e93c902f15a)


#### VALUE :
![Screenshot 2024-02-27 104132](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/946a76ff-110e-4b05-bae0-f4dedf90c6d5)


#### SATURATION :
![Screenshot 2024-02-27 104123](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/57535b44-2d5c-46e8-971b-47e865993196)


## RESULT :
Therefore working on images has been successfully implemented.






