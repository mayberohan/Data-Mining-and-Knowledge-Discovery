# 📊 Data Mining & Knowledge Discovery — DMS672

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)]()
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)]()
[![ML](https://img.shields.io/badge/Focus-Machine%20Learning-green)]()
[![Course](https://img.shields.io/badge/Course-DMS672-9cf)]()

A collection of 5 assignments and a final machine learning project completed as part of the **DMS672: Data Mining & Knowledge Discovery** course.  
Work includes Exploratory Data Analysis (EDA), extensive preprocessing, PCA, decision trees, and supervised ML modeling.

---

## 📁 Repository Structure

```bash
├── Assignment_1/      # EDA on telecom churn dataset
├── Assignment_2/      # Titanic dataset EDA
├── Assignment_3/      # Extended Titanic dataset EDA
├── Assignment_4/      # Data preprocessing + PCA
├── Assignment_5/      # Decision Tree modeling on car + churn dataset
├── Project/           # Student Performance Prediction ML Project
└── README.md

---

## 📘 Assignments Summary

### 📝 Assignment 1 — Telecom Churn EDA
**Objective:** Understand customer churn behavior using Exploratory Data Analysis.
* **Key Findings:** Analyzed customer distribution, service usage, and contract types. Identified that short tenure and high monthly charges are strong indicators of churn.

### 📝 Assignment 2 — Titanic Dataset EDA
**Objective:** Analyze factors affecting survival rates on the Titanic.
* **Key Findings:** Visualized survival trends based on gender, class, and age. Confirmed that female passengers and 1st class ticket holders had significantly higher survival rates.

### 📝 Assignment 3 — Advanced Titanic EDA
**Objective:** Deep dive into feature interactions and multivariate analysis.
* **Key Findings:** Explored family size impact and cabin location patterns. Found that smaller families had better survival chances than those traveling alone or in large groups.

### 📝 Assignment 4 — Data Preprocessing + PCA
**Objective:** Clean the dataset and reduce dimensionality for modeling.
* **Techniques:** Handled missing values, capped outliers, and performed string normalization.
* **PCA:** Reduced features to **4 Principal Components** while retaining ≥ 95% of the variance.

### 📝 Assignment 5 — Decision Trees
**Objective:** Build and optimize Decision Tree classifiers.
* **Part A (Car Evaluation):** Achieved **99% accuracy** using full tree modeling.
* **Part B (Telco Churn):** Compared full-grown vs. pruned trees. Pruning significantly improved the model's ability to generalize to new data.

---

## 🎓 Final Project — Student Performance Predictor

**Goal:** Predict student performance based on demographic and academic data using supervised machine learning.
* **Approach:** Integrated techniques from previous assignments (EDA, Preprocessing, PCA) to build a robust predictive model.
* **Outcome:** Successfully identified key factors influencing grades, such as study time and previous failures.

---