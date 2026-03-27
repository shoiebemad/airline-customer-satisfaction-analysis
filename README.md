# Airline Customer Satisfaction Analysis

## Overview
This project analyzes airline passenger satisfaction data and builds machine learning models to predict customer satisfaction. It also includes an interactive dashboard for exploring key insights.

---

## Key Features
- Data cleaning and preprocessing  
- Feature engineering (Overall Satisfaction, satisfaction levels)  
- Exploratory Data Analysis (EDA)  
- Multiple visualizations (histograms, box plots, scatter plots, sunburst)  
- Model comparison using cross-validation  
- Best model selection (**XGBoost**)  
- Model evaluation (accuracy, confusion matrix, ROC curve)  
- Interactive dashboard using Dash & Plotly  
- Model saving using joblib  

---

## Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Plotly  
- Dash  

---

## Models Evaluated
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- AdaBoost  
- Random Forest  
- Naive Bayes  
- **XGBoost (Best Model)**  

---

## Results
- **Best Model:** XGBoost  
- **Cross-validation Accuracy:** ~96.3%  

---

## Dashboard
The project includes an interactive dashboard where users can:
- Select passenger class  
- Explore age distribution  
- Analyze satisfaction levels  
- Visualize customer patterns  

---

## Model Saving
```python
joblib.dump(model_xgb, "xgboost_model.pkl")
```

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/shoiebemad/airline-customer-satisfaction-analysis.git
```

2. Navigate to the project folder:
```bash
cd airline-customer-satisfaction-analysis
```

3. Install the required libraries:
```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook to explore the analysis and models.

5. (Optional) Run the dashboard to interact with the visualizations.

---

## Conclusion

This project demonstrates a complete data science workflow, starting from data cleaning and exploratory analysis to building and evaluating multiple machine learning models.

**XGBoost achieved the highest performance** and was selected as the final model for predicting customer satisfaction.

The results highlight how data-driven approaches can be used to better understand customer behavior and improve decision-making in the airline industry.

---

