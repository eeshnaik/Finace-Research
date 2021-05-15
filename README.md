# Finance-Research
A repository that features code written to conduct quantitative finance research. It is written in Python and uses yfinance API.

Features 4 files, each to calculate the below statistics for all current S&P 500 stocks:
1) CDaR Beta - Drawdown beta of a stock based on worst p% of market drawdowns
2) ERoD Beta - Drawdown beta of a stock based on all non-zero market drawdowns
3) Maximum Drawdown - Biggest percent drawdown of a stock in last 10 years
4) U-ratio - Mean daily return of a stock divided by the ratio of its average drawdown and average drawdown length
* Stocks with history < 10 years have estimated statistics

The betas can be used to set up CAPM problems to get optimal weights for a minimum variance portfolio
