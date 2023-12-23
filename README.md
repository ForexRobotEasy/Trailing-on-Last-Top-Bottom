# Trailing on Last Top Bottom

**Description:** This code is a custom indicator developed by the Forex Robot Easy Team. It is designed to trail the last top and bottom values of a currency pair and execute buy and sell orders based on specified conditions.

**Functionality:**

- The indicator initializes by defining input parameters such as the timeframe, trailing stop value, and lot size.
- It also sets up global variables to keep track of the last top and bottom values, as well as the bars where they occur.
- The `OnInit()` function sets up the indicator buffers and labels for visualization on the chart.
- The `OnCalculate()` function is called for every new bar and updates the last top and bottom values based on the highest and lowest price levels.
- It also checks for trigger conditions to open or close buy and sell orders.
- The `OpenBuyOrder()` and `OpenSellOrder()` functions are called to open new buy and sell orders respectively.
- The `CloseBuyOrder()` and `CloseSellOrder()` functions are called to close existing buy and sell orders respectively.

**Usage:**

1. Define the desired input parameters such as timeframe, trailing stop value, and lot size.
2. Attach the indicator to the desired chart.
3. The indicator will track the last top and bottom values and execute buy and sell orders according to the specified conditions.

**Disclaimer:**

This code is not an official product of Forex Robot Easy. It is provided as a sample code that can work as described in the product review available at [Forex Robot Easy - Trailing on Last Top Bottom Review](https://forexroboteasy.com/forex-robot-review/trailing-on-last-top-bottom-unbiased-forex-software-review/). To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/).
