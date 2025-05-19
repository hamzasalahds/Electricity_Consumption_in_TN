# Tennessee Energy Consumption Forecasting
## Overview
This project applies predictive analytics techniques to forecast residential electricity consumption in Tennessee from 2010 to 2024. Leveraging historical temperature and electricity pricing data, the analysis provides insights into sector-specific consumption trends and delivers actionable recommendations for utility providers and policymakers.

[Energy Consumption PDF](https://github.com/user-attachments/files/20296011/Energy_Consumption.pdf)

## Objectives
Forecast residential energy demand using ARIMA and multiple linear regression models.

Analyze the impact of temperature and electricity prices on consumption patterns.

Provide data-driven strategies to optimize energy use and planning.

## Data Sources
U.S. Energy Information Administration (EIA)

NOAA Climate Data

## Tools & Libraries
Python (Pandas, NumPy, Matplotlib, Seaborn)

Time Series Modeling: statsmodels, pmdarima

Evaluation Metrics: RMSE, MAE, MAPE

EDA & Visualization: Heatmaps, Time Series Plots, Residual Diagnostics

## Key Features
Data preprocessing pipeline: cleaning, merging, and transforming datasets

Sector-wise consumption analysis (Residential, Commercial, Industrial)

ARIMA modeling with automatic parameter tuning (auto_arima)

Residual analysis and model validation using Ljung-Box test

Actionable insights for demand response and sustainability planning

## Results Summary
Strong correlation found between temperature and residential/commercial consumption

ARIMA model achieved RMSE of ~291,000 kWh for residential forecasts

Recommendations include peak-hour alerts, efficiency incentives, and improved data collection
