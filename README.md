# 📘 Machine Learning Models Showcase

This repository contains simple machine learning models implemented using Python and `scikit-learn`. The goal is to practice model building, evaluation, and visualization using real-world datasets.

---

## 🔹 Linear Regression: SAT vs GPA

**Goal:** Predict a student's GPA based on their SAT score.

- **Dataset:** `1.01. Simple linear regression.csv`
- **Features:**
  - Input: `SAT`
  - Output: `GPA`
- **Model:** `LinearRegression()`
- **Results:**
  - R² Score: `0.406`
  - Mean Squared Error: `0.0433`
  - Prediction Example: `SAT = 1740 → GPA ≈ 3.33`
- **Visualization:** Scatter plot with regression line

---

## 🔹 Linear Regression: Salary vs Experience

**Goal:** Predict employee salary based on years of experience.

- **Dataset:** `Salary_dataset.csv`
- **Features:**
  - Input: `YearsExperience`
  - Output: `Salary`
- **Model:** `LinearRegression()`
- **Results:**
  - R² Score: `0.9576`
  - Mean Squared Error: `30,801,096.88`
- **Visualization:** Scatter plot with regression line

---

## 🔹 News Headline Classification

**Goal:** Classify news articles based on their content using headline labels.

- **Dataset:** `news_summary.csv`
- **Features:**
  - Input: `ctext` (cleaned article content)
  - Output: `headlines`
- **Model Pipeline:**
  - `TfidfVectorizer(max_features=5000)`
  - `LogisticRegression(max_iter=1000)`
---

## 🧠 Future Improvements

- Add multivariate models and polynomial regression
- Implement classification with fewer classes
- Explore deep learning (LSTM, transformers)
- Improve evaluation metrics using cross-validation

---

> 🚀 Stay tuned for more models and refinements!
