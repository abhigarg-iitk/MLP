# Multi-Layered Preceptron

This repository contains code for MLP from scratch in Matlab. This was build as an assignment in my course CS698U. It is highly configurable.

## Problem Statement for the assignment

Aim of this assignment is to make you implement and understand the backpropagation algorithm. You have to implement a classifier for the task of handwritten digit recognition on the MNIST dataset with standard split.

* You have to code a simple multilayer perceptron from scratch, in a programming language of your choice, to solve the above task. Your code should take the number of hidden layers, number of nodes and the type of activation function, in each layer, as arguments.

* You also have to show that the gradients computed by backpropagation are correct, by calculating them numerically for all the weights and biases and showing them to be equal.

* You need to implement and experiment at least two of following activation functions:
    1. ReLU
    2. Maxout
    3. Tanh
    
* Also implement at least two of following gradient methods:
    1. GD with momentum
    2. Adam
    3. Adagrad
    4. RMSprop

* Finally, you have to experiment with different architectures i.e. how changing the number of layers, nodes in layers and different activation functions affect the performance of the network and plot their train and validation error graphs. 

### Parameters that can be adjusted

Most of the paramerters are declared in MLP_configuration_driver.m. The code is heavily commented. Also more info on how can parameters be tuned is given in README.pdf

### Running

To run the MLP you need to run MLP_configuration_driver.m 


```
MLP_configuration_driver.m
```

## Testing and accuracy

All plots form various tests can be found in README.pdf. I have achieved accuracy of around 97% with this implementation.

## License

This project is licensed under the MIT License

## Acknowledgments

* Gaurav Sharma (Course Instructor CS698U)
