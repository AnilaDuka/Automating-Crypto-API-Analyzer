# Crypto Trend Analyzer

A Python project to collect, store, and visualize real-time cryptocurrency performance data using the CoinMarketCap API. The project analyzes percent changes over different timeframes and displays trends using clear visualizations.

## Features

- Fetches live cryptocurrency data from CoinMarketCap API
- Stores historical data automatically in a CSV file
- Calculates average percent change over multiple timeframes (1h, 24h, 7d, 30d, 60d, 90d)
- Visualizes trends across top 15 cryptocurrencies using Seaborn

## How it Works

1. **Data Collection**  
   Retrieves the latest cryptocurrency listings and percent changes for the top 15 coins.

2. **Data Analysis & Visualization**  
   Calculates average percent changes and visualizes them across different timeframes.

## Technologies

- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib
- CoinMarketCap API
