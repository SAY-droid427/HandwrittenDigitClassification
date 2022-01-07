# Handwritten Digits Classification Using MNIST Dataset

The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.

The goal of the project is to classify the handwritten digits in the MNIST dataset.

## Architecture

I have used convolutional neural networks. The architecture uses:
1. Convolutional layers
2. Max pooling of pool size 2X2
3. Dropout regularization(0.2)
4. Flatten layer
5. Dense layer(activation function = rectified linear unit)
6. Dense output layer(activation function = softmax)


The accuracy achieved with the training set is 99.44% and the accuracy achieved with the test set is 99.26%.
