# Stellar Object Classification

## Overview
In this project, our main goal is to classify different types of stellar objects in a Kaggle dataset from the Sloan Digital Sky Survey (SDSS). The dataset contains 100,000 observations described by 17 feature columns and 1 class column, which identifies them as stars, galaxies, or quasars (QSO). The dataset can be found [here](https://www.kaggle.com/lucidlenn/sloan-digital-sky-survey).

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Features](#features)
- [Conclusion](#conclusion)

## Installation
To run this project, you need the following dependencies:
- Python 3.x (3.10 native)
- Jupyter Notebook
- Numpy
- Pandas
- Plotly Express
- Matplotlib
- Seaborn
- Astropy
- Scikit-learn
- Imbalanced-learn
- MLxtend

You can install the dependencies using the following command:
'pip install numpy pandas plotly plotly_express matplotlib seaborn astropy scikit-learn imbalanced-learn mlxtend'

## Usage
1. Download the dataset from the Github repo or from Kaggle.
2. Open the Jupyter Notebook file "classification.ipynb".
3. Execute each cell in the notebook to preprocess the data, visualize various aspects, perform data resampling, build and evaluate machine learning models.

## Configuration
No specific configuration is required for this project beyond installing the necessary dependencies.

## Features
- Data preprocessing and handling of missing values
- Exploratory data analysis and visualization
- Resampling of imbalanced dataset using SMOTE technique
- Object classification using various machine learning algorithms (Logistic Regression, SVM, Decision Tree, Random Forest)
- Model evaluation using accuracy, precision, recall, and F1-score
- Visualization of classification results using confusion matrices and other plots

## Conclusion
The top two models were Decision Tree and Random Forest. Random Forest attains the highest accuracy, while Decision Tree gets close but does so noticeably faster