# Deep-Learning

## Activation Function
* This decides whether the neuron is firing or not. 
### Sigmoid and Tanh 
* The range of the tanh function is [-1,1] and that of the sigmoid function is [0,1].  Sigmoid and Tanh has Vanishing Gradient problem. It means the derivative of these functions at one point would be almost zero(when the S curve flattens) and when this zero is back propagated the learning becomes really slow.

![Sigmoid and Tanh functions](./Images/Sigmoid_Tanh.jpg)
### ReLU and Leaky ReLU
* ReLU converts anything less than zero to 0 and anything greater than zero will be shown as is. In Leaky ReLU anything less than zero will be multiplied by 0.1 and values greater than zero are shown as is.
![All Activation Functions](./Images/Acitvation_Functions.png) 
