# Handwritten Digit Recognition with Deep Learning

## Overview

This Python script is dedicated to handwritten digit recognition using a deep learning model. It leverages the 'optdigits.tra' and 'optdigits.tes' datasets, each row representing an 8x8 reshaped digit image with labels in the last column. The objective is to build, train, and evaluate a deep learning model for accurate digit prediction, considering the variable number of images for different digits in the dataset.

## Introduction

The dataset comprises gray digit images stored in 'optdigits.tra' (training) and 'optdigits.tes' (testing) files, each with 65 columns per image. The goal is to construct a deep learning model that predicts the digit from a test image, without normalizing pixel values, and addressing the variable number of images for different digits in the dataset.

## Usage

1. Ensure 'optdigits.tra' and 'optdigits.tes' files are available.
2. Run the script to build and train the deep learning model.
3. Visualize the training and validation loss curves to identify potential overfitting.
4. Retrain the model with the determined number of epochs (if overfitting occurs).
5. Predict the test set and analyze results with one-hot decoding.

## Tasks

1. **Data Preparation:**
   - Load and preprocess datasets.
   - One-hot encode categorical labels.

2. **Model Construction:**
   - Build a deep learning model with 2 hidden layers (24 nodes each) and softmax activation.
   - Compile and train the model with specified parameters.

3. **Model Evaluation:**
   - Plot training and validation loss curves.
   - Identify overfitting epochs.
   - Retrain the model if necessary and report test accuracy.

4. **Prediction and Analysis:**
   - Predict the test set.
   - One-hot decode predicted digits and actual test digits.

## Conclusion

The script successfully addresses the challenge of handwritten digit recognition. Further exploration of the model's accuracy and identification of the most challenging digit to predict, with the highest error rate, can be achieved through detailed error analysis.