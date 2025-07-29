# 📈 SVR (Support Vector Regression) with RBF Kernel

This project applies **Support Vector Regression (SVR)** to predict salaries based on position level. It builds upon the same dataset used in my Polynomial Regression project, but leverages the power of SVR and feature scaling to handle non-linear patterns more effectively.

---

## 🔍 Objective

To predict salary for a given position level using SVR with an **RBF (Radial Basis Function)** kernel and demonstrate:
- Proper application of **feature scaling**
- Reverse transformation to interpret predictions in original units
- Visualization of the SVR curve vs actual data

---

## 🧠 Key Learnings

✅ Applied **StandardScaler** on both features and target  
✅ Learned importance of scaling for kernel-based models  
✅ Used **inverse_transform** to convert model predictions back to actual salary scale  
✅ Visualized the SVR model's fit to the data  
✅ Compared to earlier regression approaches

---

## 📂 Dataset

- Simple dataset with two columns:
  - `Level`: Position level (1 to 10)
  - `Salary`: Average salary for that level
- Manually created or inspired by Glassdoor/LinkedIn estimates  
- You can also try this dataset:  
  👉 [Kaggle - Position Salaries Dataset](https://www.kaggle.com/datasets/saurabhshahane/position-salaries)

---

## 🛠️ Libraries Used

```bash
numpy  
pandas  
matplotlib  
scikit-learn  
