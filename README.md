# Customer Churn Prediction

This capstone project explores how machine learning can help predict customer churn using behavioral, demographic, and subscription-related features. The goal is to build a model that accurately identifies at-risk customers and provides insight into which factors contribute most to churn.

## 📊 Problem Statement
Customer retention is a critical business concern. Identifying users likely to cancel their subscription enables companies to take proactive steps in improving satisfaction and reducing churn.

## 🔍 Dataset Overview
- Simulated customer data (demographics, behavior, support history, etc.)
- Cleaned and preprocessed in Python
- Target variable: `churn` (1 = churned, 0 = retained)

## 🧠 Models Used
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 📈 Results
- KNN performed best on validation accuracy
- Decision Tree offered the most interpretability
- Key factors influencing churn: complaints, monthly charge, and number of services

## 🛠 Tools & Technologies
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Exploratory data analysis (EDA)
- Model evaluation & comparison

## 🔗 View Report
https://github.com/noliangeles/Capstone/blob/main/index.pdf

## 📁 Future Improvements
- Deploy model with a dashboard or API
- Test ensemble methods (Random Forest, XGBoost)
- Incorporate time-series behavioral trends
