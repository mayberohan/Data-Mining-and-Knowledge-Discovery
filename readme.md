# 📊 Data Mining & Knowledge Discovery — DMS672

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)]()
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)]()
[![ML](https://img.shields.io/badge/Focus-Machine%20Learning-green)]()
[![Course](https://img.shields.io/badge/Course-DMS672-9cf)]()

A collection of 5 assignments and a final machine learning project completed as part of the **DMS672: Data Mining & Knowledge Discovery** course.  
Work includes EDA, preprocessing, PCA, decision trees, and supervised ML modeling.

---

## 📌 Table of Contents

- [Repository Structure](#repository-structure)
- [Assignments Summary](#assignments-summary)
- [Final Project — Student Performance Predictor](#final-project--student-performance-predictor)
- [Tech Stack](#tech-stack)
- [How to Run](#how-to-run)
- [Author](#author)
- [License](#license)

---

## 📁 Repository Structure

```bash
├── Assignment_1/      # EDA on telecom churn dataset
├── Assignment_2/      # Titanic dataset EDA
├── Assignment_3/      # Extended Titanic dataset EDA
├── Assignment_4/      # Data preprocessing + PCA
├── Assignment_5/      # Decision Tree modeling on car + churn dataset
├── Project/           # Student Performance Prediction ML Project
├── Assignments_Summary.md
└── README.md

```markdown
# 📘 Assignments Summary — DMS672

This document contains a detailed summary of all five assignments submitted for the **Data Mining & Knowledge Discovery** course.

---

## 📝 Assignment 1 — Telecom Churn EDA

Dataset: Telecom Customer Churn  
Objective: **Understand churn behavior** using EDA  
Key Analysis Performed:
- Customer distribution analysis
- Contract type & churn correlation
- Service usage behavior
- Senior citizen churn patterns

📌 Outcome: Identified key churn indicators like tenure, monthly charges, contract type, etc.

---

## 📝 Assignment 2 — Titanic Dataset EDA

Objective: Analyze **factors affecting survival**  
Analysis Highlights:
- Gender-based survivability trends
- Class influence on rescue priority
- Age vs survival probability
- Fare distribution insights

📌 Outcome: Confirmed strong gender + class impact on survival.

---

## 📝 Assignment 3 — Advanced Titanic EDA

Enhanced analytics over Assignment 2  
Included:
- Feature interactions
- Family size vs survival
- Cabin-based group patterns
- Statistical distribution insights

📌 Outcome: Additional multi-variable survival patterns discovered.

---

## 📝 Assignment 4 — Data Preprocessing + PCA

Performed:
- Duplicate removal (651 rows)
- Missing value imputation
- Outlier capping
- String normalization
- Dropped noisy / constant columns
- Feature Engineering:
  - Age bands
  - Weekly working hour bands
- Standardization
- PCA analysis:
  - **4 Principal Components** explain ≥ 95% variance

📌 Outcome: **Clean dataset** ready for ML modeling & feature reduction.

---

## 📝 Assignment 5 — Decision Trees

Two parts:

### Part A — Car Evaluation Dataset
- Ordinal Encoding
- Full tree modeling
- **99% accuracy achieved**

### Part B — Telco Customer Churn
- Preprocessing pipeline (OHE + ordinal encoding)
- Full-grown vs pre-pruned vs post-pruned tree
- Evaluation using recall, precision & F1-score

📌 Outcome: Improved model generalization after pruning.

---

## ✔ Summary Table

| Assignment | Focus Area | Key Skills |
|-----------|------------|------------|
| 1 | Exploratory Data Analysis | Visualization & interpretation |
| 2 | Basic EDA | Statistical analysis |
| 3 | Advanced EDA | Feature interaction analysis |
| 4 | Data preprocessing | Cleaning, PCA, feature engineering |
| 5 | Decision Tree Modeling | Classifier development & pruning |

---

🎯 These assignments build the foundation for supervised ML — applied in the final project.

---
