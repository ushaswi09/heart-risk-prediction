# Explainable Heart Disease Risk Prediction using Machine Learning

## Overview
This project predicts heart disease risk using clinical patient data and machine learning. The system provides both prediction and explainability using SHAP, making the model interpretable for healthcare applications.
Dataset size: 920 patients  
Target: Heart disease risk (0 = No Disease, 1 = Disease)

## Models Used
Three machine learning models were trained and evaluated:
- Logistic Regression — Accuracy: 84%
- Random Forest — Accuracy: 89%, AUC: 0.95 (Best Model)
- XGBoost — Accuracy: 88.6%, AUC: 0.947
Random Forest achieved the best performance and was selected as the final model.

## Explainable AI (SHAP)
SHAP was used to explain model predictions and identify important clinical features.
Key features influencing predictions:
- Age
- Cholesterol
- Maximum heart rate (thalch)
- ST depression (oldpeak)
- Chest pain type
This makes the model transparent and interpretable.
  
## System Capabilities
The system can:
- Predict heart disease risk
- Provide probability score
- Explain predictions using SHAP
- Identify important clinical risk factors
Example output:
Prediction: Heart Disease  
Risk Probability: 0.95  

## Technologies Used
- Python
- Scikit-learn
- XGBoost
- SHAP
- Pandas
- NumPy
- Matplotlib

## Conclusion
Random Forest achieved the best performance with Accuracy = 89% and AUC = 0.95.
This project demonstrates an accurate and explainable machine learning approach for cardiovascular risk prediction.

## Author
Ushaswi Karuturi  
Biomedical Engineering Student
