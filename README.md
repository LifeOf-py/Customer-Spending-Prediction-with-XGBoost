# 🧮 Customer-Spending-Prediction-with-XGBoost

This project focuses on building, tuning, and evaluating multiple **regression models** to predict how much a customer will spend on a catalog purchase based on demographic and behavioral features.

---

## 📌 Project Overview

- **Task**: Predict the continuous `Purchase` amount from customer data.
- **Goal**: Identify the best regression model that minimizes prediction error.
- **Dataset**: Customer-level features and their catalog purchase amounts.
- **Metric**: Root Mean Squared Error (RMSE)

---

## 🧰 Tools & Libraries
- Python, Jupyter Notebook
- `scikit-learn`
- `XGBoost`
- `LightGBM`
- `MLPRegressor` from `sklearn.neural_network`

---

## 🧠 Modeling Strategy

- Applied **Nested Cross-Validation** to ensure unbiased model evaluation.
- Compared models: Linear Regression, KNN, SVR, Decision Tree, Random Forest, Gradient Boosting, XGBoost, LightGBM, and Neural Network.
- Final model was tuned using `GridSearchCV` and tested on a holdout set.

---

## ✅ Results

- Best model: **XGBoost** (or Neural Net, depending on part B)
- Robust performance and generalization verified on the holdout set.

---

## 💼 Business Value

Predicting customer spend helps optimize:
- Targeted marketing
- Inventory forecasting
- Personalized promotions

---

> 📂 Explore the full notebook: `regression_modeling.ipynb`
