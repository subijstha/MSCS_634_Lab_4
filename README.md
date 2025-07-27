# MSCS 634 Lab 4: Regression Modeling and Regularization

## Lab Overview

In this lab, we explored multiple regression techniques and deepened our understanding by applying regularization methods to prevent overfitting and enhance model performance. The Diabetes Dataset from `sklearn.datasets` was used to demonstrate the following key concepts:

### Objectives
- Implemented **Linear Regression**, **Multiple Regression**, and **Polynomial Regression** models.
- Applied **Ridge Regression** and **Lasso Regression** to understand the impact of regularization.
- Evaluated models using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)
- Visualized regression results to interpret patterns and model performance.

---

## Key Insights

- **Simple Linear Regression** is easy to interpret but limited in predictive power when only one feature is used.
- **Multiple Regression** improved performance by leveraging multiple predictors.
- **Polynomial Regression** demonstrated how higher-order terms can capture nonlinear relationships, but also the risk of overfitting.
- **Ridge and Lasso Regression** showcased how regularization reduces model complexity and enhances generalization, especially in cases of multicollinearity or high-dimensional data.

---

## Challenges & Decisions

- **Feature Selection**: Careful selection and engineering of features was important to avoid redundancy and multicollinearity.
- **Regularization Tuning**: Choosing appropriate alpha values for Ridge and Lasso required experimentation to find a balance between bias and variance.
- **Overfitting**: Polynomial models required close monitoring of performance metrics to avoid overfitting.

---

## Files in Repository

- `MSCS_634_Lab_4_Regression.ipynb`: Complete lab notebook with code, visualizations, and analysis.
- `README.md`: This documentation file describing the purpose, insights, and experiences from the lab.

---

## How to Run

1. Clone this repository or download the `.ipynb` file.
2. Open the notebook in Jupyter Notebook or JupyterLab.
3. Run all cells sequentially to reproduce the regression analyses and visualizations.

---

