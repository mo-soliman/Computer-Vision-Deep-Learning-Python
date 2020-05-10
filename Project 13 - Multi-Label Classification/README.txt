In this project there are two programs.

The aim of this project is to classify different kinds of objects listed in the dataset folder, 
but the advanced step in this project is that this is a multi label classification, I mean the
neural network should tell whether this is jeans/shirt/dress and ALSO whether this is blue/red/black.

How it works? We build our neural network archieture regularly (Small VGG) but the trick is
instead of using softmax in our last layer we will use sigmoid function for each neuron in the 
output layer, this means now we can treat each neuron as an independent output!

To fire the program run the first command in the Commands.txt file, then run the remaining
commands.

You can send me a request to share with you the dataset.

Thanks to pyimage search.
