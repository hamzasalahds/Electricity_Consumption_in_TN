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

- Evaluation Metrics: RMSE, MAE, MAPE, RMSPE

- Visualization & Diagnostics: Time Series Plots, Heatmaps, Residual Analysis

## Key Features

- Data preprocessing pipeline: cleaning, merging, and transforming multi-source datasets

- Sector-wise consumption modeling: Residential, Commercial, Industrial, and Combined

- ARIMA modeling with automated hyperparameter tuning (auto_arima)

- Residual diagnostics (Ljung-Box test) for model validation

- Insights to support energy efficiency and demand response planning

## Results Summary

- SARIMAX model achieved overall strong forecast accuracy, with relative RMSE around 4.0% for the Combined sector and as low as 3.0% for Commercial consumption

- Residential forecasts exhibited higher relative RMSE (~7.6%), indicating greater variability and modeling challenges in this sector

- Industrial sector forecasts showed moderate accuracy with relative RMSE near 4.8%

- Seasonal extremes (e.g., January and July) remain challenging across all sectors, causing underpredictions during peak demand months

- RMSPE analysis confirms SARIMAX forecasts maintain percentage errors mostly under 4%, highlighting reliable relative performance despite occasional spikes

## Recommendations

- Enhance modeling by incorporating seasonality-aware methods and additional external regressors to better capture peak demand fluctuations

- Focus on improving the Residential sector forecasting through refined data collection and modeling techniques to reduce higher relative errors

- Develop targeted demand response and energy efficiency strategies during identified seasonal peaks to mitigate forecast shortfalls

- Continue monitoring and refining models using RMSPE and relative RMSE metrics for balanced absolute and percentage error insights
