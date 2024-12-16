Comparing RNN and LSTM for Predicting Apple Stock Price 

Project was carried out by Connor Rippert

**Project Description:**

This project compares two deep learning architectures—Recurrent Neural Networks (RNNs) and Long Short-Term Memory networks (LSTMs)—for predicting stock prices. Both models are well-suited for sequential data, making them an ideal choice for financial time series forecasting.

In this case, historical stock price data for Apple Inc. (AAPL) is used to train both models. The dataset is divided into training and testing sets, and the closing price is normalized for better model performance. Using a 60-day lookback period, the models are trained to predict the next day's closing price.

The project involves:

Fetching historical stock price data from Yahoo Finance.
Preprocessing the data to create time-series input-output pairs.
Building and training both RNN and LSTM models.
Comparing their performance by visualizing training loss and evaluating predictions on unseen test data.
Calculating and visualizing evaluation metrics, specifically Mean Squared Error (MSE), for both models.
Finally, a bar chart illustrates the comparison of MSE for training and testing data, providing insights into the relative strengths and weaknesses of RNNs and LSTMs for this financial forecasting task.

**Resources:**

This project was carried out with the help of the following sources: 

1. Recurrent Neural Networks (RNN) - Deep Learning w/ Python, TensorFlow & Keras p.7, https://www.youtube.com/watch?v=BSpXCRTOLJA
2. https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/
3. ChatGPT
