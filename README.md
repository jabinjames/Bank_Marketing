# Bank_Marketing
📊 Portuguese Bank Marketing Analysis

🧩 1. Project Overview

This project analyzes a Portuguese bank’s marketing campaign data to understand customer behavior and predict whether a client will subscribe to a term deposit.

The analysis includes:

Performing Exploratory Data Analysis (EDA) to uncover key patterns and trends.
Building predictive machine learning models to identify potential customers who are most likely to buy the product.
Providing actionable marketing recommendations to improve campaign success rates.

The project is divided into three main tasks:

Task 1: Complete data analysis report (EDA and visualization)

Task 2: Build a predictive model to identify customers likely to buy the product

Task 3: Suggest data-driven marketing strategies for the bank

🧠 2. Model Summary

| **Model Used**           | **Description**                  | **Accuracy**      | **ROC-AUC** |
|----------------|-----------------|---------------|--------------|
| Logistic Regression | Linear model for binary classification | ~0.91 | ~0.95 |
| Decision Tree Classifier | Tree-based classifier to capture nonlinear relationships | ~0.89 | ~0.92 |
| Random Forest Classifier | Ensemble model combining multiple trees for higher accuracy | **~0.93** | **~0.96** |


🔹 The Random Forest Classifier gave the best performance and was selected as the final model.
🔹 Hyperparameter tuning was performed using GridSearchCV to optimize model performance.
🔹 Evaluation metrics used:

