# stock-short-term-trade-test
Simple short term trading algorithm. Key idea is buy dip when drawback to EMA21.
# Data source
Yahoo finance 5-year historical data. 
Make sure your data has more than 50 days record to calculate MA50.
# Other
Since Yahoo finance public data is limited (open, high, low, close), the algorithm is very rough. 
If there are more data like 2H chart, the algorithm could be fine tuned with more details.

# Realtime Trading History

I do the trades based on the fine grained strategy in my personal account with real money.

Experiment portfolio is initialized to $20,000

All the records are saved in "realtime_trading_log.csv", update weekly.
