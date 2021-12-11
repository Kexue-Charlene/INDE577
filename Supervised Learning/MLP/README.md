# Multilayer Perceptron
In this file, we will introduce multilayer preceptron. We should know activation function, layers, and neuron first. The dataset is from MNIST dataset-CIFAR10 small images classification dataset.
This is a dataset of 50,000 32x32 color training images and 10,000 test images, labeled over 10 categories.

Multi layer perceptron (MLP) is a supplement of feed forward neural network. 
It includes three types of layers: 
* the input layer
* output layer 
* hidden layer

## Activation function
If a MLP has a linear activation function in all neurons, we say that a linear function that maps the weighted inputs to the output of each neuron. Then any number of layers can be reduced to a two-layer input-output model was displayed by linear algebra. 


## Layers
The MLP has three or more layers of nonlinearly-activating nodes. Due to the fact that MLPs are fully connected, each node in one layer connects with a certain weight 𝑤𝑖𝑗  to every node in the following layer.

## Neuron Weights
Each neuron has a bias which is always has the value 1.0. For example, a neuron may have two inputs which it requires three weights. One for each input and one for the bias. Weights are often set as a small random values such as 0~0.3.

<img src="https://miro.medium.com/max/600/1*xxZXeKfVKTRqh54t10815A.jpeg">

