# NLP_END_Session1 Assignment

**1.What is a neural network neuron?**

A Neuron is a mathematical function that model the functioning of a biological neuron. Typically, a neuron compute the weighted average of its input, and this sum is passed through a nonlinear function, often called activation function like tanh,relu or sigmoid.

**2.What is the use of the learning rate?**

The learning rate is a configurable hyperparameter used during the training of neural networks that has a small positive value, often in the range between 0.0 and 1.0.The learning rate controls how quickly the model learns the patterns in the data. Smaller learning rates require more training epochs given the smaller changes made to the weights after each update, whereas larger learning rates result in rapid changes and require fewer training epochs.

**3.How are weights initialized?**
Weight initialization is used to define the initial values for the parameters in neural network models prior to training the models on a dataset.The current standard approach for initialization of the weights of neural network layers and nodes that use the Sigmoid or TanH activation function is called “glorot” or “xavier” initialization.
There are two versions of this weight initialization method, which is referred as xavier and normalized xavier:-
- The xavier initialization method is calculated as a random number with a uniform probability distribution (U) between the range -(1/sqrt(n)) and 1/sqrt(n), where n is the number of inputs to the node.
- The normalized xavier initialization method is calculated as a random number with a uniform probability distribution (U) between the range -(sqrt(6)/sqrt(n + m)) and sqrt(6)/sqrt(n + m), where n us the number of inputs to the node (e.g. number of nodes in the previous layer) and m is the number of outputs from the layer (e.g. number of nodes in the current layer).


**4.What is "loss" in a neural network?**
Loss is nothing but a prediction error of Neural Net. And the method to calculate the loss is called Loss Function.The Loss is used to calculate the gradients and gradients are used to update the weights of the Neural Net. This is how a Neural Net is trained.


**5.What is the "chain rule" in gradient flow?**
Gradient Flow Calculus is the set of rules used by the Backprop algorithm to compute gradients. Backprop works by first computing the gradients at the output of the network (which can be computed using an explicit formula), then propagating or flowing these gradients back into the network.
