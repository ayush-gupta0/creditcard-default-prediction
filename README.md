# Predictive Modeling for Credit Card Default

## Objective
This project aims to develop a machine learning model that accurately predicts the probability of a credit card holder defaulting on their payment in the next month.

## Dataset
The project uses the "Default of Credit Card Clients" dataset from the UCI Machine Learning Repository, containing 30,000 observations.

## Methodology
1.  **Data Cleaning & EDA:** Handled inconsistent categorical data and analyzed feature distributions.
2.  **Feature Engineering:** Scaled numerical features using `StandardScaler`.
3.  **Modeling:** Trained and evaluated Logistic Regression and XGBoost models.
4.  **Evaluation:** The final XGBoost model achieved an **AUC score of 0.78**.

## How to Run
1.  Clone this repository.
2.  Install the required libraries: `pip install pandas scikit-learn xgboost matplotlib seaborn`.
3.  Run the `Credit_Default_Prediction.ipynb` notebook.
