# Performing Sentiment Analysis on IMDB Movie Reviews using Tensorflow and Keras

## Introduction

This project is a sentiment analysis of the IMDB movie review dataset. The dataset contains 50,000 reviews, which are split into 40,000 reviews for training and 10,000 reviews for testing. The training and testing sets are not balanced. The goal of this project is to train a model to predict whether a review is positive or negative.

## Purpose

The main purpose of this project is learning how to perform sentiment analysis using deep learning. The project also serves as a demonstration of my skills in deep learning and natural language processing.

## Data

The data is available at https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews.

## Methodology

The data is preprocessed by removing punctuation, and stop words. The data is then tokenized and converted to a sequence of integers. The data is then padded to a maximum length of 2048. The data is then split into training and testing sets. The model is trained on the training set and evaluated on the testing set. The model is a sequential model with an embedding layer, an average pooling layer, and a dense layer. The model is compiled with the Adam optimizer and binary cross entropy loss. The model is trained for 30 epochs with a batch size of 512 and trained again for 30 epocs with an increased batch size of 2048. The model achieves an accuracy of 0.88 on the testing set.

## Results

The model achieves an accuracy of 0.88 on the testing set.

## Conclusion

The model achieves an accuracy of 0.88 on the testing set, which is a somewhat good result. The model could be improved by using a more complex model architecture and by using a pretrained embedding layer.

## What I learned

I learned how to preprocess text data and how to use the Keras API for deep learning.

## What is next

The next step is to use a more complex model architecture and a pretrained embedding layer to improve the model's performance.
