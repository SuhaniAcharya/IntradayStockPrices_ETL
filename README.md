Intraday Stock Price Database

This project builds an end-to-end system to fetch, store, and analyze intraday stock prices using Python and SQL. It integrates with the Alpha Vantage API
, stores structured data in an SQLite database, and provides tools for querying and visualizing stock price movements.

Features:
  Fetch intraday stock data for multiple tickers from Alpha Vantage API.
  Automated data cleaning and transformation with Pandas.
  Incremental updates to database (avoids duplicate entries).
  SQL schema designed for efficient queries on stock data.
  Query historical ranges by ticker and timestamp.
  Visualization of price trends using Matplotlib.

Tech Stack:
  Python – Core programming
  Pandas – Data manipulation and cleaning
  Requests – API calls
  SQLite – Database for storing stock data
  SQL – Data querying
  Matplotlib – Data visualization
