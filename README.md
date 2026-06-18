# Predictive Analytics Using Historical Sales Data

## Project Overview

This project focuses on forecasting future sales trends using historical sales data from the Sample dataset. The workflow includes data cleaning, exploratory data analysis (EDA), predictive modeling using Linear Regression, model evaluation, and visualization of forecasting results.

## Objectives

* Clean and preprocess historical sales data.
* Analyze sales trends and patterns.
* Build a predictive model to forecast future sales.
* Evaluate model performance using statistical metrics.
* Visualize historical and predicted sales trends.

## Dataset

Dataset Used: Sample Dataset

Key Features:

* Order Date
* Sales
* Profit
* Category
* Region
* Quantity
* Discount

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

## Project Workflow

### 1. Data Cleaning

* Loaded the dataset.
* Handled missing values.
* Removed duplicate records.
* Converted date columns to datetime format.
* Created time-based features such as Year and Month.

### 2. Exploratory Data Analysis (EDA)

* Analyzed monthly and yearly sales trends.
* Examined sales by category and region.
* Performed correlation analysis.
* Identified patterns and seasonal fluctuations.

### 3. Predictive Modeling

* Aggregated sales data on a monthly basis.
* Created a Month_Number feature for forecasting.
* Trained a Linear Regression model using historical sales data.
* Generated sales forecasts for future months.

### 4. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

Results:

* RMSE: 23,416.38
* R² Score: 0.0342

The model successfully captured the overall upward trend in sales but showed limitations in modeling seasonal fluctuations and sudden changes in demand.

### 5. Visualization

Generated visualizations including:

* Monthly Sales Trend
* Sales by Category
* Sales by Region
* Actual vs Predicted Sales
* Future Sales Forecast

## Key Learnings

* Data preprocessing and feature engineering.
* Exploratory data analysis techniques.
* Time-based sales forecasting.
* Linear Regression model development.
* Model evaluation and interpretation.
* Data-driven decision making.

## Future Improvements

* Implement ARIMA or SARIMA models for time-series forecasting.
* Include holiday and seasonal features.

## Author

Rutika

