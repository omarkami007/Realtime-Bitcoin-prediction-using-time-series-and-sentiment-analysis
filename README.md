![](/img/banner.jpg)
# Realtime Bitcoin Prediction Using Time Series and Sentiment Analysis

## Overview
This project is a **[Streamlit application](https://st-bitcoin-app-007.streamlit.app/)** designed to provide real-time insights and predictions for Bitcoin prices. By combining time series analysis and sentiment analysis of Bitcoin-related news, the app helps users visualize trends, explore recent sentiment, and predict future Bitcoin prices.

---

## Features
The application offers the following functionalities:
1. **Browse Recent Bitcoin Prices**:
   - Fetch and display the latest Bitcoin price trends.
2. **Browse Recent Sentiment on Bitcoin**:
   - Analyze Bitcoin-related news sentiment (Positive, Negative, or Neutral) using **TextBlob** and **NLTK**.
3. **Visualize Price and Sentiment**:
   - Plot Bitcoin prices alongside sentiment analysis to uncover correlations.
4. **Predict Future Bitcoin Prices**:
   - Use time series models (**LSTM** and **ARIMA**) to predict future Bitcoin price trends.

---

## Models and Techniques
1. **Time Series Analysis**:
   - **LSTM (Long Short-Term Memory)**: A neural network model for capturing temporal dependencies in Bitcoin prices.
   - **ARIMA (Auto-Regressive Integrated Moving Average)**: A statistical approach to model price trends.
   
2. **Sentiment Analysis**:
   - **TextBlob**: For sentiment polarity scores.
   - **NLTK (Natural Language Toolkit)**: To preprocess and analyze Bitcoin-related news articles.

