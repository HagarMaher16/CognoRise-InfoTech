# Iris Flower Classification

## Overview

This project demonstrates how to build a machine learning model to classify Iris flower species using the **Iris dataset**. The Iris dataset consists of measurements for three species of Iris flowers: **Setosa**, **Versicolor**, and **Virginica**. The aim is to develop a model that learns from the measurements of the flowers and accurately classifies them into their respective species. The goal is to train a classification model that, given these measurements, can predict the species of a flower.

## Dataset

The Iris dataset is a widely-used dataset for beginner classification tasks. It contains 150 samples, with 50 samples for each of the three species of Iris. Each sample includes four features (measurements) and a target variable representing the species.

## Project Objectives

- **Load and preprocess the Iris dataset**.
- **Train a machine learning model** to classify Iris flowers into the three species using the provided measurements.
- **Evaluate the model's performance** using accuracy as the metric.
  
The model chosen for this task is **Logistic Regression**, a simple yet powerful classification algorithm.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`

You can install the required libraries using:

```bash
pip install pandas numpy scikit-learn
```
  
## Steps of code

1. **Data Loading**: The Iris dataset is loaded into a pandas DataFrame.
2. **Data Preparation**: The target variable (species) is label-encoded, and the data is split into training and test sets using Scikit-learn's `train_test_split` function.
3. **Model Training**: A logistic regression model is trained on the training data to learn how to classify flowers based on their measurements.
4. **Model Evaluation**: The model's performance is evaluated on the test set, achieving a high accuracy of **96.67%**.
