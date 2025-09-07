# MACD Indicator Calculator

A clean Python implementation of the MACD technical indicator, used by traders to identify market 
momentum and potential buy/sell signals.

## What is MACD?

The MACD is a trend-following momentum indicator that shows the relationship between two exponential moving averages (EMAs) of a security's price. It consists of three parts:
- MACD Line: (12-period EMA - 26-period EMA)
- Signal Line: 9-period EMA of the MACD Line
- Histogram: MACD Line - Signal Line

# The Logic Behind MACD
- - The MACD Line: This is the core of the indicator. It is calculated by subtracting the 26-period Exponential Moving
  Moving Average (EMA) from the 12-period EMA
  Example: MACD Line = 12-Period EMA - 26-Period EMA
- - The Signal Line: This is a 9-period EMA of the MACD Line itself. It acts as a trigger for buy and sell signals.
  Example: Signal Line = 9-Period EMA of the MACD Line
- - The Histogram: This represents the difference between the MACD Line and the Signal Line. It shows the momentum behind a move
  Example:  Histogram = MACD Line - Signal Line

# How Trader Use it:
Buy Signal: When the MACD Line crosses above the Signal Line.

Sell Signal: When the MACD Line crosses below the Signal Line.

The Histogram helps visualize the strength of the trend. A growing histogram means the trend is getting stronger.


## Note
This code is for **educational purposes** only. Always do your own research before making any investment decisions.
