# Traffic-EDA-Analysis

#  Temporal & Environmental Traffic Analysis on an Essential Urban Junction

A comprehensive Exploratory Data Analysis (EDA) evaluating urban traffic behavior under various temporal factors (hourly shifts, rush hours, seasonal variances) and weather conditions (rainfall depth, visibility, temperature variations).

##  Project Summary
Most traffic literature focuses strictly on morning peaks inside office-dominated districts. This study analyzes a **48,120-row traffic sensor dataset** specifically capturing a distinct evening-dominant junction (market/residential environment). The analysis evaluates how external environmental variables interact with localized daily schedules to alter density parameters and vehicle speed estimations.

---

##  Key Insights & Discoveries

### 1. High Temporal Dependencies
* **The Evening Shift:** Traffic volume clusters sharply between **6:00 PM – 9:00 PM** (the absolute worst congestion window), reflecting a residential/market layout rather than typical 9-to-5 morning business commute spikes.
* **Optimal Commute Windows:** The clear-running periods were isolated between **2:00 AM – 6:00 AM** (troughs) and **10:00 AM – 4:00 PM** (afternoon off-peak).

### 2. Weather & Environmental Resiliency
* **Heavy Rain vs. Commuter Demand:** Heavy rainfall induces a traffic drop of **20–30%**, coupled with cautious/slower velocities due to diminished visibility.
* **Essential Commuting:** Light rain or severe high temperatures yielded **almost no deviation** from standard density norms. This establishes the junction as an "essential route"—drivers continue through bad weather because their tasks cannot be delayed or bypassed.

---



---

##  Operational Recommendations

* **For Traffic Control and Municipalities:** 1. Allocate extended green-signal cycles sequentially during the peak constraint slot (**6:00 PM – 9:00 PM**).
    2. Restrict non-emergency road work or infrastructure upgrades exclusively to the low-volume months of December or July–August.
    3. Program automation systems to trigger dynamic congestion alerts the moment vehicle density breaks past **> 30 vehicles/km**.
* **For Logistics and Commercial Fleets:** Plan delivery operations strictly during the mid-day break zone (**10:00 AM – 4:00 PM**). Expect roughly a 20% spike in customer footprint throughout October and prepare for an active 15% reduction during monsoon months (July–August).

---
## Author
Tejal Joshi
