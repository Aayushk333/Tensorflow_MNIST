# Tensorflow_MNIST

Project Overview : In this project I have worked on MNIST datatset containing images of digits from 0-9. There are 70000 data points (or images) which are divided into 55000 training images , 5000 validation images and 10000 testing images. I have used the powerful tensorflow library to implement Neural networks. In this dataset each image is stored as a 1 dimensional array of pixels. So there are total 784 columns which correspond to 28*28 pixels of an image. The structure of the Neural Network implemented is of the form : 
-> Input_layer : 784 units 
-> Hidden_Layer_1 : 256 units
-> Hidden_layer_2 : 256 units
-> Output_layer : 10 units 
The activation function used is the "Relu" activation function (in each layer except the output layer). The cost function used is the softmax cross entropy function with logits. The optimizer I have used is the AdamOptimizer with a learning rate of 0.01. 
The accuracy obtained is around 85-89 %. We can play around with different number of units in the hidden layers , different learning rates , different no of iterations , different cost function , different optimizer , different types of activation function used to get different results (May be worse or may be better accuracy). 
