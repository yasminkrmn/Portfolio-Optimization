# Portfolio-Optimization

## The Efficient Frontier

The Efficient Frontier is a concept in modern portfolio theory that describes a set of optimal portfolios that offer the highest expected return for a defined level of risk or the lowest risk for a given level of expected return.

The efficient frontier class you provided is an implementation of this concept using Python.

Here is a brief explanation of the class and its methods:

EfficientFrontier class: This is the main class that calculates the efficient frontier using the input parameters.

__init__ method: This method initializes the class with the required parameters tickers, start_date, finish_date, num_portfolios, and plot. It also loads the historical stock prices for the given tickers using the yfinance library.

get_returns method: This method calculates the daily returns for the selected stocks.

get_covariance method: This method calculates the covariance matrix for the selected stocks using the daily returns.

get_portfolios method: This method generates a specified number of random portfolios with random weights and calculates the expected returns, volatility, and Sharpe ratios for each portfolio.

get_max_sharpe_portfolio method: This method returns the portfolio with the highest Sharpe ratio.

get_min_volatility_portfolio method: This method returns the portfolio with the lowest volatility.

get_efficient_frontier method: This method calculates and returns a set of optimal portfolios that form the efficient frontier.

plot_efficient_frontier method: This method plots the efficient frontier using the expected returns and volatilities of the generated portfolios.

Result class: This class is used to store the results of the efficient frontier calculation. It contains the results_df, max_sharpe_port, and min_vol_port attributes.

__init__ method: This method initializes the class with the results_df, max_sharpe_port, and min_vol_port attributes.
