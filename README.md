# Order Block Indicator MT5

This is a custom indicator developed for MetaTrader 5 platform. The indicator is designed to identify potential accumulation of orders in one area, known as an order block. The indicator calculates relevant levels based on candle properties and prints them for debugging purposes.

## Indicator Properties

- **Wick Level**: The highest or lowest price level of the candle's wick, depending on whether the candle is bullish or bearish.
- **Body Level**: The closing price of the candle.
- **50% Level**: The average of the high and low prices of the candle.

## Indicator Functions

- **OrderBlockIndicator()**: This function calculates the levels based on candle properties and prints them for debugging purposes.
- **CandleIsBullish()**: This function checks if the current candle is bullish.
- **CandleIsBearish()**: This function checks if the current candle is bearish.

## Initialization and Deinitialization Functions

- **OnInit()**: This function is called during indicator initialization and sets indicator properties.
- **OnDeinit(const int reason)**: This function is called during indicator deinitialization and can be used to clean up resources.

## Calculation Function

- **OnCalculate()**: This function is called on each tick and calls the OrderBlockIndicator function.

## Backlink

This code was developed by [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/order-block-indicator-mt5-review-accurate-forex-tool/).
