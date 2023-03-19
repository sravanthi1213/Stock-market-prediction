# Stock-market-prediction
Stock market data can be interesting to analyze and as a further incentive, strong predictive models can have large financial payoff. The amount of financial data on the web is seemingly endless.
A large and well structured dataset on a wide array of companies can be hard to come by. Here I provide a dataset with historical stock prices (last 5 years) for all companies currently found on the S&P 500 index.
The script I used to acquire all of these .csv files can be found in this GitHub repository In the future if you wish for a more up to date dataset, this can be used to acquire new versions of the .csv files.
The data is presented in a couple of formats to suit different individual's needs or computational limitations. I have included files containing 5 years of stock data (in the stocks.csv).

   ## Data

   We'll download all of the data during the project, using the `yfinance` package. 

**Project Steps**
* Download data using the yfinance package
* Create an initial machine learning model and estimate accuracy
* Build a backtesting engine to more accurately measure accuracy
* Improve the accuracy of the model

