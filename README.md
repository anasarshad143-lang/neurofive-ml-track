
# Neurofive ML Track

This repository contains my Machine Learning internship tasks completed as part of the **Neurofive ML Track**.

## Week 1 – Exploratory Data Analysis (EDA)

### Objective

The objective of this task is to explore the Titanic dataset using Python and pandas before applying any machine learning algorithms.

### Tasks Completed

- Loaded the Titanic dataset using pandas
- Explored the dataset structure with `head()`
- Inspected data types using `info()`
- Generated summary statistics using `describe()`
- Identified missing values
- Distinguished numerical and categorical columns
- Wrote a summary of the findings

## Tools Used

- Python
- Google Colab
- Pandas
- NumPy
- GitHub

## Repository Structure

```
neurofive-ml-track/
│
├── README.md
└── Week1_Titanic_EDA.ipynb
```

## Author

**Anas Bisal**

Machine Learning Intern at Neurofive Solutions


## Week 3 – Titanic Survival Prediction

### Objective

Build a machine learning classification model to predict passenger survival using Logistic Regression.

### Steps Performed

- Selected relevant features
- Encoded categorical variables using `pd.get_dummies()`
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Evaluated the model using accuracy score
- Generated and explained the confusion matrix

### Result

Model Accuracy: **(81.)**


# Week 2 Task 2 House Price Prediction using Linear Regression

## Objective

Predict house prices using Linear Regression.

## Dataset

California Housing Dataset from scikit-learn.

## Features Used

- Median Income
- House Age
- Average Rooms
- Latitude
- Longitude

## Model

Linear Regression

## Evaluation Metrics

- RMSE
- R² Score

## Visualization

Scatter plot comparing actual vs predicted prices.

## Week 3_Task 1 Model Evaluation

Original Model Accuracy: 81%

Metrics Used:
- Accuracy
- Precision
- Recall
- F1 Score

## Hyperparameter Tuning

Method: GridSearchCV

Parameters Tuned:
- C
- solver

The tuned Logistic Regression model was compared with the original model using Accuracy, Precision, Recall, and F1-score.

#Week3_Task2
# Customer Churn Prediction using Machine Learning

## Overview

This project predicts whether a telecom customer is likely to leave (churn) using machine learning techniques. The goal is to help businesses identify customers at risk of leaving so they can take proactive retention measures.

## Dataset

**Dataset:** Telco Customer Churn (Kaggle)

The dataset contains customer information such as:

* Demographics
* Account details
* Services subscribed
* Billing information
* Customer churn status

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Handling Missing Values
5. Encoding Categorical Variables
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis
10. Business Insights

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Checked dataset shape and information
* Identified missing values
* Examined customer churn distribution
* Analyzed the relationship between:

  * Contract Type and Churn
  * Tenure and Churn
  * Monthly Charges and Churn
* Generated a correlation heatmap for numerical features

## Data Preprocessing

* Removed unnecessary columns such as `customerID`
* Converted `TotalCharges` to numeric values
* Filled missing values
* Applied one-hot encoding to categorical variables

## Machine Learning Models

Two classification models were trained and compared:

* Logistic Regression
* Decision Tree Classifier

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

A comparison of both models was performed to determine which produced better predictions.

## Class Imbalance

The target variable (Churn) is moderately imbalanced, with more customers staying than leaving. This may cause the model to favor the majority class. Future improvements could include techniques such as SMOTE, undersampling, or class weighting.

## Feature Importance

The Decision Tree model was used to identify the most influential features affecting customer churn using `feature_importances_`.

Top factors influencing churn include:

* Contract Type
* Tenure
* Monthly Charges

## Business Summary

The machine learning models help identify customers who are most likely to leave the company. Contract type, customer tenure, and monthly charges were found to be the strongest indicators of churn. These insights can help businesses target high-risk customers with retention offers, improving customer satisfaction and reducing revenue loss.



## Conclusion

This project demonstrates an end-to-end machine learning workflow for solving a real-world business problem. It covers data preprocessing, exploratory analysis, model building, evaluation, and interpretation of results. Comparing Logistic Regression and Decision Tree models provides valuable insight into selecting suitable algorithms for customer churn prediction.
