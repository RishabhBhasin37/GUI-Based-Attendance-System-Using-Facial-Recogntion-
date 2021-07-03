# FaceRecognition



Technology used (Libraries):
- tkinter as tk
- tkinter import Message, Text
- cv2, os
- shutil
- csv
- numpy 
- from PIL import ImageTk,Image
- pandas 
- datetime
- time
- from itertools import count
- from functools import partial

Here we were working on Face recognition based Attendance Management System by using OpenCV(Python). One can mark their attendance by simply facing the camera. 

How it works :

1. Run only the "GUI Test-1".py file.
2. Enter the "username" and "password" as "admin" and "admin@123" respectively and press "Login".
3. Fill in the required details in the gui that opens up.
4. Click on "Take Images" to register yourself.
5. Click on "Train Images" to train the dataset.
6. Click on "Detect" to recognize the image and mark the attendance.

Note : -Please make sure you are not sitting in a very dark environment.
       -While training give different profiles of your face for better training
       -Wait patiently, till the camera opens up, sometimes takes a bit of time to open up the camera depending open the computers computational power
       -Wait patiently till it train the images. Huge no of images takes a bit of time to train.
   
Additional Steps:
    - "ImagesUnknown" folder contains the images who's faces were not recognized
    - "StudentDetails" folder consists the dataset of all the students which stores the student's Name and ID
    - "Attendance" folder consists of all the attendance taken so far  

Thanks:
Rishabh Bhasin(2K18/CO/290)
Samvit Mukherjee(2K18/CO/315)
Rishabh Jaiswal(2K18/CO/292)