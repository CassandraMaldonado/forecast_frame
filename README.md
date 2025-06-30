# Time Series Analysis & Economic Forecasting

This repository demonstrates practical applications of time series analysis in economics and energy consumption, including ARIMA modeling, regression diagnostics and pattern recognition.

## Notebooks Included

1. Okuns Law
This notebook analyzes the relationship between GDP growth and unemployment.

Key Features:
	•	Data cleaning and visualization of unemployment vs. GDP growth.
	•	OLS regression with diagnostic testing.
	•	Plots and tests for statistical validity.
        •	Economic interpretation.

2. Arima_matrix.ipynb

Purpose:
This notebook forecasts a time series using ARIMA modeling, focusing on identifying optimal lag orders and minimizing error.

Key Features:
	•	AIC matrix heatmap for ARIMA model selection
	•	Autocorrelation (ACF) and partial autocorrelation (PACF) analysis
	•	Model fitting and evaluation with RMSE and forecast plots
	•	Forecasting future time steps with confidence intervals

Outcome:
Demonstrates a methodical approach to ARIMA model tuning and time series forecasting using grid search logic visualized in matrix form.

⸻

3. energy_patterns.ipynb

Purpose:
This notebook uncovers seasonal and trend patterns in energy consumption data.

Key Features:
	•	Time series decomposition (trend, seasonal, residual)
	•	Rolling averages and smoothing techniques
	•	Visual insights into high/low usage months and long-term trends
	•	Stationarity tests and ADF checks for forecasting readiness

Outcome:
Offers actionable insights into energy usage behavior and prepares data for further modeling (e.g., ARIMA or Exponential Smoothing).
