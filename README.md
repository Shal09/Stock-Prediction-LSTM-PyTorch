# Stock-Prediction-LSTM-PyTorch

📈 Stock Price Prediction using LSTM 

**Project Overview**

This project implements a Long Short-Term Memory (LSTM) neural network using PyTorch to predict Microsoft (MSFT) stock prices. The model is trained on historical stock data and aims to forecast future stock prices based on past trends.

**Requirements**

Python 3.7+,
PyTorch,
pandas,
numpy,
matplotlib,
scikit-learn,

Steps for MSFT Stock Price Prediction using LSTM

**Data Collection**

Import libraries and set up Tiingo API.
Download MSFT stock data and save it as a CSV file.

**Data Preprocessing**

Clean data: Remove irrelevant columns.
Convert string prices to float and rename columns.

**Feature Engineering**

Create date index and lagged features 
Drop NaN values and split into features (X) and target (y).

**Data Scaling**

Scale features and target to range (-1, 1) using MinMaxScaler.
Save scalers for inverse transformation.

**Data Splitting**

Split data into train and test
Reshape data for LSTM and convert to PyTorch tensors.

**Model Creation**

Define and initialize LSTM.
Set up loss function and optimizer.

**Training Loop**

Train model using 
Save the best model.

**Prediction**

predict the next 2 days.
Inverse transform predictions back to original price scale.

**Visualization**
Plot actual vs predicted values
Plot final predictions visualization step

**📈 Results**

After training, the LSTM model will generate predictions for future stock prices. 

