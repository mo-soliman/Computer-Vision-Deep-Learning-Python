In this project there is one program.

The aim of this project to count how many times you've blinked in a video (Live-stream laptop
Camera)

How it works? First, We use the dlib package to detect the faces in the images/videos 
(using Histogram of Oriented Gradients and Linear Support Vector Machines) then feed the
results to the pre-trained facial landmarks model (Ensemble of regression trees) (68 points)
we then choose the corresponding points of the left and right eyes, we calculate the 
Eye Aspect Ratio(EAR) if it falls below a certain threshold, this means the user has blinked.

To fire the program run the first/second command in the Commands.txt file

Thanks to pyimage search. 

To download the pre-trained facial landmark detector:
http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2