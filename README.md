## Artificial Neural Networks on MNIST dataset - Artificial Intelligence Assignment 1

An artificial neural network is built for prediction of handwritten digits. MNIST dataset is used for this purpose.
Description to the variations in different implementations to select the best module - 
1. ANN_MNIST_best_Accuracy : This model of implementation has one hidden layer with 784 neurons. Adagrid optimiser is used. This gives the best accuracy among all other implementations.
2. ANN_MNIST_SGD :  This model has one hidden layer with 784 neurons. Stochastic Gradient Descent optimiser is used. 
3. ANN_MNIST_multiple_layers : This model has 4 hidden layers with 100, 250, 125, 60 neurons. Adagrid optimiser is used.
4. ANN_MNIST_overfitting : This model has 4 hidden layers with 784, 196,49, 24 neurons. This results in too many parameters to be evaluated for the existing data. The model will have parameters that overfits the training data. Hence the generalization error will be more.
5. ANN_MNIST_with_regularization : This model of implementation has one hidden layer with 784 neurons. Adagrid optimiser is used. L2 regularization methood is used. We can see from the plots that the generalization error is reduced upon usage of regularization.
