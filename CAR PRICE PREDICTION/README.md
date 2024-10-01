# Car Price Prediction

## Project Overview

This project focuses on predicting car prices based on various features such as brand, fuel type, horsepower, and more. Using machine learning techniques, we aim to create a model that can estimate the price of a car given its attributes.

In this project, we build a car price prediction model using a dataset. We preprocess the data, apply encoding where necessary, and train a model using linear regression.

## Dataset

The dataset used in this project is publicly available on Kaggle, consisting of various car features and their respective prices.

## Technologies Used

- **Python**: Programming language for data analysis and model building
- **Pandas**: For data manipulation and analysis
- **NumPy**: For numerical computations
- **Scikit-learn**: For machine learning algorithms and preprocessing
  - Linear Regression model is used for predicting car prices
  - Label Encoding is applied to categorical features

## Model Training

- The dataset is split into features (`X`) and target variable (`y`, i.e., the car price).
- Categorical features such as `CarName`, `fueltype`, and others are label encoded for use in the model.
- A **Linear Regression** model is trained to predict car prices based on the features.
