# Neurofive ML Track – Week 2

## Machine Learning Fundamentals

**Author:** Shahzaib Arshad

---

## Project Overview

This repository contains my completed Week 2 tasks for the Neurofive Machine Learning Track. The projects cover the complete beginner machine learning workflow, including Exploratory Data Analysis (EDA), data cleaning, data visualization, binary classification, and regression using Python and scikit-learn.

The objective of these tasks was to understand how data is explored, prepared, visualized, and used to build machine learning models for both classification and regression problems.

---

# Task 1 – Explore the Titanic Dataset

## Objective

Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand its structure, data quality, and important characteristics before applying machine learning.

### Activities Performed

- Loaded the Titanic dataset using Pandas.
- Explored the dataset using:
  - `head()`
  - `info()`
  - `describe()`
- Identified:
  - Number of rows and columns
  - Missing values
  - Numerical features
  - Categorical features
- Created an initial data summary.

### Technologies Used

- Python
- Google Colab
- Pandas
- NumPy

---

# Task 2 – Data Cleaning and Visualization

## Objective

Prepare the Titanic dataset for machine learning by cleaning missing values and visualizing important data patterns.

### Activities Performed

- Filled missing values using:
  - Median
  - Mode
- Removed the Cabin column due to excessive missing values.
- Detected outliers using a boxplot.
- Created visualizations:
  - Histogram
  - Boxplot
  - Bar Chart
  - Correlation Heatmap
- Identified the features that most influence passenger survival.

### Libraries Used

- Matplotlib
- Seaborn

---

# Task 3 – Titanic Survival Prediction

## Objective

Develop a binary classification model to predict whether a passenger survived the Titanic disaster.

### Machine Learning Workflow

- Selected relevant features
- Encoded categorical variables using OneHotEncoder
- Split the dataset using `train_test_split`
- Trained a Logistic Regression model
- Generated predictions
- Evaluated performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

### Model

- Logistic Regression

### Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report

---

# Task 4 – House Price Prediction

## Objective

Build a Linear Regression model to predict house prices using selected numerical features.

### Dataset

House Prices – Advanced Regression Techniques (Kaggle)

### Selected Features

- OverallQual
- GrLivArea
- GarageCars
- TotalBsmtSF
- YearBuilt

### Machine Learning Workflow

- Selected important features
- Split the dataset into training and testing sets
- Trained a Linear Regression model
- Predicted house prices
- Evaluated the model using:
  - RMSE (Root Mean Squared Error)
  - R² Score
- Compared Actual vs Predicted prices using a scatter plot

### Model

- Linear Regression

### Evaluation Metrics

- RMSE
- R² Score

---

# Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Skills Learned

During these tasks, I learned how to:

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess datasets
- Handle missing values
- Visualize data effectively
- Detect outliers
- Build classification models
- Build regression models
- Evaluate machine learning models
- Interpret confusion matrices
- Understand RMSE and R² score
- Use Google Colab for machine learning projects

---

# Repository Structure

```text
Week_2_Task_1_EDA.ipynb
Week_2_Task_2_Data_Cleaning_and_Visualization.ipynb
Week_2_Task_3_Titanic_Classification.ipynb
Week_2_Task_4_House_Price_Regression.ipynb
README.md
```

---

# Results

## Titanic Classification

- Algorithm: Logistic Regression
- Evaluation:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## House Price Prediction

- Algorithm: Linear Regression
- Evaluation:
  - RMSE
  - R² Score
  - Actual vs Predicted Scatter Plot

---

# Conclusion

These projects provided practical experience with the complete machine learning workflow, from understanding and preparing data to building predictive models and evaluating their performance. They strengthened my understanding of both classification and regression techniques using real-world datasets and Python's machine learning ecosystem.

---

## Author

**Shahzaib Arshad**

Neurofive Machine Learning Track – Week 2
