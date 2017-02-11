# Miniflow
A library that demonstrates training of data using stochastic gradient descent method

The minflow library is a part of Udacity's Nanodegree Program and has been prepared while pursuing the same

## Table of Contents
- **miniflow.py**
  
  This file consists of the set of functions used to perform a basic back propogation in a neural network
- **nn.py**
  
  This file consists of a sample neural network
  
## Usage

- Include the miniflow.py in your root project and use the following classess as follows:
  1. `Input()`
  
    Use it to declare input nodes of neural network
  2. `Linear()`
  
    Use to declare a node performing the task of linear activation  of form Y = XW+ b
  3. `Sigmoid()`
  
    Use to declare a node performing sigmodial activation
  4. `MSE`
  
    Use this node to calculate Mean Square Error
- Further functions are included to perform forward pass, backward pass and gradient descent
- In sample nn file sci-kit learn library is used to resample the dataset to perform a Stochastic Gradient Descent. The miniflow library is designed for Stochastic Gradient Descent and hence the function for gradient descent is named as `sgd_update`

## Contribution Guideline

The miniflow consists only a Linear and a Sigmoidal Activation Nodes. Contributors are expected to provide more depth to the miniflow by including more nodes and functions to perform basic Neural Network based tasks

## License

MIT license is included in the repo
