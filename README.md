# Home_loan_default

# Home Loan Default Prediction

A machine learning project to predict whether a customer is likely to default on a home loan using structured financial and demographic data.

📌 # Project Overview

Financial institutions face major risks by issuing loans to customers who may default. This project builds a predictive model that can help banks and lending agencies identify customers who are more likely to default, enabling data-driven lending decisions.

🎯 # Objective

Analyze customer application and payment history data

Perform data cleaning, preprocessing, feature engineering

Train ML models to predict the probability of loan default

Evaluate and compare model performances

Provide insights that support risk-aware lending

🗂 # Dataset

This project uses multiple datasets supplied by the bank:

1. application_train.csv

Main dataset used for training

Rows: 307,511

Columns: 122

Includes demographics, contract information, credit data, etc.

SK_ID_CURR – Unique customer identifier

TARGET – Target variable

0 → Loan fully repaid

1 → Loan defaulted

2. Other data files (if provided)

Credit bureau records

Previous loan records

Installment payments

POS cash balance

Loan application history

Each supplemental dataset is merged using SK_ID_CURR to enrich the customer profile.

🛠 # Data Preprocessing

Key steps performed:

✔ Handling large number of missing values
✔ Encoding categorical variables
✔ Outlier removal and scaling
✔ Dataset merging on customer ID
✔ Feature selection and reduction
✔ Exploratory Data Analysis

Patterns in demographics

Financial behavior trends

Default correlations

📊 # Exploratory Data Analysis (EDA)

The notebook includes several insights and visualizations:

Distribution of default vs non-default customers

Relationship between income, education, age, job type, and loan outcomes

Trends in repayment behavior

Flag features indicating financial risk

🤖 # Machine Learning Models

Multiple models were trained and compared:

Logistic Regression

Random Forest

Gradient Boosting / XGBoost

Support Vector Machines

Other potential models tested

Model performance comparison included:

Accuracy

Precision, Recall, F1 Score

ROC-AUC

Confusion Matrix
