# Basic Image Classifier with Keras

This project implements a basic image classifier using the Keras deep learning library. In this project, we will:

- Load the MNIST dataset of hand-written digits.
- Design a deep learning model architecture.
- Train the model on the training data and evaluate its performance.
- Save the trained model for later use.
- Load the saved model and use it to classify new images.

## Introduction

In this code, we implement a basic image classifier using Keras, a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano.

## Dataset

We use the MNIST dataset, which is a large database of handwritten digits widely used for training various image processing systems. The dataset consists of 60,000 training images and 10,000 testing images, each of size 28x28 pixels.

![MNIST Dataset](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

## Getting Started

To run the code, ensure you have the following libraries installed:
- Keras
- TensorFlow
- Matplotlib
- Pillow

# Implementation

## Load the Dataset
- Load the MNIST dataset using Keras.

## Preprocess the Data
- Normalize the pixel values to the range [0, 1].

## Build the Model
- Design a Convolutional Neural Network (CNN) architecture using Keras Sequential API.

## Compile the Model
- Compile the model with appropriate loss function and optimizer.

## Train the Model
- Train the model on the training data and validate it on the testing data.

## Evaluate the Model
- Evaluate the model's performance on the testing data.

## Save and Load the Model
- Save the trained model to a file and load it for later use.

# Results

After training the model, we achieved an accuracy of around 98% on the testing dataset.

# Conclusion

This project demonstrates the implementation of a basic image classifier using Keras. By following the provided steps, you can train your own image classification model and use it for various applications.

Feel free to explore and modify the code according to your requirements!

