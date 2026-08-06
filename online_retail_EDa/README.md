# 🛒 Online Retail II - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project presents an **Exploratory Data Analysis (EDA)** of the **Online Retail II** transactional dataset. The objective is to analyze customer purchasing behavior, sales trends, product performance, seasonal demand, and geographical revenue distribution to uncover actionable business insights.

The analysis focuses on understanding how customers interact with the business and preparing the dataset for future analytics tasks such as customer segmentation, forecasting, and recommendation systems.

---

## 📂 Project Structure

```
├── online_retail_Eda.ipynb      # Complete Exploratory Data Analysis
├── README.md                    # Project documentation
```

---

## 📊 Dataset Information

The dataset contains over **1.06 million retail transactions** with the following features:

| Column | Description |
|---------|-------------|
| Invoice | Unique transaction ID |
| StockCode | Product code |
| Description | Product name |
| Quantity | Number of items purchased |
| InvoiceDate | Transaction date & time |
| Price | Unit price |
| Customer ID | Customer identifier |
| Country | Customer location |

The dataset is ideal for customer analytics, revenue analysis, product performance evaluation, and time-series business intelligence.

---

# 🎯 Project Objectives

This analysis answers several important business questions:

- How frequently do customers purchase products?
- Which products generate the highest revenue?
- Who are the highest-value customers?
- How does revenue change over time?
- Are there seasonal sales patterns?
- Which countries contribute the most revenue?
- What data quality issues exist?
- How can the data be prepared for future machine learning projects?

---

# 🧹 Data Cleaning

Several preprocessing steps were performed before analysis:

- Converted `InvoiceDate` to datetime format
- Converted numeric columns to appropriate data types
- Created a **Revenue** column (`Quantity × Price`)
- Removed duplicate records
- Trimmed unnecessary whitespace
- Removed cancelled invoices
- Removed zero-price transactions
- Identified negative quantities as returns
- Retained missing Customer IDs for product analysis
- Created additional time-based features:
  - Year
  - Month
  - Day
  - Weekday
  - Hour

---

# 📈 Exploratory Data Analysis

The notebook includes:

- Dataset overview
- Missing value analysis
- Duplicate detection
- Descriptive statistics
- Revenue analysis
- Customer analysis
- Product analysis
- Country-wise sales
- Time-series trends
- Seasonal analysis
- Order quantity distribution
- Correlation analysis
- Outlier detection

---

# 🔍 Key Insights

### 📦 Order Size

- Most purchases contain a small number of products.
- Median order quantity is **4 items**.
- Distribution is highly right-skewed due to bulk orders.

### 💰 Revenue Trends

- Revenue increases significantly during the final quarter.
- **November** records the highest sales.
- Strong holiday-season demand is observed.

### 🕒 Customer Activity

- Peak purchasing hours:
  - **10:00 AM – 3:00 PM**
- Weekdays outperform weekends.
- Saturday has the lowest activity.

### 👥 Top Customers

- A small group of customers generates a large portion of total revenue.
- The dataset exhibits a strong **Pareto (80/20) effect**.

### 🌍 Geographic Performance

- The **United Kingdom** contributes the majority of sales.
- Other countries such as **EIRE** and **Netherlands** contribute much smaller shares.

### 📊 Quantity vs Revenue

- Larger purchase quantities generally generate higher revenue.
- A few extreme transactions create noticeable outliers.

---

# ⚠️ Data Quality Observations

The analysis identified several important issues:

- Missing Customer IDs
- Duplicate transactions
- Negative quantities (returns)
- Zero-price records
- Revenue outliers
- Quantity outliers

These issues were handled appropriately to improve the reliability of the analysis.

---

# 💼 Business Insights

The analysis suggests that:

- Sales are highly seasonal.
- Holiday periods drive significant revenue growth.
- Customer spending is heavily concentrated among a small number of high-value customers.
- Most customers place relatively small orders.
- Business operations are strongly dependent on the UK market.
- Marketing campaigns should be aligned with weekday business hours for maximum effectiveness.

---

# 🚀 Future Work

This cleaned dataset can be used for:

- RFM Customer Segmentation
- Customer Lifetime Value (CLV)
- Market Basket Analysis
- Product Recommendation Systems
- Sales Forecasting
- Demand Prediction
- Customer Churn Prediction
- Time-Series Analysis

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📌 Conclusion

This EDA provides a comprehensive understanding of the **Online Retail II** dataset by uncovering customer purchasing behavior, sales trends, product performance, and geographic revenue distribution.

The project highlights the importance of proper data cleaning and exploratory analysis before predictive modeling. The insights generated can support inventory planning, promotional strategies, customer retention, and future machine learning applications.

---

## ⭐ If you found this project helpful, consider giving it a star!
