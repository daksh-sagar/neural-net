## Neural Network (Feed Forward) from scratch and classification of MNIST data set using the network .

The network consists of a single hidden layer, and is written in _Python_ using just _NumPy_, and `expit` function from _SciPy_

The notebook `Neural-Network.ipynb` consists of the actual **Neural Netowrk** _class_, and `MNIST-Data.ipynb` consists of code that uses this neural network to classify handwritten digits data present in **MNIST data set**.

### Instructions to run the code on your PC.

1. Use `git clone` to clone the repo to your pc.
2. `cd` into the project directory and inside your terminal run `mkdir data`.
3. Download the [training dataset](http://www.pjreddie.com/media/files/mnist_train.csv 'Training dataset') and [testing dataset](http://www.pjreddie.com/media/files/mnist_test.csv 'Training dataset')
4. Put the downloaded files inside `data` directory
5. Done

Varying the parameters of the network, i.e. **number of epochs**, **number of nodes in the hidden layer**, and **the learning rate** give varying performance.
The best I've got is **97.5%** _(very impressive)_ .
