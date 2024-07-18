# Human-cardiac-infarction-prognosis
Cardiac disease prediction
Here's a concise summary and structure for a GitHub README file based on the content of the provided document:

This repository contains a machine learning project aimed at predicting heart disease using various classification algorithms. The project involves data preprocessing, exploratory data analysis (EDA), feature scaling, and the implementation of multiple machine learning models.

## Table of Contents

- [Overview](#overview)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Scaling](#feature-scaling)
- [Model Building and Evaluation](#model-building-and-evaluation)
- [Feature Importance](#feature-importance)
- [Requirements](#requirements)
- [Usage](#usage)

## Overview

This project uses a dataset to predict the presence of heart disease in patients. Several machine learning models are applied and evaluated to determine the most effective approach.

## Data Preprocessing

- Imported necessary libraries: `numpy`, `pandas`, `seaborn`, `matplotlib`, `plotly`, `sklearn`
- Loaded the dataset and inspected its structure
- Converted categorical variables to string type
- Checked for and confirmed the absence of null values

## Exploratory Data Analysis (EDA)

- Generated summary statistics
- Created visualizations such as histograms, box plots, and heatmaps to understand feature distributions and correlations

## Feature Scaling

- Applied different scaling techniques to the data:
  - RobustScaler
  - StandardScaler
  - MinMaxScaler

## Model Building and Evaluation

Implemented and evaluated the following machine learning models using cross-validation (StratifiedKFold):

- Logistic Regression
- Naive Bayes (GaussianNB)
- Support Vector Machines (SVC) with linear, sigmoid, RBF, and polynomial kernels
- K-Nearest Neighbors (KNeighborsClassifier)
- Decision Tree (DecisionTreeClassifier)
- Random Forest (RandomForestClassifier)

- XGBoost (XGBClassifier)

Proofs and Results
![sample_scatter_plot1](https://github.com/user-attachments/assets/fe28436c-094a-4f32-acc6-64853568d47c)
![sample_scatter_plot](https://github.com/user-attachments/assets/ffbda725-148f-43aa-8f0c-d5453d6686f1)
![newplot](https://github.com/user-attachments/assets/a9c7a2e7-34c5-453b-846d-d9804f94eee3)
![image](https://github.com/user-attachments/assets/2ddf9d56-5bdc-4812-8301-88577ec4aaa5)


Credits: DURGANCE GAUR for helping me through it 


