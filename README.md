# LSTM Stock Predictor

![deep-learning.jpg](Images/deep-learning.jpg)

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. 

I built and evaluated deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, I used deep learning recurrent neural networks to model bitcoin closing prices. One model uses the FNG indicators to predict the closing price while the second model used a window of closing prices to predict the nth closing price.

List of Action Items Completed:

1. [Prepared the data for training and testing](#prepare-the-data-for-training-and-testing)
2. [Built and trained custom LSTM RNNs](#build-and-train-custom-lstm-rnns)
3. [Evaluated the performance of each model](#evaluate-the-performance-of-each-model)

- - -
