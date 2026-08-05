# 🩺 Pima Indians Diabetes - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the **Pima Indians Diabetes Dataset** to understand the clinical factors associated with diabetes. The analysis focuses on data quality, feature distributions, relationships between variables, and multivariate interactions before building any machine learning model.

The dataset contains medical records of **768 female patients of Pima Indian heritage**, with the objective of predicting whether a patient has diabetes based on diagnostic measurements.

---

## 🎯 Objectives

- Understand the clinical meaning of each feature.
- Identify and handle missing values represented as biologically impossible zeros.
- Explore feature distributions using univariate analysis.
- Investigate relationships between features and diabetes outcome.
- Discover hidden multivariate patterns and high-risk patient groups.
- Prepare the dataset for future machine learning modeling.

---

# 📊 Dataset Information

- **Dataset:** Pima Indians Diabetes Database
- **Source:** https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
- **Rows:** 768
- **Columns:** 9
- **Target Variable:** Outcome

---

# 📋 Feature Description

| Feature | Description |
|----------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-hour serum insulin (μU/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Genetic predisposition score for diabetes |
| Age | Patient age (years) |
| Outcome | Diabetes status (0 = Non-Diabetic, 1 = Diabetic) |

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Checked dataset structure and summary statistics.
- Verified missing values and duplicate records.
- Found no duplicate observations.
- Identified biologically impossible zero values in:
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
- Replaced invalid zeros with missing values.
- Imputed missing values using an appropriate statistical method.
- Verified all missing values were successfully handled.

---

# 📈 Exploratory Data Analysis

## 🔹 Univariate Analysis

Performed:

- Histograms
- KDE Plots
- Box Plots
- Distribution Analysis
- Target Class Distribution

Key observations:

- Glucose, Insulin and Diabetes Pedigree Function are right-skewed.
- Insulin contains extreme outliers.
- Outcome is moderately imbalanced.
- BMI approximately follows a normal distribution.

---

## 🔹 Bivariate Analysis

Analyzed relationships between each feature and Outcome using:

- KDE Plots
- Box Plots
- Violin Plots
- Scatter/Strip Plots
- Percentage Bar Charts
- Correlation Heatmap

Major findings:

- Glucose is the strongest predictor of diabetes.
- Higher BMI is associated with diabetic patients.
- Older individuals show higher diabetes prevalence.
- Higher Diabetes Pedigree Function indicates greater genetic risk.
- Blood Pressure shows only a weak relationship with Outcome.

---

## 🔹 Multivariate Analysis

Performed:

- Bubble Scatter Plot
- Faceted Regression Analysis
- Pairplot
- Correlation Heatmap

Important insights:

- High glucose combined with higher BMI forms clear high-risk clusters.
- BMI and SkinThickness exhibit a positive linear relationship.
- Multiple clinical variables together separate diabetic and non-diabetic patients better than any single feature.
- Glucose, BMI, Age and Insulin together provide the clearest distinction.

---

# 🔥 Key Insights

- Glucose is the most influential feature associated with diabetes.
- Diabetes is driven by the interaction of multiple physiological variables rather than a single measurement.
- Insulin contains heavy right-skewness and several extreme outliers.
- BMI, Age, and Diabetes Pedigree Function strengthen diabetes prediction when combined with Glucose.
- No severe multicollinearity exists among predictor variables.

---

# 📚 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🚀 Future Work

- Feature Engineering
- Feature Scaling
- Machine Learning Model Development
- Model Evaluation
- Hyperparameter Tuning
- Model Explainability using SHAP/LIME

---

# 📖 References

- Kaggle Dataset: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

---

## 👩‍💻 Author

**Sona Kunwar**

 Data Scientist | Python | SQL | Power BI | Machine Learning
