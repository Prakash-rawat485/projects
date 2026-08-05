<div align="center">

# 🍔 Food Delivery Time Prediction
### Exploratory Data Analysis (EDA) & Data Cleaning

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=26&duration=3500&pause=800&color=36BCF7&center=true&vCenter=true&width=900&lines=Exploratory+Data+Analysis;Data+Cleaning+Pipeline;Business+Insights;Geospatial+Analysis;Delivery+Time+Prediction+Project" />

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-success?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)

</p>

---

> **Transforming raw food delivery data into meaningful business insights through professional data cleaning and exploratory data analysis.**

</div>

---

# 📑 Table of Contents

- Project Overview
- Dataset
- Objectives
- Data Cleaning
- Exploratory Data Analysis
- Business Insights
- Key Findings
- Technologies
- Project Structure
- Future Improvements
- Author

---

# 🚀 Project Overview

Food delivery platforms generate thousands of orders every day. Understanding the factors that influence delivery time is essential for improving customer satisfaction and operational efficiency.

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on a real-world food delivery dataset.

The analysis focuses on:

- Data Cleaning
- Missing Value Treatment
- Feature Engineering
- Distribution Analysis
- Temporal Analysis
- Geographical Analysis
- Business Insights
- Data Quality Assessment

The final cleaned dataset becomes suitable for machine learning models that predict food delivery time.

---

# 📊 Dataset Information

The dataset contains information about

- Delivery Partner
- Restaurant
- Customer Location
- Vehicle Condition
- Weather
- Delivery Time
- Ratings
- Traffic
- City
- Festival
- Multiple Deliveries
- Order & Pickup Time

---

# 🎯 Objectives

✔ Understand dataset quality

✔ Clean inconsistent data

✔ Remove invalid records

✔ Create useful features

✔ Explore numerical variables

✔ Analyze categorical variables

✔ Study geographical patterns

✔ Discover operational insights

✔ Prepare data for Machine Learning

---

# 🧹 Data Cleaning Pipeline

The raw dataset contained multiple quality issues that were systematically resolved.

### ✔ Missing Values

- Converted string `"NaN"` into proper missing values.
- Inspected missing values across all columns.

---

### ✔ Duplicate Records

- Verified duplicate observations.
- Confirmed dataset uniqueness.

---

### ✔ Data Type Conversion

Converted

- Age
- Ratings
- Multiple Deliveries

to numeric format.

Converted

- Order Date
- Order Time
- Pickup Time

into datetime objects.

---

### ✔ Text Cleaning

Standardized

- Weather Conditions
- City Names
- Target Variable

Removed unwanted text from

```
Time_taken(min)
```

---

### ✔ Feature Engineering

Created

```
Preparation Time
```

using

```
Pickup Time - Order Time
```

Corrected negative values caused by midnight crossover.

---

### ✔ Coordinate Validation

Detected invalid GPS coordinates

```
(0,0)
```

for both

- Restaurant

- Delivery Location

These records were flagged for removal during spatial analysis.

---

# 📈 Exploratory Data Analysis

The project explores

## Numerical Variables

- Age
- Ratings
- Delivery Time
- Preparation Time

using

- Histogram
- KDE
- Boxplot
- Statistical Summary

---

## Categorical Variables

Analyzed

- Vehicle Condition
- Multiple Deliveries
- Weather
- Traffic
- City

using Countplots and Frequency Analysis.

---

## Temporal Analysis

Analyzed

- Order Placement Time

- Pickup Time

to identify

- Peak Hours

- Off-Peak Hours

- Restaurant Efficiency

---

## Geographical Analysis

Visualized

- Restaurant Locations

- Delivery Locations

Detected invalid GPS records and observed operational clusters.

---

# 📊 Major Findings

## 👨 Delivery Partners

- Average age ≈ **30 years**
- Majority between **20–40 years**
- Very few age outliers

---

## ⭐ Customer Ratings

- Average Rating **4.63**
- Median **4.70**
- Ratings are highly concentrated above **4.5**
- Excellent customer satisfaction

---

## 🚚 Delivery Time

- Average delivery time **26 minutes**
- Most deliveries finish within **18–35 minutes**
- Few extreme delays exceed **50 minutes**

---

## 🍽 Preparation Time

- Average preparation time **10 minutes**
- Very stable process
- Minimal variability

---

## 📦 Multiple Deliveries

Most riders deliver

- One order at a time

Multiple deliveries are relatively uncommon.

---

## 🚲 Vehicle Condition

Vehicle conditions

```
0
1
2
```

appear almost equally distributed.

Condition **3** is very rare.

---

## 🌍 Geographic Analysis

Restaurant and customer locations form

clear delivery clusters.

Detected invalid

```
(0,0)
```

coordinates.

---

## 🕒 Order Trends

Peak demand occurs during

**6 PM – 11 PM**

Restaurant pickups closely match order placements, indicating efficient coordination.

---

# 💼 Business Insights

The EDA reveals several operational insights:

✔ High customer satisfaction

✔ Stable restaurant preparation

✔ Efficient pickup operations

✔ Evening demand dominates business

✔ Delivery network concentrated in urban regions

✔ Dataset quality significantly improved after preprocessing

---

# 📂 Project Structure

```
Food-Delivery-EDA/

│

├── Data/

│      train.csv

│

├── Notebook/

│      Food_Delivery_EDA.ipynb

│

├── Images/

│      Histogram.png

│      Boxplot.png

│      Heatmap.png

│      Scatter.png

│

├── README.md

│

└── requirements.txt
```

---

# 🛠 Technologies Used

| Tool | Purpose |
|-------|----------|
| Python | Programming |
| Pandas | Data Cleaning |
| NumPy | Numerical Operations |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Analysis |

---

# 🔮 Future Improvements

- Machine Learning Model
- Feature Selection
- Hyperparameter Tuning
- XGBoost
- Random Forest
- LightGBM
- SHAP Explainability
- Interactive Dashboard using Streamlit
- Real-time Delivery Time Prediction

---

# 📌 Conclusion

The exploratory analysis successfully transformed a raw delivery dataset into a clean, structured, and analysis-ready dataset. Key operational patterns—including consistent restaurant preparation times, excellent delivery partner ratings, evening demand peaks, and geographically clustered delivery zones—provide valuable insights for logistics optimization. The cleaned dataset establishes a strong foundation for predictive modeling and future machine learning applications aimed at improving delivery efficiency and customer experience.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&duration=3000&pause=800&color=00C853&center=true&vCenter=true&width=700&lines=Thank+You+for+Visiting!;Happy+Learning!;Keep+Building+Amazing+Projects!" />

</div>
