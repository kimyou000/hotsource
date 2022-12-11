# hotsource
---
### Project Overview

##### ENG
Find the Wrong Picture Project
The Find the Wrong Picture project finds different parts of the two images.
And it also has other additional functions.

##### KR
틀린 그림 찾기 프로젝트


## Summary    
 The similarity of each image is mainly measured **using the cv2 library** and other parts are extracted.   
 
### Function_example       
 - Cut_Image_Circle()   
 - Diff_Image()   
 - image_similarity()    

### Demo 
 - image
 - ![image](https://user-images.githubusercontent.com/88136923/206916602-b632fea6-872b-4a25-9c76-7f30f75e75d5.png)

 - video

### Package Used
```
import cv2
import numpy as np
import matplotlib.pylab as plt
from skimage.metrics import structural_similarity as compare_ssim
import imutils
from PIL import Image
from PIL import ImageChops
```

### How to execute




<hr>   

### Reference
[link 1](https://bkshin.tistory.com/entry/OpenCV-9-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EC%97%B0%EC%82%B0)    
[link 2](https://m.blog.naver.com/codinglab9807/222711897434)    
