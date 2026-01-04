# Banking Customer Churn Prediction
Assessing the causes of customer churn in the Banking sector

A data-driven machine learning project focused on **predicting customer churn in the banking sector**.  
This project leverages exploratory data analysis and supervised learning models to identify customers at high risk of leaving, enabling banks to take **proactive, targeted retention actions**.

**Motivation:**  
Customer acquisition is significantly more expensive than retention. By predicting churn early and understanding its drivers, financial institutions can improve customer lifetime value, reduce revenue leakage, and design smarter engagement strategies.

---

**Model Pipeline Overview**
[ Raw Data ] → [ Cleaning & EDA ] → [ Feature Engineering ] → [ ML Models ] → [ Churn Prediction ]

# Key Features

**Exploratory Data Analysis (EDA)**  
  Deep dive into customer demographics, account behavior, and churn patterns.

**Feature Engineering**  
  Encoding categorical variables, scaling numeric features, and optimizing inputs for ML models.

**Predictive Modeling**  
  Implementation and comparison of multiple classification models such as:
  - Logistic Regression  
  - Random Forest  
  - Gradient Boosting / XGBoost (if applicable)

**Model Evaluation**  
  Performance measured using:
  - Accuracy  
  - Precision & Recall  
  - F1-score  
  - ROC-AUC

**Business Insights**  
  Identification of high-impact churn drivers (e.g., tenure, balance, activity level).


**Project Structure**
Banking-Customer-Churn
┣ Banking_CustomerChurn.ipynb
┣ assets
┃ ┣ eda.png
┃ ┣ model_comparison.png 
┃ ┗ feature_importance.png
┗ README.md

---

## Installation & Setup

**Clone the Repository**

git clone https://github.com/your-username/banking-customer-churn.git
cd banking-customer-churn 

- Run the Notebook
jupyter notebook Banking_CustomerChurn.ipynb

**Dataset Overview**
Type: Tabular banking customer data
Target Variable: Churn (Binary: Yes / No)
10 000+ rows
Key Features Include:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Estimated Salary
Dataset was derived from a real-world banking churn dataset from Kaggle

**Results & Insights**
- Customers with low tenure and low engagement show higher churn probability.
- Account balance and number of products are strong churn indicators.
- Ensemble models outperform baseline linear models in recall and ROC-AUC.
- Predictive modeling enables early intervention strategies, such as personalized offers or outreach.


**Tech Stack**
Language: Python
Environment: Jupyter Notebook
Libraries:
pandas, numpy
matplotlib, seaborn
scikit-learn

## Author
Shingai Kamoto
MBA Candidate (Business Analytics) | Data & Strategy Enthusiast
Focus Areas: Analytics, Operations, Strategy, Machine Learning
