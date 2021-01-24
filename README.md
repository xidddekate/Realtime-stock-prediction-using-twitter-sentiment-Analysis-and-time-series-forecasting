# Realtime-stock-prediction-using-twitter-sentiment-Analysis-and-time-series-forecasting

The WebApp can be used for predicting future Stocks based on data collected using AlphaVantage API and yfinance API.
The front end of the Web App is based on **Flask** . The App forecasts stock prices of the next seven days for any given stock under **NASDAQ** or **NSE** as input by the user. Predictions are made using three algorithms: **ARIMA, LSTM, Linear Regression**. The Web App combines the predicted prices of the next seven days with the **sentiment analysis of tweets** by using tweepy to give recommendation whether the price is going to rise or fall

Image Credits : https://freepik.com

# How to Use

simply run app.py file 

# Screenshots


<img src="https://github.com/xidddekate/Realtime-stock-prediction-using-twitter-sentiment-Analysis-and-time-series-forecasting/blob/main/Screenshot%20(44).png">

<br><br> **Enter the Ticker (Stock Symbol)**
<br>

<img src="https://github.com/xidddekate/Realtime-stock-prediction-using-twitter-sentiment-Analysis-and-time-series-forecasting/blob/main/Screenshot%20(45).png">

<br><br> **Get the Predictions and accuracies by different types of models**
 <br> 
 
<img src="https://github.com/xidddekate/Realtime-stock-prediction-using-twitter-sentiment-Analysis-and-time-series-forecasting/blob/main/Screenshot%20(46).png">
<img src="https://github.com/xidddekate/Realtime-stock-prediction-using-twitter-sentiment-Analysis-and-time-series-forecasting/blob/main/Screenshot%20(47).png">

<br><br> **Twitter Sentiment Analysis**
 <br> 
 
<img src="https://github.com/xidddekate/Realtime-stock-prediction-using-twitter-sentiment-Analysis-and-time-series-forecasting/blob/main/Screenshot%20(48).png">

<br><br> **BUY OR SELL ?**
 <br> 
 
<img src="https://github.com/xidddekate/Realtime-stock-prediction-using-twitter-sentiment-Analysis-and-time-series-forecasting/blob/main/Screenshot%20(49).png">


# Improvements

WebApp can be deployed into production but can be slow sometimes. Good Infrastructure and Online Learning can be implemented in the model to provide faster results to end users.
Any other Contributions are welcomed...
