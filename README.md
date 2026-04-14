# 🌍 War Impact on Economy — Data Analysis Project

A comprehensive data analysis project exploring the economic consequences of armed conflicts across the globe. This project examines how wars affect GDP, inflation, unemployment, poverty, and reconstruction costs using real-world conflict data.

---

## 📌 Project Overview

War doesn't just cause human suffering — it devastates economies for decades. This project analyzes economic indicators across **11 major global conflicts** to uncover patterns in how warfare disrupts financial systems, labour markets, and national productivity.

The analysis covers the full data science pipeline:
- Data cleaning & feature engineering
- Exploratory Data Analysis (EDA)
- Time series & trend analysis
- Comparative pre-war vs during-war analysis
- Correlation analysis
- Linear Regression predictive modeling

---

## 📊 Dataset

- **Source:** [Kaggle](https://www.kaggle.com)
- **File:** `war_economic_impact_dataset.csv`
- **Size:** ~100,000 records across 11 conflicts
- **Coverage:** GDP change, inflation, unemployment, poverty rates, war costs, reconstruction costs, and more

---

## 🔍 Key Findings

- **Palestine (Gaza)** recorded the most severe average GDP contraction at **−72.6%**, nearly 45 percentage points worse than any other country in the dataset.
- **Ongoing conflicts** cause deeper GDP damage (−35.0%) than resolved ones (−27.5%), while inflation rates are nearly identical — confirming that structural economic damage compounds over time, not monetary instability.
- **Reconstruction costs** consistently exceed war costs by approximately **2.7×** — rebuilding an economy costs nearly three times more than the war itself.
- **Inflation and Currency Devaluation** are strongly correlated (0.79) — monetary instability is one interconnected phenomenon, not two separate effects.
- **Unemployment Spike and Poverty Rate** correlate at 0.78 — labour market collapse is the primary civilian poverty driver during conflict.
- The **Linear Regression model** achieved R² = 0.043, confirming that wartime GDP contraction is a complex, multi-causal phenomenon that no single variable can capture — a finding, not a failure.

---

## 🛠️ Tech Stack & Libraries

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, feature engineering |
| `numpy` | Numerical operations |
| `matplotlib` | Custom visualizations and charts |
| `seaborn` | Correlation heatmap |
| `scikit-learn` | Linear Regression model, train/test split, metrics |
| `joblib` | Model serialization |

---

## 📁 Project Structure

```
global-conflict-economic-impact/
├── README.md
├── War_impact_Economy.ipynb
├── war_economic_impact_dataset.csv
└── outputs/
    └── (all chart .png files)
    ├── conflict_frequency.png
    ├── gdp_by_country.png
    ├── most_affected_sector.png
    ├── outlier_boxplots.png
    ├── time_series_gdp_inflation.png
    ├── rolling_average_trend.png
    ├── resolved_vs_ongoing.png
    ├── correlation_heatmap.png
    └── regression_model.png
```

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn joblib
   ```

3. Add the dataset CSV to the project root, then run:
   ```bash
   python war_impact_economy.py
   ```

4. All output charts will be saved to the `outputs/` folder.

---

## 👤 Author

Made with 💙 as part of a data science portfolio project.
