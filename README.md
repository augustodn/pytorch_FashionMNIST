# Fashion-MNIST with Pytorch
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, 
associated with a label from 10 classes. Fashion-MNIST is intended to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. 
It shares the same image size and structure of training and testing splits.

# Dataset Preview
This is a sample of how the data looks like in the original [dataset](https://github.com/zalandoresearch/fashion-mnist).
![fashion-mnist dataset](https://github.com/augustodn/pytorch_FashionMNIST/blob/master/img/fashion-mnist-sprite.png)

# Accuracy and Model Details
The model consists of two CNN layers with kernel size 5, activated by ReLU and Max Pool with kernel size 2. The last layer consist of a fully connected one with 7*7*32 inputs and 10 outputs, for
each class. Most of the details about it are clearly developed in this [medium](https://adenevreze.medium.com/cnns-with-pytorch-6cf7ed114af7) article. Also there are extensive notes 
in the jupyter notebook attached. This architecture, has about 90% accuracy obtained after only 6 epochs.

<img src="https://github.com/augustodn/pytorch_FashionMNIST/blob/master/img/2layersCNN.png" width="800">

# Labels
Each training and test example is assigned to one of the following labels:

0. T-shirt/top
1. Trouser
2. Pullover
3. Dress
4. Coat
5. Sandal
6. Shirt
7. Sneaker
8. Bag
9. Ankle boot

# Libraries Used
- Pytorch
- Numpy
- Matplotlib
