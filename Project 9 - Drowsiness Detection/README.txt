In this project there is one program.

The aim of this project is to ensure you don't fall a sleep while driving by raising an
alarm!

How it works? First, We use the dlib package to detect the faces in the images/videos 
(using Histogram of Oriented Gradients and Linear Support Vector Machines) then feed the
results to the pre-trained facial landmarks model (Ensemble of regression trees) (68 points)
we then choose the corresponding points of the left and right eyes, we calculate the 
Eye Aspect Ratio(EAR) if it falls below a certain threshold for a multiple frames,
this means that you are falling a sleep and an alarm will be raised.

To fire the program run the first command in the Commands.txt file

Thanks to pyimage search. 

To download the pre-trained facial landmark detector:
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2