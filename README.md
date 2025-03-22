# stock-price-prediction-timeseries

## Overview
This project explores and analyzes stock price data from 1980-1981. The goal is to evaluate different forecasting methods to predict stock prices accurately. The methods used include:

- Simple Moving Average (MA)
- Exponential Moving Average (EMA)
- Holt's Exponential Smoothing
- Winter's Exponential Smoothing
- Regression Analysis

## Dataset
The dataset consists of daily stock prices for the years 1980 and 1981. The data was cleaned and analyzed to detect trends, seasonality, and patterns.

## Methods
1. **Simple Moving Average (MA)**: Predicts future stock prices based on the average of historical prices.
2. **Exponential Moving Average (EMA)**: Similar to MA but gives more weight to recent data points.
3. **Holt's Exponential Smoothing**: Extends simple exponential smoothing by adding a trend component.
4. **Winter's Exponential Smoothing**: Extends Holt's method by adding a seasonal component.
5. **Regression Analysis**: Uses linear regression to predict future stock prices based on historical data.

## Evaluation
The models were evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE). Lower values indicate better model performance.

## Results
- **Simple Moving Average**: High MSE and RMSE, indicating poor performance.
- **Exponential Moving Average**: Improved performance with higher alpha values, but still high MSE and RMSE.
- **Holt's Model**: Better performance when predicting the last five days of the year.
- **Winter's Model**: Best performance with the lowest MSE and RMSE when predicting the last five days of the year.
- **Regression Analysis**: High MSE and RMSE, indicating poor performance.

## Future Work
- Experiment with more advanced forecasting models like ARIMA, SARIMA, and VECM.
- Include more data and additional years to improve model accuracy.
- Consider external factors like political stability, inflation, and oil prices.

## Resources
- [Understanding Exponential Moving Average (EMA)](https://www.investopower.com/understanding-exponential-moving-average-ema/)
- [Decomposition to Improve Time Series Prediction](https://quantdare.com/decomposition-to-improve-time-series-prediction/)
- [Time Series Patterns](https://otexts.com/fpp2/tspatterns.html)
