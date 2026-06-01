# ✈️ Flight Delay & Operational Risk Analysis

An end-to-end Exploratory Data Analysis (EDA) dashboard project decoding the root structural causes, patterns, and timing vectors behind commercial airline delays. 

---

## 📌 Project Overview & The Problem
In aviation, operational efficiency dictates profitability and customer retention. When a single flight is delayed, it triggers a costly multi-city domino effect across the entire network. 

**The Challenge:** Raw delay minutes alone do not tell the whole story. To build proactive mitigation systems, airlines must understand *where* the stress originates, *how* different delays interact, and *when* the network is most vulnerable. 

This project cleans, transforms, and analyzes a multi-feature flight dataset to identify structural bottlenecks, map delay propagation pathways, and deliver actionable operational profiles.

---

## 🧪 Core Hypotheses Tested

## 🧪 Core Hypotheses Tested

* **Hypothesis 1 (The Weather Factor):** Bad weather conditions directly destabilize scheduled times and lead to severe flight delays. 
  *(Status: **PARTIALLY UNIQUE** — While weather causes massive individual spikes, the data shows it happens far less frequently than standard carrier or late-aircraft issues).*

* **Hypothesis 2 (The Late Cascade):** Leaving late directly results in reaching late. A delay at departure creates an immediate, unrecoverable delay at arrival.
  *(Status: **CONFIRMED** — Departure Delay (`Dep_Delay`) holds the highest correlation score ($r = 0.47$) with actual Arrival Delays (`Arrival_Delay_15_Min`), proving that late departures almost always guarantee late landings).*

---

## 📊 Key Analytical Insights

### 1. Network Traffic & Day-of-Week Risk Profiles
* **The Main Highway:** The vast majority of scheduled flights run cleanly—experiencing **0 Cancelled** and **0 Diverted** status flags—forming a highly resilient baseline network stream.
* **The Friday Flashpoint:** **Day 5 (Friday)** acts as the major operational bottleneck, capturing the highest volume of delayed flights (**6.5%** of the entire network). 
* **The Mid-Week Safe Zone:** **Tuesday (Day 2)** and **Wednesday (Day 3)** represent the most stable operational windows, plunging down to the lowest delay frequencies (**3.5%** and **3.3%**).

### 2. Operational Stress & Delay Drivers
* **The Critical Cascade Point:** Even minor operational friction pushes a flight out of the "On Time" zone. Once a flight registers past a minor baseline threshold, it is pushed entirely into a **100% Guaranteed Delayed State**.
* **Carrier vs. Distance:** Long-distance hauls do not inherently cause delays. Instead, delays are heavily dominated by **Carrier Delays** and **Late Aircraft Delays**.
* **The "L-Shape" Isolate:** Carrier issues (mechanical, crew, boarding) and Late Incoming Aircraft issues are mutually exclusive independent killers. They rarely happen at the same time on a single flight; a flight is typically compromised by one *or* the other.

---

## 🎨 Visualizing the Insights

To maximize presentation clarity, this project moves away from chaotic, over-plotted scatter charts and applies specialized diagnostic frameworks:

### A. Parallel Categories Profile
By tracking individual flight streams from left to right, we visually expose the "highways" of the network. On-time flights form a flat, massive horizontal path at the bottom, while high-risk flights branch off into a distinct delay ecosystem on specific days.

### B. Hierarchical Cluster Maps
Using a correlation engine, this visual automatically groups variables by behavioral similarity. It visually isolates the core domino effect cluster (Carrier Delay $\rightarrow$ Departure Delay $\rightarrow$ Late Aircraft Delay) away from unrelated flight features like Distance.

---

## 🛠️ Tech Stack & Methodology
* **Language:** Python 3+
* **Core EDA Engines:** `pandas`, `numpy`
* **Visualization Layer:** `seaborn`, `matplotlib`
* **Advanced Interactive Visuals:** `plotly.express`
* **Statistical Methods:** Pearson Correlation Matrix Clustering, Density Hexagonal Binning, Faceted Grid Analysis


   author-
   prakash rawat(data scientist)
