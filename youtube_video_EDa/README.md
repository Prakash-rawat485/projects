<!--
  DEvideos EDA README
  A polished animated GitHub README for your exploratory data analysis project
-->

<h1 align="center">DEvideos YouTube Trending Dataset EDA</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=900&lines=Exploratory+Data+Analysis+on+YouTube+Trending+Videos;Understanding+Views%2C+Likes%2C+Comments+%26+Trends;Feature+Engineering+for+Video+Analytics;Python+%7C+Pandas+%7C+Matplotlib+%7C+Seaborn" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Pandas-EDA-150458?style=for-the-badge&logo=pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge&logo=plotly" />
  <img src="https://img.shields.io/badge/Seaborn-Insights-2E5EAA?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter" />
</p>

---

## Overview

This project presents a complete exploratory data analysis of the **DEvideos YouTube trending dataset**. The goal is to understand how video metadata, engagement metrics, and publishing patterns influence trending behavior across categories, time periods, and content types.

The analysis focuses on:
- Data cleaning and inspection.
- Distribution study of views, likes, dislikes, and comments.
- Correlation and relationship analysis.
- Time-based and category-based insights.
- Feature engineering for future modeling.

---

## Dataset Description

The dataset contains **40,840 records** and **16 original columns** related to YouTube trending videos. It includes:
- Video identifiers and titles.
- Channel information.
- Category labels.
- Publish and trending timestamps.
- Tags and descriptions.
- Engagement metrics such as views, likes, dislikes, and comment count.
- Status flags like comments disabled and ratings disabled.

This dataset is ideal for:
- Exploratory analysis.
- Engagement pattern study.
- Trend forecasting.
- Multi-class classification using `category_id`.

---

## Objectives

The main objectives of this EDA are:
1. Understand the structure and quality of the dataset.
2. Analyze distributions of numerical features.
3. Detect skewness and outliers in engagement variables.
4. Study correlations among key metrics.
5. Explore the effect of time and content category on trending behavior.
6. Engineer useful features for deeper analysis and modeling.

---

## Tools Used

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pandas,matplotlib,seaborn,jupyter,git,github" />
</p>

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

---

## Workflow

### 1. Data Loading
The dataset was loaded and inspected using standard pandas functions.

### 2. Data Cleaning
- Checked column types.
- Parsed date and time fields.
- Identified missing or malformed values.
- Reviewed duplicate-like patterns and irrelevant fields.

### 3. Feature Engineering
New features were created to improve analysis:
- `publish_day`
- `publish_weekday`
- `publish_hour`
- `video_age`
- `title_length`
- `description_length`
- `tag_count`
- `like_ratio`
- `comment_ratio`
- `dislike_ratio`

### 4. Visual Analysis
The notebook includes plots for:
- Histograms.
- Boxplots.
- Correlation heatmaps.
- Category-wise comparisons.
- Time-based trends.

---

## Key Findings

### Engagement Metrics Are Highly Skewed
Views, likes, dislikes, and comments are not normally distributed. A small number of viral videos dominate the upper range, while most videos remain in the lower range.

### Views and Likes Move Together
Videos with high views generally receive high likes and comments, showing strong positive engagement relationships.

### Time Matters
Publishing time and trending date patterns suggest that upload timing influences video performance.

### Category Imbalance Exists
Some categories appear much more frequently than others, which can affect both analysis and future machine learning models.

### Engineered Ratios Add Value
Normalized engagement features make it easier to compare videos fairly, especially when raw counts vary widely.

---

## Visual Summary

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=your-username&theme=react-dark&hide_border=true" alt="Activity Graph" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=your-username&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=your-username&layout=compact&theme=tokyonight" alt="Top Languages" />
</p>

> Replace `your-username` with your GitHub username.

---

## Project Insights

- Trending videos are driven by a mixture of content popularity and timing.
- Highly engaged videos often show strong public response in likes and comments.
- Right-skewed distributions make median and percentile-based analysis more useful than mean-only reporting.
- Category-level comparisons help reveal which content types dominate trending lists.
- Feature engineering improves the dataset’s value for classification and predictive tasks.

---

## Future Scope

This dataset can be extended further for:
- Predicting video category.
- Studying viral growth patterns.
- Comparing engagement across regions or channels.
- Building dashboard visualizations.
- Applying machine learning for trend prediction.

---

## Repository Structure

```text
DEvideos-EDA/
├── DEvideos.Eda.ipynb
├── README.md
├── data/
│   └── DEvideos.csv
├── images/
│   └── plots/
└── reports/
    └── eda_report.pdf
```

---

## How to Run

```bash
git clone https://github.com/your-username/DEvideos-EDA.git
cd DEvideos-EDA
pip install -r requirements.txt
jupyter notebook
```

---

## About Me

I am a data analyst and Python enthusiast focused on EDA, data cleaning, visualization, and backend-friendly analytical workflows. My work often combines technical exploration with professional reporting and clear storytelling.

---

## Contact

<p align="center">
  <a href="https://www.linkedin.com/in/your-linkedin/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://github.com/your-username">
    <img src="https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github" />
  </a>
</p>

---

## Acknowledgment

This project was developed as part of an exploratory data analysis workflow to better understand YouTube trending patterns and engagement behavior.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:36BCF7,100:1E90FF&height=120&section=footer" />
</p>
