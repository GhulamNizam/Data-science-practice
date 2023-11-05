# Stroke Prediction Classifier

![Stroke Prediction]( https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-zcXfs2_eYgGTCbxEGqCoVJ_qUvLCc5_Y6qNy4C_dnBpoVkPub7ngxrkKiWYo9Db_zGc&usqp=CAU) 

## Overview

This repository contains the code and documentation for a machine learning model developed to predict the likelihood of stroke occurrence in patients. The project includes data analysis, exploratory data analysis (EDA), data preprocessing, visualization, and the implementation of various machine learning models. The best-performing models were selected based on accuracy and log loss evaluations. GridSearchCV was used to optimize a Decision Tree and Random Forest model. 

## Table of Contents

- [Data](#data)
- [Data Analysis](#data-analysis)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Visualization](#visualization)
- [Model Building](#model-building)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Model Evaluation](#model-evaluation)
- [Prediction](#prediction)

## Data

The dataset used for this project can be found in `/kaggle/input/stroke-prediction-dataset/healthcare-dataset-stroke-data.csv`. It includes various features such as age, hypertension, heart disease, BMI, and smoking status, which are used to predict the likelihood of stroke.

## Data Analysis

- Data analysis involved understanding the structure of the dataset, checking for missing values, and identifying potential data quality issues.

## Exploratory Data Analysis (EDA)

- Exploratory Data Analysis was conducted to gain insights into the dataset, including univariate, bivariate, and multivariate analyses.
- Statistical summaries and visualizations were used to understand the distribution of features and their relationships with the target variable (stroke).

## Data Preprocessing

- Data preprocessing involved handling missing values, encoding categorical variables, and scaling/normalizing numerical features.

## Feature Engineering

- Feature engineering was performed to create new features or transform existing ones to improve model performance.

## Visualization

- Visualization techniques such as heatmaps and correlation matrices were used to visualize the relationships between features and the target variable.

## Model Building

- Various machine learning models were implemented, including Decision Tree, Random Forest, and other classifiers.

## Hyperparameter Tuning

- GridSearchCV was used to optimize the hyperparameters of the Decision Tree and Random Forest models to improve model performance.

## Model Evaluation

- Model performance was evaluated using metrics such as accuracy and log loss. The best-performing models were selected for prediction.

## Prediction

- The final models were used to make predictions on new data.
