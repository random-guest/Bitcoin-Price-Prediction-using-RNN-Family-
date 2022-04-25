# Term Project: Bitcoin Price Prediction
-------------------------------------------------
This repo is meant to keep track of the progress of completing the term project.
The data that will be used is attached.
The data is in the form of Open-High-Low-Close-Volume data-type for Bitcoin prices between 2013 and 2021.

# Updates/Comments
--------------------------------------------------------
1. The tunned version of the first model, which pure LSTM was completed and uploaded. The MAE dropped from 1502 to 776, while the RMSE dropped from 3403 to 1564.
The result is still to be improved. 

The following models were implemented, but not tunned yet. Tunning these models will be the last step, before getting the best out of them and start writing the report:

2. The second model is GRU:
3. The third model is Bidirectional LSTM:
4. The fourth model is Bidirectional GRU:
5. The fifth model is 1D-Convolutional-Bidirectional-GRU:
6. The sixth model is 1D-Convolutional-Bidirectional-LSTM:


# Critical note
------------------------------------------------------
* The models fails to predict sudden change in the price using only LSTM network.
