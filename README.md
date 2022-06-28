# Real-Time-Drowsiness-Detection

### Descriptions

This code may detect your eyes and inform you if you are asleep using OpenCV.

### Applications
This can be utilized by individual who frequently drive or work for extended periods of time, which may result in an accident.

### Requirements for the Code
The example code is written in Python.

### Dependencies
Import cv2, Import imutils, Import dlib, Import scipy.

### Description
Using a real-time video feed, a computer vision system can detect driver tiredness automatically. If the driver looks to be drowsy, an alert will sound.

### Algorithm
Six (x, y)-coordinates are used to represent each eye, beginning at the left corner and moving clockwise around the eye. If the Eye Aspect ratio is less than 0.18 in 3 consecutive frames, an alert is triggered.

EAR=  (||p2-p6||+||p3-p5||)/(2||p1-p4||)

### Execution
To run code, type: python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav

### Result
https://user-images.githubusercontent.com/75069789/176060337-c530914a-7fb8-4093-8e59-487d69482286.mp4

### References
Adrian Rosebrock, PyImageSearch Blog
