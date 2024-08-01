# Image-classification-using-CNN-CIFAR10-dataset


**Overview**

This project demonstrates image classification using a Convolutional Neural Network (CNN). The dataset used includes various categories of images which the CNN model is trained to classify.

**Dataset**

Dataset Source: https://www.cs.toronto.edu/~kriz/cifar.html


Categories: 10


Number of Images: 60000


**Project Structure**

**Data Preprocessing:** Steps taken to preprocess the data.

Resizing images.


Normalizing pixel values.


Splitting the dataset into training and testing sets.


**Model Architecture:** Description of the CNN model used.

Input Layer: Shape (32, 32, 3)


**Convolutional Layers:**


Conv2D (32 filters, kernel size 3x3, activation 'relu')

MaxPooling2D (pool size 2x2)

Conv2D (64 filters, kernel size 3x3, activation 'relu')

MaxPooling2D (pool size 2x2)

Flatten Layer


**Dense Layers:**


Dense (64 units, activation 'relu')

Dense (10 units, activation 'softmax')


**Training**


**Optimizer:** Adam


**Loss Function:** Sparse Categorical Crossentropy


**Metrics:** Accuracy


**Epochs:** 10


**Evaluation**


**Accuracy:** 70 %

