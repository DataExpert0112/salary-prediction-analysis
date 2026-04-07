# 🧠 Salary Prediction & Job Market Analysis

## 📌 Project Overview
This project analyzes a dataset of 250,000 job records to uncover salary trends and build a machine learning model capable of predicting salaries based on job-related features such as experience, education, industry, and location.

The dataset was sourced from Kaggle and is designed to simulate real-world job market conditions for analytical and predictive modeling purposes.

---

## 🎯 Objectives
- Analyze salary trends across industries, education levels, and experience
- Identify key factors influencing salary variations
- Develop a machine learning model for salary prediction
- Generate actionable insights for job seekers and employers

---

## 🧹 Data Cleaning
The dataset was preprocessed to ensure quality and consistency:
- Handled missing values using appropriate imputation techniques
- Removed duplicate records
- Standardized categorical variables (e.g., education level, job roles)
- Addressed salary skewness and outliers using transformation methods

---

## 📊 Exploratory Data Analysis (EDA)
Comprehensive EDA was conducted to understand the dataset and uncover patterns:
- Salary distribution analysis
- Salary comparison across education levels and experience
- Industry-based salary insights
- Correlation analysis of numerical variables

---

## 📈 Key Insights
- **Experience** is the strongest predictor of salary
- **Location** significantly influences earnings, with the USA and India showing dominant trends
- Higher education levels (PhD, Master’s) are associated with higher median salaries
- Company size plays a role in salary distribution
- Salary data is right-skewed due to the presence of high-income earners

---

## 🤖 Machine Learning Model

### Models Used
- Linear Regression (Baseline Model)
- Random Forest Regressor (Improved Model)

### 📈 Model Performance
| Metric | Linear Regression | Random Forest |
|--------|------------------|--------------|
| R² Score | 0.963 | 0.961 |
| MAE | 5,436 | - |
| RMSE | 7,125 | - |

---

## 🔥 Feature Importance
Top features influencing salary predictions:
- Experience Years (~20%)
- Location (India, USA)
- Company Size
- Education Level (PhD)
- Job Role (Data Analyst, Business Analyst)

---

## 🛠 Tools & Technologies
- Python
- Pandas & NumPy (Data Manipulation)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine Learning)

---
