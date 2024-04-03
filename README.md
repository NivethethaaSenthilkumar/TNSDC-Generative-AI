# TNSDC-Generative-AI
Handwritten Number Recognition
Description:
RealTime-DigitRecognition application for predicting output corresponding to handwritten images.
Utilizes SVC (support vector classifier) and a sequential model in Keras.
Initial training done on 8x8 MNIST dataset with SVC, but accuracy is low with handwritten images resized from 600x600 to 8x8.
Created a sequential model in Keras trained on 28x28 MNIST dataset, resulting in significantly improved results for handwritten digits.
Interface built using Pygame.
Image preprocessing performed using Scipy and OpenCV.

Dataset:
MNIST dataset used, consisting of 70,000 labeled 28x28 pixel grayscale images of hand-written digits.
Split into 60,000 training images and 10,000 test images.
10 classes, one for each digit.

Sample Images:
Provided sample images of handwritten characters from the MNIST dataset.

Dependencies:
Sklearn, Keras, TensorFlow/Theano, OpenCV, Pygame, Pandas, NumPy, Scipy, Matplotlib.
