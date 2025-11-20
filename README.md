Task 5: EDA
📝 Project Overview

This project is part of my Data Analyst Internship (Task 5), where I performed Exploratory Data Analysis (EDA) on the Titanic dataset using Python and Pandas.
The goal is to understand the dataset, clean it, analyze it, and generate insights through visualizations.

🛠 Tools Used

Python

Pandas (main library used)

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📄 Dataset Used

Titanic Dataset – Yasser H (Kaggle)
File: Titanic-Dataset.csv

🚀 Work Done
1. Data Loading & Basic Check

Loaded CSV using Pandas

Viewed rows, columns, datatypes

Found missing values using .isnull().sum()

Generated summary statistics using .describe()

2. Data Cleaning (Pandas)

Filled missing Age with median

Filled Embarked with mode

Dropped Cabin due to many missing values

Managed categorical and numerical columns

3. Exploratory Data Analysis

Using Pandas + visualization libraries:

Age distribution

Fare distribution

Count of Sex

Count of Passenger Class

Survival comparison with Gender & Class

4. Correlation Analysis

Created correlation matrix using Pandas

Visualized with heatmap

5. Feature Engineering

Extracted Title from Name using Pandas string functions

Created AgeGroup using Pandas cut()

🔍 Key Findings

Females survived more than males

1st class passengers had higher survival rates

Children had better survival chances

Higher fare = higher probability of survival

Title feature (Mr, Mrs, Miss…) showed survival trends

📁 Files Included

Task5_EDA.ipynb – EDA notebook

Titanic-Dataset.csv – Dataset used

Task5_EDA_Report.pdf – PDF summary

README.md – This file

🏁 Conclusion

This EDA task helped me understand how to use Python Pandas for data loading, cleaning, visualization, and extracting insights.
The project improved my skills in preparing data and analyzing patterns effectively.
