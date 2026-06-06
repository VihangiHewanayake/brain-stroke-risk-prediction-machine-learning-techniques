# Brain Stroke Risk Prediction Using Machine Learning Techniques

## Project Overview

This project develops machine learning models to predict brain stroke risk using demographic, medical, and lifestyle-related factors. The analysis includes data preprocessing, exploratory data analysis (EDA), feature engineering, class balancing using SMOTE, and predictive modeling.

## Objectives

* Predict stroke occurrence using machine learning techniques.
* Identify the most influential stroke risk factors.

## Dataset

Source: Brain Stroke Dataset (Kaggle)

Features:

* Age
* Gender
* Hypertension
* Heart Disease
* Average Glucose Level
* BMI
* Smoking Status
* Work Type
* Residence Type
* Marital Status

Target Variable:

* Stroke (0 = No, 1 = Yes)

## Machine Learning Models

* Logistic Regression
* Random Forest
* K-Nearest Neighbors (KNN)

## Data Preprocessing

* Duplicate removal
* Outlier detection and treatment
* One-hot encoding
* Standardization
* SMOTE balancing

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix

## Key Findings

* Age was the strongest predictor of stroke occurrence.
* Average glucose level, hypertension, and BMI were also important risk factors.
* Random Forest achieved the highest accuracy (89.67%).
* Logistic Regression achieved the best ROC-AUC score (0.84).

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Author

Vihangi Hewanayake
University of Colombo
