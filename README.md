# bokeh-stock-market

A live visualization of more than 7000 stock prices and indicators using bokeh.

## Stock visualization includes:

* Candlesticks-style with daily low, high, open and close.

* Bollinger bands (2 std).

## Stock indicators include:

* Simple Moving Average (aka SMA) (5 days, 10 days, 50 days and 100 days).

* Moving Average Convergence Divergence (aka MACD), including line + signal and histogram.

* Relative Strength Index (aka RSI), including graphic indications os oversold and overbought.

* On-Balance Volume (aka OBV).

## To run:
Go to https://iexcloud.io/, sign up for a free account to get the required API token.

Rename `config-sample.json` to `config.json` and put the API token in the `config.json` file.

Run `pip install -r requirements.txt` to install all the required python packages to run the program.

Run `bokeh serve run.py`

## Some notes:

Data provided by [IEX Cloud](https://iexcloud.io/).

This software is experimental, don't go around spending your savings with it.

If you see a bug (as if that's possible!) or have any question please submit an issue.

If you improve the code please consider a pull request. 

## Screenshot:

![Screenshot](screenshot.png?raw=true "Title")
