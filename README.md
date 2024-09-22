# NY_House_Prediction_Machine_Learning

New York Housing Price Prediction
This project aims to develop a machine learning system that predicts the housing prices in New York City. Using data from over 200,000 property sale records, the project employs various machine learning models to understand the key determinants of housing prices. The project demonstrates how ML algorithms can be applied in the real estate domain, providing valuable insights for homebuyers, real estate investors, and urban planners.

Table of Contents
Introduction
Project Overview
Dataset
Installation
Project Structure
Models and Evaluation
SHAP Analysis
Results
Contributors
Introduction
The goal of this project is to predict real estate prices in New York City by analyzing property features such as size, location, and amenities. By employing machine learning models, the project assesses which features contribute the most to price prediction.

Project Overview
The project follows these steps to develop the prediction system:

Data Preparation: Importing the dataset and examining the key features.
Data Preprocessing and Visualization: Cleaning the dataset, handling null values, and visualizing data trends.
Train-Test Split: Splitting the dataset into training and testing sets (80:20 ratio).
Model Building: Using regression algorithms such as Linear Regression, Decision Trees, Random Forest, Gradient Boosting, and more.
Model Evaluation: Evaluating models using metrics like R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
Hyperparameter Tuning: Using GridSearchCV to fine-tune models for optimal performance.
SHAP Analysis: Analyzing the contribution of each feature to the model’s prediction using SHAP.
Dataset
The dataset used in this project was sourced from Kaggle. It contains information on housing prices, number of bedrooms, property square footage, and more.

https://www.kaggle.com/datasets/nelgiriyewithana/new-york-housing-market


Models and Evaluation

Models Implemented

Linear Regression

Decision Tree

Random Forest

Gradient Boosting

Histogram-Based Gradient Boosting

Evaluation Metrics

R-squared

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

We used K-fold cross-validation with K=5 to ensure robust evaluation.

SHAP Analysis
We used SHAP (SHapley Additive exPlanations) to interpret model predictions. The SHAP values helped identify the most important features affecting housing prices, such as the number of bedrooms and square footage.

Results
The best performing model was Linear Regression, with the following metrics:

R-squared: 0.9999
Mean Absolute Error (MAE): 374.94
Mean Squared Error (MSE): 21,922,349.87
