Data-Science-Project---Mobile Money Fraud-Detection

Enhancing Fraud Detection in Mobile Money Transactions with Machine Learning Techniques

This project investigates how machine learning models can improve fraud detection in mobile money transactions by minimizing false positives while accurately identifying frauds. Random Forest, Extreme Gradient Boosting (XGBoost), and One-Class Support Vector Machine (One-Class SVM) models are developed and compared using a simulated dataset.

Data Source: Kaggle (https://www.kaggle.com/datasets/mtalaltariq/paysim-data/data)

Data Type: Tabular Data

Time Frame: Simulated Transactions (Not tied to specific dates)

Data Format: CSV
The Dataset contains: Step (time), transaction type, amount, old and new balances for sender and receiver, fraud label (isFraud), and flagged transactions (isFlaggedFraud).

Features Engineered:

Amount Difference (diff_amount)

Time Gap Between Transactions (diff_time)

Encoded Transaction Types

Standardized Numerical Features

Result Summary

XGBoost outperformed Random Forest and One-Class SVM with the highest recall and F1-score, making it the most suitable model for real-time fraud detection systems.


How to Run the Code

Libraries used:

pandas, numpy, matplotlib, seaborn

scikit-learn, xgboost

Clone the repository: git clone https://github.com/Jafarurchintala/Data-Science-Final-Project.git

Open and run the Jupyter Notebook to:

Install the required packages

Open and run the Jupyter Notebook






