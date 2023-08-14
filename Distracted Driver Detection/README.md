# Distracted Driver Detection 
This repository contains code for building and training a Convolutional Neural Network (CNN) model to perform distracted driver detection. The goal of this project is to classify images of drivers based on their state of distraction, utilizing the State Farm Distracted Driver Detection dataset.

## Introduction
Distracted driver detection involves identifying whether a driver is distracted based on images of their behavior while driving. In this project, we use the TensorFlow and Keras libraries to implement a CNN model. The model is trained on a dataset containing images of drivers in various states of distraction.

## Model
A Convolutional Neural Network (CNN) is used to classify the images. The CNN architecture includes convolutional layers, max-pooling layers, and fully connected layers. The model is compiled with an Adam optimizer and categorical cross-entropy loss.

## Results
The training process will be displayed in the terminal, showing the loss and accuracy of the model during training. The script will also save a DataFrame containing the predicted probabilities for each class for the testing images.
