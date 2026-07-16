# Neurofive ML Track

This repository contains my Machine Learning assignments, notebooks, and practical projects completed as part of the Neurofive ML Track.

## Task 1: Titanic Exploratory Data Analysis

In Task 1, I performed initial Exploratory Data Analysis on the Titanic dataset using Python, Pandas, and NumPy.

### Work completed
- Loaded the Titanic dataset using `pandas.read_csv()`
- Inspected the first rows using `head()`
- Reviewed dataset structure using `info()`
- Generated numerical statistics using `describe()`
- Identified total rows and columns
- Checked missing values
- Identified numerical and categorical features
- Wrote a short data story based on the findings

## Task 2: Data Cleaning and Visualization

In Task 2, I cleaned the Titanic dataset and created visualizations to better understand patterns, outliers, and relationships between features.

### Work completed
- Filled missing `Age` values using the median
- Filled missing `Embarked` values using the mode
- Removed the `Cabin` column because it contained too many missing values
- Created an age-distribution histogram
- Detected fare outliers using a boxplot
- Created a passenger survival bar chart
- Created a correlation heatmap
- Analyzed which feature appears to affect survival the most

## Key Finding

Passenger sex appears to have the strongest effect on survival. Female passengers had a much higher survival rate than male passengers. Passenger class also influenced survival, as first-class passengers generally had better survival chances.

## Tools and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset

Titanic - Machine Learning from Disaster

## Notebook

- `Titanic_EDA.ipynb`

## Author

**Shahzaib Arshad**
