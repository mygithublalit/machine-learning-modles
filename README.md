# machine-learning-modles

This is stock price predictor model using recurrent neural network algorithm (RNN) using long short term memory (LSTM). It used passed 60 days data to predict next day closing price. 

## steps follow to get model ready
1. import data from pandas dataset - yahoo source
2. plot the closing price of passed 10  years
3. normalizing data - transforming
4. splitting data into train and test  dataset test_size=20%
5.  x_train : last 60 days closing price, y_train = next day actual price
6.  reshape the data into right format as lstm required data in 3-D
7.  designed model using 2-LSTM and 2-Dense layer
8.  compile the model using adam(optimizer) and MSE(loss function)
9.  train the model
10. predict the model on validation dataset
11. again plot the training, validation, prediction data on graph
12. now predict for unknown dataset to generalize the result
