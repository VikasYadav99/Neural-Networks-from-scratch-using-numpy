# Neural-Networks-from-scratch-using-numpy

**In this notebook shallow neural network for classification is implemented without any API using numpy.**

**Pandas and matplotlib are used for data analysis and visualization.**

Data for heart risk detection was taken from kaggle and then modified.

For trying any architecture for shallow network
1. Create en empty list results
1. Create an object of class neural network and pass the layers list for number of neurons in each layer.
2. Activation function to be used in string format like 'sigmoid, 'tanh', 'relu' or 'leaky relu'
3. Run try_net function by passing the object created and some hyper parameters like initial learning rate (alpha0), beta for momentum in gradient descent and number of iterations.
4. Now after a while a plot of cost v/s iterations will be created
5. You can see the reults by running the last 3 cells of code.
