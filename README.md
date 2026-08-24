📈 Linear Regression from Scratch & with Scikit-learn
A hands-on implementation of Simple and Multiple Linear Regression — built both from first principles (using Gradient Descent and the Normal Equation) and with scikit-learn, to demonstrate a solid understanding of the underlying math, not just the library calls.
🎯 Project Overview
This project predicts Salary based on Years of Experience . The goal wasn't just to get a working model, but to understand why it works — from the cost function and gradients up to the final predictions.
🧠 What's Inside
Notebook Section
Description
1. Data Loading & Cleaning
Handling missing values, checking data types
2. Exploratory Data Analysis
Scatter plots, correlation checks
3. Linear Regression (Scikit-learn)
Quick baseline model using LinearRegression()
4. Linear Regression (From Scratch)
Manual implementation using Gradient Descent — deriving the cost function, computing partial derivatives, and updating weights step by step
5. Model Evaluation
R² Score, MSE, RMSE, and residual plots to check model fit
6. Comparison
Verifying that the from-scratch model converges to the same coefficients as scikit-learn
🛠️ Tech Stack
Python
NumPy
Pandas
Matplotlib
Scikit-learn
📊 Key Results
R² Score: ]
MSE: []
Gradient Descent converged to coefficients matching scikit-learn's output within [X] epochs.
🚀 How to Run

Code
📚 What I Learned
How the cost function (MSE) is derived and why we minimize it
How partial derivatives and the chain rule are used to compute gradients
The difference between the Normal Equation and Gradient Descent as two ways to solve the same problem
How to evaluate a regression model beyond just "does it run" — using R², residual plots, and train/test splits to catch overfitting
🔗 Connect
Built by Zarmeen Gul — learning AI/ML from scratch, one concept at a time.
