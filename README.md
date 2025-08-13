# 📊 Bank Marketing ML Project

This project covers **preprocessing, exploration, and modeling** of the Bank Marketing dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).  
The goal is to predict whether a client will subscribe to a term deposit after a marketing campaign.

---

## 📂 Dataset

- **Raw Dataset:** `bank-additional-full.csv`
- **Preprocessed Dataset:** `bank-marketing-preprocessed.csv`
- **Source:** [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

---

## 🔍 Features

**Categorical Variables:**  
`job`, `marital`, `education`, `month`, `day_of_week`, `poutcome`  

**Numerical Variables:**  
`duration`, `campaign`, `pdays`, `previous`, `emp.var.rate`, `cons.price.idx`, `cons.conf.idx`, `euribor3m`, `nr.employed`  

---

## 🛠 Preprocessing Steps

1. Handling missing values (`unknown` replaced or imputed with `mode`).
2. One-Hot Encoding for categorical variables.
3. Standardization for numerical variables.
4. Handling class imbalance via:
   - Random upsampling
   - SMOTE (Synthetic Minority Oversampling Technique)

---

## 🤖 Models Implemented

- Logistic Regression
- Support Vector Machine (Linear & RBF)
- Ridge Regression
- Polynomial Regression

---

## 📈 Results


| Model                          | Accuracy | Precision | Recall | F1 Score | AUC     |
|--------------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression            | 0.8710   | 0.8716    | 0.8711 | 0.8710   | 0.8711  |
| SVM (Linear Kernel)            | 0.8741   | 0.8765    | 0.8744 | 0.8740   | 0.8744  |
| SVM (RBF Kernel)                | 0.9056   | 0.9095    | 0.9059 | 0.9054   | 0.9059  |
| Ridge Regression               | 0.2542   | 0.3107    | 0.1705 | 0.2202   | 0.7374  |
| Polynomial Regression (deg=2)  | 0.0068   | 0.2750    | 0.0045 | 0.0089   | 0.5054  |
