# Face recognition with python
Face recognition in real time.
This is a simple Python project for face recognition using the [dlib](http://dlib.net/) face recognition library. The project allows for face recognition on images and in real-time using a webcam.

## How it Works

The project works as follows:

1. Upon program startup, the face image database is loaded.
2. The program then opens an image or turns on the webcam and starts recognizing faces in the image or video stream.
3. If the recognized face is in the database, the program grants access, such as opening a door. If the face is not in the database, the program denies access.


## Dependencies
The project uses the following libraries:
1. face_recognition
2. dlib

![rec_face_id](https://user-images.githubusercontent.com/78686988/226090728-9750415c-310b-47a8-b74c-f28853fbc4e1.jpg)
