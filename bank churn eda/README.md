# 💳 Bank Customer Churn Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a bank customer dataset to understand why customers leave (churn). The goal is to identify key behavioral patterns that lead to churn.

---

## 🎯 Objective

* Analyze customer data to find churn patterns
* Identify important features affecting churn
* Generate actionable insights

---

## 📊 Dataset Description

The dataset contains customer information including:

* Demographics (age, gender, income, etc.)
* Account details (credit limit, card type)
* Customer behavior (transactions, spending, inactivity)

Target Variable:

* **Attrition_Flag** → Indicates whether a customer has churned or not

---

## 🔍 EDA Steps Performed

### 1. Data Understanding

* Checked dataset shape, structure, and data types
* Understood all features

### 2. Data Cleaning

* Verified missing values
* Handled 'Unknown' categories

### 3. Target Variable Analysis

* Calculated churn percentage
* Observed class imbalance

### 4. Univariate Analysis

* Analyzed individual features
* Studied distributions of numerical and categorical variables

### 5. Bivariate Analysis

* Compared features with churn
* Used boxplots and countplots

### 6. Correlation Analysis

* Identified relationships between numerical features
* Detected multicollinearity among credit-related variables

### 7. Feature Engineering

* Created `activity_level` based on transaction count

### 8. Statistical Analysis

* Compared mean, median, and spread between churned and existing customers

---

## 📈 Key Insights

* Most customers (~84%) stay, while ~16% churn
* Churn is **not driven by age or personal details**
* Customers who churn:

  * Perform fewer transactions
  * Spend less money
  * Stay inactive for longer
  * Show declining activity over time
* Transaction count and inactivity are the **strongest indicators of churn**
* Credit-related features show redundancy due to high correlation

---

## 🧠 Final Conclusion

Customers do not leave suddenly. They gradually reduce their usage, spending, and activity before churning. Behavioral features are the most important indicators of churn.

---

## 🚀 Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📌 Future Work

* Build a machine learning model to predict churn
* Handle class imbalance
* Feature selection and model optimization

---

## 👤 Author

* Vicky

