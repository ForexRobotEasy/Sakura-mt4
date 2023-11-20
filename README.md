# Sakura MT4 Code ReadMe

**Developer**: Forex Robot Easy Team  
**Developer's Site**: [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-sakura-mt4-forex-software-a-safe-and-effective-trading-tool/) (For detailed reviews and trading results of this product)

**Note**: ForexRobotEasy is not the official developer of this product. We only show sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Overview
This code represents a custom breakout strategy implemented in the Sakura MT4 Expert Advisor. The strategy aims to capture potential price movements that occur after a breakout of the day's high or low. It incorporates risk management techniques, such as setting stop loss and take profit levels based on the breakout range and calculating position size based on a specified risk percentage.

## Strategy Description
The breakout strategy implemented in this code follows the steps outlined below:

1. Get the current day's high and low.
2. Calculate the breakout range as the difference between the day's high and low.
3. Calculate the stop loss and take profit levels based on the breakout range and user-defined percentage inputs.
4. Calculate the position size based on the selected risk level and the calculated stop loss.
5. Check if the spread is within the allowed range.
6. Check if there are any high-impact news events based on the user-defined impact level.
7. Open a buy position at the breakout of the day's high and a sell position at the breakout of the day's low.
8. Check if the orders were successfully opened.

## Parameters
The code includes the following user-defined parameters:

- **RiskPercentage**: Risk percentage per trade.
- **StopLossPercentage**: Stop loss percentage of the breakout range.
- **TakeProfitPercentage**: Take profit percentage of the breakout range.
- **MaxSpread**: Maximum allowed spread in points.
- **NewsImpactLevel**: Minimum impact level of news to block orders.

## Usage
To use this code, follow these steps:

1. Set the desired values for the user-defined parameters.
2. Compile and attach the Expert Advisor to a chart in the MT4 platform.
3. The Expert Advisor will execute the breakout strategy on each tick, considering the risk management rules and news impacts.

## Backlink and Product Description
For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-sakura-mt4-forex-software-a-safe-and-effective-trading-tool/).

**Note**: ForexRobotEasy is not the official developer of this product. We only show sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
