
# Bitcoin Price Prediction using LSTM

This project aims to predict the future price of Bitcoin using Long Short-Term Memory (LSTM), a type of recurrent neural network (RNN), which is well-suited for time-series data.

### Overview
Bitcoin has emerged as a popular cryptocurrency, and its price movements attract significant attention from investors and traders. Predicting Bitcoin prices accurately can be challenging due to the volatile nature of the cryptocurrency market. This project utilizes LSTM models, a type of deep learning architecture, to forecast Bitcoin prices based on historical data.

### Key Features
* Data Acquisition:

    Collect historical Bitcoin price data from a reliable source such as Yahoo Finance using web scraping techniques.
* Data Preprocessing:

    Clean, scale, and structure the raw data into appropriate input-output pairs for training the LSTM model.
* Model Building:

    Construct an LSTM model using the TensorFlow Keras API, comprising input, LSTM, dropout, and dense layers to learn and predict Bitcoin prices.
* Model Training:

    Train the LSTM model on the prepared data, optimizing it to minimize the mean squared error loss and prevent overfitting using dropout regularization and early stopping.
* Evaluation:

    Evaluate the trained model's performance on a separate test set to assess its ability to generalize to unseen data.
* Visualization:

    Visualize the predicted Bitcoin prices against the actual prices using Matplotlib, providing insights into the model's performance.
* Prediction for Tomorrow:

    Predict the Bitcoin price for tomorrow using the trained LSTM model, enabling forecast future price trends.



## Badges


![Deep Learning](https://img.shields.io/badge/Deep%20Learning-purple.svg)
![Python](https://img.shields.io/badge/python-green.svg)![Web Scraping](https://img.shields.io/badge/Web-Scraping-blue.svg)