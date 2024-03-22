# Slash_image_classifier
This project implements a Convolutional Neural Network (CNN) model to automatically categorize images uploaded on the Slash e-commerce application into predefined categories.
# Functionality
The model can classify images into the following categories:
* Fashion
* Nutrition
* Accessories
* Artifacts
* Beauty
* Games
* Home
# Code Structure
The code is organized into the following sections:
### Data Preparation:
Performs data augmentation using ImageDataGenerator for training data.
Defines training and validation data generators using flow_from_directory.
### Model Building:
Creates a Sequential CNN model.
Defines convolutional layers with activation functions.
Adds pooling layers for dimensionality reduction.
Implements a flatten layer to prepare data for fully connected layers.
Defines dense layers with activation functions for classification.
### Model Compilation:
Configures the model with optimizer, loss function, and metrics.
### Model Fit:
Trains the model on the prepared training data with validation on the validation set.
### Visualization:
Plots the training and validation loss and accuracy curves.
### Model Evaluation:
Evaluates the model's performance on the validation data.
### Model Prediction:
Defines a function "predictions" to load, preprocess, and predict the category of an image.
Demonstrates the prediction on a test image.
### Model Saving:
Saves the trained model for future use.
# Dependencies
The code requires the following Python libraries:
*numpy
*tensorflow
*os
*matplotlib.pyplot
*keras
