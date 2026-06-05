## Google Trend Time Series Analysis

## Project Title
Bitcoin vs Crypto Crash: A Time Series Analysis using VAR and SARIMA Models.

## Project Overview
This project analyzes Google Trends search interest for keywords "Bitcoin" and "Crypto Crash" using time series analysis techniques. The objective is to examine the relationship between the two search terms and compare the forecasting performance of VAR and SARIMA models.

## Research Objective
The main objectives of the study are:
- To analyze the relationship between Bitcoin and Crypto Crash search activity.
- To test whether one variable helps predict the other using Granger Causality.
- To develop forecasting models using VAR and SARIMA.
- To Compare the forecasting performance of both models.
- To identify the most suitable forecasting approach for Google Trends data.

## Data Source
- Sources: Google Trends 
- Collection Method: Pytrends Python Library
- Frequency: Weekly Data
- Time Period: December 2020-December 2025.
- Keywords: Bitcoin and Crypto Crash

## Methodology
### Data Preparation
- Data collection using Pytrends
- Data cleaning and Validation
- Exploratory data analysis

### Statistical Analysis
- Augmented Dickey-Fuller (ADF) test
- Stationary verification
- Granger Causality Test

### VAR Model 
- Lag order selection
- VAR estimation
- Residual diagnostics
- Impulse Response Function
- Forecast Error Variance Decomposition
- Forecast generation

### SARIMA Model
- ACF and PACF analysis
- Model selection using AIC and BIC
- Residual diagnostics
- Ljung- Box test
- Forecast generation

### Model Evaluation
- Forecast comparison
- Root Mean Squared Error
- VAR vs SARIMA performance assessment

## Key Findings
- Bitcoin search activity exhibits stronger persistence and volatility than Crypto Crash searches.
- Granger Causality analysis indicates that Bitcoin search contains useful information for predicting Crypto Crash searches.
- The VAR model achieved lower forecasting errors than the SARIMA model.
- Incorporating interactions between variables improved forecasting performance.
- VAR was identified as the preferred forecasting model for this dataset.


## Technologies used
- Python
- Pandas
- Numpy
- matplotlib
- statsmodels
- Scikit-learn
- pytrends
- Jupyter Notebook

## Result Summary
The forecasting performance of both models was evaluated using out-of-sample predictions and RMSE metrics. While both VAR and SARIMA captured the overall behavior of the series, the VAR model produced more accurate forecasts and lower forecasting errors. This suggests that incorporating the interaction between Bitcoin and Crypto Crash search activity provides additional predictive information. Overall, the VAR model was found to be the more effective approach for forecasting Google Trends data in this study.

## Limitations
- Google Trends measures public search interest rather than actual cryptocurrency prices or trading activity.
- Only two keywords were analyzed in this study.
- Unexpected market events may affect forecasting accuracy.
- Forecasts are based on historical patterns and assumptions that may not always hold in the future.

## Conclusion
- This project compared VAR and SARIMA models for forecasting Google Trends data related to Bitcoin and Crypto Crash searches. While both models provided useful insights, the VAR model demonstrated superior forecasting performance by incorporating the dynamic relationship between the two variables.
- Based on forecast accuracy and model evaluation metrics, VAR was selected as the preferred forecasting approach for this study.

