# Insurance-EDA

# 🏥 Insurance Risk & Charges: 5-Star Exploratory Data Analysis (EDA)

This project performs an end-to-end Exploratory Data Analysis (EDA) on a health insurance dataset to uncover the true hidden drivers behind high medical claims. 

## 🎯 Project Overview: What & Why

1. **Data Cleaning & Preprocessing**
   * *Why:* Removed missing/duplicate values to prevent unclean data from skewing our statistical results.
2. **Univariate Analysis**
   * *Why:* To analyze the distributions of customer demographics (Age, Sex, Region, Children) and health metrics (BMI, Smoker status).
3. **Smoker vs. Charges (Box Plot Analysis)**
   * *Why:* To isolate and visualize the direct financial baseline gap between smokers and non-smokers.
4. **Age vs. Charges (Scatter Plot Analysis)**
   * *Why:* To determine if aging causes a linear cost increase and how habits alter this trajectory.
5. **BMI vs. Charges (The Interaction Effect)**
   * *Why:* To test the clinical obesity threshold ($BMI \ge 30$) and its compounded impact when paired with smoking.
6. **Children vs. Charges (Violin Plot Analysis)**
   * *Why:* To observe how family size alters risk distribution and claims volume.
7. **Feature Correlation Analysis (Heatmap Matrix)**
   * *Why:* To establish mathematical proof (on a scale of 0 to 1) identifying the single most powerful billing predictor.

## 💎 Key Discoveries (The Hidden Gems)
* **The Smoking Tax:** Smoking acts as a massive, non-negotiable financial penalty—adding an immediate **\$15,000 to \$20,000** baseline to a profile regardless of youth.
* **The Lethal Multiplier:** Crossing the obesity barrier ($BMI \ge 30$) keeps costs low for non-smokers, but instantly **doubles** costs for smokers from \$20,000 to \$40,000+.
* **The Large Family Cap:** Counter-intuitively, families with 4-5 children rarely hit peak charges, proving large family structures are highly stable risk pools.
* **Mathematical Proof:** The Correlation Heatmap confirms **Smoking is King (0.79 score)**, while demographics like Gender and Region sit near 0.00 impact.

## 🛠️ Technologies Used
* Python 3
* Pandas & NumPy (Data Wrangling)
* Matplotlib & Seaborn (Advanced Visualization)

## Author
Tejal Joshi
