# Volume-Control
#Installing few Modules
To run the above code, the following modules need to be installed in your system. To install these, open command prompt in yous system, ans type the following command individually - 
pip install mediapipe
pip install opencv-python
pip install numpy
pip install pycaw


#About the project
This project is created in Python-3 language using OpenCV, Mediapipe and Pycaw libraries.
The uses of OpenCV, Mediapipe and Pycaw libraries in the project are as follows:
 1.) OpenCV  : It is a library of programming functions mainly for real-time computer vision. In this project it is used to detect the motion of the hand and controll the volume accordingly
 2.) Mediapipe : It is an open-source machine learning library of Google, which has some solutions for face recognition and gesture recognition, and provides encapsulation of python, js and other languages. MediaPipe Hands is a high-fidelity hand and finger tracking solution. It uses machine learning (ML) to infer 21 key 3D hand information from just one frame.
 3.) Pycaw : Python Audio Control Library

 #Working principle
 The camera in our device is used for this project. It detects our hand with points in it so as it can see the distance between our thumb finger tip and index finger tip. The distance between the points 4 and 8 is directly proportional to the volume of device.

 #Approach / Methodology
-Detect hand landmarks
-Calculate the distance between thumb tip and index finger tip.
-Map the distance of thumb tip and index finger tip with volume range. For my case, distance between thumb tip and index finger tip was within the range of 30 – 350 and the volume range was from -63.5 – 0.0.
-In order to exit press ‘Spacebar'
