# Bitcoin Price Prediction

This is a time series machine learning project for predicting Bitcoin closing price using historical price data.

The project uses Bitcoin price data from Yahoo Finance and builds a simple baseline model with Linear Regression.

## What I practiced

- Loading financial time series data
- Working with date-based data
- Creating lag features
- Time series train/test split
- Training a regression model
- Evaluating model performance
- Saving the trained model

## Tools used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- YFinance
- Joblib

 Model

- Linear Regression

## Features

The model uses the previous day closing price to predict the next closing price.

## Result

The model achieved a high R2 score because Bitcoin closing prices are strongly related from one day to the next.

## Files

- `main.ipynb`
- `bitcoin_price_model.pkl`

## Notes

This is a beginner-friendly time series forecasting project and part of my machine learning practice.
