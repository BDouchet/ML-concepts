# Introduction to Neural Networks

## What is a neuron

Biologically, a neuron is a cell transmitting an electrical signal from neurons to other neurons. Neuron are composed of 3 main parts :

*  Dendrits, capting input signal
*  Nucleus, prcessing this signal
*  Axon & Axon Terminals, conveying and sending the signal to the next neurons

![Neuron Scheme](https://upload.wikimedia.org/wikipedia/commons/4/44/Neuron3.png)

The Artificial Neural Networks (ANN) is composed of neurons similar to biological neurons. The artificial neuron (or perceptron) is also composed of three parts and they work in the same way. 

* Weights, giving more or less importance to input parts of the signal
* Core of the perceptron processing the signal : Wieghted Sum of the signal and add of a bias. 
![equation](https://latex.codecogs.com/gif.latex?WS%20%3D%20X%5E%7BT%7D.W%20&plus;%20w_%7B0%7D)
with ![equation](https://latex.codecogs.com/gif.latex?X%3D%5Cbegin%7Bpmatrix%7D%20x_%7B1%7D%5C%5C%20x_%7B2%7D%5C%5C%20...%5C%5C%20x_%7Bn%7D%20%5Cend%7Bpmatrix%7D%20and%20%5C%3B%20W%3D%5Cbegin%7Bpmatrix%7D%20w_%7B1%7D%5C%5C%20w_%7B2%7D%5C%5C%20...%5C%5C%20w_%7Bn%7D%20%5Cend%7Bpmatrix%7D) the input signal and the weights.
* Activation function, apply a function to the weighted sum and send the output. For instance, the step function in the following example 

![Perceptron Scheme](https://images.deepai.org/glossary-terms/perceptron-6168423.jpg =100x200)

