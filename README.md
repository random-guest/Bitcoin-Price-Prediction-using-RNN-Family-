# We have one Model, and 4 different Dataset

# Model 1: LSTM with Historical Bitcoin Data 

For running this model, simply download its jupter notebook, and run it.

# Model 1: LSTM with Historical Bitcoin Data and 5 Technical Indicators

For running this model, simply download its jupter notebook, and run it.

# Model 1: LSTM with Historical Bitcoin Data, 5 Technical Indicators, and Bitcoin Tweets Analysis

For running this model, you need the .csv file that has all of these data together.
You can find it in the relative folder, histo_TI_bitcoin_tweet.csv.
This file was formed by:

1. Extracting 21 k tweets from 2021-01-01 to 2202-07-01, cleaning them.
2.  getting their subjectivity and Polarity Scores
3.  Grouping them by their means to a daily format, to match that of historical bitcoin price, then finally were merged all together. 

This work was done using two helper notebooks, Get_raw_Tweets.ipynb and preprocess_raw_tweets_.ipynb.

Therefore, to run this model:

1. Download histo_TI_bitcoin_tweet.csv and Final_LSTM_historical_Data_and_TI_Bitcoin_tweets.ipynb
2. open jupternotebook, upload this .csv there, and run the Final_LSTM_historical_Data_and_TI_Bitcoin_tweets.ipynb


# Model 1: LSTM with Historical Bitcoin Data, 5 Technical Indicators, Bitcoin Tweets Analysis, and Russia-Ukraine War tweets Analysis

The same applies here. 
for running this model, download LSTM_historical_Data_and_TI_Bitcoin_Russia_Ukraine_tweets.ipynb and histo_TI_bitcoin_russia_Ukraine_tweet.csv file, that contains:
1. Historical prices of bitcoin
2. Technical Indicators data
3. Bitcoin tweets analysis data
4. Russia - Ukraine War tweets analysis data

Open jupyternotebook, upload the csv file to the local environment and run the code.

# Results Analysis
As we noticed from adding the Russia-Ukraine war tweets analysis, the model performance was improved, therefore, we can conclude that the bitcoin prices was affected by the Russia-Ukraine War. 

