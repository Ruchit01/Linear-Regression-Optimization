# Linear Regression Optimization

This project implements and compares different optimization methods for
multivariable linear regression using the California Housing dataset.

## Optimization Methods

-   Batch Gradient Descent
-   Stochastic Gradient Descent
-   Mini-Batch Gradient Descent
-   Closed-form solution using the Normal Equation

## What I Explored

-   Multivariable Linear Regression
-   Feature Standardization
-   Cost Function
-   Gradient Descent
-   Optimization and Convergence
-   R² Score
-   Comparison of different optimization methods

## Results

The project compares the methods based on:

-   Convergence behavior
-   Cost reduction
-   Running time
-   R² score

Batch Gradient Descent gives a smoother convergence, while Stochastic
Gradient Descent makes more frequent updates but has more fluctuations.
Mini-Batch Gradient Descent provides a balance between the two. The
closed-form solution is very fast for this dataset.

## Dataset

The California Housing dataset is loaded directly using
`fetch_california_housing()` from Scikit-learn, so the dataset file is
**not included** in this repository.

## Technologies Used

-   Python
-   NumPy
-   Pandas
-   Matplotlib
-   Scikit-learn
-   Jupyter Notebook
