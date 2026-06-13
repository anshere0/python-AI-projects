# Telco Customer Churn Prediction using Logistic Regression

## Project Overview

Customer churn is a significant challenge in the telecommunications industry, as losing existing customers directly impacts revenue and business growth. This project develops a Machine Learning model using Logistic Regression to predict whether a customer is likely to leave the telecom service provider.

The project follows a complete Machine Learning workflow including data exploration, preprocessing, feature engineering, model training, evaluation, and interpretation of results.

## Dataset

Dataset: Telco Customer Churn Dataset

Source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Target Variable:

* Churn

  * Yes = Customer left
  * No = Customer stayed

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Missing Value Treatment
4. Categorical Feature Encoding
5. Feature Scaling
6. Train-Test Split
7. Logistic Regression Model Training
8. Performance Evaluation
9. Feature Importance Analysis
10. Business Insights

## Model Performance

| Metric          | Value |
| --------------- | ----- |
| Accuracy        | 81%   |
| ROC-AUC Score   | 0.84  |
| Churn Precision | 0.66  |
| Churn Recall    | 0.57  |
| Churn F1-Score  | 0.61  |

## Key Findings

* Customers with month-to-month contracts are more likely to churn.
* Customers with longer tenure are less likely to leave.
* Billing and service-related features significantly influence churn behavior.
* Logistic Regression provides a strong baseline model with good interpretability.

## Future Improvements

* Apply SMOTE to address class imbalance.
* Experiment with Random Forest and XGBoost.
* Perform advanced feature engineering.
* Hyperparameter optimization using GridSearchCV.

## Author

Ansh Arora
