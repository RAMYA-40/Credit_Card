# Credit Card Default Prediction 💳📊

## Project Overview

This project focuses on predicting whether a credit card customer is likely to default on their payment in the next month. The dataset contains information about customers' demographic details, credit limits, bill amounts, previous payments, and repayment status.

The project uses **Python and Machine Learning** techniques for data preprocessing, exploratory data analysis, feature selection, data balancing, and classification.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn

## Dataset

The project uses the **Credit Card Default Dataset (`creditcard.csv`)**.

The dataset includes:

* Customer demographic information
* Credit limit
* Repayment status
* Bill amounts
* Previous payment amounts
* Default payment status

## Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas and converted into a DataFrame for analysis.

### 2. Data Exploration

The dataset is explored using:

* `head()` and `tail()`
* Dataset shape and column information
* Descriptive statistics
* Missing value checking
* Duplicate value checking

### 3. Exploratory Data Analysis

Correlation analysis and heatmaps are used to understand relationships between numerical features.

### 4. Data Preprocessing

The dataset is cleaned and prepared by:

* Renaming columns for better understanding
* Converting categorical values into meaningful labels
* Handling outliers using the IQR method
* Encoding categorical features using Label Encoding and One-Hot Encoding

### 5. Handling Class Imbalance

**SMOTE (Synthetic Minority Oversampling Technique)** is applied to balance the target classes and improve model performance.

### 6. Feature Selection

`SelectKBest` with the `f_classif` scoring method is used to identify the most relevant features for prediction.

### 7. Feature Scaling

The selected features are standardized using **StandardScaler** before training the machine learning model.

### 8. Model Training

A **Logistic Regression** classification model is trained using the processed dataset.

### 9. Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report

## Machine Learning Model

### Logistic Regression

Logistic Regression is used to classify customers into two categories:

* **YES** – Customer is predicted to default
* **NO** – Customer is predicted not to default

## Objective

The main objective of this project is to develop a machine learning model that can identify customers who may default on their credit card payments, helping financial institutions take preventive actions.

## Conclusion

This project demonstrates the complete machine learning workflow, starting from data exploration and preprocessing to feature selection, class balancing, model training, and evaluation. Logistic Regression is used as the classification model to predict credit card payment default.

## Future Improvements

* Compare multiple machine learning algorithms.
* Perform hyperparameter tuning.
* Improve feature engineering.
* Evaluate the model using additional performance metrics.
* Develop a simple web interface for credit default prediction.
S
