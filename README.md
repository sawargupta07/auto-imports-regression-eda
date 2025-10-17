# auto-imports-regression-eda
EDA and Multiple Linear Regression on the Auto Imports dataset (Colab + Python + StatsModels)

# 🚗 Auto Imports Regression & EDA (Google Colab)

A complete **Exploratory Data Analysis (EDA)** and **Multiple Linear Regression** project performed on the *1985 Auto Imports Dataset*.

This repository demonstrates how to clean, analyze, and model real-world automobile data entirely in **Google Colab**, using **Pandas**, **Seaborn**, and **StatsModels**.

---

## 📘 Overview

The project explores how automobile attributes (engine size, weight, fuel type, etc.) influence the **price** of a vehicle.  
It follows a clear 3-notebook workflow:

| Notebook | Description |
|-----------|--------------|
| [`01_munging_eda.ipynb`](notebooks/01_munging_eda.ipynb) | Data loading, cleaning (“?” handling), numeric conversion, and correlation analysis. |
| [`02_models_ols.ipynb`](notebooks/02_models_ols.ipynb) | Builds and compares two regression models (full vs. reduced). |
| [`03_assumptions_anova.ipynb`](notebooks/03_assumptions_anova.ipynb) | Performs ANOVA and diagnostic checks for regression assumptions. |

---

## 🎯 Objectives

- Practice a complete **data-to-model workflow** in Python.  
- Quantify relationships between vehicle specifications and price.  
- Validate linear regression assumptions with ANOVA and residual diagnostics.  
- Showcase clean, reproducible code using **Google Colab + GitHub**.

---

## 🧠 Dataset Summary

**Name:** Auto Imports Database  
**Records:** 205 automobiles  
**Attributes:** 26 (numeric + categorical)

| Example Feature | Description |
|------------------|-------------|
| `symboling` | Risk rating (-3 safe → +3 risky) |
| `engine-size` | Engine displacement (cm³) |
| `horse-power` | Engine output |
| `curb-weight` | Vehicle weight |
| `price` | Target variable (USD) |

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Automobile)

---

## 🧰 Tools & Libraries

- 🐍 **Python 3.10+**
- 📊 **Pandas**, **NumPy**, **Seaborn**, **Matplotlib**
- 🧮 **StatsModels**
- ☁️ **Google Colab** (for easy Drive integration)

---

## 📈 Results Summary

- Positive correlation between `engine_size`, `curb_weight`, `width` and `price`.  
- Negative correlation between fuel efficiency (`city_mpg`, `highway_mpg`) and price.  
- Reduced model achieved nearly the same explanatory power as full model (`R² ≈ 0.84`).  

---

## ▶️ Run It Yourself (Colab)

1. Open any notebook and click:
