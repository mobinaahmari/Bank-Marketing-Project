# Bank Marketing ML Project

This project involves preprocessing, exploring, and modeling the Bank Marketing dataset using Python and machine learning techniques.

## Dataset
- Original CSV: `bank-additional-full.csv`
- Preprocessed CSV: `bank-marketing-preprocessed.csv`
- Dataset source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

## Features
- Categorical variables: job, marital, education, month, day_of_week, poutcome
- Numerical variables: duration, campaign, pdays, previous, emp.var.rate, cons.price.idx, cons.conf.idx, euribor3m, nr.employed

## Models Implemented
1. Logistic Regression
2. Support Vector Machine (Linear & RBF)
3. Ridge Regression
4. Polynomial Regression

## Preprocessing Steps
- Handle missing values
- One-hot encoding for categorical features
- Standardization of numerical features
- Handling class imbalance (upsampling & SMOTE)
