# Multi Layer Net
This is a demonstration of a Deep Learning model built from the groud up in Julia 1.1.0.
### Objective
Correctly classify the digits in the [MNIST dataset](http://yann.lecun.com/exdb/mnist/)
### Required Modules
```julia
using Plots
using CSV
```
### Objectives
* Initialize random weights
* Adjust the weights to correctly classify the [MNIST dataset](http://yann.lecun.com/exdb/mnist/)
* Demonstate an understanding of the structure and implementation of Machine Learning Algorithms

### Structure
* A 6 layer nueral net layered in this order:
* L1 - 784 inputs, 125 outputs
* L2 - 125 inputs, 75 outputs
* L3 - 75 inputs, 150 outputs
* L4 - 150 inputs, 55 outputs
* L5 - 55 inputs, 10 outputs

### Results
![alt text](https://github.com/erichc91/DATA_4319/blob/master/Multi%20Layer%20Perceptron/Cost%20history.png)
