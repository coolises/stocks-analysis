# stocks-analysis
Stocks analysis using python packages

## Jupyter notebooks
### [yf_ta_part1](yf_ta_part1.ipynb)
This notebook plots the following stock charts:
1. Price and Volume charts
2. Price, SMA, and EMA charts
4. Price, SMA-50, and SMA-200 charts

_yf_ta_part1.properties_ under _config_ folder has the following parameters that you can configure to pass to the notebook:
- TICKER - Ticker symbol, e.g., MSFT, this must be a ticker symbol
- START - start date, e.g. 2021-01-01. This property needs to be adjusted for a ticker as some of them may not have older data
- TEMPLATE - template for display, it must be one of plotly's template types, e.g. plotly_dark, check [Theming and templates in Python](https://plotly.com/python/templates/) for other templates
- TICKERS  -  list of similar stocks to compare performance. You can also add an index such as Nasdaq 100 (^NDX) to the list


Stock Technical Analysis uses the following main packages:
- yfinance - reading stocks data
- TA Lib - Technical Analysis, e.g., SMA, EMA calculations
- plotly - plotting graphs
- jproperties - reading the property file
- pandas - date utilities

An example of a chart showing Price and Volume:![newplot (4)](https://github.com/smudali/stocks-analysis/assets/30547825/69aa318a-c6cf-4516-9060-17eb8522d749)

## Medium Article
- [Plot Moving Averages using Python APIs](https://medium.com/@sugath.mudali/plot-moving-averages-using-python-apis-9a313b2b75ae)

### [yf_ta_part2](yf_ta_part2.ipynb)
This notebook plots the following stock charts:
1. Candlestick
2. RSI and Volume
3. Bollinger Bands
4. MACD

## Medium Article
See [Plot Candlestick, RSI, Bollinger Bands, and MACD charts using yfinance Python API](https://medium.com/@sugath.mudali/plot-candlestick-rsi-bollinger-bands-and-macd-charts-using-yfinance-python-api-1c2cb182d147)

### [av_insert_earnings](av_insert_earnings.ipynb)
This notebook inserts Earnings data into MongoDB Atlas database

## Medium Article
- [Company Earnings and Income Dashboards with MongoDB and Alpha Vantage API]()

### [av_insert_income_statements](av_insert_income_statements.ipynb)
## Medium Article
- [Company Earnings and Income Dashboards with MongoDB and Alpha Vantage API]()

