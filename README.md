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


