### Industrial Copper Modeling ###
## Overview ##
This project aims to build predictive models to assist the copper industry in making informed decisions regarding sales, pricing, and lead management.
The project involves data preprocessing, exploratory data analysis (EDA), machine learning (ML) modeling, and the development of a web application using Streamlit.

## Skills and Technologies
1. Python Scripting
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Machine Learning
5. Streamlit

## Domain
1. Manufacturing
## Problem Statement
The copper industry deals with data related to sales and pricing, which can be complex and noisy. Manual predictions are often inaccurate and time-consuming.
This project aims to create a machine learning regression model to predict selling prices and a classification model to manage leads (status: WON or LOST).

### Approach ###
## Data Understanding and Preprocessing: ##

1. Identify variable types and distributions.
2. Handle missing values using mean, median, or mode.
3. Treat outliers using IQR or Isolation Forest.
4. Address skewness with appropriate transformations (e.g., log transformation).
5. Encode categorical variables.
   
## Exploratory Data Analysis (EDA): ##

Visualizing outliers and skewness using boxplots, distplots, and violin plots.
## Feature Engineering: ##

Engineer new features and drop highly correlated columns.
## Model Building and Evaluation: ##

Split the dataset into training and testing sets.
Train and evaluate classification models (e.g., ExtraTreesClassifier, XGBClassifier, Logistic Regression).
Train and evaluate regression models.
Optimize models using cross-validation and grid search.
Train regression and classification models.
Evaluate models using appropriate metrics (accuracy, precision, recall, F1 score, AUC for classification; RMSE for regression).

## Model Deployment: ##
Develop a Streamlit web application for user interaction.
Create input fields for model prediction.
Implement feature engineering and scaling steps in the web application.

## Model Saving: ##
Use the pickle module to save and load models, encoders, and scalers.

### Learning Outcomes ###
## Python Programming and Data Analysis Libraries: ##

Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit.
## Data Preprocessing: ##
Handling missing values, outlier detection, data normalization.

## EDA: ##

Visualizing data using various plots.

## Machine Learning: ##

Regression and classification modeling.
Model evaluation and optimization.

## Feature Engineering: ##

Creating informative data representations.
## Web Application Development: ##

Using Streamlit for interactive applications.
## Manufacturing Domain Knowledge: ##

Applying ML to solve industry-specific problems.
