# FaceExpressionRecognition-ML
This project focuses on facial expression recognition using deep learning. The task is to classify facial images into one of seven emotion categories using the FER-2013 dataset.

The full explanation of the dataset, models, experiments, and results is provided in the final project report included in this repository.

## Problem Description

Facial Expression Recognition (FER) is treated as a multi-class classification problem.

* **Input:** 48×48 grayscale facial image
* **Output:** One of seven emotions
  *(anger, disgust, fear, happiness, sadness, surprise, neutral)*

## Models Implemented

The following models were implemented and compared:

* Baseline Neural Network (fully connected)
* Baseline Convolutional Neural Network (CNN)
* **Enhanced CNN (best performing model)**
* Fine-tuned VGG-16 model

## Results Summary

* The baseline NN performed poorly due to lack of spatial feature extraction.
* CNN-based models significantly improved performance.
* The **Enhanced CNN achieved the best validation accuracy (~66%)**.
* The VGG-16 model showed high training accuracy but suffered from overfitting and did not outperform the custom CNN.

## Dataset

* FER-2013 dataset
* 35,887 grayscale images
* Image size: 48×48
* 7 emotion classes
* Predefined training and validation split

## Tools and Frameworks

* Python
* TensorFlow / Keras
* NumPy
* Google Colab (GPU)
