# Introduction to Neural Networks

## What is a neuron

Biologically, a neuron is a cell transmitting an electrical signal from neurons to other neurons. Neuron are composed of 3 main parts :

*  Dendrits, capting input signal
*  Nucleus, prcessing this signal
*  Axon & Axon Terminals, conveying and sending the signal to the next neurons

<img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Neuron3.png" width="400" height="é00">

\
\
The Artificial Neural Networks (ANN) is composed of neurons similar to biological neurons. The artificial neuron (or perceptron) is also composed of three parts and they work in the same way. 

* Weights, giving more or less importance to input parts of the signal
* Core of the perceptron processing the signal : Wieghted Sum of the signal and add of a bias. 
\
![equation](https://latex.codecogs.com/gif.latex?WS%20%3D%20X%5E%7BT%7D.W%20&plus;%20w_%7B0%7D)
with  the input signal and the weights :\
![equation](https://latex.codecogs.com/gif.latex?X%3D%5Cbegin%7Bpmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%5C%5C%20...%5C%5C%20x_%7Bn%7D%20%5Cend%7Bpmatrix%7D%20and%20%5C%3B%20W%3D%5Cbegin%7Bpmatrix%7D%20w_%7B1%7D%5C%5C%20w_%7B2%7D%5C%5C%20...%5C%5C%20w_%7Bn%7D%20%5Cend%7Bpmatrix%7D).
* Activation function, apply a function to the weighted sum and send the output. For instance, the step function in the following example. The idea of the activation function is to only activate the most useful neurons.

The number of parameters of a neuron is thus equal to n+1.

<img src="https://images.deepai.org/glossary-terms/perceptron-6168423.jpg" width="400" height="200">

\
\
## The Neural Network

Neural Networks are composed of layers and layers are made of neurons. In the following example, the NN has 5 layers. The hidden layers are composed of 4 neurons. The depth of a neural network is defined by the number of hidden layer and the width by the number of neurons in each layer. 

In this example, the number of parameters is :
* For layer 1 (Input): 0
* For layer 2 : 4 * (3 + 1) = 16
* For layer 3 or 4 : 4 * (4 + 1) = 20
* For layer 5 : 4 + 1 = 5
which gives a total number parameters equal to 61.

<img src="https://i.pinimg.com/originals/b0/81/89/b08189699368cf0b71eed9931ee70881.png" width="400" height="200">

To find the most efficient combination of weights, we need to use backpropagation algorithm

