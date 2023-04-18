# Air-Quality-PM2.5-Prediction

This project aims to predict PM2.5 readings in Nairobi throughout the day by building a time series model.

 PM2.5 are tiny particles in the air that reduce visibility and cause the air to appear hazy when levels are elevated.

# Dataset 
The data used for this project is sourced from one of Africa's largest open data platforms - [Open Africa](https://africaopendata.org/).


# Project Overview
The project consists of four Jupyter notebooks:

1. **Data Wrangling with MongoDB**:In this notebook, data is queried from a MongoDB database and cleaned for further analysis.

2. **Forecasting_PM2_5_Using_Linear_Regression**: In this notebook, a linear regression model is built to predict PM2.5 readings for the next hour using historical data.

3. **Forecasting_PM2_5_Using_Autoregressive_Model**: In this notebook, an autoregression model is built to predict PM2.5 readings for the next hour using historical data. The model is improved by tuning its hyperparameters.

4. **Forecasting_PM2_5_Using_ARMA_Model**: In this notebook, an ARMA (Autoregressive Moving Average) model is built to predict PM2.5 readings for the next hour using historical data.

# Learning Outcomes

Throughout this project, the following concepts were covered:

• Querying data from a MongoDB database.

• Cleaning and preparing time series data for analysis.

• Building linear regression, autoregression, and ARMA models for time series prediction.

• Tuning hyperparameters to improve model performance.

# Requirements

The following packages are required to run the project:

☞ numpy

☞ pandas

☞ matplotlib

☞ pymongo

☞ sklearn

☞ statsmodels

# Usage

To use this project, simply clone the repository and run the Jupyter notebooks in the order listed above. The notebooks are well documented, and the code is commented to explain what is happening at each step.

# Acknowledgments

The data used for this project was sourced from Open Africa - one of the largest open data platforms in Africa.















