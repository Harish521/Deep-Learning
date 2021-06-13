# Deep-Learning

## Activation Function
* This decides whether the neuron is firing or not. 
### Sigmoid and Tanh 
* The range of the tanh function is [-1,1] and that of the sigmoid function is [0,1].  Sigmoid and Tanh has Vanishing Gradient problem. It means the derivative of these functions at one point would be almost zero(when the S curve flattens) and when this zero is back propagated the learning becomes really slow.

![Sigmoid and Tanh functions](./Images/Sigmoid_Tanh.jpg)
