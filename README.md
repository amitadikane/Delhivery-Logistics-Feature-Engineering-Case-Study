# Delhivery Logistics — Feature Engineering Case Study

**Domain:** Logistics / Supply Chain  
**Tools:** Python (Pandas, NumPy, SciPy, Scikit-learn), Matplotlib, Seaborn  
**Focus:** Data Cleaning → Aggregation → Feature Engineering → Hypothesis Testing

---

## 📌 Problem Statement

Delhivery’s raw data contains **multiple scan-level rows per package** (similar to connecting-flight legs). Before any forecasting model can be built, this data must be cleaned, merged into route segments and full trips, and engineered into useful features.

---

## 🎯 Project Steps

1. **Clean & Explore** raw scan-level data
2. **Merge rows** into route segments (source → destination) and then into full trips using appropriate aggregations (`sum`, `first`, `last`)
3. **Engineer features** from timestamps and location names (city, state, month/day/year)
4. **Compare** actual vs OSRM-estimated time and distance (visual + statistical analysis)
5. **Detect & treat outliers**, encode categoricals, scale numeric features
6. **Surface business insights** (top states, busiest corridors) and recommendations

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- SciPy (statistical tests)
- Scikit-learn (MinMaxScaler, StandardScaler)
- Matplotlib & Seaborn

---

## 📊 Key Features Engineered

- Trip-level aggregated time and distance
- Time-based features (hour, day, month, year extracted from timestamps)
- Location features (source/destination city & state)
- Difference between actual and OSRM estimated time/distance
- Segment count per trip

---

## 💡 Business Insights

- Identified highest volume states and busiest source-destination corridors
- Quantified deviation between actual delivery performance and OSRM estimates
- Highlighted routes with consistent delays → opportunity for operational improvement

---

## 📁 Repository Structure

```
├── README.md
├── notebooks/
│   └── delhivery_feature_engineering.ipynb
├── data/                  # (add cleaned sample if shareable)
├── insights/
│   └── key_findings.md
└── requirements.txt
```

---

## 🚀 Skills Demonstrated

- Real-world messy data cleaning
- Multi-level aggregation (scan → segment → trip)
- Feature engineering from timestamps & geography
- Outlier detection & treatment
- Statistical comparison of actual vs estimated metrics
- Business storytelling from logistics data

---

**Author:** Amit Narendra Adikane  
**LinkedIn:** [amit-adikane](https://www.linkedin.com/in/amit-adikane-4060a91b1/)

---
