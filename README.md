# Risk-Return
Using pandas to calculate and compare the profitability and risk of different investments using the Sharpe Ratio:

# About

This program first imports the pandas library, which is a powerful library for working with data in Python. It then defines a function called calculate_sharpe_ratio that takes in a series of returns and a risk-free rate and calculates the Sharpe ratio for those returns.
Next, it defines a function called compare_investments that takes in a list of tickers and a risk-free rate. It loads the stock data for each ticker using the pandas read_csv function and calculates the returns for each ticker. It then calculates the Sharpe ratio for each ticker using the calculate_sharpe_ratio function.
Finally, it sorts the Sharpe ratios in descending order and prints the results.
To use this program, you will need to have the stock data for each ticker in a CSV file with the same name as the ticker (e.g., "AAPL.csv", "GOOG.csv", etc.). The CSV files should have a column called "Adj Close" that contains the adjusted closing price for each day.
