# Task 1: Data Cleaning & Preprocessing

## Objective
Clean and prepare the Titanic dataset for machine learning.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Steps performed
1. Explored the data (shape, data types, null values): 891 rows, 12 columns
2. Handled missing values: Age filled with median, Embarked with mode, Cabin dropped (687 of 891 missing)
3. Dropped non-useful columns: PassengerId, Name, Ticket
4. Encoded categorical features: Sex (label encoding), Embarked (one-hot encoding)
5. Visualized outliers with boxplots and removed them from Age and Fare using the IQR method (891 rows reduced to 718)
6. Standardized Age and Fare using StandardScaler

## Files
- Titanic-Dataset.csv: original dataset
- titanic_cleaned.csv: cleaned dataset
- Untitled0.ipynb: full code (notebook)
- boxplots_before.png / boxplots_after.png: outlier visualizations
