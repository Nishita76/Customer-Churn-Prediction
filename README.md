# Customer-Churn-Prediction
Customer churn prediction is a crucial task for businesses to identify customers who are likely to stop using their services. By predicting churn, companies can take proactive measures to retain customers and reduce revenue loss.
The goal of this project is to build a machine learning model that predicts whether a customer will churn (leave) or not, based on historical data.

Datasrt: The dataset here used is the IBM Telco customer churn dataset which contains customer details, including demographics, account information, and usage patterns. The target variable is "Churn", which indicates whether a customer has churned (Yes) or not (No).

### Machine Learning Models Used:
We trained and evaluated multiple models:
- Logistic Regression 
- Random Forest
- XGBoost
- K-Nearest Neighbors
- Support Vector Classifier

After training and cross-validating multiple models, successfully built a churn prediction model with 80% accuracy with Logistic Regression model. 
Feature importance analysis provides actionable insights for retention strategies.
The model can be improved further by hyperparameter tuning and additional feature engineering.

The final predictions, including customer IDs and churn probabilities, are saved in a CSV file (churn predictions) for business analysis.
