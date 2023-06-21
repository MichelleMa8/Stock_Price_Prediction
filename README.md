# stock_price_prediction

In this project, I collected five-year stock price data of NVIDIA and Microsoft to make a prediction of future stock prices. I built a statistic model, ARIMA model, and a deep learning model, LSTM model to solve the problem. 

After tuning the model, I find the best (p, q) for NVDA ARIMA model is (5, 1), the best (p, q) for MSFT ARIMA model is (3, 2), and the RMSE of best NVDA LSTM is 15.43, the RMSE of best MSFT LSTM is 9.40. Also, I find that ARIMA can only be used to predict short-term price, while LSTM is able to predict long-term price. 
