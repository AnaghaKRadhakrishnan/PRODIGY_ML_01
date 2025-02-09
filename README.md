# PRODIGY_INFOTECH_TASKS
This repository showcases a task I have completed during my internship in PRODIGY INFOTECH

# House Prices Prediction Using Linear Regression

This project implements a **Linear Regression** model to predict house prices based on various features like square footage, number of bedrooms, number of bathrooms, and other important features from the **"House Prices: Advanced Regression Techniques"** dataset.

## Project Overview

In this project, we build a machine learning model to predict the sale prices of houses using the `train.csv` dataset provided by Kaggle **House Prices: Advanced Regression Techniques**. The dataset contains information about house attributes such as square footage, number of bedrooms, bathrooms, and more. We use **Linear Regression** to train the model and make predictions.

## Dataset

The dataset used in this project is from the Kaggle competition [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). 

**Features Used for Prediction:**
- `GrLivArea`: Above ground living area in square feet.
- `TotRmsAbvGrd`: Total number of rooms above grade (does not include bathrooms).
- `FullBath`: Number of full bathrooms.
- `HalfBath`: Number of half bathrooms.
- `BedroomAbvGrd`: Number of bedrooms above grade.


## Steps Involved

1. **Data Loading**: Load and explore the dataset to check the features and data quality.
2. **Data Preprocessing**: Handle missing values, drop irrelevant columns, and select features for prediction.
3. **Model Training**: Train a **Linear Regression** model on the training dataset.
4. **Model Evaluation**: Evaluate the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
5. **Prediction**: Make predictions on the test dataset.


The following libraries have been downloaded for running this project in google colab

- pandas
- scikit-learn
- matplotlib

