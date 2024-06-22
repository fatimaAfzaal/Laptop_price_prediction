# Laptop Price Prediction

This project involves predicting laptop prices using various machine learning models. The dataset contains specifications of laptops and their prices.

## Table of Contents
- Dataset
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Model Building
- Model Evaluation

## Dataset
The dataset includes laptop specifications like RAM, storage, and processor type, along with the corresponding prices.

## Data Preprocessing
1. Load the dataset using pandas.
2. Drop irrelevant columns ('Number of Ratings' and 'Number of Reviews').
3. Handle missing values.
4. Convert categorical variables to numerical using one-hot encoding.

## Exploratory Data Analysis (EDA)
1. Visualize the distribution of laptop prices.
2. Analyze the distribution of RAM sizes.
3. Explore the relationship between RAM size and laptop price.

## Model Building
1. Split the data into training and testing sets.
2. Train a Gradient Boosting Regressor.
3. Train a Random Forest Regressor for comparison.

## Model Evaluation
1. Calculate Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score for both models on training and testing data.
2. Perform cross-validation to validate the models.
