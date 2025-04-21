# Flight-Delay-Trends-USA

This project performs exploratory and explanatory data analysis using various Python libraries, with the output visualized.

---
## 🔍 Project Overview
The project is divided into two key parts:
1. **Exploratory Analysis** — Investigates structure, trends, and relationships using univariate, bivariate, and multivariate analysis.
2. **Explanatory Analysis** — Builds a narrative through visual, highlighting key insights on delays and performance patterns.

--- 

## 🔗 Dataset Source
- [Reporting Carrier On-Time Performance Data Description(Bureau of Transportation Statistics)](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ)
- [Download dataset directly (airline_2m.tar.gz)](https://drive.google.com/file/d/14hyGmVzJlDdqU_3K6598pWNM_n33x8lc/view?usp=sharing)

---

## 💼 What I Did

### 🔎 Part I – Exploratory Analysis
- Investigated the **structure and content** of the airline on-time performance dataset (~2M rows).
- Defined research questions around delays, cancellations, seasonal patterns, and airline comparisons.
- Conducted:
  - **Univariate Analysis**: Explored distributions of `DepDelay`, `ArrDelay`, `CarrierDelay`, etc.
  - **Bivariate Analysis**: Analyzed relationships between delays and month, day of week, time of day, and airline.
  - **Multivariate Analysis**: Created facet plots to examine delay patterns by airline, day, and cancellation status..

### 📊 Part II – Explanatory Analysis
- Presented a **polished narrative** with key insights derived from EDA.
- Focused on 5 core visualizations with clean formatting:
  1. **Distribution of Flight Delays** – Histogram showing right-skewed delay patterns.
  2. **Monthly Cancellations** – Bar plot revealing seasonal cancellation peaks (e.g., winter).
  3. **Airline-wise Cancellations** – Bar chart comparing disruption rates by carrier.
  4. **Impact of Departure on Arrival Delays** – Scatter plot showing cascading delay effects.
  5. **Airport-Specific Delays** – Heatmap showing which airports have consistently high delays.
- Explained each chart with detailed comments for storytelling clarity.
- Summarized key trends in flight operations and visual insights.
  
---

  ## 📂 Files

- [Part_I_Exploration_template.ipynb](/notebook/Part_I_explanatory_template.ipynb)
- [Part_II_Exploration_template.ipynb](/notebook/Part_II_explanatory_template.ipynb)


