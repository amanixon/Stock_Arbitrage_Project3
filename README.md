# Detection of Statistical Arbitrage using Machine Learning Techniques in NYSE: AI Stocks
## Project Overview:
* The goal of this project is to deploy machine learning models to detect statistical arbitrage opportunities in the New York Stock Exchange (NYSE). By leveraging machine learning techniques, we aim to identify patterns and signals that can indicate potential arbitrage opportunities in NYSE-listed stocks. We will utilize regression and time delay neural network techniques for our analysis.


## Procedure:
* Analysis of AI Computer sector stocks using regression to model an index.
* Assessment of the index's correlation with the target stock (NVIDIA Corp).
* Prediction of market price based on historical data.
  
## Project Phases:
* Pick an Asset: NVDA
* Component stock: SMCI
* Historical Data API: 2015-2024: use their daily returns
* Develop a trading algorithm based on multiple regression models:
    * Ordinary Least Squares(OLS):  Series Models for Volatility Forecasts and Statistical Arbitrage linear model and inference and prediction
    * Vector Autoregression(VAR): Prepare the data by combining the adjusted close prices of both stocks into a single data frame. Then, we can use the VAR model from the statsmodels library to fit the model and make predictions
    * Pairs Trading Model: Take long and short positions in the two securities based on deviations from their historical relationship. When one security deviates from the other, the model enters a trade with the expectation that the prices will converge.
    *  Actual Returns vs Strategy Returns: Assess the accuracy of your forecasts by comparing them to the actual values in your test dataset using Mean Absolute Error (MAE) 




## Future Work:
* Increase the level of accuracy between the target and component stock.
* Add more component stocks:  MFST, GOOGL, META, AMD, MRVL, AVGO, ANET, ALAB, AAPL, AMZN, PLTR, INTC, SOUN


## Dataset and Source Code:
* Data obtained from the NASDAQ Historical Data section.
* Source code for neural network obtained from Matlab Neural Network Toolbox.


## References:
* https://www.macrotrends.net/stocks/research
* https://www.nasdaq.com/market-activity/quotes/historical
* https://www.mathworks.com/help/stats/neural-networks-for-classification.html





