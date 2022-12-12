# hotsource
---
### Project Overview

##### ENG
Find the Wrong Picture Project
The Find the Wrong Picture project finds different parts of the two images.
And it also has other additional functions.

##### KR
틀린 그림 찾기 프로젝트
틀린 그림 찾기 프로젝트는 두개의 이미지의 다른 부분을 찾아주고 다른 부가적인 기능들도 가지고 있다.


## Summary    
 The similarity of each image is mainly measured **using the cv2 library** and other parts are extracted.   
 
### Function_example       
 - Cut_Image_Circle()   
 - Diff_Image()   
 - image_similarity()    

### Demo 
 - image
 - ![image](https://user-images.githubusercontent.com/88136923/206916602-b632fea6-872b-4a25-9c76-7f30f75e75d5.png)
 ![KakaoTalk_20221212_020744038](https://user-images.githubusercontent.com/88136923/207089737-9736c486-b1ae-45be-a418-66e1d82833ef.jpg)
![KakaoTalk_20221212_130215251_01](https://user-images.githubusercontent.com/88136923/207089772-b3ba625e-abe2-49f0-9ec5-f3fbf899dcad.jpg)
![KakaoTalk_20221212_130215251_02](https://user-images.githubusercontent.com/88136923/207089790-fe7b9f67-8512-46e0-904b-9c242f7def88.jpg)
![KakaoTalk_20221212_130215251_03](https://user-images.githubusercontent.com/88136923/207089798-06de7e6f-5705-4004-9c6b-b9aafdfce98d.jpg)
![KakaoTalk_20221212_130239088](https://user-images.githubusercontent.com/88136923/207089814-c87fab65-cb80-4424-9446-36355693a38d.png)
<img width="1237" alt="KakaoTalk_20221212_175350514" src="https://user-images.githubusercontent.com/88136923/207089836-b5391e96-37ac-41a9-8b70-590d68ecdc37.png">


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
