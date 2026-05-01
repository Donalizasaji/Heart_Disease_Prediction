# Heart Disease Prediction using Machine Learning

## Overview

This project predicts the presence of heart disease using patient clinical data and machine learning classification models. The project includes data preprocessing, exploratory data analysis, statistical testing, model building, model comparison, and feature importance analysis.

## Dataset

The dataset contains medical attributes related to heart disease diagnosis.

### Features

- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- FBS over 120
- EKG Results
- Max Heart Rate
- Exercise Angina
- ST Depression
- Slope of ST
- Number of Vessels Fluro
- Thallium
- Heart Disease

The target variable is **Heart Disease**, where:

- Presence = 1
- Absence = 0

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- Sweetviz
- YData Profiling
- SciPy

## Project Workflow

1. Loaded the heart disease dataset
2. Checked dataset shape, data types, unique values, duplicates, and missing values
3. Converted the target column into numerical format
4. Detected outliers using boxplots
5. Removed outliers from the Cholesterol column using the IQR method
6. Performed Exploratory Data Analysis
7. Generated automated profiling reports using YData Profiling and Sweetviz
8. Performed Chi-Square statistical tests
9. Split the data into training and testing sets
10. Scaled the features using StandardScaler
11. Built and evaluated multiple classification models
12. Compared model performance using confusion matrices and accuracy scores
13. Analyzed important features affecting heart disease prediction

## Models Used

- Logistic Regression
- Decision Tree Classifier using Entropy
- Decision Tree Classifier using Gini
- XGBoost Classifier
- Neural Network
- Voting Classifier

## Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

## Statistical Testing

Chi-Square tests were performed to check the association between selected categorical features and heart disease.

Features tested include:

- Thallium
- Chest Pain Type

## Key Insights

- The project compares multiple machine learning models for heart disease prediction.
- Feature scaling was applied before model training.
- Outlier treatment was performed on the Cholesterol column.
- Feature importance analysis was used to identify influential health attributes.
- Automated EDA reports were generated using Sweetviz and YData Profiling.


