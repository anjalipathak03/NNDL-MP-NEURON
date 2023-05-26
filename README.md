# `NNDL MP NEURON`
 
 It is very well known that the most fundamental unit of deep neural networks is called an artificial neuron/perceptron. But the very first step towards the perceptron we use today was taken in 1943 by McCulloch and Pitts, by mimicking the functionality of a biological neuron.
 - The MP neuron is mankind’s first simplified mathematical model of the neuron. This model was developed by McCulloch and Pitts in 1943. The MP neuron model is also known as the linear threshold gate model. They are widely used in proving logic functions.
 - The MP Neuron served as a foundation for the development of more sophisticated artificial neural network models, such as the perceptron and later multilayer neural networks. These models expanded upon the MP Neuron by incorporating activation functions, multiple layers, and learning algorithms, enabling them to solve more complex problems.

## Characteristics of MP Neuron :

When MP neurons are modeled as neural networks, they are connected by directed weighted paths in a neural network which we will study later.
When we pass the Adder function value in the Activation function of an MP neuron, there are 2 possibilities: the neuron may fire (label 0) or it does not fire (label 1).
The activation function is based on the threshold value. There is a fixed threshold for each neuron and if the net input to the neuron is greater than the threshold then the neuron fires.

![image](https://github.com/03anjali/NNDL-MP-NEURON/assets/91782986/252ac479-593d-4d8c-b30e-e9d3acec6b2a)

The MP Neuron is a binary threshold logic unit that takes binary inputs and produces a binary output. It consists of multiple input lines, each associated with a weight, and a threshold value. The inputs can be either 0 or 1, and the weights represent the relative importance of each input. The threshold value determines the firing condition of the neuron.

The operation of the MP Neuron is as follows:

The neuron receives binary inputs on its input lines.
Each input is multiplied by its corresponding weight.
The weighted inputs are summed up.
If the sum exceeds the threshold value, the neuron fires and produces an output of 1. Otherwise, it outputs 0.

The MP Neuron can be seen as a simple decision-making unit that fires only if the weighted sum of inputs exceeds a certain threshold.
It can be used to model logical functions and perform simple binary classifications. However, it has limitations, such as the inability to represent complex decision boundaries or handle continuous inputs.

