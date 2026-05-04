# 🚗 Used Car Market Analysis & Pricing Strategy

## 📌 Project Overview
This project involves a deep-dive **Exploratory Data Analysis (EDA)** of the used car market. The goal was to identify the primary drivers of vehicle valuation and develop a logic-based model to distinguish between fair market value and overpriced listings.

### 🎯 Key Business Objectives
* **Predictive Insights:** Evaluate how age, mileage, and brand reputation impact resale value.
* **Operational Efficiency:** Automate data cleaning to handle anomalies in mileage and manufacturing years.
* **Strategic Decision Making:** Differentiate between "Prediction" (what the price is) and "Decision Making" (whether the car is a good buy).

---

## 🛠️ Technical Implementation

### 1. Data Cleaning & Robustness
To ensure high-quality analysis, the following preprocessing steps were executed:
* **Anomaly Detection:** Identified and removed "future" manufacturing years and invalid fuel categories.
* **Outlier Management:** Addressed extreme price points (e.g., $0 or $999,999) using median imputation to maintain a balanced distribution[cite: 1].
* **Missing Value Strategy:** Handled null values in mileage and engine specifications to prevent biased correlations[cite: 1].

### 2. Custom Depreciation Logic
I developed a Python-based function to calculate the **Intrinsic Depreciated Value** of each vehicle, assuming a base year of 2026[cite: 1]:
* **Tier 1 (0–5 Years):** 15% annual depreciation[cite: 1].
* **Tier 2 (> 5 Years):** 10% annual depreciation[cite: 1].

**Price Evaluation Formula:**  
`Actual Listing Price - Calculated Depreciated Value = Price Difference`[cite: 1]

| Result | Market Interpretation |
| :--- | :--- |
| **Positive Difference** | Overpriced: Listing exceeds calculated depreciation[cite: 1]. |
| **Negative Difference** | Underpriced: Potential "Good Deal" for buyers[cite: 1]. |
| **Near Zero** | Fair Market Value: Aligns with standard depreciation curves[cite: 1]. |

---

## 📊 Key Findings (EDA)
* **Price Skewness:** After cleaning, the price distribution achieved a skewness of approximately **-0.089**, indicating a near-normal distribution suitable for statistical modeling[cite: 1].
* **Brand Dominance:** High-tier brands like Toyota and Honda showed lower depreciation rates compared to luxury or niche brands[cite: 1].
* **Risk Factors:** Vehicles exceeding 15 years were categorized as "High Risk" due to accelerated value loss[cite: 1].

---

## 🚀 How to Use
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Prakash-rawat485/Learning-core-python.git](https://github.com/Prakash-rawat485/Learning-core-python.git)
