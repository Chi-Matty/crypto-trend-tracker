# crypto-trend-tracker
Automated Crypto Market Tracking Every 6 Hours from Yahoo Finance with Python

## Project Description
This project automates the extraction of real-time cryptocurrency data, including coin name, price, change, change percentage, and volume, from Yahoo Finance every 6 hours over a 3-day period. The goal is to track market behavior and spot short-term trends. The script uses Python libraries like requests, BeautifulSoup, pandas, and seaborn to scrape, store, and visualize the data in a structured CSV file for ongoing analysis.

### The collected data is then analyzed to:

Visualize price trends of top cryptocurrencies like Bitcoin, Ethereum, WETH, and Lido Staked ETH

Compare daily percentage changes across coins
Identify average change patterns and trading volumes

Analyze correlations between price, volume, and volatility

Discover mild positive correlation between price and volume (~0.26)

Reveal slight negative correlation between price and daily % change (~–0.15), suggesting higher-priced coins tend to show more stability
