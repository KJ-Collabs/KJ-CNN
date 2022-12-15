# KJ-CNN

A convolutional neural network, created to help us further our understanding in the field of computer vision.

## Explanation
A convolutional neural network is a type of artificial neural network, that uses a mixture of [convolution](#convolution) and [pooling](#pooling) in its hidden layers in an attempt to prevent the overfitting that is common in multilayer perceptrons.

## Convolution
Convolutional layers convolve the input - meaning they 'slide' a convolution kernal over the inputs to the layer to generate a feature map, which is the output of the layer. One advantage of the convolution operation is that it results in far less parameters for the model to learn. For example, using fully connected layers, propagating through two layers of 50 neurons each would require 2500 total weights, whereas a 5x5 convolution kernal only result in 25 parameters to learn, regardless of the number of neurons in either layer.

## Pooling
Pooling layers are used to reduce the dimensions of data in the CNN.