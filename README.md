# Tennessee Energy Consumption Forecasting
## Overview
This project applies predictive analytics techniques to forecast electricity consumption across residential, commercial, and industrial sectors in Tennessee from 2010 to 2024. Leveraging historical temperature and pricing data, the analysis provides sector-specific insights and delivers actionable recommendations for utility providers and policymakers.



[Tennessee Energy Insights PDF](https://github.com/hamzasalahds/Electricity_Consumption_in_TN/blob/main/Tennessee%20Energy%20Insights.pdf)

## Objectives

- Forecast energy demand using ARIMA, SARIMAX, and multiple linear regression models

- Analyze the impact of temperature and electricity prices on consumption patterns

- Provide data-driven strategies for energy optimization and policy planning

## Data Sources

- U.S. Energy Information Administration (EIA)

- NOAA Climate Data

## Tools & Libraries

- Python: Pandas, NumPy, Matplotlib, Seaborn

- Time Series Modeling: statsmodels, pmdarima

- Evaluation Metrics: RMSE, MAE, MAPE

- Visualization & Diagnostics: Time Series Plots, Heatmaps, Residual Analysis

## Key Features

- Data preprocessing pipeline: cleaning, merging, and transforming multi-source datasets

- Sector-wise consumption modeling: Residential, Commercial, Industrial, and Combined

- ARIMA modeling with automated hyperparameter tuning (auto_arima)

- Residual diagnostics (Ljung-Box test) for model validation

- Insights to support energy efficiency and demand response planning

## Results Summary

- The SARIMAX model performed well during stable weather periods but underpredicted usage during extreme months like January and July across all sectors

- Residential sector: Low error in February and April (<3%), but significant underpredictions during seasonal peaks (up to 11.7%)

- Commercial sector: Similar trends, with notable underpredictions in summer months (July and August)

- Industrial sector: Highest fluctuations in summer; best accuracy in February and November

- Combined sector: Smoothed variations with errors as low as 1.21% in February, but still challenged by seasonal extremes


## Recommendations

- Incorporate seasonality-aware models or external regressors to improve peak demand forecasting

- Introduce peak-hour alerts and targeted energy efficiency incentives during high-consumption months

- Enhance data collection on weather and occupancy patterns for better accuracy
