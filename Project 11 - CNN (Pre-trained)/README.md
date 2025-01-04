In this project there is one program.

The aim of this project is to classify different kinds of objects listed in synset_words.txt
file.

How it works? First, we load the pre-trained CNN model by OpenCV, we then select our test image
resize and normalize it, the feed forward the resized image to the neural network. We then get the
highest output probability, check its index and its corresponding output class.
Then re-draw the input image with the name of the output class and confidence percentage.

Cool fact: On my laptop it take around 0.1 second to feed forward and image, this means we can
display a video with 10 FPS with each frame labeled with the corresponding output class :)

To run the program run any command in the Commands.txt file

Thanks to pyimage search.

To download the CNN Pre-trained model:
http://dl.caffe.berkeleyvision.org/bvlc_googlenet.caffemodel
