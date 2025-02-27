# Activations-Functions-in-Neural-Network

An activation function is a mathematical function applied to the output of a neuron (i.e., the linear combination of inputs and weights) in a neural network. It introduces non-linearity into the network, enabling it to learn complex relationships in data. Without an activation function, a neural network would behave like a single-layer linear model, regardless of how many layers it has.
Here Artificial neural network for different activation functions has been build to analyze the mnist dataset to observe how the accuracy of model changes with the activation functions
## Differnt types of Activation function
### Linear
A linear function f(x)=x and hence the network can only learn linear patterns

### Signmoid
σ(x)= 1/1+e^−x
The output of sigmoid function ranges 0 to 1
### Tanh function
tanh(x)= e^x + e^−x/e^x − e^−x
The output ranges from -1 to 1

### Relu Function
max(0,x)
ranges 0 to ∞

## Relu function yields high accuracy
1. Mitigates Vanishing Gradients
* Sigmoid and Tanh saturate for large ∣𝑥∣ causing gradients to become very small.
* ReLU outputs 0 for negative inputs and grows linearly for positive inputs, allowing stronger gradients.
2. Simplicity & Efficiency
*max(0,𝑥) is computationally cheaper compared to exponential functions in Sigmoid/Tanh.
* Training often converges faster.
3. Sparse Activation
* Many neurons output 0, creating a sparse representation.
* This can improve generalization and reduce overfitting in practice.

4. Empirical Success

ReLU is widely used and tested across various tasks (computer vision, NLP).
It often yields good results without requiring special tuning.
 
​

 
​
