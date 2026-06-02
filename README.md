# Customer-Churn-Intelligence-System
End-to-end customer churn analytics and prediction system using Python, feature engineering, model comparison, and business-driven retention insights.


## Overview

Customer churn is one of the most critical challenges faced by subscription-based businesses. Acquiring a new customer is often significantly more expensive than retaining an existing one, making customer retention a key business objective.

This project develops an end-to-end customer churn analytics and prediction pipeline using the Telco Customer Churn dataset. The objective is to identify customers likely to leave, understand the factors influencing churn, and generate actionable business recommendations to improve customer retention.

---

## Dataset

**Source:** IBM Telco Customer Churn Dataset

The dataset contains information about telecom customers, including:

* Customer demographics
* Account information
* Subscription details
* Internet services
* Billing information
* Contract types
* Customer churn status

### Dataset Size

* Records: 7,043 customers
* Features: 21 attributes

---

## Project Objectives

* Analyze customer behavior and churn patterns
* Identify key drivers of customer attrition
* Perform feature engineering to improve predictive performance
* Compare multiple machine learning models
* Evaluate models using industry-standard metrics
* Generate business recommendations for customer retention

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Joblib

---

## Project Workflow

### 1. Data Cleaning

* Handled missing values in TotalCharges
* Converted incorrect data types
* Removed unnecessary identifiers
* Checked for duplicate records

### 2. Feature Engineering

Created additional business-oriented features:

* Customer Lifetime Value (CLV)
* Average Monthly Spend
* Tenure Groups

### 3. Exploratory Data Analysis (EDA)

Performed detailed analysis to understand:

* Churn distribution
* Contract type impact
* Tenure trends
* Billing behavior
* Internet service influence
* Payment method patterns

### 4. Data Preprocessing

* One-Hot Encoding
* Feature Scaling
* Train-Test Split
* Class imbalance handling

### 5. Machine Learning Models

The following classification models were evaluated:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier
* XGBoost Classifier

### 6. Model Evaluation

Models were compared using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## Key Insights

### High Churn Risk Customers

Analysis revealed that customers are more likely to churn when they:

* Have month-to-month contracts
* Are new customers with low tenure
* Use electronic check payments
* Lack technical support services
* Have higher monthly charges

### Customer Retention Opportunities

Potential retention strategies include:

* Promoting long-term contracts
* Providing onboarding programs for new customers
* Offering bundled technical support plans
* Creating targeted retention campaigns for high-risk customers

---

## Results

### Best Performing Model

XGBoost achieved the strongest overall performance for churn prediction.

### Important Features

Top factors influencing churn:

1. Contract Type
2. Tenure
3. Monthly Charges
4. Tech Support
5. Internet Service Type
6. Payment Method
7. Customer Lifetime Value


Data Analytics | Machine Learning | Business Analytics
