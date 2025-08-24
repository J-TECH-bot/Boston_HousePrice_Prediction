🏠 Boston House Price Prediction
📌 1. Project Overview

This project predicts house prices in Boston using the well-known Boston Housing dataset. The goal is to understand how different features (e.g., number of rooms, crime rate, location) influence house prices and to build a predictive model using Linear Regression.

⚙️ 2. Dataset

Source: Boston Housing Dataset (from scikit-learn or UCI repository)

Features: 13 attributes such as crime rate, number of rooms, property tax rate, etc.

Target Variable: MEDV (Median value of owner-occupied homes in $1000s)

🧠 3. Model Used

Algorithm: Linear Regression

Reason: Linear Regression is a simple yet powerful supervised learning algorithm, often used as a baseline for regression problems. It helps in understanding the relationship between independent variables and target values.

📊 4. Steps in the Project

Data Preprocessing

Loaded the dataset

Checked for missing values

Performed feature scaling (if needed)

Exploratory Data Analysis (EDA)

Correlation heatmaps

Distribution of house prices

Relationship between features and target

Model Training

Applied Linear Regression

Split data into train & test sets

Fitted the model

Evaluation

Metrics: R² Score, Mean Squared Error (MSE), Mean Absolute Error (MAE)

🚀 5. Results & Conclusion

The model achieved an R² score of ~0.xx on the test set.

Found that features like average number of rooms (RM) and lower status population percentage (LSTAT) have the most significant effect on house prices.

While Linear Regression provides a good baseline, more advanced models (Random Forest, Gradient Boosting, etc.) can improve performance.
