# Car Price Prediction Model


## Project Overview:

This project aims to develop a machine learning model to predict the price of used cars based on various features like make, model, year, mileage, fuel type, transmission type, and engine power. The model will be trained on a dataset of used cars and evaluated using appropriate metrics.

## Dataset:

The dataset used for this project contains information about various car models, including:

Car Name: The make and model of the car.
Year: The year of manufacture.
Fuel Type: The type of fuel used by the car (e.g., petrol, diesel).
Transmission Type: The type of transmission (e.g., manual, automatic).
Owner: The number of previous owners.
Mileage: The current mileage of the car.
Engine Power: The engine power in horsepower.
Seats: The number of seats in the car.
Selling Price: The price of the car (target variable).

## Data Preprocessing:

**Handling Missing Values:** Missing values were handled using appropriate techniques like imputation or removal.
**Text removal from numerical columns:** Certain columns has text like **Engine Power** has **cc** which needs to be removed.
**Data Cleaning:** Outliers were identified and handled, and inconsistent data was cleaned.
**Feature Scaling:** Numerical features were scaled to a common range to improve model performance.

## Model Development:

**Data Splitting:** The dataset was split into training and testing sets.
**Model Selection:** Various machine learning models were explored, including:
**Linear Regression
Random Forest Regression
Gradient Boosting Regression
XGBoost Regression**
**Model Training:** The selected model was trained on the training set.

## Model Evaluation:

The model's performance was evaluated using metrics like:
Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.
Root Mean Squared Error (RMSE): The square root of MSE, providing a measure of prediction error in the same units as the dependent variable.   
Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual values.
R-squared: Measures the proportion of variance in the dependent variable explained by the model.

## Future Work:

Additional Features: Explore incorporating additional features like car condition, safety ratings and regional demand to improve model accuracy.
Time Series Analysis: Analyze time-series data to capture trends and seasonality in car prices.
Ensemble Methods: Combine multiple models to improve predictive performance.
Deep Learning: Experiment with deep learning techniques for more complex modeling.
By following these steps and continuously refining the model, we can build an accurate and reliable car price prediction system.
