# COVID-Stock-Correlation
This webapp finds the correlation between COVID cases in a state and a stock price

Users input a stock ticker symbol and a state abbreviation and the backend will make a request via yfinance to get the data.  This app then uses pandas to get the pearson, kendall, and spearman correlations and displays it on the bottom of the webpage
