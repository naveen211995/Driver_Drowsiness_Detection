# Driver Drowsiness Detection System using OpenCV and Keras
A countless number of people drive on the highway day and night with lack of sleep and many lead to accidents when feeling sleepy.
So to prevent these accidents we will be building a system using Python, OpenCV and Keras which will alert the driver when he/she feels sleepy.

---
In this project we will be using OpenCV to detect images from webcam and feed them into Deep Learning model which will classify whether the person's eyes are Open or Closed.
Below are the steps of how we deal with the projects:
1. Take image as input from webcam.
2. Detect the face in the frame and create a Region of Interest.
3. Detect the eyes from ROI and then feed it to the classifier.
4. Classifier will categorize whether the eyes are Open or Closed.
5. Then we will calculate the score to check whether the person is drowsy.

---
## Pre-requisites:-
**OpenCV:** For Face and Eye detection
**Tensorflow:** Keras using Tensorflow as backend
**Keras:** To build our classification model
**Pygame:** To play alarm sound

---
## Files:
Download the zip file with the name Drowsiness_Detection and extract the file in your system.
The contents of the zip file are as below:
**Haar cascade files** folder consists of xml files that are needed to detect objects from the image.
**Model** folder contains our model file **cnnCat2.h5** which was trained on CNN.

---
## Steps to perform:
**Step-1:  ** Take image as input from the webcam.
**Step-2:  ** Detect Face in the image frame and create Region of Interest(ROI)
**Step-3:  ** Detect Eyes from ROI and feed it to classifier
**Step-4:  ** Classifier will classify whether eyes are Open or Closed.
**Step-5:  ** Calculate score to check whether person is feeling Drowsy or Not.
