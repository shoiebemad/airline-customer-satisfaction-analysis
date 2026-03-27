Airline Customer Satisfaction Analysis

This project analyzes airline passenger satisfaction data and builds machine learning models to predict whether a customer is satisfied or not. It also includes an interactive dashboard for exploring key insights.

📊 Project Overview

The goal of this project is to:

Understand factors affecting airline customer satisfaction
Perform data cleaning and exploratory data analysis (EDA)
Build and compare multiple machine learning models
Select the best-performing model
Visualize results through an interactive dashboard
🧠 Key Features
Data preprocessing and cleaning
Feature engineering (Overall Satisfaction, satisfaction levels)
Exploratory Data Analysis (EDA)
Multiple visualizations (histograms, box plots, scatter plots, sunburst)
Model comparison using cross-validation
Final model: XGBoost
Model evaluation (accuracy, confusion matrix, ROC curve)
Interactive dashboard using Dash & Plotly
Model saving using joblib
🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
XGBoost
Plotly
Dash
Matplotlib / Seaborn
🤖 Machine Learning Models

The following models were evaluated:

Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Decision Tree
AdaBoost
Random Forest
Naive Bayes
XGBoost (Best Model)
📈 Results
Best Model: XGBoost
Cross-validation Accuracy: ~96.3%
XGBoost outperformed all other models in predicting customer satisfaction.
📊 Dashboard

An interactive dashboard was built using Dash, allowing users to:

Select passenger class
Explore age distribution
Analyze satisfaction levels
Visualize customer behavior patterns
💾 Model Saving

The final trained model is saved using joblib:

joblib.dump(model_xgb, "xgboost_model.pkl")
▶️ How to Run
Clone the repository:
git clone https://github.com/shoiebemad/airline-customer-satisfaction-analysis.git
Navigate to the project folder:
cd airline-customer-satisfaction-analysis
Install dependencies:
pip install -r requirements.txt
Run the notebook or dashboard.
📌 Conclusion

This project demonstrates a complete data science workflow, from data analysis to machine learning and deployment. XGBoost proved to be the most effective model for predicting airline customer satisfaction.
