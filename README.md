## Stock_Prediction

# Overview/Business Problem
Many investors would like to predict the movement of stock prices in order to make informed investment decisions regarding when to buy, sell or hold a stock. Additionally, stock price prediction can help with a portfolio’s risk management by assessing potential stock price movements and implementing strategies to mitigate potential fluctuation risks. Finally, stock price prediction can be invaluable in market analysis/research, allowing investors to understand the financial market, including trends, volatility patterns and other factors that may affect stock prices.

# Solution
* Obtain our data source
* Explore our data source and learn out about it
* Clean our data if necessary
* Visualize our data source
* Create a model–Regression
* Train our model–separating training and test 
* Evaluate our model


# Data
Initial data contained data on 2,853 trading days for Ambarella, Inc (AMBA) between 2012-10-11 and 2024-02-15.
Column Names and descriptions for AMBA Data Set:
* date - Date that the trading of AMBA took place
* open price - Price of the house ( prediction target )
* close price - Close price adjusted for splits
* high - Highest price sold on the trade date
* low - Lowest price sold on the trade date
* Adjusted close - Adjusted close price adjusted for splits and dividend and/or capital gain distributions.
* volume - Volume of shares sold 

* My data source came from Yahoo finance. Prices marked are in USD.

* The data appears quite clean with no null values

* Data types found in 7 columns are: float64(5), int64(1), object(1)
