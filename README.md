Laptop Price Predictor – Machine Learning Project

A machine learning model that predicts laptop prices based on hardware specifications such as RAM, processor, GPU, storage, display type, and brand. The goal of this project is to understand how different features influence laptop pricing and to build an accurate predictive model using Python and Scikit-learn.

**Project Overview

-->In this project, I built a regression model to estimate the price of laptops by analyzing a dataset containing their specifications.
The workflow includes:

Data cleaning & preprocessing
Feature engineering
Exploratory Data Analysis (EDA)
Model training & evaluation
Selecting the best-performing model

--> Dataset

The dataset contains laptop specifications such as:
Brand
Processor
RAM
Storage (HDD/SSD)
GPU
Display Type
Operating System
Weight
Price (Target Variable)


--> Technologies Used

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Jupyter Notebook

-->Exploratory Data Analysis (EDA)

Key EDA steps included:
Checking for missing values
Visualizing price distribution
Understanding correlations between specs & price
Identifying high-impact features (e.g., RAM, processor, GPU)

-->Sample insights:

Gaming GPUs significantly increase price
SSD-based laptops tend to cost more than HDD-only laptops
RAM and Processor type show highest correlation with price

-->Machine Learning Models Used

The following regression models were trained and compared:
Linear Regression
Random Forest Regressor
XGBoost Regressor (if used)
Gradient Boosting Regressor (optional)

-->Best Model

The best model was selected based on metrics like:
R² Score
RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)

-->Key Features / Highlights

End-to-end machine learning pipeline
Feature engineering for categorical & numerical data
EDA visualizations for insights
Multiple model comparison
Price prediction based on real-world features
