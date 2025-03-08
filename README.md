# NVDA-stock-trend-analysis
This project analyzes the 5-year stock trend of NVIDIA Corporation (NVDA) using historical stock price data. The analysis aims to identify patterns, trends, and key insights that can help investors and analysts understand NVDA's stock movement over time.

# Data Sources
* The dataset used for this analysis is based on historical stock price data for NVDA.
* Data may be sourced from Yahoo Finance, Alpha Vantage, or other financial APIs.
* The dataset typically includes:
  * Date
  * Open Price
  * Close Price
  * High
  * Low
  * Volume

 # Closing Price visualization
 ![5bbab1c702562d414d6541a874b86bb](https://github.com/user-attachments/assets/33753978-d6d9-453d-b9a4-6bce687ef317)
 This plot shows NVIDIA Stock Close Price Trends within 5 years. It is so obvious the price starts growing rapidly after Year 2023. 

 # Closing Price moving Averages
 ![41345e426a5b376f4e5717385d2f20a](https://github.com/user-attachments/assets/6912a92d-23f2-4f3b-b030-bf6348f0c5d8)
Moving average is crucial in stock trend analysis because it can help traders identify trends and remove noise. 
This plot shows 50 days SMA and 100 days EMA. 
The difference between SMA and EMA is: 
* SMA gives equal weight to all data points.
* EMA gives more weight to recent data points.

# Cumulative returns over five years
![e395f95ac5c1c55e93c6b8de358b826](https://github.com/user-attachments/assets/d5d0fd78-81a0-49f1-8f0a-d36f0d585820)
To evaluate long-term performance, we need Cumulative returns which helps investors see how a stock performs for an extended period. 
My next step is to compare NVIDA with S&P500 and Nasdaq to determine if NVDIA is standout in the market. 

# Daily returns
![bc9a7eb6fa9a9ea1d7bc27e17c8b6e8](https://github.com/user-attachments/assets/ab111235-23aa-4203-95cd-65712a744cfe)
To measure volatility and risk, we need daily returns plot. Large fluctuations indicate higher volatility and high volatility means greater potential for profit&loss. 
Also, for short-term trading, we can use daily returns as a strong support. 

# Volatility over 5 years
![545486979457e7f98eca783c06c6f44](https://github.com/user-attachments/assets/7b851e6d-e61a-45e3-b792-a72482bdc44b)
Compared with daily returns for short term, I plot a 30-day rolling volatility over 5 years to show potential trade operations for long term. 

# NVIDIA Stock Price with Bollinger Bands
![88e620ef5eec6ff7cff60df2b9853c2](https://github.com/user-attachments/assets/17ebc05d-02d9-41b2-a270-1547b614b8a2)
To identify Overbought&Oversold conditions, I build Bollinger Bands plot. 
* When the price touches or exceeds the upper band, the stock is considered overbought, meaning it may be due for a pullback.
* When the price touches or falls below the lower band, the stock is oversold, suggesting a potential buying opportunity.
For early 2020 to 2023, Bollinger Bands remain stable.
For mid 2023 to 2024, there is an obvious strong uptrend where the price touches upper band rapidly.
For late 2024 to 2025, the increasing volatility shows market uncertainty and potential correlations. 

# Suggestions
* For Bollinger Bands, NVDIA stock is currently in an overbought zone, it indicates the price may pull back. Because of high volatility, a price swings could occur soon.
* For moving averages, NVDIA has an execllent performance for long-run but we should wait until the price dropping near 50-day SMA.
* For short-term traders, I can see several peaks from 2023 to 2025 like March-April, June-July. Maybe it is a good point to buy some and sell it pretty quick once the price goes higher. 



