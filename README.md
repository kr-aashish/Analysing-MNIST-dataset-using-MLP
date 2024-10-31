### Analyzing MNIST dataset using MLP
#### Jul 2020 - Jul 2020
- Flattened the images of MNIST dataset 2D 28×28 tensor to a vector of size 784 before feeding it to the multilayer perceptron network.
- Defined the neural network with 2 hidden layers containing 512 nodes each with ReLU activation and 10 output nodes followed by a Softmax function to get the probability of the classes.
- Used cross entropy loss as loss function, SGD as optimizer and trained the model in batches with batch size of 20.
- Used randomly choosen 20% of the training data for validation to decide the most optimum number of epochs for the network.
- Got an overall accuracy of all 10 classes as 97%.
