# superstore sales-EDA

# 🏆 Retail Superstore Sales & Logistics Optimization (EDA)

## 📌 Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on a retail superstore dataset containing **9,800 transactions**. The goal is to audit the store's performance across three critical business pillars: **Revenue Growth**, **Customer Purchasing Patterns**, and **Logistics & Shipping Efficiency** to prevent revenue leakage and streamline operations.

## 📁 Repository Structure
* `superstore sales EDA (1).ipynb` - The complete Jupyter Notebook containing documented Python code, visual plots, and technical insights.
* `train(1).xls.xlsx` - The raw retail dataset used for the analysis.
* `cleaned_train.csv` - The processed and sanitized dataset ready for analysis/modeling.
* `README.md` - Technical documentation and executive summary of the project.

## 🧪 Hypotheses Evaluated
* **Hypothesis 1 (Ship Mode vs Days):** Premium shipping modes have significantly lower delivery timelines compared to economy modes. *(STATUS: ACCEPTED)*
* **Hypothesis 2 (Sales vs Days):** High-value orders are fast-tracked and shipped faster by the logistics team than low-value retail orders. *(STATUS: REJECTED)*
* **Hypothesis 3 (Category vs Sales vs Segment):** Customer segments show identical purchasing behavior and average spend across all product categories. *(STATUS: REJECTED)*
* **Hypothesis 4 (Category vs Ship Mode vs Days):** Heavy and bulky categories like Furniture face longer shipping delays in premium tiers compared to lightweight Office Supplies. *(STATUS: REJECTED)*

## 🔍 Key Findings & Executive Summary
1. **Flawless SLA Execution:** Premium shipping modes strictly adhere to delivery timelines (e.g., Same Day shipping averages ~0 days). Furthermore, physical product weight or complexity (like heavy Furniture) introduces zero operational friction in the warehouse processing pipeline.
2. **The High-Value Tech Goldmine:** While customer segments behave uniformly across standard commodity categories, **Home Office** buyers spike aggressively within the **Technology** domain, averaging premium transaction sizes near **$500**.
3. **Fulfillment Prioritization Blind Spot:** The scatter-regression analysis uncovers that high-revenue corporate orders ($5,000 to $14,000) face the exact same shipping bottlenecks and maximum 7-day delays as minor retail orders, signaling an operational blind spot.

## 🚀 Strategic Recommendations
* **Value-Based Routing:** Automate an order-routing rule in the warehouse management system to push any transaction exceeding **$2,000** into a priority processing lane (VIP queue) to clear locked revenue faster and improve cash liquidity.
* **Targeted Tech Campaigns:** Shift the technology category's primary marketing budget toward remote workers and Home Office users with premium workspace ecosystem bundles.

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook
  
  AUTHOR
  ** Tejal Joshi**
