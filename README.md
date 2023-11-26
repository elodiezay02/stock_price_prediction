# stock_price_prediction

## Description
This project is about forecasting stock market with the utilization of Long Short-Term Memory (LSTM) and Recurrent Neural Networks (RNN). Since the stock nature contains a huge amount of noise and using neural networks for the prediction of time series has become widespread and the power of neural networks is well known, I use RNN and LSTM (special type of RNN) models due to its memory property

The workflow is to the following:
1. Acquire daily close data 
2. Preprocess the data, then make the train-validation splits and the last proportion is used to forecast.
3. Use the neural network to learn from the training data.
4. Test the model with the validation set - this gives us a gauge of how good our model is
5. Try different hyperparameter values such as look back window, n_epochs, hidden_units, hidden_layers


## Limits
Although we can better use the data, here are some scope limits that I haven't yet done (but I try to carry out as soon as possible)
1. Only Close price is used for the trainning and forecasting process
2. The time interval is daily
3. Models built are only on FPT stock

## Future Work
1. Feature engineeing: vwap, sma, rolling volatilities, .....
2. Build models for all 4 stocks
3. Try other models maybe using ensembling method
4. Tuning hyperparameter with Grid/Random search
5. Try other time interval (hour/minute)
