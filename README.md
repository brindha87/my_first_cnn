# my_first_cnn

Learn to build a CNN for image classification.

## Input Images
Color images of size 32x32

## Number of output classes
10 classes

## Model Architecture:
3 Convolution layers are added, each followed by a MaxPooling layer.

Finally, the array is flattened into a vector, and passed on to a fully connected layer of 50 nodes.

Then, there is an output layer with 10 nodes using softmax activation function, because we want to classify images having 10 classes. The softmax function would return the probabilities of the object belonging to that particular class.
