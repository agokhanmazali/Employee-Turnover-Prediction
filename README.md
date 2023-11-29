# Employee Attrition Analysis

## Introduction
This repository contains code for analyzing employee attrition using various machine learning models and techniques. It focuses on exploratory data analysis (EDA), visualization, data cleaning, model training, and evaluation for predicting employee attrition.

## Usage Requirements
- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, imbalanced-learn, xgboost, lightgbm, tensorflow, imblearn
- Google Colab (for running in a Colab environment)

## Importing and Dataset Overview
- Imports necessary libraries and mounts Google Drive.
- Loads the dataset from the specified path and displays a summary of the dataset.

## Visualizing Dataset
- Replaces categorical columns ('Attrition', 'OverTime', 'Over18') with integers for visualization purposes.
- Displays a heatmap to check for missing data.
- Presents histograms of various features, identifying tail-heavy features, and drops irrelevant columns.

## Data Analysis
- Compares and describes employees who left and those who stayed.
- Computes correlations and visualizes them using heatmaps.
- Visualizes age, job role, marital status, and job involvement against attrition.

## Data Cleaning and Preprocessing
- Cleans the data, drops irrelevant columns, and prepares the dataset for model training.

## Model Training and Evaluation
### Individual Models
- Trains and evaluates Logistic Regression, Random Forest, Deep Learning (Neural Network), and LightGBM models.
- Evaluates models' accuracy, confusion matrices, and classification reports.

### Ensemble Models
- Builds ensemble models using majority voting and stacking.
- Evaluates ensemble models' accuracy, confusion matrices, and classification reports.

### Feature Selection and Model Evaluation
- Implements feature selection using SelectKBest.
- Trains models on selected features and evaluates their performance.

## Use Cases

### Human Resource Management
This codebase serves as a powerful tool for HR departments and management teams to proactively address employee attrition. By identifying patterns and factors contributing to attrition, organizations can take preventive measures, such as targeted retention strategies, improving workplace conditions, or addressing specific concerns that might lead to attrition.

### Decision Support System
For business leaders and decision-makers, this analysis provides valuable insights into the drivers of employee attrition. It assists in informed decision-making for resource allocation, workforce planning, and policy adjustments aimed at reducing attrition rates and improving overall employee satisfaction and retention.

### Employee Engagement and Well-being
Understanding the factors associated with attrition helps companies focus on improving employee engagement and well-being. It enables the implementation of initiatives, programs, or policies that enhance job satisfaction, work-life balance, career development, and overall employee experience, fostering a positive work environment.

### Predictive Analytics for Recruitment
By utilizing machine learning models trained on historical attrition data, organizations can predict potential attrition for new hires. This predictive capability aids in identifying high-risk candidates during the recruitment process, allowing HR teams to take proactive measures to mitigate attrition risks and optimize talent acquisition strategies.
