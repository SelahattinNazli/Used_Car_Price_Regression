
# Used Car Price Prediction with Regression
This project aims to build a regression model to predict the price of used cars based on various attributes such as mileage, brand, model, year, engine power, and other features. The dataset used in this project consists of historical data on used cars, including their specifications and selling prices.

## Project Overview

The primary goal of this project is to develop a machine learning model that can accurately predict the price of a used car based on the available features. The project follows a typical machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and optimization.

## Dataset

The dataset used in this project contains the following key columns:


**brand:** The brand of the car (e.g., Tesla, Lucid, Rivian)

**model:** The specific model of the car.

**model_year:** The year in which the car model was manufactured.

**milage:** The mileage of the car in miles.

**fuel_type:** The type of fuel used (e.g., Electric, Gasoline).

**engine:** The engine power of the car.

**transmission:** The type of transmission (e.g., Automatic, Manual).

**ext_col:** Exterior color of the car.

**int_col:** Interior color of the car.

**accident:** Information about reported accidents.

**clean_title:** Indicates whether the car has a clean title.

**price:** The selling price of the car.

## Project Pipeline

**Data Preprocessing:**

Handled missing values in critical columns such as milage, price, fuel_type, etc.
Converted categorical variables into numeric values using encoding techniques.
Feature scaling was applied to ensure that the model treats all features equally.
Exploratory Data Analysis (EDA):

Performed visual and statistical analyses to explore relationships between features and the target variable (price).
Analyzed the distribution of key variables such as mileage, engine power, and model year.

## Model Building:

**Gradient Boosting Regressor**

**XGBoost**

**LightGBM**

The models were compared based on performance metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.
