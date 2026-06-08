
# Sales Forecasting Using Python

## Project Overview
This project uses historical sales data to forecast future sales using Python.
The dataset contains sales records of multiple stores and items.

## Dataset
Dataset used: Store Item Demand Forecasting dataset

The original dataset contains sales data from 2013 to 2017.
In this project, 4 years of data from 2014 to 2017 was used for forecasting.

## Objective
The objective of this project is to analyze historical sales data and build a machine learning model to forecast future sales.

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Steps
1. Loaded the sales dataset
2. Checked missing values and dataset information
3. Converted date column into datetime format
4. Selected 4 years of historical sales data
5. Created daily total sales data
6. Performed exploratory data analysis
7. Created time-based, lag, and rolling features
8. Trained multiple machine learning models
9. Compared models using MAE, RMSE, R2 Score, and MAPE
10. Forecasted sales for the next 30 days

## Models Used
- Baseline Model
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Evaluation Metrics
- MAE
- RMSE
- R2 Score
- MAPE

## Output
The project generates:
- Sales trend graph
- Monthly sales analysis
- Day-wise sales analysis
- Actual vs predicted sales graph
- Next 30 days sales forecast
- CSV files containing predictions

## Conclusion
This project shows how historical sales data can be used to predict future demand.
The forecasting model can help businesses in inventory planning, sales strategy, and demand management.
