# kaggle-digit-recognizer

Recognize the digits in MNIST data

Repository for source code of kaggle competition: https://www.kaggle.com/c/digit-recognizer

# Overview

MNIST ("Modified National Institute of Standards and Technology") is the benchmark dataset for computer vision. In this competition, the goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. Different machine learning and deep learning techniques are applied to achieve this.

# Getting started

You can make a clone of the repository from Github on your local machine using the following command (prerequisite: you need git installed on your system):

$ git clone https://github.com/obaidur-rahaman/kaggle-digit-recognizer

# Data

data folder contains original data

# Repository structure

01-eda: Exploratory data analysis

Different techniques and methods were applied to explore the data:

1. Support Vector Machine: This standard machine learning technique was applied to perform the classification. An accuracy ot 0.91 was obained with this.

2. Simple deep learning method: A basic deep learning network was constructed and its performance was evaluaed (accuracy = 0.92)

3. Multilayer perceptron: A MLP was implemented (accuracy = 0.95)

4. Principle component analysis: PCA was applied to reduce the dimentionality of the features. It produced an accuracy of 0.96 in combination with MLP.

02-cleaning: Cleaning and preprocessing of data

03-feature_engineering: Engineering new features



04-modelling: Fitting different models on the cleaned data and predict results.

# Training



# Acknowledgments

More details about the dataset, including algorithms that have been tried on it and their levels of success, can be found at http://yann.lecun.com/exdb/mnist/index.html. The dataset is made available under a Creative Commons Attribution-Share Alike 3.0 license.

Team

Obaidur Rahaman
Hossein Amirkhani
