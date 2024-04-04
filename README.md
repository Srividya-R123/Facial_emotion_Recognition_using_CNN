# Facial Emotion Recognition using CNN

## Overview
This project is aimed at developing a facial emotion recognition system using Convolutional Neural Networks (CNN). The system takes images of human faces as input and predicts the corresponding emotion expressed by the person in the image. 

## Features
- Utilizes CNN architecture for accurate facial emotion recognition.
- Recognizes a variety of emotions including happiness, sadness, anger, surprise, fear, disgust, and neutral.
- Supports real-time emotion detection from static images.

## Dataset
The facial emotion recognition CNN model was trained on the [FER2013 dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data), which contains labeled facial images categorized into seven emotion classes.

## Model Architecture
The CNN architecture used for facial emotion recognition consists of multiple convolutional and pooling layers followed by fully connected layers. The final layer employs softmax activation to predict the probability distribution over the emotion classes.

## Performance
The model achieves an accuracy of approximately 92% on the validation set with 64 batch size and 60 epochs and 59% accuracy on 10 epochs and 32 batch size. Performance may vary depending on factors such as image quality, lighting conditions, and facial expressions.

