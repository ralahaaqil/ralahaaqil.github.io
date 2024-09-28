---
title: "Image Classifier Model to Detect Diseases on Leaves"
excerpt: "This project deals with the development of a convolutional neural network to detect the presence of diseases on leaves. <br/><img src='/images/project2.jpg' width = '50%'>"
collection: portfolio
---

This project involves the development of a convolutional neural netrwork model that detects the presence of diseases on leaves. The training data consisting of around 20,000 images is preprocessed and augmented. Tensorflow and Keras are used to load the data and build a convolutional neural network.

The neural network consists of three convolutional layers, each having a 2D convolutional layer, a maxpooling layer and a dropout layer or regularization purposes. L2 regularization is also implemented in each of the 2D convolutional layers. The final set of layers in the network consist of the flatten and fully connected layers.

Early stopping and reduction of learning rate is applied during the training process. The model performs well with over 90% accuracy, and good precision, recall and f1 scores.

The GitHub repository for the notebook can be found here: 
