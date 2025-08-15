# Exchange-Rate-Room-Revenue-Analysis
Author: Yap Zhi Ling
## Project Overview
This project investigates whether exchange rates can effectively predict hotel room revenue using time series forecasting models. Through comprehensive analysis using SARIMA and SARIMAX models, we examine the predictive power of USD/SGD exchange rates on hotel room revenue.
## Methodology
1. Exploratory Data Analysis - Time Series Visualisation, Identifying Lag, Seasonal Decomposition
2. Stationary Testing - ADF & KPSS Tests, ACF & PACF Plots
3. Data Preprocessing - Differencing, Adding Lag & COVID Binary Mask Variable
4. Model Development - auto_arima, Log Transformation
5. Model Comparison - Forecast Accuracy (MAE/RMSE/MASE)
## Key Findings
* SARIMA and SARIMAX models produced identical coefficients and AIC values
* Exchange rates do not significantly improve room revenue prediction
* Adding exchange rate as an exogenous variable provides no additional forecasting value
## Repository Structure
```
├── README.md
├── requirements.txt
└── sarima_analysis.ipynb
```
## Getting Started
1. Clone the repository
2. Install the dependencies
3. Get the raw data from [Singapore Hotel Room Revenue](https://data.gov.sg/datasets/d_8e62605f0c1c948702b6ea0fe45242d3/view?dataExplorerPage=1) & [USD to SGD Exchange Rate](https://tablebuilder.singstat.gov.sg/table/TS/M700051)
4. Open and run the analysis
