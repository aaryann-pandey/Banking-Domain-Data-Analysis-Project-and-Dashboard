🏦 Bank Customer Data Analysis (BankEDA)

This project performs Exploratory Data Analysis (EDA) on a Banking dataset to uncover patterns in customer behavior, income distribution, and financial activities.
It focuses on cleaning, visualizing, and analyzing customer data to derive key business insights.

📌 Overview

Banking institutions generate large volumes of customer data.
Through EDA, this project aims to identify how income, loans, savings, and account balances relate to customer loyalty and financial habits.

This notebook focuses on:

Loading and cleaning raw banking data

Categorizing customers based on income bands

Exploring distributions of financial and demographic variables

Identifying correlations between key banking metrics

Visualizing relationships using statistical plots

🧠 Dataset

The dataset used is Banking.csv, which contains various financial and demographic attributes of customers.

Feature	Description
Age	Customer’s age
Estimated Income	Annual estimated income
Superannuation Savings	Customer’s retirement savings
Credit Card Balance	Total outstanding balance on credit cards
Bank Loans	Total loan amount
Bank Deposits	Amount deposited in bank accounts
Checking Accounts	Number of checking accounts
Saving Accounts	Number of saving accounts
Foreign Currency Account	Whether the customer holds a forex account
Business Lending	Business loan amount
Loyalty Classification	Customer’s loyalty level
Risk Weighting	Risk category assigned
Properties Owned	Number of properties owned
Joined Bank	Date when the customer joined the bank
⚙ Technologies Used

Python 3

Pandas, NumPy – Data cleaning and manipulation

Matplotlib, Seaborn – Visualization and EDA

Jupyter Notebook – Development environment

🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

Data Cleaning: Handling missing values, formatting dates, and creating income bands (Low, Mid, High)

Univariate Analysis: Histograms of numerical features like deposits, loans, and age

Bivariate Analysis: Regression plots between related variables (e.g., loans vs. credit card balance)

Correlation Heatmap: Measuring relationships among key financial metrics

Categorical Analysis: Examining distributions for occupation, loyalty classification, and risk weighting

Key Insights:

High-income customers tend to maintain larger deposits and savings balances

Loan and credit card balances show positive correlation

Loyalty and income categories reflect diverse financial behaviors

📈 Results

Detailed understanding of customer financial segments

Clear visual insights into income distribution and account usage

Correlation map highlighting key drivers of customer wealth and banking activity
