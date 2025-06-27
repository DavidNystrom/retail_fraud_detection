## Fraud Detection in Retail Transactions

This project builds a fraud detection system for retail transaction data, aiming to identify and flag fraudulent purchases in real time. It addresses the critical problem of financial losses due to fraud by using data science to distinguish between legitimate and suspicious activity. By learning patterns from past transactions, the model enables early detection and helps protect business revenue.

The system leverages classification models such as logistic regression, random forests, and XGBoost, with special attention to class imbalance via techniques like SMOTE oversampling and class weighting. Tools include scikit-learn for modeling and evaluation, and Seaborn for visualizations. The pipeline includes exploratory analysis, feature engineering, model training, and deployment. A Flask API will be implemented to allow real-time fraud scoring on new transactions, simulating integration into a live transaction processing system.
