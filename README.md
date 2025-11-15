# Data-analytics-Daily-task
This repository contains my data analyst practice projects using python
Dataset: Mall Customer Dataset (from Kaggle)
Objective: Clean and preprocess data for analysis
Steps performed:
Loaded the dataset into a Pandas DataFrame.
Verified column names and dataset structure using head().
Checked for missing values using isnull().sum() — no missing values found.
Checked for duplicate rows — no duplicates found.
Cleaned the column names by:
converting to lowercase
replacing spaces with _
removing special characters
Standardized the Gender column by converting it to lowercase and removing spaces.
Generated statistical summary using describe() to understand data distribution.
Performed outlier detection on Age, Annual Income, and Spending Score — no outliers found.
Exported the final cleaned dataset as Mall_Customers_Cleaned.csv.
