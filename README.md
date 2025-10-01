# Cryptocurrency Price Prediction

This repository includes the code files for the MSc Data Science (FT) Project: Prediction of Cryptocurrency prices 


## Overview 

* The aim is to accurately predict the price of four cryptocurrencies (BTC, ETH, LTC, XRP) using three models: LSTM, CNN-LSTM, LSTM-HMM.


### Dataset 

The original dataset sourced from Kaggle was preprocessing to be used as an input for  the three models. 


### Models 

1. LSTM model
2. CNN-LSTM model
3. LSTM-HMM model


### Implementation 

Each model has 4 versions in the repository, one for each currency. The models' are tuned on the BTC dataset using Optuna (one in each model's folder). 

All three models were tuned, trained and tested. To run a model, ensure the dataset is in the directory, you have access to a NVIDIA A100 GPU (or similar compute). 


#### Results 


### Bitcoin Results  

| Model     | MSE      | RMSE     | MAE      | MAPE    | R²     |
|-----------|----------|----------|----------|---------|--------|
| LSTM      | 0.002137 | 0.043395 | 0.03236  | 0.1045  | 0.4939 |
| CNN-LSTM  | 0.006940 | 0.082860 | 0.06990  | 0.2246  | 0.4671 |
| LSTM-HMM  | 0.000280 | 0.016790 | 0.01211  | 0.0409  | 0.9327 |

