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
| Logistic Regression | Linear model for binary classification | 0.91 | 0.95 |
| Decision Tree Classifier | Tree-based classifier to capture nonlinear relationships | 0.89 | 0.92 |
| Random Forest Classifier | Ensemble model combining multiple trees for higher accuracy | **0.93** | **0.96** |


🔹 The Random Forest Classifier gave the best performance and was selected as the final model.

🔹 Hyperparameter tuning was performed using GridSearchCV to optimize model performance.

🔹 Evaluation metrics used:

🧾 3. Dataset Used

Dataset: Bank Marketing Dataset

Source: UCI Machine Learning Repository

File Used: bank-additional-full.csv

⚙️ 4. Tools and Technologies

Python,Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
GridSearchCV, ROC-AUC, Accuracy Score

📈 5. Results and Insights

🔍 Model Insights:

The Random Forest Classifier performed best with an accuracy of around 93% and ROC-AUC of 0.96.

Important features influencing customer subscription:

-duration (call duration)

-poutcome_success (previous campaign success)

-contact_cellular (contact type)

-month_mar, month_oct (month of contact)

-pdays (days since last contact)

💡 Marketing Recommendations:

1. Target customers who had a successful previous campaign and were contacted via cellular.

2. Focus campaigns in high-performing months (e.g., March, October).

3. Personalize communication based on customer age, job type, and call duration.

4. Avoid over-contacting (limit campaign count) to reduce negative responses.

5. Retrain model periodically using the latest campaign data to adapt to changing trends.
