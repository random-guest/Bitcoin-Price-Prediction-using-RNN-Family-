# Bitcoin Price Prediction in the time of Russia-Ukraine War using LSTM.

# Motivation
Understanding the sudden drop in the bitcoin price which took place at the period of the start of the Russia-Ukraine War.

# Main Aim
To study the effects of Russia-Ukraine tweets on the performance of a simple LSTM model in predicting the next day's closing price of the bitcoin.

# Data Used
1. Recent Historical Bitcoin data (open, high, low, close, volume) of daily data between 2021-01-01 and 2022-07-01.
2. Technical Indicators (Moving Average - MA, Moving Average Convergence Divergence - MACD, Exponential Moving Average - EMA, Bollinger bands, Momentum).
3. Recent Bitcoin Tweets (21k tweets were analyzed between 2021-01-01 and 2022-07-01).
4. Recent Russian-Ukraine War Tweets (30 k tweets were analyzed between 2021-01-01 and 2022-07-01).

# Model Used
Long-Short-Term-Memory Model (LSTM).

# Future Work
1. Model wise: Add a state-of-the-art model that utilizes Transformer architecture.
2. Data wise: Apply feature engineering for improving the performance.
3. Integrate time2vec paper to convert the time into a feature vector.

# Conclusion
Bitcoin's price was affected by the Russia-Ukraine War.
