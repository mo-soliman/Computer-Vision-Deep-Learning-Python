The aim of this project is to build a bounding box regressor, where it predicts the top left and bottom right
points of the box and then draws the box around the detected object (airplanes in this project)

We have only one category of objects (airplanes) so I will only focus on bulding the bounding box regressor.
we will use the VGG neural network architecture, but and we will freeze the convolutional layers parameters
and we will train the parameters of the fully connected layers only.
In the output layer we will have 4 neurons (x and y for each point), 
each neuron is activated using sigmoid function (outputs from 0 to 1) where (0,0) corresponds to the top left
of the image and (1,1) corresponds to the bottom right of the image.

The input dimension is (224,224,3)

To download the dataset:
http://www.vision.caltech.edu/Image_Datasets/Caltech101/

To run the project run the first command in the Commands.txt file to train the neural network, 
then run the remaining commands.

Thanks to pyimage search.
