# 🎓 Student Performance Analysis & Prediction

This project analyzes student exam performance and builds models to:
- Explore score patterns with EDA
- Predict **Pass/Fail** (classification)
- Predict **exact average score** (regression)

Dataset: Kaggle – Students Performance in Exams  
(If not included in this repo, download: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

## 📂 Structure



## 🔍 EDA Highlights
- Score distributions
- Effect of gender & parental education
- Correlations among math, reading, writing

## 🤖 Models
- **Classification:** Random Forest (Pass/Fail)
- **Regression:** Linear Regression, Random Forest Regressor

## 📊 Results
- Classification accuracy: **0.95%**
- Linear Regression: **R² ≈ 1.00**
- Random Forest Regression: **R² ≈ 0.99**

## ⚙️ Run Locally
```bash
pip install -r requirements.txt
jupyter notebook notebook/Student_Performance.ipynb

