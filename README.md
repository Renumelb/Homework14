# Homework14 Deep Learning

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. 

One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency.

Using deep learning models (Long Short-Term Memory Recurrent Neural Network), evalute the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data. 

Each model will be evaluated on test data (split between train and test- 70:30). We will repeat the process multiple times with different epoch and batch size numbers until we find a model with the best predictor. Then we will use the model to make predictions and compare these to actual values.

# Deep learning model set up and execution steps for each i.e. FNG Index and Closing prices in tweo separate notebooks.
- Prepare the data for training and testing
- Build and train a custom LSTM RNN
- Evaluate the performance of the model

# Conclusion
Based on the results of the two models, it appears that Closing prices are a far better indicator for predicting prices.

Which model has a lower loss?
Model using Closing prices has a lower loss

Which model tracks the actual values better over time?


Which window size works best for the model?


