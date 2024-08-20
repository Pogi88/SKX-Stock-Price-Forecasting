# 📈 Skechers (SKX) Stock Price Forecasting

## 🛠 Project Overview:

This project focuses on forecasting the stock prices of Skechers U.S.A., Inc. (SKX) using advanced time series analysis techniques. The analysis covers daily stock data from November 26, 2020, to February 9, 2024, applying various statistical models to predict future prices.

## 🚀 Key Components:

### Data Loading and Transformation:

- Loaded and cleaned the SKX stock price data.
- Handled missing values, particularly those arising from non-trading days, by filling in the gaps with appropriate methods.
- Visualized trends using time series plots and moving averages (5-day and 12-day SMAs).

### Change Point and Structural Break Analysis:

- Analyzed change points in the time series using methods like PELT and structural break tests.
- Identified and examined potential structural changes in the stock price trends.
  
### Stationarity and Autocorrelation Testing:

- Performed tests like ADF, PP, KPSS, and Zivot-Andrews to check for stationarity.
- Identified that the original time series was non-stationary and applied differencing to achieve stationarity.
  
### Forecasting Models:

- Exponential Smoothing (ETS): Modeled and forecasted stock prices using ETS, with a focus on identifying components and examining residuals.
- Moving Average (MA): Applied SARIMA models with different configurations to forecast stock prices.
- ARIMA: Developed and compared multiple ARIMA models to determine the best fit for forecasting.
  
### Model Comparison:

- Compared the performance of ETS, MA, and ARIMA models.
- Determined the ETS model as the best performing one based on accuracy metrics (RMSE and MAPE).
  
### Final Forecasting:

- Provided forecasts for SKX stock prices for the next 7 days using the selected models.
- Compared the forecasted values with actual stock prices to evaluate the models' predictive accuracy.
  
## 📊 Skills Demonstrated:

- Time Series Analysis and Forecasting
- Statistical Testing and Model Validation
- Data Cleaning and Preprocessing
- Use of R for financial data analysis
- Advanced Visualization Techniques
