# Prosper Loan Data Exploration

### 📊 Project Overview

This project explores the Prosper loan dataset to uncover trends, borrower behaviors, and factors influencing loan performance. Using Python and data visualization techniques, the analysis examines key variables such as credit scores, loan status, income ranges, and debt-to-income ratios to gain insights into credit risk and lending patterns.

### 🎯 Key Objectives
* Understand the distribution and characteristics of loans and borrowers.

* Explore relationships between variables like Credit Score, Loan Status, Income Range, Debt-to-Income Ratio, etc.

* Identify trends and outliers in the dataset to inform potential modeling efforts
### 🧰 Tools & Libraries
* Python

* pandas

* numpy

* matplotlib

* seaborn

* Jupyter Notebook

### 📌 Dataset
The Prosper Loan data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.But I have selected few features for my analysis. So my data set contains 84853 Rows and 14 Columns.

### 📈 Insights Summary

The primary goal of this analysis was to identify the key features that influence the BorrowerRate, which is a critical factor for potential borrowers. I selected BorrowerRate as the target variable due to its importance in reflecting loan affordability and risk.

Key findings include:

* Prosper Score and Credit Score show strong relationships with both Loan Status and BorrowerRate, indicating their effectiveness in assessing borrower risk and setting interest rates.

* Employment Status and Credit Rating are also valuable predictors, particularly in evaluating the likelihood of loan default. These features can help Prosper more accurately assign interest rates and manage credit risk.

* There is a positive correlation between Loan Amount and Stated Monthly Income, which aligns with expectations — borrowers with higher incomes are typically eligible for larger loans.

* Overall, the analysis supports the use of Prosper Score and credit-related features in shaping lending decisions and pricing loans appropriately.









