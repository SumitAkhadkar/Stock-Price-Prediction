# Stock Prediction Using LSTM
![image](https://github.com/SumitAkhadkar/Stock-Price-Prediction/assets/131847108/85857350-e277-4791-917d-004c5b10d660)
[![MIT License](https://img.shields.io/badge/Stock-LSTM-green.svg)](https://choosealicense.com/licenses/mit/)

Predicting stock prices is a challenging task, but it can be made more accurate using advanced machine learning techniques like Long Short-Term Memory (LSTM) neural networks. This repository contains code and resources for predicting stock prices using LSTM, allowing you to make informed investment decisions.


## Table of Contents

- [Introduction](#Introduction)
- [Packages](#Packages)
- [Dataset](#Dataset)
- [Data Source](#Data-Source)
- [Conclusion](#Conclusion)
- [Contribution](#Contribution)
  


## Introduction
Stock markets are known for their volatility, and predicting the future price of a stock is a complex task. However, LSTM, a type of recurrent neural network (RNN), has shown promising results in time series forecasting, making it a suitable choice for stock price prediction.

This project demonstrates how to build and train an LSTM model to predict stock prices based on historical data. By using this repository, you can gain insights into the world of stock prediction and leverage the power of machine learning for your investment decisions.

## Packages
Before running the code ensure you have the following packages installed:

- Python 3.x
- TensorFlow
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-Learn

## Dataset
To train and test the LSTM model, you will need historical stock price data. I have use your Tata company dataset. The dataset contain following columns:

- Date: The Date of stock price.
- Open: The price at which a stock started trading.
- Low: Lowest price of stock on that period.
- Close: The price at which a stock close trading.
- Adj Close: Adjusted close price of a stock.
- Volume: Total amount of trading activity.

## Data Source

- [Yahoo Finance Stock Price Data ](https://finance.yahoo.com/quote/TATACONSUM.NS/history?p=TATACONSUM.NS)

## Conclusion

- As evident from the chart above, the model closely approximates the actual stock price trends. Consequently, it can be inferred that this LSTM model is likely to yield high accuracy for this dataset.
- However, the model's accuracy could be improved further by expanding the training dataset and augmenting the number of LSTM layers.

## Contribution
Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or create a pull request.
