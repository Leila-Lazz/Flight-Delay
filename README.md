# ✈️ Flight Delay Prediction (Binary Classification)

## Overview

This project builds a machine learning pipeline to predict whether a flight will be **delayed** or **on time/early** using historical flight and operational data. It aims to help airlines anticipate disruptions, optimize crew scheduling, and reduce operational costs.

> **Dataset:** [Airlines Dataset to Predict a Delay](https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay) — 539,383 flight records (Kaggle)

---

## Key Features

- 📊 **Exploratory Data Analysis (EDA)** — temporal patterns, airline comparisons, delay distributions
- 🔧 **Feature Engineering** — departure hour, day of week, airline carrier, route, flight duration
- 🤖 **Multi-model Training & Comparison** — 5 classifiers benchmarked side by side
- 📈 **Business-oriented Evaluation** — Recall ≥ 75%, F1-Score ≥ 0.70, ROC-AUC ≥ 0.80

---

## ML Algorithms

| Model | Type |
|---|---|
| Logistic Regression | Baseline |
| Decision Tree | Baseline |
| Random Forest | Ensemble |
| Gradient Boosting | Advanced ⭐ |
| XGBoost | Advanced ⭐ |

---

## Tech Stack

| Category | Technologies |
|---|---|
| Language | Python 3 |
| Environment | Jupyter Notebook |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Advanced Models | XGBoost |
| Preprocessing | StandardScaler, train_test_split |
| Evaluation | Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix |

---

## Project Structure

```
Flight-Delay/
├── ML_PJ_Flight_Delay.ipynb   # Full analysis & training pipeline
└── README.md
```

---

## Team — ML Aviators

| Student | Contributions |
|---|---|
| Noah Delhi | Data preprocessing, feature engineering, model development |
| Othmane ElKadiri | EDA, visualizations, model evaluation |
| Leila Lazzem | Dataset selection, business analysis, recommendations |

---

## Results

- Advanced ensemble models (Gradient Boosting, XGBoost) outperformed simpler baselines
- Key predictive features: **departure hour** and **airline carrier**
- Estimated business impact: **$10–15M in annual savings** through proactive delay management
