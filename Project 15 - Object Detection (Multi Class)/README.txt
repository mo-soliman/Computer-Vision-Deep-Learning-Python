The aim of this project is to 
1- Build a bounding box regressor, where it predicts the top left and bottom right points of the box and then
draws the box around the detected object

2- Classify the type of the object in the image (airplane, motorcycle, face)

I will use the VGG neural network architecture, but I will freeze the convolutional layers parameters
and will train the parameters of the fully connected layers only.

We have 2 branches coming out from the last convolutional layer (after flattening) 
as we have 2 outputs, one for the classification problem (3 neurons) and one for the localization problem
(4 neurons) 

The 3 neurons corresponds to the airplane, motorcycle, face and they are activated by softmax function.

The 4 neurons (x and y for each point), each neuron is activated using sigmoid function 
(outputs from 0 to 1) where (0,0) corresponds to the top left of the image and (1,1) corresponds 
to the bottom right of the image.

The input image dimension is (224,224,3)

To download the dataset:
http://www.vision.caltech.edu/Image_Datasets/Caltech101/

To run the project run the first command in the Commands.txt file to train the neural network, 
then run the remaining commands.

Thanks to pyimage search.
