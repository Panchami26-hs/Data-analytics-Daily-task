Objective:
Clean and prepare a raw dataset containing customer demographic and spending information.

Tools Used:

Python (Pandas)

Jupyter Notebook

Output:

Cleaned dataset → Mall_Customers_Cleaned.csv

Summary of Cleaning Steps (Mall Customer Dataset)

Loaded the raw Mall Customers dataset from Kaggle.

Checked for missing values and found none.

Checked for duplicate rows and found none.

Cleaned column names:

Converted to lowercase

Replaced spaces with _

Removed special characters

Standardized Gender column:

Stripped extra spaces

Converted to lowercase (male, female)

Converted data types to appropriate formats.

Performed statistical summary using df.describe().

Checked for outliers in Age, Income, and Spending Score — none found.

Exported cleaned dataset as Mall_Customers_Cleaned.csv.


