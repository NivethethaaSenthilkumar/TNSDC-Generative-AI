# TNSDC-Generative-AI

# Handwritten Number Recognition

## Overview

This project is a RealTime-DigitRecognition application designed to predict outputs corresponding to handwritten images of digits. It utilizes machine learning algorithms and deep learning models to classify handwritten digits and provide accurate predictions.

## Project Components

1. **Model Training**: 
   - The project employs two main models for handwritten digit recognition:
     - Support Vector Classifier (SVC): Initially trained on the 8x8 MNIST dataset.
     - Sequential Model in Keras: Trained on the 28x28 MNIST dataset, resulting in improved accuracy for handwritten digits.

2. **Interface**: 
   - The user interface is created using Pygame, providing an interactive platform for users to input handwritten digits and receive predictions in real-time.

3. **Image Preprocessing**:
   - Image preprocessing is a crucial step in the project, performed using Scipy and OpenCV to enhance the quality of input images before feeding them into the models for classification.

## Dataset

The project utilizes the MNIST dataset, a widely used benchmark dataset for handwritten digit classification tasks. The dataset consists of 70,000 labeled 28x28 pixel grayscale images of digits (0-9), split into 60,000 training images and 10,000 test images.

## Dependencies

To run this application, you'll need the following dependencies:

- Sklearn
- Keras
- TensorFlow/Theano
- OpenCV
- Pygame
- Pandas
- NumPy
- Scipy
- Matplotlib

## Video Link
https://drive.google.com/file/d/1cssj3e00L1hEMHPemkUxvU2wbRsHO59x/view?usp=sharing
