# Fashion-Mnist-with-ANN-and-CNNs

The main goal of this project is to test different deep learning techniques, compare them and see what impact they have on solving a specific problem. In this case I choose Fashion MNIST data set which have images of different clothing in 10 classes. 

The architectures whose results I will compare are:
-Artifical Neural Network,
-Convolutional Neural Network,
-Convolutional Neural Network with data generator,
-Pretrained Convolutional Neural Network.

All convolutional networks have the same layers, the last network was first trained on the standard MNIST dataset and then it was trained on the actual Fashion MNIST dataset. ANN was trained on comparisons.


For the code to work, it is necessary to create a folder called "data". Then download the data from the links below:
- https://www.kaggle.com/datasets/zalando-research/fashionmnist - for Fashion MNIST,
- https://www.kaggle.com/datasets/oddrationale/mnist-in-csv - for MNIST,
And copy "fashion-mnist_test.csv", "fashion-mnist_train.csv", "mnist_test.csv" and "mnist_train.csv" files to data folder, due data is to big for put it in this repository.  
