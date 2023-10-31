# SP500_TimeSeries_Forecasting

In these notebooks, I have done Time Series Analysis on S&P500 stock prices imported using ```yfinance``` library.

## Will S&P Increase?
  1. In this notebook, I compared the closing prices of the present day and the next day to create a target. 1 if increase else 0.
  2. Used RandomForestClassifier to classify if the stock price will increase on the next day or not.
  3. Obtained a decent accuracy score.

## Pytorch LSTM TimeSeries
  1. Used LSTM to do TimeSeries Analysis in Pytorch.
  2. Utilized Dataset class to use data frame dataset.
  3. The result obtained is shown below.

![Result](/Pytorch_LSTM_TimeSeries/result.jpg?raw=true "Result of Closing price prediction")

 
