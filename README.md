# Logistic Regression and AdaBoost Classifier from Scratch

Implementation of a `Logistic Regression (LR)` classifier and `AdaBoost` algorithm.
The python notebook `solve.ipynb` contains the necessary code to implement the models and evaluate them on different datasets.


## Contents

- [Dataset](#dataset)
- [Workflow of the Implementation](#workflow-of-the-implementation)
  - [Data Preprocessing](#data-preprocessing)
  - [Evaluation of the Models](#evaluation-of-the-models)

## Problem Specification

[CSE472 Assignment 2](CSE472_Assignment_2.pdf)

## Dataset

- [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- [Adult](https://archive.ics.uci.edu/dataset/2/adult)
- [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Workflow of the Implementation

1. Data Preprocessing
1. Implementation of Logistic Regression
1. Implementation of AdaBoost
1. Getting the top features
1. Evaluation of the Models

### Data Preprocessing

Techniques used for data preprocessing:

- Handling missing values using `median`, `quadratic interpolation` imputation or `drop`

> **Note**: Specific Datasets were handled differently based on the nature of the data.

- Encoding categorical variables using `OneHotEncoder` or `LabelEncoder`
- Normalizing the data using `StandardScaler` or `MinMaxScaler`

### Evaluation of the Models

The results of the models were evaluated using the following metrics:

- Accuracy
- Sensitivity
- Specificity
- Precision
- False Discovery
- F1 Score

The results can be found in the `report` folder.
