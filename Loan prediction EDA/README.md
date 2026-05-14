# Loan Approval Prediction - Exploratory Data Analysis (EDA) 🏦

## 📌 Project Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) on the **Loan Approval Dataset**. The primary objective is to identify the key factors that influence loan eligibility and to understand the relationships between various applicant attributes (financial, social, and behavioral) and the final loan status.

---

## 🛠️ Tech Stack & Libraries
The analysis was performed using Python and the following data science libraries:
- **Data Manipulation:** matplotlib.pyplot, pand, numpy, seaborn, plotly.express
- **Visualization:** Matplotlib, Seaborn, Plotly

---

## 📂 Dataset Description
The dataset includes several features critical to financial risk assessment:
- **Personal Details:** Gender, Marital Status, Education, Dependents.
- **Financial Status:** Applicant Income, Co-applicant Income, Loan Amount, Loan Term.
- **Credit Profile:** Credit History (Repayment reliability).
- **Property Info:** Property Area (Urban, Semi-urban, Rural).
- **Target Variable:** Loan_Status (Approved/Rejected).

---

## 🔍 Key Steps in the Analysis

### 1. Data Cleaning & Preprocessing
- **Missing Value Treatment:** Identified and handled null values in critical columns like `Credit_History`, `Self_Employed`, and `LoanAmount`.
- **Feature Engineering:** (e.g., Total Income, Income-to-Loan Ratio) to better capture applicant affordability.

### 2. Univariate Analysis
Explored the distribution of individual variables to identify skewness (e.g., right-skewed income data) and outliers using:
- Histograms & KDE Plots
- Count Plots for categorical features

### 3. Bivariate & Multivariate Analysis
Investigated the relationship between the target variable (`Loan_Status`) and predictors:
- **Credit History vs. Approval:** Analyzed how repayment history dictates the bank's decision.
- **Income Segments:** Visualized how total household income affects loan capacity.
- **Categorical Interactions:** Used Treemaps and Stacked Bar charts to see the combined impact of Marital Status and Dependents.

---

## 💡 Key Business Insights
Based on the analysis, the following conclusions were drawn:
1. **Credit History is King:** Applicants with a positive credit history have a significantly higher probability of approval.
2. **The "Affordability" Balance:** It’s not just about high income; the ratio of the requested Loan Amount to the Total Household Income is a stronger indicator of risk.
3. **Household Support:** The presence of a co-applicant often strengthens the financial profile, leading to higher approval rates for married applicants.
4. **Demographic Trends:** Semi-urban properties show a higher approval trend compared to other regions.

---

## 🚀 Conclusion
The EDA demonstrates that lending decisions are a balance of **Repayment Reliability** and **Sustainability**. This analysis serves as a foundation for building robust machine learning models to automate the loan approval process.

---
*Created by Prakash Rawat as part of a Data Science Portfolio.*

