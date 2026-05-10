# 📊 E-Commerce Customer Churn Analysis & Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Data Science](https://img.shields.io/badge/Field-Data%20Science-success.svg)]()
[![Portfolio](https://img.shields.io/badge/Project-Portfolio-orange.svg)]()

## 📝 Project Overview
This project performs an in-depth **Exploratory Data Analysis (EDA)** on e-commerce customer behavior to identify key drivers of churn. By utilizing complex multivariate visualizations—including **Hexbin Plots**, **Clustermaps**, and **Mosaic Plots**—this analysis uncovers the relationship between customer satisfaction, engagement, and price sensitivity.

## 🚀 Key Insights
* **The Engagement Threshold:** Customers with an engagement score below **4.5** are in the "Danger Zone," regardless of their satisfaction levels.
* **Passive Churn:** Identified a segment of customers who are "Happy but Gone"—high satisfaction scores but very low engagement.
* **The Deal-Hunter Loop:** A **0.96 correlation** between Price Sensitivity and Discount Usage suggests that high-discount strategies may be training customers to only buy during sales.
* **Loyalty Protection:** Mosaic Plot analysis reveals that **Loyalty Membership** significantly reduces the proportion of churn, acting as a primary retention anchor.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Statsmodels
- **Environment:** Jupyter Notebook

## 📂 Visualizations Explained

### 1. Hexbin Plot (Density Analysis)
Used to solve the "overplotting" problem in massive datasets, allowing us to see the density of customer concentration between **Return Rate** and **Satisfaction Score**.

### 2. Hierarchical Clustermap
Automatically grouped features into "Families" based on behavior:
- **The Happiness Family:** Satisfaction Score & Product Reviews.
- **The Deal Family:** Price Sensitivity & Discount Usage.
- **The Loyalty Family:** Account Age & Total Orders.

### 3. Mosaic Plot (Proportional Risk)
A multivariate tool that encodes population size into the **width** of the boxes, proving that while non-members are fewer in number, they churn at a much higher vertical rate than loyalty members.

## 📉 Visual Summary
| Visualization | Key Takeaway |
| :--- | :--- |
| **Correlation Heatmap** | Support tickets are the #1 negative driver of satisfaction (-0.79). |
| **Bubble Chart** | "At-Risk Whales" (Big spenders with low engagement) are the highest priority for recovery. |
| **Pairplot** | Engagement Score shows a clear vertical decision boundary for churn. |

## Author:
prakash rawat(data scientist)
