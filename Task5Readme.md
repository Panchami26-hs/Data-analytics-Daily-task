

These are steps what i did to complete the task
 1. Importing Libraries
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt


 These libraries help in loading the dataset, analyzing data, and creating visualizations.

 2. Loading the Dataset
df = pd.read_csv("train.csv")


 This command loads the Titanic dataset into a DataFrame called df.

 3. Display First Few Rows
df.head()


 Shows the first 5 rows of the dataset to understand what the data looks like.

 4. View Dataset Shape
df.shape


 Tells how many rows and columns are present in the dataset.

 5. Check Dataset Information
df.info()


 Shows column names, data types, and missing values.

 6. Summary Statistics
df.describe()


 Gives statistical values like mean, median, min, max for numerical columns.

 7. Check Missing Values
df.isnull().sum()


 Counts how many missing values are present in each column.

 Visualization Queries
 8. Histogram
df.hist(figsize=(12,6))
plt.show()


   Displays distribution of numerical columns (Age, Fare, etc.).

 9. Count Plot for Survival
sns.countplot(x="Survived", data=df)


   Shows how many passengers survived and how many did not.

 10. Survival vs Gender
sns.countplot(x="Survived", hue="Sex", data=df)


   Compares survival based on gender.

 11. Survival vs Passenger Class
sns.countplot(x="Survived", hue="Pclass", data=df)


  Shows survival differences across 1st, 2nd, and 3rd class passengers.

 12. Boxplot (Age vs Survival)
sns.boxplot(x="Survived", y="Age", data=df)


  Helps understand the age range of passengers who survived vs didn't.

 13. Correlation Heatmap
plt.figure(figsize=(10,6))
sns.heatmap(df.corr(numeric_only=True), annot=True, cmap="coolwarm")
plt.show()


  Shows how different numerical variables are related to each other.

 14. Pairplot (Optional)
sns.pairplot(df[['Survived','Age','Fare','Pclass']])


 Shows multiple graphs comparing relationships between selected columns.


