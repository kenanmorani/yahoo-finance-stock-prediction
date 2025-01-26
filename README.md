# Yahoo Finance Stock Prediction using Machine Learning

This project demonstrates how to use machine learning techniques to predict stock prices using historical data from Yahoo Finance. The primary focus is on building a predictive model using LSTM (Long Short-Term Memory) networks to forecast the next day's closing prices. The dataset includes various technical indicators like RSI, MACD, and Bollinger Bands, which are used as features for model training.

## Project Overview
- **Data Source**: The data is fetched from Yahoo Finance and includes key stock market features such as Open, High, Low, Close, and Volume.
- **Technical Indicators**: 
  - **RSI (Relative Strength Index)**
  - **MACD (Moving Average Convergence Divergence)**
  - **Bollinger Bands**
- **Machine Learning Model**: An LSTM-based deep learning model is used to predict the next day's closing price.
- **Evaluation Metrics**: The model’s performance is evaluated using RMSE (Root Mean Squared Error).

## Features
- Historical stock data processing.
- Feature engineering with technical indicators (RSI, MACD, Bollinger Bands).
- Model training with LSTM (Long Short-Term Memory) neural networks.
- Model evaluation with RMSE for stock price prediction.

## Requirements
- Python 3.11.11  
- Libraries:  
matplotlib==3.10.0  
numpy==1.26.4  
pandas==2.2.2  
scikit-learn==1.6.1  
seaborn==0.13.2  
tensorflow==2.17.1   
yfinance==0.2.52

## Detailed Documentation
The detailed paper is underconsideration and expected to be published soon on arXiv as a preprint. A current documentation version can be found using the follwoing link:  
https://drive.google.com/file/d/10RTQp3N63gzXmQk79tKA_9MzNkBfZzKs/view?usp=sharing

## Installation

Clone the repository:
```bash
!git clone https://github.com/kenanmorani/yahoo-finance-stock-prediction.git



