In this project there are two program.

The aim of this project to detect Facial landmarks such as:
- Eyes
- Eyebrows
- Nose
- Mouth
- Jawline

How it works? First, We use the dlib package to detect the faces in the images/videos 
(using Histogram of Oriented Gradients and Linear Support Vector Machines) then feed the
results to the pre-trained facial landmarks model (Ensemble of regression trees) (68 points)
and the program will output the image highlighting the facial landmarks. 

To run the first program, type the first/second/third command to run the program on a 
pre-saved image.

To run the second program, type the fourth command to run the program on the laptop
camera.

Thanks to pyimage search. 

To download the pre-trained facial landmark detector:
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2