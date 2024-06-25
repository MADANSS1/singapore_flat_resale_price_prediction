
# Singapore Resale Flat Prices Prediction 

# Introduction

This project aims to predict the resale prices of Singapore flats using HDB data and machine learning techniques. The data undergoes extensive preprocessing, including outlier handling and categorical feature encoding. Various regression models were tested to select the best performer. The user-friendly Streamlit application allows users to input features and receive real-time predictions, enhancing the understanding of the housing market. Deployed on Render, the app ensures easy access and smooth performance, empowering users to make informed decisions about flat resale prices in Singapore.

## App

https://singapore-flat-resale-price-prediction-1-4jv7.onrender.com/

## Objective

The objective of this project is to develop a robust and accurate machine learning model to predict the resale prices of Singapore Housing Development Board (HDB) flats. By leveraging historical resale data and advanced data processing techniques, we aim to create a user-friendly web application that provides real-time predictions. This application is intended to help potential buyers, sellers, and real estate professionals make informed decisions based on reliable price predictions, ultimately contributing to a better understanding of the Singapore real estate market.

## Source of data

https://beta.data.gov.sg/collections/189/view
## Technology used
1. Python

2. Numpy

3. Pandas

4. Scikit-Learn

5. Pickle

6. Streamlit

7. Render
# Overview
## Data Collection and Preprocessing
1. Data Source: Historical resale flat data downloaded from official HDB sources, covering the period from 1990 to the present.

2. Initial Cleaning: Managed missing values, corrected inconsistencies, and ensured data integrity.

3. Feature Engineering: Enhanced the dataset by creating new features and transforming existing ones to capture underlying patterns better.

## Data Exploration and Handling

1. Outlier Detection: Identified and managed outliers to ensure model robustness.

2. Skewness Correction: Corrected skewed distributions using appropriate transformations.

3. Categorical Encoding: Encoded categorical features using techniques like Label Encoding to convert them into numerical formats suitable for machine learning algorithms.

## Model Selection and Training
1. Cross-validated different regression models (e.g., Linear Regression, Random Forest Regressor).

2. Evaluated performance metrics to choose the best model for predicting resale prices.

3. Selected the DecisionTree Regressor based on superior performance in terms of R-squared and Mean Squared Error metrics.

## Model Deployment

1. Model Serialization: Saved the trained DecisionTree Regressor model using pickle for later use in the application.

2. Dashboard Development: Built an interactive dashboard using Streamlit, allowing users to input relevant features and get predictions on flat resale prices.

3. Deployment: Deployed the application on Render for easy access and smooth performance.




## Packages
!pip install pandas

!pip install numpy

!pip install matplotlib

!pip install streamlit

!pip install scikit-learn

!pip install streamlit_option_menu


## Reference

1.Python Documentation

2.pandas Documentation

3.numpy Documentation

4.Streamlit Documentation

5.scikit-learn Documentation

