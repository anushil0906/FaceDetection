# FaceDetection

a face detection system using c++ and openCV 


**Project DEMO**

https://github.com/user-attachments/assets/6a70847a-47c1-463a-998b-a729abad742d


**REQUIREMENTS**

OpenCV : https://opencv.org/

 **PATH**
 
set path for opencv bin in environment variables 
as 
your_opencv_dir_name\opencv\build\x64\vc14\bin


**Explaination**

A C++ application that contains OpenCV frameworks for implementing real-time facial detection. He used the Cascade Classifier class to load and apply the pre-trained Haar Cascade model (haarcascade_frontalface_default.xml), which is based on the Viola-Jones algorithm. This algorithm uses Haar-like rectangular features for figuring out human faces on the basis of edges and patterns, scanning images at multiple scales to locate regions most likely to contain faces.

This program accepts user input for image paths, processes them through the trained model, and then uses OpenCV's rectangle() function to overlay green boxes on detected faces. It demonstrated Encapsulation as Cascade Classifier is a class that encapsulates the internal data structure of the Haar Cascade model, and functions such as load("haarcascade_frontalface_default.xml") and detectMultiScale() that work on that data are part of this encapsulation process.

Then the OpenCV library provides interfaces such as imread(), imwrite(), and detectMultiScale(), which is a concept of abstraction.

The detectMultiScale() function uses polymorphism, which can be overloaded, as it can take different parameters (image, scaling factor, and min neighbors), showing compile-time polymorphism.

