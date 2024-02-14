# Gold Mini Breakout MT4

This code is a sample implementation of the Gold Mini Breakout trading strategy for the MT4 platform. It is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Strategy Overview

The Gold Mini Breakout strategy aims to identify breakouts in the price range of gold and take advantage of potential trends. It uses moving averages, range breakout, average true range (ATR), and customizable trading strategies like grid and martingale.

## Functions

### MovingAverage(int period, int shift, int price)

This function calculates the moving average of a given price for a specified period and shift. It returns the moving average value.

### RangeBreakout(double range)

This function checks if the current price breaks the range of the highest and lowest prices. It returns true if the range is broken, otherwise false.

### AverageTrueRange(int period)

This function calculates the average true range for a specified period. It returns the average true range value.

### OpenPosition(int type, double volume)

This function opens a trading position based on the specified type (OP_BUY or OP_SELL) and volume. It sends an order to the market.

### ClosePosition()

This function closes all open positions by iterating through the orders and closing them individually.

### CustomizeStrategy(bool grid, bool martingale)

This function allows customization of the trading strategy by activating or deactivating the grid and martingale strategies. The logic for the grid and martingale strategies should be implemented within this function.

### ActivateStrategies(bool grid, bool martingale)

This function activates or deactivates the grid and martingale strategies based on the provided parameters.

## Usage

To use this code, follow these steps:

1. Install the MT4 platform and open it.
2. Create a new Expert Advisor (EA) and copy this code into the EA.
3. Customize the strategy by activating or deactivating the grid and martingale strategies using the `ActivateStrategies` function.
4. Test the code on the MT4 platform to ensure compatibility and functionality.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, use MQL5.

For detailed reviews and trading results of this product, visit the [product review page](https://forexroboteasy.com/forex-robot-review/gold-mini-breakout-mt4-review-risky-grid-martingale-strategy/).
