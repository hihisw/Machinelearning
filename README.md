# MachineLearning

my personal learning notes, where I use it to study and implement basic concepts and implementations of Machine Learning. Here you can find some of my experiments and thoughts on learning.

## dnnWithOutLibs

This repository contains a simple implementation of a deep neural network (DNN) without the use of external libraries. The DNN is implemented in Python.

### Usage

You can instantiate the neural network by providing the model's architecture (shape) and the learning rate.

```python
# Instantiate the neural network with the desired architecture and learning rate
nn = MultiLayerNeuralNetwork(layer_sizes=[4, 100, 10, 3], learning_rate=0.01)
```
In the above example, [4, 100, 10, 3] represents the architecture of the neural network, with 4 input nodes, 100 nodes in the hidden layer, 10 nodes in the second hidden layer, and 3 output nodes.

### Parameters

layer_sizes : A list specifying the number of nodes in each layer of the neural network, including the input and output layers.
learning_rate : The learning rate used for training the neural network.

### Reference

- Make Your Own Neural Network - Tariq Rashid