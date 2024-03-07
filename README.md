# PRODIGY_ML_01

Overview
This project focuses on building a machine learning model to predict house prices based on various features such as square footage, number of bedrooms, and number of bathrooms. The model is implemented using linear regression, a simple yet powerful technique commonly used in real estate valuation and housing market analysis.

Motivation
Predicting house prices accurately is essential for various stakeholders in the real estate industry, including homeowners, buyers, sellers, and investors.

Features
LotArea: Lot size in square feet
Bedroom: The number of bedrooms in the house.
bath1: Basement full bathrooms
bath2: Basement half bathrooms
bath3: Full bathrooms above grade
bath4: Half baths above grade
SalePrice: Prices of the houses

Dataset
The dataset used in this project contains historical data on house prices along with the corresponding features. It has been sourced from Kaggle.

Methodology
Data Preprocessing: Clean and preprocess the dataset to check if multicollinearity is present between the independent variables
Model Training: Train a linear regression model using the training data.
Model Evaluation: Evaluate the model's performance using various regression metrics such as Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, and R-squared.

Results
The trained linear regression model achieved [insert performance metrics].
The model's predictions are accurate within [insert percentage] of the actual house prices on average.

Future Work
Explore advanced regression techniques such as polynomial regression or regularization methods to potentially improve model performance.
Incorporate additional features or external datasets (e.g., neighborhood demographics, school ratings) to enhance the predictive power of the model.

Language Used
Python

Libraries Used
Pandas
NumPy
scikit-learn

Technology Used
Jupyter Notebook
