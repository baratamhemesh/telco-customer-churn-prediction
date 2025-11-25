<img width="1058" height="598" alt="Screenshot 2025-11-25 130610" src="https://github.com/user-attachments/assets/3c23a29e-a33e-4363-b6d8-9d1224cb7da1" />
Telco Customer Churn Prediction
Overview

This project predicts customer churn in the telecom sector using machine learning and presents key business insights through a Power BI dashboard. The objective is to identify customers most likely to discontinue service and understand the major factors driving churn.

Dataset:

The dataset contains information on:
Customer demographics
Internet and service subscriptions
Contract and billing details
Monthly and total charges
Churn status (Yes/No)
Rows: ~7043
Columns: ~21


Tools and Technologies:

Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
Google Colab
Random Forest Classifier
Power BI
Project Workflow
Data cleaning and preprocessing
Exploratory data analysis
Train-test split
Random Forest model training
Evaluation using accuracy, precision, recall and F1-score
Feature importance analysis
Power BI dashboard creation


Key Insights:

Customers with month-to-month contracts have the highest churn rate.
New customers (0–6 months tenure) churn more frequently than long-term customers.
Customers with high monthly charges are more likely to churn.
Fiber Internet users show higher churn rates than DSL users.
Customers using electronic check as payment method have higher churn.


Recommendations:

Encourage upgrades to annual or biennial contracts through offers.
Improve onboarding and support during the first six months.
Consider pricing adjustments or value additions for high-billing customers.
Investigate service quality for Fiber Internet users.
Promote more convenient billing methods to reduce churn from electronic check users.

Repository Contents

Machine learning notebook (Churn Prediction.ipynb)

Clean dataset (clean_telco.csv)

Power BI dashboard (Telco_Customer_Churn_Dashboard.pbix)

Presentation slide deck (Customer_Churn_Presentation)

README file

Result


This project demonstrates how machine learning and analytics can be used together to identify churn risks, guide customer retention strategies, and support data-driven decision-making.

