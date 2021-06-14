# Stock-price-prediction-using-LSTMs

This project is about predicting the future 'close' prices of 'AAPL' using LSTM's.

The real time stock data is obtained from 'tiingo' (https://www.tiingo.com) using an api key.

The closing price data is arranged in a way such that the value of next day depends upon the values of last timestamp days.
Them an lstm model is trained that is able to minimize the 'mean_squared_error'.

This is how the model looks like

![Screenshot (166)](https://user-images.githubusercontent.com/62187533/121901220-d382ce00-cd43-11eb-91a0-e5df749aaacc.png)


Below is a visual representation of how the model predicts the values:

![st1](https://user-images.githubusercontent.com/62187533/121900542-26a85100-cd43-11eb-9b14-f9a2274595e2.png)

