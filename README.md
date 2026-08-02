---

# Week 3 – Machine Learning Fundamentals

# Task 1 – Model Evaluation & Hyperparameter Tuning

## Objective

Evaluate and improve the Titanic Survival Prediction model by using advanced evaluation metrics and hyperparameter tuning.

### Activities Performed

- Revisited the Logistic Regression model developed in Week 2.
- Evaluated the model using:
  - Precision
  - Recall
  - F1-score
  - Classification Report
- Explained why accuracy alone can be misleading for imbalanced datasets.
- Performed hyperparameter tuning using **GridSearchCV**.
- Tuned the following hyperparameters:
  - C
  - Solver
- Compared the original model with the tuned model using a performance comparison table.
- Improved model performance through parameter optimization.

### Model

- Logistic Regression (Original)
- Logistic Regression (Tuned using GridSearchCV)

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report

---

# Task 2 – Customer Churn Prediction

## Objective

Develop machine learning models to predict customer churn and identify the most important business factors influencing customer retention.

### Dataset

Telco Customer Churn Dataset (Kaggle)

### Activities Performed

- Performed quick Exploratory Data Analysis (EDA).
- Analyzed:
  - Contract Type
  - Customer Tenure
  - Monthly Charges
  - Internet Service
  - Payment Method
- Cleaned and prepared the dataset.
- Converted categorical variables using One-Hot Encoding.
- Checked and handled class imbalance using balanced class weights.
- Trained two machine learning models:
  - Logistic Regression
  - Decision Tree Classifier
- Compared model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Identified the top three customer churn factors using Decision Tree Feature Importance.
- Prepared a business-oriented summary based on the findings.

### Models

- Logistic Regression
- Decision Tree Classifier

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report
- Feature Importance

---

# Updated Repository Structure

```text
Week_1_Task_1_Titanic_EDA.ipynb
Week_1_Task_2_Data_Cleaning_and_Visualization.ipynb
Week_2_Task_3_Titanic_Classification.ipynb
Week_2_Task_4_House_Price_Regression.ipynb
Week_3_Task_1_Model_Evaluation_and_Tuning.ipynb
Week_3_Task_2_Customer_Churn_Prediction.ipynb
README.md
```

---

# Additional Skills Learned

During Week 3, I also learned how to:

- Evaluate classification models using multiple metrics.
- Interpret Precision, Recall, and F1-score.
- Understand why accuracy alone may be misleading.
- Perform Hyperparameter Tuning using GridSearchCV.
- Compare machine learning models effectively.
- Build Decision Tree classification models.
- Analyze Feature Importance.
- Detect and handle class imbalance.
- Translate machine learning results into business insights.
- Present machine learning findings to non-technical stakeholders.

---

# Overall Learning Outcomes

Across Weeks 1, 2, and 3, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Data Visualization
- Feature Engineering
- Classification
- Regression
- Model Evaluation
- Hyperparameter Tuning
- Decision Trees
- Feature Importance Analysis
- Business Problem Solving
- Customer Churn Prediction
- Google Colab
- Scikit-learn
- GitHub Version Control

---

# Future Improvements

Future enhancements for these projects may include:

- Hyperparameter tuning using RandomizedSearchCV.
- Cross-validation for better model evaluation.
- Ensemble learning methods such as Random Forest and XGBoost.
- Customer churn prediction using Gradient Boosting algorithms.
- Feature selection and dimensionality reduction techniques.
- Model deployment using Flask or Streamlit.
