# Module 4 Project - Stock Predictions

### Goals
- Predict ideal entry and exit points for trading securities
 - [Ichimoku Cloud](https://github.com/geomms/Mod4_Project/blob/master/Ichimoku%20Cloud.ipynb)
 - [Logistic Regression](https://github.com/geomms/Mod4_Project/blob/master/Logistic%20Regression%20Model.ipynb) 
- Forecast future prices
 - [SVR Model](https://github.com/geomms/Mod4_Project/blob/master/SVR%20Model.ipynb)
 - [ARIMA Model](https://github.com/geomms/Mod4_Project/blob/master/ARIMA%20Model.ipynb)
 - [Price Forecast](https://github.com/geomms/Mod4_Project/blob/master/Price%20Forecast.ipynb)

## Data used: Yahoo Finance library to pull stock data

## Project Objective:
- Forecast prices for better trades
- If forecasting is not accurate, predict entries and exits or long and short positions

### Metrics Used:
- Cross validation score mean

### Methods Used
* Statistics
* Data Cleaning
* Data Organizing/Exploring
* Feature Engineering
* Machine Learning
* Data Visualization
* Predictive Modeling
* Logistic Regression

### Solutions:
- Selecting the right features and checking score results of models
- Use noncolinear technical indicators to improve accuracy and reduce overfitting

#### Recommendations for further developments:
- More stocks to analyze
- Predict long/short positions closer to trade time vs. backtesting
  
## Project Findings:
- Using more features did not necessarily imporve the model
- Trying to forecast future prices was difficult
- More optimal to find long/short entries
- Model predicted 85% accuracy for short positions, 68% for long positions
- Features and models are better at choosing shorts rather than longs.

## Further Analysis
 - Improve accuracy for long entries
 - Build algorithm using predictions to execute trades
