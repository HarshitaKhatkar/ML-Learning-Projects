# Multiple Linear Regression - Startup Profit Prediction

This project implements a **Multiple Linear Regression** model to predict the profit of startups based on features like:
- R&D Spend
- Administration
- Marketing Spend
- State (as categorical data)

### 📊 Objective
To build a model that can estimate a startup's profit using multiple independent variables.

---

## 📁 Dataset
- The dataset includes 50 startups.
- Features:
  - `R&D Spend`
  - `Administration`
  - `Marketing Spend`
  - `State` (categorical)

---

## ⚙️ Libraries Used
- numpy
- pandas
- matplotlib
- scikit-learn

---

## 📈 Model Summary
- Preprocessed categorical data using dummy variables (OneHotEncoding).
- Avoided the **dummy variable trap** by removing one dummy column.
- Trained a Multiple Linear Regression model using scikit-learn.
