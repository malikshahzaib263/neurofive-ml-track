# Neurofive Machine Learning Track

## End-to-End Machine Learning Portfolio

**Author:** Shahzaib Arshad  
**Track:** Machine Learning Fundamentals  
**Organization:** Neurofive Solutions

---

## About This Repository

This repository documents my practical work completed during the **Neurofive Solutions Machine Learning Track**.

The projects progress from Exploratory Data Analysis and data preprocessing to classification, regression, model evaluation, hyperparameter tuning, feature engineering, ensemble learning, handling imbalanced datasets, ML pipelines, and deployment.

The track provided hands-on experience with the complete machine learning lifecycle:

**Raw Data → EDA → Data Cleaning → Feature Engineering → Preprocessing → Model Training → Evaluation → Optimization → Deployment**

---

# Repository Overview

The repository contains projects completed across six weeks:

| Week | Project / Task | Key Concepts |
|---|---|---|
| Week 1 | Titanic Exploratory Data Analysis | EDA, Pandas, NumPy |
| Week 1 | Titanic Data Cleaning & Visualization | Missing Values, Outliers, Visualization |
| Week 2 | Titanic Survival Prediction | Logistic Regression, Classification |
| Week 2 | House Price Prediction | Linear Regression, RMSE, R² |
| Week 3 | Model Evaluation & Hyperparameter Tuning | Precision, Recall, F1, GridSearchCV |
| Week 3 | Customer Churn Prediction | Decision Tree, Logistic Regression, Business Analysis |
| Week 4 | ML Pipeline & Feature Engineering | Pipeline, ColumnTransformer, Feature Engineering |
| Week 4 | Random Forest vs XGBoost | Ensemble Learning, Feature Importance |
| Week 5 | Credit Card Fraud Detection | Imbalanced Data, SMOTE |
| Week 5 | ML Model Deployment | Streamlit, Joblib, Deployment |
| Week 6 | WorkforceIQ Capstone | End-to-End ML, Multiple Models, Deployment |

---

# Week 1 – Data Exploration & Preparation

## Task 1 – Titanic Exploratory Data Analysis

### Objective

Understand the structure and quality of a real-world dataset before applying machine learning.

### Work Completed

- Loaded the Titanic dataset using Pandas
- Explored data using `head()`, `info()`, and `describe()`
- Identified dataset dimensions
- Identified numerical and categorical variables
- Examined missing values
- Analyzed basic statistical characteristics
- Created an initial data story

### Technologies

- Python
- Google Colab
- Pandas
- NumPy

---

## Task 2 – Data Cleaning & Visualization

### Objective

Clean the Titanic dataset and use visualization to identify patterns, anomalies, and relationships.

### Work Completed

- Handled missing values using median and mode
- Removed features with excessive missing information where appropriate
- Detected numerical outliers using boxplots
- Created histograms
- Created boxplots
- Created bar charts
- Generated a correlation heatmap
- Investigated factors associated with passenger survival

### Technologies

- Pandas
- Matplotlib
- Seaborn

---

# Week 2 – Machine Learning Fundamentals

## Task 3 – Titanic Survival Prediction

### Objective

Build a binary classification model to predict whether a Titanic passenger survived.

### Workflow

- Selected relevant features
- Handled missing values
- Encoded categorical variables
- Split data using `train_test_split`
- Trained Logistic Regression
- Generated predictions
- Evaluated model performance

### Evaluation

- Accuracy
- Confusion Matrix
- Classification Report

### Model

**Logistic Regression**

---

## Task 4 – House Price Prediction

### Objective

Develop a regression model for predicting residential property prices.

### Dataset

**House Prices – Advanced Regression Techniques**

### Selected Features

- OverallQual
- GrLivArea
- GarageCars
- TotalBsmtSF
- YearBuilt

### Workflow

- Selected important housing features
- Prepared training and testing datasets
- Trained a Linear Regression model
- Generated price predictions
- Compared actual and predicted values

### Evaluation Metrics

- RMSE
- R² Score
- Actual vs Predicted Scatter Plot

### Model

**Linear Regression**

---

# Week 3 – Model Evaluation & Business ML

## Task 5 – Model Evaluation & Hyperparameter Tuning

### Objective

Move beyond accuracy and evaluate classification models using more appropriate metrics.

### Work Completed

- Revisited the Titanic classification model
- Calculated Precision
- Calculated Recall
- Calculated F1-score
- Generated classification reports
- Analyzed why accuracy can be misleading
- Used GridSearchCV for hyperparameter optimization
- Tuned multiple model parameters
- Compared baseline and optimized model performance

### Key Concepts

- Precision
- Recall
- F1-score
- Hyperparameter Tuning
- GridSearchCV
- Model Comparison

---

## Task 6 – Customer Churn Prediction

### Objective

Predict customer churn and translate machine learning results into useful business insights.

### Dataset

**Telco Customer Churn**

### Workflow

- Performed quick EDA
- Investigated contract type
- Analyzed customer tenure
- Analyzed monthly charges
- Processed categorical features
- Examined target class imbalance
- Trained Logistic Regression
- Trained Decision Tree Classifier
- Compared both models
- Analyzed Decision Tree feature importance
- Identified major churn-driving factors
- Produced a non-technical business summary

### Models

- Logistic Regression
- Decision Tree Classifier

### Business Focus

The project demonstrates how machine learning can help businesses identify customers at higher risk of leaving and support proactive retention strategies.

---

# Week 4 – Professional Machine Learning Workflows

## Task 7 – ML Pipeline with Feature Engineering

### Objective

Build a reusable machine learning workflow using scikit-learn Pipeline and ColumnTransformer.

### Work Completed

- Built a complete preprocessing pipeline
- Used `ColumnTransformer`
- Applied `StandardScaler` to numerical features
- Applied `OneHotEncoder` to categorical features
- Combined preprocessing and model training
- Created engineered features
- Compared performance before and after feature engineering
- Reduced preprocessing inconsistencies and potential data leakage
- Saved the final pipeline using Joblib

### Feature Engineering

Examples included:

- `FamilySize`
- `IsAlone`

### Technologies

- Scikit-learn Pipeline
- ColumnTransformer
- StandardScaler
- OneHotEncoder
- Joblib

---

## Task 8 – Ensemble Learning: Random Forest vs XGBoost

### Objective

Compare ensemble machine learning algorithms against earlier single-model approaches.

### Models

- Logistic Regression / Previous Baseline
- Random Forest
- XGBoost

### Work Completed

- Trained Random Forest
- Trained XGBoost
- Compared ensemble models with the previous baseline
- Evaluated model performance
- Extracted feature importance
- Visualized important features
- Compared how Random Forest and XGBoost learn from data

### Key Learning

Random Forest combines multiple independently trained decision trees, while XGBoost builds trees sequentially so that later trees focus on correcting errors made by earlier models.

---

# Week 5 – Real-World ML & Deployment

## Task 9 – Handling Imbalanced & Messy Data

### Project

**Credit Card Fraud Detection**

### Objective

Understand how severe class imbalance affects machine learning models and apply appropriate techniques to address it.

### Workflow

- Loaded and inspected credit card transaction data
- Checked missing and duplicate values
- Analyzed fraud vs legitimate transactions
- Visualized target class imbalance
- Created stratified training and testing sets
- Built a baseline Logistic Regression model
- Evaluated Precision, Recall and F1-score
- Applied SMOTE to training data
- Retrained the model
- Compared performance before and after SMOTE

### Imbalance Technique

**SMOTE – Synthetic Minority Over-sampling Technique**

### Key Learning

Accuracy alone can be misleading in highly imbalanced datasets. A fraud detection model can achieve very high accuracy while still failing to identify fraudulent transactions.

Therefore, greater attention was given to:

- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Task 10 – Deploy Your Model as a Live Web App

### Project

**Titanic Survival Predictor**

### Objective

Turn a trained machine learning model into an interactive application that can be used without writing Python code.

### Workflow

- Built a complete Titanic preprocessing pipeline
- Trained Logistic Regression
- Saved the pipeline using Joblib
- Created an interactive Streamlit interface
- Added passenger input fields
- Automatically calculated engineered features
- Generated survival predictions
- Displayed prediction probabilities
- Prepared the application for cloud deployment

### Application Inputs

- Passenger Class
- Sex
- Age
- Siblings / Spouses
- Parents / Children
- Fare
- Port of Embarkation
- Family Size
- Travelling Alone status

### Technologies

- Python
- Streamlit
- Pandas
- Scikit-learn
- Joblib
- GitHub

### Live Application

Add deployed Streamlit URL here:

`LIVE_APP_URL`

---

# Week 6 – Capstone Project

# WorkforceIQ – Employee Attrition Risk Prediction System

## Problem Statement

Employee turnover creates significant challenges for organizations through recruitment costs, onboarding expenses, productivity losses, and loss of organizational knowledge.

**WorkforceIQ** is an end-to-end machine learning system designed to estimate employee attrition risk using historical HR information.

The project demonstrates the complete machine learning lifecycle from raw data analysis to model deployment.

---

## Dataset

IBM HR Analytics Employee Attrition Dataset

The dataset contains employee information related to:

- Age
- Department
- Job Role
- Monthly Income
- Overtime
- Job Satisfaction
- Environment Satisfaction
- Work-Life Balance
- Total Working Years
- Years at Company
- Career progression
- Attrition status

---

## Exploratory Data Analysis

The project investigates relationships between employee attrition and factors including:

- Overtime
- Job Role
- Monthly Income
- Age
- Years at Company
- Job Satisfaction
- Work-Life Balance

---

## Feature Engineering

Additional features were developed to represent employee satisfaction and career patterns.

### TotalSatisfaction

Combines multiple employee satisfaction indicators.

### CompanyTenureRatio

Represents the proportion of total professional experience spent at the current company.

### IncomePerYearExperience

Measures employee income relative to total professional experience.

### PromotionGap

Captures career progression information based on company tenure and time since last promotion.

---

## Data Preprocessing

A reusable preprocessing pipeline was developed using:

- `SimpleImputer`
- `StandardScaler`
- `OneHotEncoder`
- `ColumnTransformer`
- `Pipeline`

This ensures preprocessing remains consistent between model training and future predictions.

---

## Models Compared

Four machine learning algorithms were evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost

### Evaluation Metrics

Models were compared using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

The final model is selected primarily using F1-score while also considering other metrics because employee attrition represents an imbalanced classification problem.

---

## Model Comparison

Update the following table with the final Colab results:

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | TBD | TBD | TBD | TBD | TBD |
| Decision Tree | TBD | TBD | TBD | TBD | TBD |
| Random Forest | TBD | TBD | TBD | TBD | TBD |
| XGBoost | TBD | TBD | TBD | TBD | TBD |

---

## WorkforceIQ Deployment

The selected model pipeline is saved using:

`joblib`

The final system is designed to be deployed through a Streamlit application where employee information can be entered through an interactive interface.

The application returns an estimated attrition risk based on the trained machine learning model.

### Live Application

`WORKFORCEIQ_LIVE_APP_URL`

---

# Capstone Business Value

Employee attrition can create substantial financial and operational costs for organizations. WorkforceIQ demonstrates how historical HR data can be transformed into actionable predictive insights.

The system analyzes employee characteristics including satisfaction, overtime, income, tenure, work-life balance, and career progression to identify patterns associated with attrition.

Such a system could support HR teams in identifying areas that may require attention and developing proactive retention strategies.

The predictions are intended to act as **decision-support information rather than replacing human HR judgment**.

---

# Technologies & Tools

### Programming

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-learn
- XGBoost
- Logistic Regression
- Linear Regression
- Decision Trees
- Random Forest

### ML Engineering

- Pipeline
- ColumnTransformer
- StandardScaler
- OneHotEncoder
- SimpleImputer
- GridSearchCV
- SMOTE
- Joblib

### Deployment

- Streamlit
- Streamlit Community Cloud

### Development

- Google Colab
- Git
- GitHub

---

# Machine Learning Skills Developed

Through this track, I gained practical experience in:

- Exploratory Data Analysis
- Data Cleaning
- Missing Value Handling
- Outlier Detection
- Data Visualization
- Feature Engineering
- Categorical Encoding
- Feature Scaling
- Classification
- Regression
- Model Evaluation
- Confusion Matrix Analysis
- Precision, Recall and F1-score
- RMSE and R²
- ROC-AUC
- Hyperparameter Tuning
- GridSearchCV
- Class Imbalance Handling
- SMOTE
- Ensemble Learning
- Random Forest
- XGBoost
- Feature Importance
- Scikit-learn Pipelines
- Model Serialization
- Streamlit Application Development
- ML Model Deployment
- Git/GitHub Version Control
- Translating ML results into business insights

---

# Repository Structure

```text
neurofive-ml-track/
│
├── Week_1/
│   ├── Week_1_Task_1_Titanic_EDA.ipynb
│   └── Week_1_Task_2_Titanic_Data_Cleaning.ipynb
│
├── Week_2/
│   ├── Week_2_Task_3_Titanic_Classification.ipynb
│   └── Week_2_Task_4_House_Price_Regression.ipynb
│
├── Week_3/
│   ├── Model_Evaluation_and_Tuning.ipynb
│   └── Customer_Churn_Prediction.ipynb
│
├── Week_4/
│   ├── ML_Pipeline_Feature_Engineering.ipynb
│   └── Random_Forest_vs_XGBoost.ipynb
│
├── Week_5/
│   ├── Week_5_Task_1_Handling_Imbalanced_Data.ipynb
│   │
│   └── Task_2_Streamlit_Deployment/
│       ├── app.py
│       ├── requirements.txt
│       └── titanic_final_pipeline.joblib
│
└── Week_6/
    └── WorkforceIQ/
        ├── notebooks/
        │   └── Week_6_Capstone_WorkforceIQ.ipynb
        ├── model/
        │   └── workforceiq_attrition_model.joblib
        ├── app.py
        ├── requirements.txt
        └── README.md
