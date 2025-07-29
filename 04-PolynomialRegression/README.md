# 📌 Polynomial Regression – Position Level vs Salary

## 📁 Dataset Information
- **Source**: Self-collected using platforms like Google, Glassdoor, and LinkedIn.
- **Features**:
  - `Position`: Roles ranging from Business Analyst to CEO.
  - `Level`: Numeric representation of hierarchy (1 to 10).
  - `Salary`: Annual salary in USD.

## 🎯 Objective
To predict the average salary of an employee based on their position level using **Polynomial Regression**.

> Example: A Region Manager at level 6 has worked for 2 years. Instead of predicting salary at level 6, we input **6.5** to get a more realistic estimate.

## 🧠 Concepts Covered
- Polynomial feature transformation using `PolynomialFeatures` from Scikit-learn.
- Fitting a non-linear regression model using a linear regression base.
- Model training and prediction with custom input levels (e.g., 6.5).
- Visualization of Linear vs Polynomial Regression fit.

## 📊 Visualization
- Plotted graphs show that the **Polynomial model** fits the data better than a linear one.
- Ideal for predicting intermediate values that aren't explicitly in the dataset.

## 🛠️ Libraries Used
```bash
numpy  
pandas  
matplotlib  
scikit-learn
```

## 💡 Real-World Use Case
In organizations, promotions or time spent at a position affects salary. This model helps approximate realistic salaries for levels like **5.5, 6.7**, etc., making it useful for HR analytics and compensation planning.

---

🚀 Built as part of my machine learning learning journey. Stay tuned for the main projects!
