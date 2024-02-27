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
image = cv2.imread('Jais.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2GRAY)
cv2. imshow('gray_scale', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
***The image should be Converted to HSV :***
```
import cv2
image = cv2.imread(''Jais.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2HSV)
cv2. imshow('my_img', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
***Display the H, S and V planes :***
```
import cv2
image=cv2.imread("Jais.jpg",1)
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
![Screenshot 2024-02-27 105213](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/2f857edf-4ae9-4af9-8a46-b6e865d388f6)


#### GRAY SCALE :
![Screenshot 2024-02-27 105253](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/8a65e429-cfd1-4920-9e2c-c34e198df35e)



#### HSV :




#### HUE :
![Screenshot 2024-02-27 105427](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/5a296f4f-336c-4de0-9f34-47fc38cd57c8)


#### VALUE :
![Screenshot 2024-02-27 105500](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/ce8e38ca-2262-4990-bae5-b45f4ca35a5c)


#### SATURATION :
![Screenshot 2024-02-27 105437](https://github.com/Jaiganesh235/workshop-dipt-1/assets/118657189/4f532e34-10c8-4449-9156-a81b56f14052)


## RESULT :
Therefore working on images has been successfully implemented.






