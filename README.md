# Bitcoin Price Prediction in the time of Russia-Ukarine War using LSTM.

# Motivation
The sudden drop in the bitcoin price that took place at the period of the start of Russia-Ukraine War.

# Main Aim
To study the effects of Russia-Ukarine tweets on the performance of a simple LSTM model in predicting next day closing price.

# Data Used
1. Recent Historical Bitcoin data (open, high, low, close, volume) of daily data between 2021-01-01 and 2022-07-01.
2. Technical Indicators (Moving Average - MA, Moving Average Convergence Divergence - MACD, Exponential Moving Average - EMA, Bollinger bands, Momentum).
3. Recent Bitcoin Tweets (21k tweets were analyzed between 2021-01-01 and 2022-07-01).
4. Recent Russian-Ukarine War Tweets (30 k tweets were analyzed between 2021-01-01 and 2022-07-01).

# Model Used
Long-Short-Term-Memory Model (LSTM).

# Future Work
1. Model wise: Add state-of-the-art model that utlizes Transformer architecture.
2. Data wise: Apply feature engineering for improving the performance.
3. Integrate time2vec paper to convert the time into feature vector.

# Conclusion
Bitcoin's price was affected by the Russia-Ukraine War.
