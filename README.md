# opencvcontrib
Modified files of xfeatures2d in which opening and closing sampling pattern using FREAK is added.

mreako.cpp and mreakc.cpp are source files which has to be added in xfeatures2d module of OpenCV version 3.3.1.

xfeatures.2d is the modified file where this two classes are added.

Follow the following instrustions to add this modules :
1) Download opencv and opencv_contrib from Github as mentioned on https://www.learnopencv.com/install-opencv3-on-ubuntu/.
2) Add mreako.cpp and mreakc.cpp in following location "opencv_contrib\modules\xfeatures2d\src" in opencv_contrib folder after downloading. 
3) Replace existing xfeatures.2d in "opencv_contrib\modules\xfeatures2d\include\opencv2" by our file.
4) Now build OpenCV as mentioned on https://www.learnopencv.com/install-opencv3-on-ubuntu/.

NOTE - This files are for OpenCV version 3.3.1

We have changed the sampling pattern in MREAK which is different than that of FREAK which is implemented followed by opening and closing of images.

Following is a simple example :

1) Image 1

![image 1](example/a1.jpg)

2) Image 1 opened

![Image 1 opened](example/a1open.jpg)

3) Image 1 closed

![Image 1 closed](example/a1close.jpg)

4) Image 2

![image 2](example/a2.jpg)

5) Image 2 opened

![Image 2 opened](example/a2open.jpg)

6) Image 2 closed

![image 2 closed](example/a2close.jpg)

7) All 1498 FREAK keypoints

![All 1498 FREAK keypoints](example/all_1498.jpg)

8) Best FREAK keypoints

![Best FREAK keypoints](example/freak.jpg)

9) Best opened keypoints in MREAK

![Best opened keypoints in MREAK](example/opened_keypoints.jpg)

10) Best closed keypoints in MREAK

![Best closed keypoints in MREAK](example/closed_keypoints.jpg)

11) Both keypoints combined

![Both keypoints combined](example/both.jpg)
