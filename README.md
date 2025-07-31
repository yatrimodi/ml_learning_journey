# 📘 ML Learning Journey – Daily Model Progress

A collection of beginner-friendly machine learning models trained daily as part of my AI/ML learning journey. Each day features a different dataset and model type.

---

## 📅 Day 1 – Linear Regression: SAT vs GPA

**🎯 Goal:** Predict GPA based on SAT scores using Simple Linear Regression.

- 📁 Dataset: `1.01. Simple linear regression.csv`
- 🔢 Features:
  - Input: `SAT`
  - Output: `GPA`
- ⚙️ Model: `LinearRegression()`

**📊 Results:**
- ✅ R² Score: `0.406`
- 📉 Mean Squared Error (MSE): `0.0433`
- 🔍 Example Prediction: `SAT = 1740 → GPA ≈ 3.33`

📈 **Visualization:**  
Scatter plot of SAT vs GPA with a regression line.

---

## 📅 Day 2 – Linear Regression: Salary vs Years of Experience

**🎯 Goal:** Predict Salary based on Years of Experience using Simple Linear Regression.

- 📁 Dataset: `Salary_dataset.csv`
- 🔢 Features:
  - Input: `YearsExperience`
  - Output: `Salary`
- ⚙️ Model: `LinearRegression()`

**📊 Results:**
- ✅ R² Score: `0.9576`
- 📉 Mean Squared Error (MSE): `30,801,096.88`

📈 **Visualization:**  
Scatter plot of Experience vs Salary with a regression line.

---

## 📅 Day 3 – Text Classification: News Headlines

**🎯 Goal:** Classify news content based on headlines using TF-IDF and Logistic Regression.

- 📁 Dataset: `news_summary.csv`
- 🔢 Features:
  - Input: `ctext` (cleaned article text)
  - Target: `headlines`
- ⚙️ Model Pipeline:
  - `TfidfVectorizer(max_features=5000)`
  - `LogisticRegression(max_iter=1000)`

---

> *Keep learning, keep building!* 💻✨
