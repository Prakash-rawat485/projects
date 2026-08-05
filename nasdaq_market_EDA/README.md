# Nasdaq-Market-Microstructure-EDA-.
An institutional-grade EDA project reverse-engineering structural behaviors, exchange specializations, and regulatory tail-risks across 8,049 active asset listings using advanced Python stratification."

## Problem Statement

Financial markets, particularly tech-heavy indices like the NASDAQ, exhibit high volatility driven by complex macroeconomic factors, investor sentiment, and algorithmic trading patterns. Predicting market movements remains a significant challenge due to non-linear dependencies in historical time-series data. This project aims to develop a robust machine learning framework to analyze historical NASDAQ index/stock data to:

- Identify Patterns: Detect significant trends and anomalies in price movements using time-series analysis.
- Enhance Predictive Capability: Utilize technical indicators and historical price features (Open, High, Low, Close, Volume) to forecast future trends.
- Mitigate Uncertainty: Provide a data-driven outlook to assist stakeholders in understanding market volatility and risk management."
- 
# 📈 Nasdaq Microstructure Analysis & Compliance Risk Vetting

An institutional-grade Exploratory Data Analysis (EDA) project that transforms raw market metadata into actionable portfolio risk intelligence. This project reverse-engineers structural patterns, exchange specializations, and regulatory compliance metrics across **8,049 active asset listings**.

---

## 🔍 Executive Summary: The Core Insight
Yeh project architectural data gaps ko ek structured market intelligence mein badalta hai. Missing records ko delete karne ke bajaye, humne exchange ke operational metadata ko reverse-engineer kiya hai taaki institutional design ko map kiya ja sake aur **8,049 asset listings** ke beech systemic risk vectors ko locate kiya ja sake.

---

## 🛠️ The Data Strategy (What & Why)

* **Financial Status Vetting:** 4,666 missing values ko **`'N'` (Normal)** se backfill kiya.
  * *The Logic:* Exchange guidelines ke mutabik, distress flags ($D, E, H$) sirf exceptionally apply kiye jaate hain. Ek khali entry ka matlab hi yeh hai ki company compliant aur healthy hai. Agar hum in rows ko drop karte, toh dataset ka **58%** sabse clean data bina kisi galti ke delete ho jata.
* **Market Category Alignment:** 4,666 hidden blank spaces ko **`'Other' / 'Not Applicable'`** se fill kiya.
  * *The Logic:* Traditional corporate market tiers **ETFs** ya cross-exchange hosted listings par apply nahi hote. Inhe is tarah categorize karne se structural data bias khatam ho jata hai.
* **Redundancy Elimination:** **`CQS Symbol`** column ko permanently drop kiya.
  * *The Logic:* Yeh feature main `Symbol` column ka 100% identical clone tha, jo dataset mein faltu data redundancy badha raha tha.

---

## 📊 The Analytics Verdict (The Hidden Patterns)

* **Exchange Specialization Spectrum:** Public trading platforms bohot hi polarized tareeke se kaam karti hain. **NYSE (`N`)** pure tarah se ek traditional corporate equity engine hai jisme **0.0% ETFs** hain. Iske bilkul ulta, **NYSE Arca (`P`) aur Cboe (`Z`)** exclusively passive hubs hain jahan **93.1% aur 95.2% sirf ETFs** hain. **Nasdaq (`Q`)** akela aisa exchange hai jo ek diversified hybrid marketplace ki tarah kaam karta hai.
* **Compliance Tail-Risk Asymmetry:** Regulatory failure poore public market mein randomly distribute nahi hota. **ETFs ke paas absolute compliance immunity ($0\%$ risk) hai**. Corporate vulnerability poori tarah se small-cap **Capital Market (`S`)** tier mein trapped hai, jabki elite **Global Select (`Q`)** tier near-perfect operational resilience show karta hai.

---

## 🎯 The Data Scientist Conclusion
> *"Overall public listing ecosystem structurally sound hai aur 97.4% financially stable hai. Advanced logarithmic transformations aur matrix heatmaps ke zariye tail-risks ko isolate karke, yeh project raw data cleaning aur institutional-grade portfolio risk research ke beech ka gap successfully khatam karta hai."*

---



https://github.com/user-attachments/assets/ca175a9d-cb83-417a-ae11-c760f170584d




## 💻 Tech Stack Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Scaling Techniques:** Logarithmic Transformation ($Y-\text{axis} = \log_{10}$)

  ## Author
  Tejal Joshi

  ## Linkedin

https://www.linkedin.com/feed/
