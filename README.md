# Loan Default Prediction – Credit Risk Analysis

## Project Overview

This project aims to predict whether a borrower will default on a loan using historical LendingClub data (2007–2015).

We use data analysis and machine learning to help **Nordhavn Bank** (a fictional bank) identify high-risk borrowers, improve lending decisions and reduce potential financial losses.

## Business Problem

Can machine learning predict loan defaults more effectively than the bank's current loan approval rule (grades A–D)?

## Project Objectives

- Analyse historical loan data and identify default patterns.
- Calculate key performance indicators (KPIs).
- Clean and prepare the dataset.
- Build and compare two machine learning models.
- Identify the main factors influencing loan defaults.
- Evaluate model performance and fairness.
- Provide data-driven recommendations to the bank.

## Dataset

- **Source:** LendingClub (Kaggle)
- **Period:** 2007–2015
- **Original dataset:** Approximately 2.26 million loans.
- **Project sample:** 100,000 loans.
- **Target variable:** Loan default (1 = Default, 0 = Repaid).

We use loans issued up to 2014 for training and loans from 2015 for testing.

## Machine Learning Models

We compare two classification models:

1. **Logistic Regression:** An interpretable baseline model for predicting loan defaults.
2. **XGBoost:** A gradient boosting model that identifies more complex patterns in the data.

We evaluate both models using:
- ROC-AUC
- Recall
- Precision

We also use SHAP to explain model predictions and investigate potential fairness issues.

## Tools & Technologies

- Python
- Pandas & NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Jupyter Notebook
- Git & GitHub

## Project Structure

```text
loan-default-prediction/
│
├── data/
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_kpi_analysis.ipynb
│   ├── 03_model_comparison.ipynb
│   └── 04_explainability_fairness.ipynb
│
├── outputs/
├── README.md
└── requirements.txt
```

## Expected Outcome

Our goal is to identify the best-performing model, understand the factors behind loan defaults and recommend how Nordhavn Bank can reduce lending risks through data-driven decisions.

## Disclaimer

This is an educational project. Nordhavn Bank is fictional, and the models are developed for learning and demonstration purposes.

## Team

Developed by a team of three beginner data analysts as part of a collaborative data analytics and machine learning project.
