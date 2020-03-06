# jetsonnano-face-recognition
This repository contained the code I pulled from this turorial of running face recognition algorithm on raspberry Pi https://www.pyimagesearch.com/2018/06/25/raspberry-pi-face-recognition/

You may need to recreate the dataset of face images of those people you want the machine to recognize. The given dataset includes all of my photos and my wife.

The original source code use picamera library to capture frames from the camera. However, this library does not support to work on Jetson Nano at the moment, so I have modified the code to capture frames using OpenCV package.

Happy coding!
