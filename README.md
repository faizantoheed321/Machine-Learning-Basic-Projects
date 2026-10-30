# Machine-Learning-Basic-Projects 🚀

Welcome to **Machine-Learning-Basic-Projects**, a comprehensive repository featuring end-to-end Machine Learning models, predictive pipelines, and executive dashboards built during **Summer 2026 (Week 1 Sprint)**. Submitted on **October 30–31, 2026**.

This repository contains 8 core machine learning projects covering binary and multi-class classification, regression pipelines, class imbalance techniques, and feature engineering.

---

## 📌 Executive Dashboards & Project Highlights

### 1. Telco Customer Churn Enterprise Executive Dashboard

> **Goal:** Predict subscriber churn and identify key retention drivers.
> **Key Metrics:** Analyzed **7.04k customers** with an average churn rate of **26.54%**. Evaluated model feature importance where fiber optic internet was a positive churn predictor while long-term contracts significantly boosted retention.

---

### 2. Credit Card Fraud Detection Pipeline

> **Goal:** Detect fraudulent transactions in highly imbalanced financial datasets.
> **Key Metrics:** Evaluated **226,970 records** (baseline fraud rate: 0.176%). The primary **Random Forest** model achieved a **Recall of 81.25%** and an **ROC-AUC Score of 0.9767** across operational interval chunks.

---

### 3. Automotive Price Valuation Model

> **Goal:** Predict secondary car market prices using large-scale tabular regression.
> **Key Metrics:** Trained on **1,000,000 rows**. Base Random Forest model achieved an **R² Score of 98.04%** with a baseline MAE of **$1,362.99**.

---

### 4. HR Employee Attrition Executive Summary

> **Goal:** Identify employee turnover risk factors and handle class imbalance.
> **Key Metrics:** Evaluated **1,233 retained vs. 237 churned** employees. Threshold tuning (0.25) identified top risk drivers including monthly income, age, and overtime work.

---

### 5. Olist Brazilian E-Commerce Executive Dashboard

> **Goal:** Forecast delayed orders and e-commerce delivery logistics risks.
> **Key Metrics:** Analyzed **110,196 total records** with an overall delay rate of **7.91%**. Optimized Random Forest classifier achieved **57.00% Recall** and an **ROC-AUC of 0.7272**.

---

### 6. Loan Default Risk Scoring

> **Goal:** Calculate default probability across loan applicant tiers.
> **Key Metrics:** Compared Logistic Regression against Random Forest. Identified interest rates, annual income, loan term, and loan amount as the top primary risk drivers.

---

### 7. House Price Estimation Pipeline

> **Goal:** Predict housing valuation through regularized linear regression and ensemble methods.
> **Key Metrics:** Compared Linear Regression (R² = 0.653), Ridge Regression (R² = 0.652), and Random Forest (R² = 0.612).

---

### 8. Medical Cost Insurance Prediction

> **Goal:** Estimate health insurance charges based on demographic and lifestyle factors.
> **Key Metrics:** Dataset contains 1,337 records across 6 features. **Random Forest Regressor** achieved an **R² Score of 87.8%** vs Linear Regression (80.7%), identifying **smoker status (60.1%)** and **BMI (21.6%)** as top cost drivers.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.10+
* **Data Processing & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, XGBoost, LightGBM
* **Visualization & Dashboards:** Matplotlib, Seaborn, Plotly

---

## 📂 Repository Structure

```text
Machine-Learning-Basic-Projects/
├── 01-telco-customer-churn/
│   ├── notebook.ipynb
│   └── README.md
├── 02-credit-card-fraud-detection/
│   ├── notebook.ipynb
│   └── README.md
├── 03-automotive-price-valuation/
│   ├── notebook.ipynb
│   └── README.md
├── 04-hr-employee-attrition/
│   ├── notebook.ipynb
│   └── README.md
├── 05-olist-ecommerce-delays/
│   ├── notebook.ipynb
│   └── README.md
├── 06-loan-default-risk-scoring/
│   ├── notebook.ipynb
│   └── README.md
├── 07-house-price-estimation/
│   ├── notebook.ipynb
│   └── README.md
├── 08-medical-cost-insurance/
│   ├── notebook.ipynb
│   └── README.md
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/faizantoheed321/Machine-Learning-Basic-Projects.git
   cd Machine-Learning-Basic-Projects
   ```

2. **Set up a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

---

## 👤 Author

**Faizan Toheed**

* **Degree:** BS Data Science @ University of Management and Technology (UMT), Lahore
* **Focus Areas:** Machine Learning, Generative AI, Agentic AI & HCI
* **GitHub:** [@faizantoheed321](https://github.com/faizantoheed321)
