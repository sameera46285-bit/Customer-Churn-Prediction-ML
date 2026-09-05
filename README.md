# Customer-Churn-Prediction-ML
# Customer Churn Prediction Using Machine Learning

## Project Overview

This project focuses on predicting customer churn using machine learning techniques. The project follows an end-to-end machine learning workflow including exploratory data analysis, data preprocessing, model training, hyperparameter tuning, and model evaluation.

## Problem Statement

Customer churn refers to customers discontinuing their subscription or service. The objective of this project is to predict whether a customer is likely to churn based on customer-related information such as age, tenure, usage frequency, support calls, payment delays, subscription type, contract length, total spending, and recent interaction history.

## Goal

The goal is to build and evaluate machine learning models that can predict customer churn and identify important factors associated with customer churn.

## Models Used

* Logistic Regression
* Random Forest Classifier
* Tuned Random Forest Classifier using GridSearchCV

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Final Model Results

The tuned Random Forest achieved:

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 0.9993 |
| Precision | 0.9999 |
| Recall    | 0.9988 |
| F1-Score  | 0.9994 |

## Best Parameters

* Number of Estimators: 200
* Maximum Depth: None
* Minimum Samples Split: 2

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* GitHub

## Project Structure

```text
Customer-Churn-Prediction-ML/
│
├── Sameera_K_FinalProject_MLInternship(1).ipynb
├── model_comparison_results.csv
└── README.md
```
