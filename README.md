# Credit Card Fraud Detection 💳🔍

## Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Fraudulent transactions are rare and highly imbalanced compared to normal transactions, making this an interesting and challenging problem to solve. The goal is to build a model that can identify fraudulent transactions with high precision and accuracy.

## Dataset

The dataset used for this project is the Credit Card Fraud Detection dataset available on Kaggle. It contains 284,807 transactions, of which only 492 (0.17%) are fraudulent.

Features: 30 anonymized features including Time and Amount

Target: Class (1 indicates fraud, 0 indicates no fraud)

## Approach

1. Data Preprocessing

Handled missing values and outliers

Scaled numerical features (Time, Amount) using StandardScaler

Applied SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance

2. Exploratory Data Analysis (EDA)

Visualized the distribution of transactions and identified patterns

Plotted correlation heatmaps, transaction amounts, and fraud detection distribution

3. Machine Learning Models

Several classification models were tested to find the best model for detecting fraud:

Logistic Regression

Decision Trees

Random Forest Classifier

4. Model Evaluation

Metrics: Accuracy, Precision, Recall, and F1-Score

Best model achieved over 99% on the test set with a high recall rate for fraud detection.

## Results

Best Model: Random Forest Classifier with precision of 98%, recall of 96%, and F1-score of 97%

Imbalanced Data Handling: SMOTE significantly improved model performance by balancing the dataset.

## Conclusion

This project demonstrated the effectiveness of machine learning in fraud detection, especially when dealing with imbalanced datasets. Future work could involve using deep learning models or optimizing hyperparameters for better performance.

## Technologies Used

### Programming Language: Python

### Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SMOTE (from imblearn)
