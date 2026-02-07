# AI & Machine Learning – Task 2
Feature Engineering, Model Optimization & Performance Comparison

Author: Narendra Kumar Sharma

Internship Domain: Artificial Intelligence & Machine Learning  

---

## Project Overview

This project is part of AI/ML Internship Task-2, focused on building a professional machine learning workflow that includes data preprocessing, feature scaling, training multiple regression models, and comparing their performance using evaluation metrics.

The California Housing Dataset is used to predict median house prices based on socioeconomic and geographical features.

---

## Dataset

Dataset Name: California Housing Dataset  
Source: scikit-learn (fetch_california_housing)  

Target Variable:
- Median House Value  

Input Features:
- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

---

## Models Implemented

The following regression models were trained and evaluated:

1. Linear Regression – baseline model  
2. Ridge Regression – regularized linear model  
3. Decision Tree Regressor – captures non-linear relationships  

---

## Methodology

1. Dataset loading and inspection  
2. Feature-target separation  
3. Feature scaling using StandardScaler  
4. Train-test split (80% training, 20% testing)  
5. Model training  
6. Model evaluation using:
   - RMSE (Root Mean Squared Error)
   - R² Score  
7. Best model selection  
8. Visualization (Actual vs Predicted values)

---

## Results Summary

| Model | RMSE | R² Score |
|------|------|----------|
| Linear Regression | 0.745581 | 0.575788 |
| Ridge Regression | 0.745554 | 0.575819 |
| Decision Tree Regressor | 0.724234 | 0.599732 |

Best Model: Decision Tree Regressor  

Reason:
- Lowest prediction error
- Highest explanatory power

---

## Visualization

An Actual vs Predicted House Prices scatter plot was generated to visually evaluate the performance of the best model.

---

## Tools & Technologies

- Python  
- Jupyter Notebook  
- pandas, NumPy  
- scikit-learn  
- matplotlib  

---

## Files Included

AI_ML_Task2_Model_Comparison.ipynb – Notebook with model training, evaluation, and comparison

Task2_Model_Comparison_Report.pdf – Report summarizing methodology and results


---

## Conclusion

This project demonstrates the importance of feature scaling, model comparison, and objective evaluation in machine learning.

The Decision Tree Regressor performed best due to its ability to model non-linear relationships in housing data.

---
