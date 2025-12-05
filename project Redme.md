HR Analytics – Employee Attrition Prediction
Project Overview

Employee attrition (employees leaving the company) is a major challenge for HR departments.
This project uses Machine Learning to predict whether an employee is likely to leave the organization based on various factors such as job role, salary, working hours, experience, satisfaction level, etc.

The final goal is to provide a predictive model that helps HR teams take preventive actions and improve employee retention.

 Objectives

Analyze employee-related data

Identify factors leading to attrition

Build a machine learning model

Explain model predictions using SHAP

Provide insights for HR decision-making

 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

SHAP (Model Explainability)

Jupyter Notebook

GitHub

 Dataset

The dataset contains employee details such as:

Age

Department

Monthly Income

Years at Company

Job Role

Overtime

Job Satisfaction

Work-life Balance

Attrition (Target Variable)

Steps Involved
1. Data Loading & Cleaning

Import the dataset

Check missing values

Remove duplicates

Convert categorical columns using Label Encoding

2. Exploratory Data Analysis (EDA)

Univariate analysis

Bivariate analysis (Attrition vs. Age, Salary, Overtime)

Correlation heatmap

Key findings added

3. Data Preprocessing

Split data into train & test sets

Apply StandardScaler

Handle class imbalance (if required)

4. Model Building

We tested:

Logistic Regression

(Optional future models) Random Forest, XGBoost

Final chosen model: Logistic Regression
Scaled data was used to improve performance.

5. Model Evaluation

Metrics used:

Accuracy

Confusion Matrix

Precision, Recall, F1-score

6. SHAP Model Explainability

Used SHAP to understand feature contribution

Generated summary plot

Identified most influential factors causing attrition

 Results

Final model accuracy: ~86%

Important features influencing attrition included:

Overtime

Monthly Income

Job Satisfaction

Age

Work-Life Balance
