# LSTM Stock Predictor

![deep-learning.jpg](Images/deep-learning.jpg)

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, you will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

You will need to:

- [LSTM Stock Predictor](#lstm-stock-predictor)
    - [Files](#files)
  - [Instructions](#instructions)
    - [Prepare the data for training and testing](#prepare-the-data-for-training-and-testing)
    - [Build and train custom LSTM RNNs](#build-and-train-custom-lstm-rnns)
    - [Evaluate the performance of each model](#evaluate-the-performance-of-each-model)
    - [Resources](#resources)

- - -

### Files

[Closing Prices Starter Notebook](Starter_Code/lstm_stock_predictor_closing.ipynb)

[FNG Starter Notebook](Starter_Code/lstm_stock_predictor_fng.ipynb)

- - -

## Summary

![FNG](https://user-images.githubusercontent.com/93293695/184510919-b747cbe3-4f76-4cdc-a2a0-9981c287673f.PNG)

![CPM](https://user-images.githubusercontent.com/93293695/184510922-b336105e-ef25-40bf-9ecd-4e18325fa561.PNG)


- - -

### Resources

[Keras Sequential Model Guide](https://keras.io/getting-started/sequential-model-guide/)

[Illustrated Guide to LSTMs](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21)

[Stanford's RNN Cheatsheet](https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-recurrent-neural-networks)
