# Neural-Network
This program applies a neural network for the purposes of identifying hand-drawn digits from the MNIST dataset.

![image](https://github.com/AaronSarkar/Neural-Network/assets/170950397/65712905-c412-4371-b106-e8ce6a6cc14a)

The neural network consists of 3 dense/fully connected layers, each using a sigmoid function for activation. For each image, the grayscale RGB values of the pixels are flattened and fed through the neural network, manipulating the shape of the input array as well as the numbers within using matrix multiplications with the weights and biases. Then, to asses the performance of the neural network, the mean squared cost function is used, which is then fed backwards through the neural network using gradient descent, adjusting the weights and the biases incrementally until the correct result is determined. The final testing accuracy of this neural network ended up being 96%, easily beating the random chance value of 10%.

![image](https://github.com/AaronSarkar/Neural-Network/assets/170950397/761dfea5-de16-417a-92b4-c8fb8cf438ff)




