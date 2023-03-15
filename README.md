# COVID-Stock-Correlation
This webapp finds the correlation between COVID cases in a state and a stock price

Users input a stock ticker symbol and a state abbreviation and the backend will make a request via yfinance to get the data.  This app then uses pandas to get the pearson, kendall, and spearman correlations and displays it on the bottom of the webpage

Initially, the website was hosted on AWS EC2 and used AWS S3 for storage, but later was taken down due to hosting costs. 

To run the app, you must install all libraries shown in data.py.  the python flask file needs to be started first to ensure the server works, but a major change needs to be done in the flask code, which queries AWS S3 (no longer used).  You can change the directory to be a local directory instead for both the writing data and reading data portions.

![Sample Correlation image](https://user-images.githubusercontent.com/98242285/225436622-89cec12b-10d0-40ea-8d55-dc9231d28986.png "Sample Correlation Image")
