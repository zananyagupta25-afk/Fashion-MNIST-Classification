# Fashion MNIST Classification using Deep Learning
Deep learning project for classifying fashion images using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN).

## Project Overview

This project focuses on building and comparing different deep learning models to classify clothing images from the Fashion MNIST dataset. The goal is to understand how neural networks perform in image classification tasks and compare the performance of Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN).

## Dataset

The Fashion MNIST dataset contains 70,000 grayscale images of clothing items divided into 10 categories.
Each image has a resolution of 28 × 28 pixels.

Classes in the dataset:

* T-shirt / Top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle Boot

## Project Workflow

### 1. Data Preprocessing

* Loaded dataset using TensorFlow/Keras
* Normalized pixel values to improve model performance
* Reshaped images to match CNN input format
* Converted labels into one-hot encoding

### 2. Models Implemented

#### Artificial Neural Network (ANN)

* Flatten layer
* Dense layers with ReLU activation
* Softmax output layer for classification

#### Basic CNN Model

* Convolution layers for feature extraction
* MaxPooling layers for dimensionality reduction
* Fully connected dense layers

#### Deep CNN Model

* Multiple convolution layers
* Batch Normalization
* Dropout for regularization
* Improved feature extraction

### 3. Model Optimization

* Early stopping to prevent overfitting
* Model checkpointing to save the best model

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Plotly
* Google Colab

## Results

The CNN models achieved better accuracy compared to the ANN model due to their ability to capture spatial features in images.

## Learning Outcomes

Through this project, I learned:

* Image preprocessing techniques
* Building ANN and CNN architectures
* Preventing overfitting using regularization
* Model evaluation and comparison
* Visualization of model performance

## Future Improvements

* Implement transfer learning
* Deploy the model using a web interface
* Train with more complex architectures

## Author

Ananya Gupta  
B.Tech Student | Machine Learning Enthusiast

