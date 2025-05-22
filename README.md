# Osteoporosis-Risk-Predictor
This project analyzes and preprocesses a dataset to prepare for predicting osteoporosis risk based on various health and lifestyle factors. It involves data cleaning, encoding, normalization, and exploratory visualization.

The dataset used is osteoporosis.csv, which contains health and lifestyle data for 1958 individuals, including:
  - Age
  - Hormonal Changes
  - Family History
  - Body Weight
  - Calcium Intake
  - Vitamin D Intake
  - Physical Activity
  - Alcohol Consumption
  - Medical Conditions
  - Medications
  - Prior Fractures
  - Osteoporosis (Target Variable)


The data preprocessing steps include:

1. Restoring Original Missing Values:
  - Replacing placeholder "None" back to NaN to reflect original missing values.

2. Cleaning:
  - Replacing missing categorical values with "None".
  - Dropping the non-informative Id column.

3. Renaming Columns:
  - Standardized column names for consistency by replacing spaces with underscores.

5. Label Encoding:
  - Encoded categorical features using LabelEncoder for use in machine learning models.

5. Normalization:
  - Normalized the Age column using MinMaxScaler due to its skewed distribution.


Histograms and KDE plots were generated to analyze the distribution of the Age variable and count plots were created for each categorical feature to inspect class distributions. The target variable Osteoporosis was converted to categorical for better visualization.

Predictive models (e.g., Logistic Regression, Decision Trees, Random Forests) were implemented using Scikitlearn, with Decision Tree having the highest accuracy of 91%.


