# Demand Forecasting & Monte Carlo Simulation Hackathon

## Overview
This project focuses on demand forecasting and inventory planning using time series models, machine learning models, and Monte Carlo simulation.

## Business Problem
The company faces irregular demand patterns, missing monthly order periods, and unreliable long-term forecasts. This makes production planning difficult and increases the risk of overproduction or stockouts.

## Objective
Compare forecasting approaches across different planning horizons and recommend a more reliable production planning strategy.

## Methods Used
- Exploratory data analysis
- Data preprocessing
- Feature engineering
- Time series reconstruction
- ARIMA and SARIMA forecasting
- Random Forest
- XGBoost
- Linear Regression
- Monte Carlo simulation
- Forecast evaluation using MAPE, MAE, RMSE, and R-squared

## Key Findings
The 2-month forecasting horizon performed much better than the 5-month horizon. The project found that forecast accuracy deteriorates significantly over longer horizons due to irregular order patterns and missing monthly data.

## Business Recommendation
The company should shorten its production and planning cycle from 5 months to 2 months or less where operationally feasible. This supports smaller production batches, rolling monthly demand reviews, and more flexible inventory planning.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files
- `demand_forecasting_monte_carlo.ipynb`: Full analysis and modeling notebook
- `final_report.pdf`: Final hackathon report