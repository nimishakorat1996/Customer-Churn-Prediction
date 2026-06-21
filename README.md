# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn is one of the most critical challenges faced by subscription-based businesses such as telecom companies, banks, insurance providers, and SaaS companies. Acquiring a new customer is often more expensive than retaining an existing one. Therefore, identifying customers who are likely to leave can help organizations take proactive measures and improve customer retention.

This project focuses on predicting customer churn using machine learning techniques on the IBM Telco Customer Churn dataset. The project covers the complete Data Science lifecycle, including data cleaning, exploratory data analysis, feature engineering, machine learning model development, model evaluation, explainable AI, and model deployment preparation.

---

## Business Problem

A telecommunications company wants to identify customers who are likely to discontinue their services.

### Objectives

- Analyze customer behavior and service usage patterns.
- Identify factors contributing to customer churn.
- Build machine learning models to predict churn.
- Compare multiple algorithms and select the best-performing model.
- Provide actionable business recommendations to reduce customer attrition.

---

## Dataset Information

### Dataset Source

IBM Telco Customer Churn Dataset

### Dataset Features

- Customer demographics
- Account information
- Contract details
- Billing information
- Service subscriptions
- Customer churn status

### Target Variable

- **Churn**
  - Yes = Customer Left
  - No = Customer Stayed

---

## Technology Stack

### Programming Language

- Python

### Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- SHAP
- Joblib

### Development Environment

- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

- Imported IBM Telco Customer Churn Dataset
- Loaded data using Pandas

### 2. Data Cleaning

Performed:
- Missing value handling
- Data type conversion
- Duplicate checking
- Invalid value correction
- Removal of unnecessary columns

### 3. Exploratory Data Analysis (EDA)

Analyzed:
- Churn distribution
- Customer tenure
- Monthly charges
- Contract types
- Internet services
- Payment methods

Visualizations:
- Count Plots
- Histograms
- Box Plots
- Correlation Analysis

### 4. Feature Engineering

Implemented:
- Label Encoding
- Feature Transformation
- Feature Selection
- Data Standardization

### 5. Machine Learning Models

#### Logistic Regression
Baseline classification model.

#### Random Forest Classifier
Ensemble learning model for improved performance.

#### XGBoost Classifier
Advanced gradient boosting model used as the final model.

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## Explainable AI

SHAP (SHapley Additive Explanations) was used to:

- Interpret model predictions
- Identify important features
- Improve model transparency

### Important Features

- Contract Type
- Monthly Charges
- Tenure
- Internet Service
- Payment Method

---

## Results

### Model Comparison

| Model | Purpose |
|---------|----------|
| Logistic Regression | Baseline Model |
| Random Forest | Ensemble Learning |
| XGBoost | Final Selected Model |

XGBoost achieved the best predictive performance and was selected as the final model.

---

## Business Insights

Customers are more likely to churn if they:

- Have month-to-month contracts
- Have shorter tenure
- Pay higher monthly charges
- Do not subscribe to additional support or security services

### Recommendations

- Encourage long-term contracts
- Provide loyalty rewards
- Improve customer engagement
- Target high-risk customers with retention campaigns

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction_Advanced.ipynb
│
├── models/
│   ├── customer_churn_model.pkl
│   └── scaler.pkl
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── app.py
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Enhancements

- Streamlit Web Application
- Hyperparameter Tuning
- Cross Validation
- SMOTE for Class Imbalance
- Cloud Deployment (AWS/Azure)
- Real-Time Prediction API

---

## Learning Outcomes

This project demonstrates:

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Machine Learning
- Explainable AI
- Model Evaluation
- Business Problem Solving

---
