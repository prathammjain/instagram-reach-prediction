# 📊 Instagram Reach Prediction

Predicting the organic reach of Instagram posts using real-world data, regression techniques, and feature engineering.

## 📌 Project Summary

This project explores how different posting patterns (like day of week, post trends, etc.) influence Instagram reach. It applies techniques from linear and polynomial regression to predict post performance, with a focus on interpretability and real-world insight.

## 🔍 Problem Statement

Can we forecast how many people a future Instagram post will reach based on the day, trend, and past performance?  
Using a time-series dataset of post reach, we aim to build a model that helps creators post more strategically.

---

## 🧠 Techniques Used

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Linear Regression
- Polynomial Regression
- RMSE & R² Evaluation
- Residual Plot Analysis

---

## 📈 Results

| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | 15719.82 | 0.67 |
| Polynomial Regression | 17138.21 | 0.61 |

While linear regression surprisingly outperformed the polynomial model, both gave insights into which factors impact reach.

---

## 🔬 Key Learnings

- **Day of Week** was a strong signal for engagement.
- Feature scaling improved convergence and accuracy.
- Some nonlinear trends did not significantly outperform linear ones.
- Residual plot showed areas of model weakness.

---

## 📁 Project Structure

