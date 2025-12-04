# Lloyd-Bank---Customer-Churn-prediction-Forage-job-simulation-
This repository contains my solution for the Lloyds Banking Group – Data Science Job Simulation on Forage. The project focuses on analyzing customer data, engineering impactful features, and building a machine-learning model to predict customer churn.

## 🎯 Project Objectives
- **Understand Churn Drivers:** Identify demographic, behavioral, and transactional factors influencing customer churn.  
- **Predict At-Risk Customers:** Build machine learning models to flag potential churners.  

## 📊 Dataset Overview
- **Initial Dataset:** 22 features, 1,000 customers
- **Final Dataset:** 17 features, standardized and cleaned  
- **Target Variable:** ChurnStatus (Churned vs. Retained)  
- **Churn Rate:** 20.40% (284 churned customers)
(Initial Dataset available on Forage)

## Exploratory Data Analysis (EDA)
### Key EDA Components
- Demographic analysis (age, gender, income, marital status)  
- Behavioral pattern analysis (login frequency, spending, service usage)  
- Correlation analysis with churn  

## Data Processing Pipeline
- **Data Cleaning:** Missing value handling, feature selection  
- **Feature Engineering:** Standardization of numerical variables  
- **Class Balancing:** SMOTE oversampling for minority class (churn)  
- **Data Splitting:** 80-20 train-test split with stratification

## Model Building & Prediction
### Modeling Components
- Implementation of 5 classification algorithms:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - Support Vector Machine (SVM) 
- Hyperparameter tuning with grid search  
- Comprehensive model evaluation (AUC, precision, recall, F1-score)  
- Feature importance analysis  
- Threshold optimization and calibration  
## Best Performing Model
- Random Forest
