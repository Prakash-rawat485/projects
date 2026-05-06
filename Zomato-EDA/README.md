
# 🍽️ Zomato Dataset — Exploratory Data Analysis (EDA)

## 📌 Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of the Zomato dataset, focusing on understanding restaurant trends, customer preferences, pricing patterns, and rating behavior.

The analysis aims to extract actionable insights that can help in **business decision-making, market understanding, and recommendation systems**.

---

## 🎯 Objectives

* Analyze restaurant distribution across locations
* Understand factors influencing restaurant ratings
* Study pricing trends and affordability
* Identify popular cuisines and service types
* Examine the relationship between cost, rating, and votes

---

## 📂 Dataset Description

The dataset contains information about restaurants listed on Zomato, including:

* **Restaurant Name**
* **Location / City**
* **Cuisines**
* **Average Cost for Two**
* **Price Range**
* **Rating (Aggregate Rating)**
* **Votes**
* **Online Delivery Availability**
* **Table Booking Availability**

---

## 🧱 Workflow

### 1. Data Understanding

* Loaded and explored dataset structure
* Reviewed column meanings and distributions
* Identified key variables for analysis

---

### 2. Data Cleaning

* Handled missing or inconsistent values
* Removed irrelevant columns (if any)
* Converted data types where necessary
* Cleaned rating formats (e.g., "NEW", "-")

---

### 3. Univariate Analysis

* Distribution of ratings
* Distribution of cost for two
* Frequency of restaurants by location
* Most common cuisines

---

### 4. Bivariate Analysis

* Cost vs Rating relationship
* Votes vs Rating correlation
* Online delivery vs rating comparison
* Table booking vs pricing insights

---

### 5. Multivariate Analysis

* Location + cuisine + rating interaction
* Price range vs service availability
* High-rated vs low-rated restaurant characteristics

---

### 6. Data Visualization

* Bar charts for categorical insights
* Histograms for distribution analysis
* Boxplots for outlier detection
* Heatmaps for correlation analysis

---

## 📊 Key Insights

* **Ratings are heavily skewed**
  → Most restaurants fall in mid-range ratings (3.0–4.0)

* **Votes strongly correlate with ratings**
  → Higher engagement often indicates better-rated restaurants

* **Cost does not always determine quality**
  → Expensive restaurants are not necessarily highly rated

* **Online delivery is common but not a rating driver**
  → Convenience ≠ quality perception

* **Certain cuisines dominate the market**
  → Reflects regional demand patterns

---

## 📈 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📌 Use Cases

* Restaurant recommendation systems
* Market segmentation analysis
* Pricing strategy optimization
* Customer preference analysis

---

## ⚠️ Limitations

* Dataset may not be fully up-to-date
* Ratings may be biased or user-dependent
* External factors (ambience, service quality) not captured

---

## 🚀 Future Work

* Build a **restaurant recommendation model**
* Perform **sentiment analysis on reviews**
* Apply **clustering for restaurant segmentation**
* Use **machine learning to predict ratings**

---

## 📎 Project Structure

```id="c4p0l2"
📁 zomato-eda
│── 📄 zomato_.ipynb
│── 📄 README.md
```

---

## 👨‍💻 Author

This project was developed as part of a data analysis practice to strengthen skills in **EDA, visualization, and insight generation**.

---

## ⭐ Contribution

Contributions and suggestions are welcome. Feel free to fork and enhance the analysis.

---
