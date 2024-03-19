# MACD Divergence Tester MT5

This is a code for an Expert Advisor (EA) that scans the forex market for potential trading opportunities based on MACD (Moving Average Convergence Divergence) divergence. It is designed to be used with MetaTrader 5 (MT5) trading platform.

## Product Description

The MACD Divergence Tester MT5 is a powerful tool for forex traders who want to automate their trading strategies. It scans multiple currency pairs and timeframes in real-time to identify potential trading opportunities based on MACD divergence.

MACD is a popular technical indicator used by traders to identify trend reversals and momentum shifts in the market. It consists of three components: the MACD line, the signal line, and the histogram. When the MACD histogram crosses above or below the zero line, it indicates a potential trend reversal.

The MACD Divergence Tester MT5 takes advantage of this concept by scanning for instances where the MACD histogram changes direction from positive to negative or vice versa. When this divergence occurs, it generates a trading signal to buy or sell the currency pair.

Key Features:
- Real-time scanning: The EA scans multiple currency pairs and timeframes in real-time to identify trading opportunities.
- Customizable parameters: Traders can adjust the MACD parameters and other trading preferences to suit their trading strategies.
- One-click trading: The EA automatically executes trades based on the identified MACD divergence signals.
- Backtesting: Traders can test the code and verify its reliability by running backtests.

ForexRobotEasy is not the official developer of this product. We only provide sample code that can work as described in the product. To find the official developer of this product, please refer to the MQL5 website.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/macd-divergence-tester-mt5-review-one-click-forex-scanning/).

## How It Works

1. The EA initializes by enabling real-time scanning for all symbols and timeframes.
2. On each tick, the EA loops through all symbols and timeframes.
3. For each symbol and timeframe, the EA calculates the MACD indicator values using the `iMACD` function.
4. The MACD values are then checked for divergence. If the MACD histogram changes from positive to negative, a buy signal is generated. If it changes from negative to positive, a sell signal is generated.
5. The trade is executed using the `CTrade` object, with the appropriate symbol, volume, and order type.
6. The process continues for all symbols and timeframes.
7. Customizable scanning parameters can be adjusted in the `OnDeinit` function.
8. The code can be tested and verified using the `OnTester` function.

Please note that this code is provided as an example and should be thoroughly tested and customized before using it in live trading.
