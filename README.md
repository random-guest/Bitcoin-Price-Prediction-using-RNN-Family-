# Bitcoin Price Prediction in the time of Russia-Ukarine War using RNN Family 


# Aim
1. To predict next day closing price of Bitcoin.
2. To study the effects of Russia-Ukarine tweets on the performance of several Deep Learning models (perhaps something new).
3. To compare the effects of using Technical Indicators, Bitcoin tweets and Russia-Ukarine tweets on the performance of the implemented models.

# Models Used
1. LSTM
2. 1D-Conv-LSTM
3. Bi-LSTM
4. 1D-Conv-Bi-LSTM
5. GRU
6. 1D-Conv-GRU
7. Bi-GRU
8. 1D-Conv-Bi-GRU

# Data Used
1. Recent Historical Bitcoin data (open, high, low, close, volume) that encloses the Russian-Ukarine War time period. 
2. Technical Indicators (Moving Average - MA, Moving Average Convergence Divergence - MACD, Exponential Moving Average - EMA, Bollinger bands, Momentum).
3. Recent Bitcoin Tweets.
4. Recent Russian-Ukarine War Tweets.

# Future Work
1. Model wise: Add state-of-the-art model that utlizes Transformer architecture.
2. Data wise: Apply feature engineering.
3. Integrate time2vec paper to convert the time into feature vector.
