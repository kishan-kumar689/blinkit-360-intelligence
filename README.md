# 🛒 Blinkit 360° Intelligence
## End-to-End Quick Commerce Analytics & Coastal Karnataka Expansion Feasibility

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![SQL](https://img.shields.io/badge/SQL-SQLite-green)
![ML](https://img.shields.io/badge/ML-Scikit--learn%20%7C%20XGBoost-orange)
![DL](https://img.shields.io/badge/DL-TensorFlow%20%7C%20BERT-red)
![BI](https://img.shields.io/badge/BI-Power%20BI-yellow)

---

## 📌 Project Overview

A full-stack data science portfolio project analysing quick commerce operations 
for a Blinkit-style platform, with a business feasibility study for expansion 
into Coastal Karnataka (Udupi, Manipal, Kundapura).

**Dataset:** Custom-built realistic dataset (10 tables, 100,000+ rows) designed 
from scratch using Python based on industry benchmarks — not a Kaggle download.

---

## 🎯 Business Questions Answered

1. What are the revenue trends and seasonality patterns?
2. Where are delivery SLA breaches happening and why?
3. Which customer segments are most valuable?
4. Which marketing channels give the best ROI?
5. Is Coastal Karnataka a viable expansion market?

---

## 📂 Project Structure

```
blinkit-360-intelligence/
├── 📂 notebooks/
│   ├── 01_data_loading_and_cleaning.ipynb   # Phase 1
│   ├── 02_sql_kpis_business_metrics.ipynb   # Phase 2
│   ├── 03_machine_learning_models.ipynb     # Phase 3
│   └── 04_deep_learning_models.ipynb        # Phase 4
├── 📂 outputs/
│   └── (20 charts & visualizations)
├── 📂 powerbi/
│   └── blinkit_360.pbix                     # Phase 5
├── README.md
└── requirements.txt
```

> ⚠️ **Note:** Raw and cleaned data files are not included in this repo 
> due to size constraints. The dataset generation script is available 
> in the notebooks folder.

---

## 🔧 Tech Stack

| Layer | Tools |
|-------|-------|
| Data Generation | Python, NumPy, Pandas, Faker |
| Data Cleaning | Pandas, NumPy |
| EDA | Matplotlib, Seaborn |
| SQL KPIs | SQLite, Pandas |
| ML Models | Scikit-learn, XGBoost |
| Deep Learning | TensorFlow, Keras, HuggingFace Transformers |
| Dashboard | Power BI Desktop |

---

## 📊 Phase Summary

### ✅ Phase 1 — Data Cleaning & EDA
- Cleaned 10 datasets (110 duplicates removed, nulls handled)
- Feature engineered: order_hour, sla_breached, value_segment
- Key finding: 8PM is peak demand hour (869 orders)

### ✅ Phase 2 — SQL KPIs (10 Business Metrics)
- Total Revenue: ₹1.65 Crore | AOV: ₹1,513
- On-Time Delivery: 78.2% | SLA Breach: 21.8%
- Email ROAS: 3.24x (best channel)
- **Coastal Karnataka AOV ₹1,536 > Mumbai ₹1,480** 🎯

### ✅ Phase 3 — Machine Learning Models
| Model | Purpose | Performance |
|-------|---------|-------------|
| K-Means Clustering | RFM Customer Segmentation | 4 segments identified |
| XGBoost Regressor | Revenue Forecasting | MAPE 3.6%, R² 0.894 |
| Random Forest | Churn Prediction | Accuracy 90%, AUC 0.967 |

### ✅ Phase 4 — Deep Learning Models
| Model | Purpose | Performance |
|-------|---------|-------------|
| LSTM | Demand Forecasting | MAE 4.18 units/day |
| DistilBERT | Sentiment Analysis | 91% accuracy |

### ✅ Phase 5 — Power BI Dashboard (5 Pages)
1. 🏠 Revenue Overview
2. 🚚 Delivery Performance
3. 👥 Customer Intelligence
4. 📣 Marketing & Products
5. 🗺️ Expansion Scorecard

---

## 🗺️ Expansion Verdict

> **Coastal Karnataka (Udupi + Manipal + Kundapura) contributes 30.5% of 
> total revenue across just 3 cities, with an AOV of ₹1,536 — exceeding 
> Mumbai's ₹1,480. The data strongly supports expansion!**

---

## 💡 Key Insights

- 🎯 Festive season (Oct-Dec) drives **35% revenue spike**
- 🚨 SLA breach root cause: **dark store operations**, not last-mile
- 👥 Loyal customers have **7.5x higher LTV** than one-time buyers
- 🌿 Fruits & Dairy damage rate **2.88%** — cold chain investment needed
- 📧 Email marketing **ROAS 3.24x** — best performing channel
- 🍲 **Idli Batter #3 top product** — validates South Indian market focus

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/blinkit-360-intelligence.git

# Install dependencies
pip install -r requirements.txt

# Run notebooks in order
jupyter notebook
```

---

## 👤 Author

**[Your Name]**  
MBA in Data Science | 3 Years Supply Chain Experience  
Targeting: Data Scientist | Analytics Manager roles

---

## 📄 License
MIT License
