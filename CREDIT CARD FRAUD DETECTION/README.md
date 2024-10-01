# Credit Card Fraud Detection

## Overview

This project focuses on building a machine learning model designed to detect fraudulent credit card transactions. Given the sensitive nature of credit card fraud, identifying fraudulent activities is crucial for financial institutions. This project uses transaction data, preprocesses, and trains a classification algorithm to differentiate between fraudulent and legitimate transactions.

The dataset includes features representing transaction data, and the goal is to predict whether a transaction is fraudulent (1) or legitimate (0). This project evaluates the model using metrics such as **Accuracy**, **Precision**, **Recall**, and **F1-Score**.

## Project Objectives

- **Load and Preprocess transaction data** for effective model training.
- **Train a classification model**, such as Logistic Regression or Random Forest, to distinguish between fraudulent and non-fraudulent transactions.
- **Evaluate the model** using key metrics: Precision, Recall, and F1-Score.
  
## Dataset

The dataset used in this project is a credit card transaction dataset, where each row represents a transaction, and the target variable indicates whether the transaction was fraudulent or not.

The dataset contains the following:
- **Features**: Anonymized features (`V1`, `V2`, `V3`, ..., `V28`), `Time`, and `Amount` representing transaction details.
- **Target**: `Class` (1 for fraud, 0 for legitimate transactions).

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`

You can install the required libraries using the following command:

```bash
pip install pandas numpy scikit-learn
```

## Steps of the code

1. **Data Loading and Preprocessing**:
   - Load the credit card transaction data.
   - Split the data into training and testing sets using `train_test_split`.

2. **Model Training**:
   - Train a **Random Forest** model to classify transactions as fraudulent or legitimate.

3. **Model Evaluation**:
   - The model's accuracy is evaluated using the test set, with metrics such as **Precision**, **Recall**, and **F1-Score** providing deeper insights into the model's performance.

4. **Results**:
   - The model achieved an **Accuracy** of 99.96%.
   - Key metrics:
     - **Precision**: 0.97
     - **Recall**: 0.78
     - **F1-Score**: 0.87
