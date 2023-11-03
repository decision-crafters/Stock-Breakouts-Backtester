# Python Backtesteer for Stock Breakouts
The Colab Notebook contains the function I developed for coding the profitability of breakout setups for a given stock in its entire history. The source for the stock data is Yahoo Finance and was scraped using the `yahoo-fin` open-source library. The output of the function is a histogram for the breakout profits and some trading probabilities. 

## Sample Output
Using my `breakout_profitability(ticker)` function, here the output for Apple Inc. (ticker = AAPL):

![image](https://github.com/marvin-rubia/Stock-Breakouts-Backtester/assets/140475770/1641ce40-5e1c-479e-94da-36db5122faa4)

In addition to this chart, the function also outputs supplementary information:
"Additional Info: The first breakout for AAPL was observed on 1982-10-06 while the most recent breakout was on 2022-10-28. The average positive profit is 17.42% while the average negative profit (from false breakouts) is -6.16%."
