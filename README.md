# Human-cardiac-infarction-prognosis
Cardiac disease prediction
Here's a concise summary and structure for a GitHub README file based on the content of the provided document:

---

# Heart Disease Prediction

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
![image](https://github.com/user-attachments/assets/30eb6b1f-6a4a-435d-8beb-b107053eb721)
![sample_scatter_plot5](https://github.com/user-attachments/assets/6c89da27-0d3e-43cb-990b-06a73aee09ce)
![sample_scatter_plot3](https://github.com/user-attachments/assets/083aa270-0e71-47ba-b8e5-401b74280d75)
![sample_scatter_plot1](https://github.com/user-attachments/assets/27b31d43-2630-41bd-a587-1818d851d1e4)
![sample_scatter_plot](https://github.com/user-attachments/assets/281946ea-23e3-44c0-abac-63abf6e1a6eb)
![image](https://github.com/user-attachments/assets/9d1a26b0-f8a9-425f-a752-6994c07358b3)

Credits: DURGANCE GAUR for helping me through it 


