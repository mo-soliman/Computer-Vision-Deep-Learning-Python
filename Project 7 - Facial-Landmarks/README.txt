In this project there is one program.

The aim of this project to detected Facial landmarks such as:
- Eyes
- Eyebrows
- Nose
- Mouth
- Jawline

How it works? First, We use the dlib package to detect the faces in the images 
(using Histogram of Oriented Gradients and Linear Support Vector Machines) then feed the
results to the pre-trained facial landmarks model (Ensemble of regression trees) (68 points)
and the program will output the image highlighting the facial landmarks. 

To fire this program, type the first/second/third command to run the program on a 
pre-saved image.

Thanks to pyimage search. 

To download the pre-trained facial landmark detector:
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2