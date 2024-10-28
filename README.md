Wine Quality Prediction
Project Overview
This project focuses on predicting wine quality using a dataset containing various chemical properties of wine samples. The model is based on Linear Regression and aims to estimate the quality of a wine sample based on its observed chemical characteristics.

Files
WineQT.csv: The initial dataset containing wine samples and their respective chemical properties.
Code Explanation
Dataset Import and Exploration

The dataset is imported and its shape (number of rows and columns) is checked.
Null or NaN values are checked to ensure data cleanliness.
The Id column is removed as it does not contribute to prediction.
Data Visualization

A bar plot is created to visualize the relationship between wine quality and alcohol content.
Dataset Split

The dataset is split into features (X) and the target variable (y), which is the wine quality.
The data is further split into training and testing sets using an 80-20 split.
Model Training

A Linear Regression model is created and trained on the training data.
Prediction

A prediction is made using a random sample from the feature set.
Error Calculation

The square error is calculated between a random actual value and the model’s prediction to evaluate performance
