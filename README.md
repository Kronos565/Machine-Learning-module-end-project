# Car Price Prediction Project

## Project Overview

A Chinese automobile company aspires to enter the US market by establishing a local manufacturing unit to compete with existing US and European car manufacturers. To help understand the factors affecting car prices in the American market, a consulting firm gathered data on various car features. This project builds and compares multiple regression models to predict car prices, identifies the most significant features affecting pricing, and tunes hyperparameters to optimize model performance.

## Key Features

- **Data Cleaning & Preprocessing:**
  - Handling missing values and outliers.
  - Dropping irrelevant columns (e.g., `car_ID`, `CarName`, `symboling`, `peakrpm`, `compressionratio`, `stroke`, `carheight`).
  - Encoding categorical variables (using Label Encoding for binary features and One-Hot Encoding for nominal features).
  - Standardizing numerical features.

- **Exploratory Data Analysis (EDA):**
  - Correlation analysis and heatmap visualization to understand the relationships between features and the target variable (`price`).

- **Model Implementation:**
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Support Vector Regressor

- **Model Evaluation:**
  - Evaluation of models using R-squared (R²), Mean Squared Error (MSE), and Mean Absolute Error (MAE).
  - Creation of an evaluation matrix to compare model performances side-by-side.

- **Hyperparameter Tuning:**
  - Tuning the Gradient Boosting Regressor using GridSearchCV to optimize performance.

## Conclusion

This project demonstrates a complete workflow for predicting car prices using machine learning. By thoroughly cleaning and preprocessing the data, performing detailed exploratory analysis, and implementing multiple regression models, we were able to compare different approaches using robust evaluation metrics. Hyperparameter tuning, particularly on the Gradient Boosting Regressor, further improved model performance. The final evaluation matrix provides clear insight into which model best predicts car prices. Future work may involve further feature engineering, exploring additional modeling techniques, and integrating more diverse datasets to enhance prediction accuracy.
