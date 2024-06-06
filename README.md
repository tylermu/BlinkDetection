# Blink Detection

A real-time facial recognition program to track blinkrate.

## Description

This Python-based program tracks an individuals blinkrate through either a live-video on something like a webcam, or from a pre-recorded video. The program will open a dialog window to show the video being 
presented while a counter tracks the number of blinks in the top right, and displays green "Blink Detected" text whenever the program detects a blink. Note: This program is best used when the face is in full view infront of 
the camera and the face is well lit. 

## Getting Started

### Dependencies

* This program should run on any python compiler
* All the libraries necessary for running the program are listed at the top of BlinkDetection.py. If these do not download automatically when the program is run, please use your compilers command to install a new library and insert the name of each library into the download command. 

### Installing

* To download the program, download BlinkDetection.py at https://github.com/tylermu/BlinkDetection/blob/main/BlinkDetection.py
* You will also need a .dat file containing the map for the facial landmarks which can be downloaded here: https://github.com/italojs/facial-landmarks-recognition/blob/master/shape_predictor_68_face_landmarks.dat

### Executing program

* Executing the program is as simple as clicking the run button, assuming all libraries have been installed. Refer to the dependencies section above for troubleshooting these libraries.

## Authors

Contributors names

* Tyler Muchow
* Cameron Doffing


## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [GeeksForGeeks](https://www.geeksforgeeks.org/eye-blink-detection-with-opencv-python-and-dlib/)
