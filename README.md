# Mood Detection Project

## Overview
This project aims to develop a mood detection model using facial expression images. The dataset used for training and testing the model is the FER2013 dataset, which contains grayscale images of faces categorized into seven different emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral.

The project involves preprocessing the image data, building a neural network model using TensorFlow and Keras, training the model on the training dataset, and evaluating its performance on the testing dataset. The results are visualized using a confusion matrix to analyze how well the model predicts different emotions.

## Technologies Used
- TensorFlow
- Keras
- scikit-learn
- OpenCV
- NumPy
- Matplotlib
- Seaborn

## Dataset
The FER2013 dataset is used for training and testing the mood detection model. It contains images of faces annotated with one of seven emotions. The dataset is divided into training and testing sets, and the preprocessing includes resizing images to 48x48 pixels, normalizing pixel values to the range [0, 1], and one-hot encoding the categorical labels.

