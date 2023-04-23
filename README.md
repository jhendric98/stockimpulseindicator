# Stock Impulse and ATR Indicator

This Python script fetches stock data, calculates the Average True Range (ATR), detects impulses based on price change, and plots the stock's closing price, ATR, and impulses. The impulse detection is designed to identify sudden changes in stock prices driven by events or news.

## Requirements
To run this script, you need Python 3.x and the following libraries:

- pandas
- yfinance
- matplotlib

To install these libraries, run:

```
pip install pandas yfinance matplotlib
```

## Usage

1. Open the script stock_impulse_atr_indicator.py in your favorite code editor or IDE.
2. Customize the script by changing the ticker variable to the stock symbol of your choice.
3. Adjust the price_change_threshold variable to set the percentage change threshold for impulse detection.
4. Update the date range for the stock data by modifying the start and end parameters in the yf.download() function.

Run the script:

```
python stock_impulse_atr_indicator.py
```
The script will fetch the stock data, perform the calculations, and plot the closing price, ATR, and impulses on a chart.

## Customization

The script can be customized by modifying the following variables:

- **ticker:** Set this variable to the stock symbol you want to analyze (e.g., 'AAPL', 'GOOGL', 'MSFT').
- **price_change_threshold:** Set this variable to the desired percentage change threshold for impulse detection.
- **atr_period:** Set the period used for calculating the Average True Range (default is 14).

Additionally, you can update the date range for the stock data by modifying the start and end parameters in the yf.download() function.

