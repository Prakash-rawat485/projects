

# 🚖 Uber Rides Exploratory Data Analysis (EDA)

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-darkblue.svg?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Data%20Viz-orange.svg?style=flat-square)](https://seaborn.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-purple.svg?style=flat-square)](https://plotly.com/)

An end-to-end Exploratory Data Analysis (EDA) project analyzing Uber ride patterns, pricing structures, passenger behaviors, and geographic distances to uncover core real-world insights driving ride-hailing ecosystems.

---

## 📌 Project Overview
This repository focuses on breaking down the underlying factors that govern Uber ride fares. By examining key attributes such as pickup/dropoff coordinates, timestamps, passenger metrics, and computed spatial distances, this project tests common hypotheses against empirical data to evaluate how a modern transportation network operates.

### 🔬 Core Hypotheses Tested
* **Distance vs. Fare:** Does greater distance consistently translate to proportional fare growth? *(Status: **Confirmed**)*
* **Passenger Impact:** Do larger passenger groups incur higher base meter charges? *(Status: **Refuted**)*
* **Temporal Patterns:** Do peak hours, weekend nights, or specific seasons dramatically shift distance and pricing baselines? *(Status: **Partially Confirmed via Traffic & Demand Factors**)*

---

## 📊 Key Insights & Real-World Realities

### 1. 📏 Distance is King (`Correlation = 0.90`)
* **Insight:** There is a near-perfect positive correlation between `distance_km` and `fare_amount`. 
* **Real-World Meaning:** Uber’s core pricing engine operates strictly on a distance-first framework. While traffic delays add minor variation, your destination's distance remains the primary billing driver.

### 2. 👥 Passenger Count Has Zero Impact (`Correlation = 0.013`)
* **Insight:** The statistical connection between the number of passengers and the final ride fare is practically non-existent.
* **Real-World Meaning:** When you hail a standard cab or vehicle, you rent the **entire vehicle** and the driver's time, not individual seats. The meter calculates fares based purely on distance and idling time—it does not care whether there is 1 passenger or a full group of 4 sharing the backseat.

### 3. 📅 Saturday Night "Dip" Anomalies
* **Insight:** Surprisingly, Saturdays display the lowest average fare amounts (dipping near **$11.80**).
* **Real-World Meaning:** This is caused by a drop in long-distance work/business commutes and airport runs typical of weekdays. Weekend demand is dominated by localized, short-distance social trips and nightlife runs within entertainment hubs.

### 4. ☀️ Summer Peaks vs. ❄️ Winter Dips
* **Insight:** Average trip distances peak sharply during **May and June** (~3.95 km) and fall to their lowest in **January** (~3.69 km). 
* **Real-World Meaning:** Favorable summer weather encourages outdoor exploration, leisure travel, and recreational tourism, pushing trip distances up. Conversely, freezing winter weather contracts travel to local, immediate neighborhoods.

### 5. 👥 Passenger Distribution Behavior (Violin & Bubble Breakdown)
* **Short-Distance Domination:** Across all group sizes, the vast majority of rides remain highly localized urban trips under **5 km**, keeping general fares under $20.
* **Solo Long Hauls:** The longest individual trips (stretching up to **50 km** with fares crossing **$220+**) are taken almost exclusively by single passengers.
* **Group Constraints:** Trips containing exactly 4 passengers are heavily restricted to short ranges, capping out cleanly under **30 km**.

---

## 🛠️ Tech Stack & Workflow

### 1. Data Cleaning & Optimization
* Handled missing spatial records across coordinates (`dropoff_longitude` & `dropoff_latitude`).
* Eliminated uninformative operational columns (`Unnamed: 0`, `key`) to streamline computational memory.
* Extracted structural temporal attributes from timestamps (`hour`, `day`, `weekday`, `month`, `year`).

### 2. Advanced Visualization Architecture
* **Univariate Studies:** Distribution density profiles of fares and distances using Seaborn KDE plots.
* **Bivariate Explorations:** Box plots and violin plots characterizing passenger caps vs. spatial range.
* **Multivariate Analytics:** Parallel Coordinates plots tracking complex multi-lane data paths (`Passengers ➔ Weekday ➔ Fare Class ➔ Hour`).
* **Algorithmic Clustering:** Hierarchical `sns.clustermap()` using dendrogram branches to instantly separate core fare metrics from uncorrelated temporal attributes.

AUTHOR-
prakash rawat(data scientist)


---
