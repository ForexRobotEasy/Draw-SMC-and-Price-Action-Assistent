# Draw SMC and Price Action Assistant

This code is a trading robot that assists with drawing key elements on a price chart for Forex trading. It is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Global Variables

- `referenceCandle1`: User input for the reference candle 1.
- `referenceCandle2`: User input for the reference candle 2.
- `buyOrderColor`: Color of the Buy Order block.
- `sellOrderColor`: Color of the Sell Order block.
- `fairValueGapColor`: Color of the Fair Value Gap.
- `marketStructureColor`: Color of the Market Structure.
- `liquidityRegionColor`: Color of the Liquidity Region.

## OnTick()

This function is the main entry point of the trading robot. It is called on every tick of the price chart.

- Get the closing prices of the reference candles.
- Draw the Buy Order block using the `ObjectCreate` function, with the specified coordinates and color.
- Draw the Sell Order block using the `ObjectCreate` function, with the specified coordinates and color.
- Draw the Fair Value Gaps using the `ObjectCreate` function, with the specified coordinates and color.
- Draw the Market Structure (code not provided).
- Identify and highlight potential market liquidity regions (code not provided).
- Implement the rest of the trading logic.

## OnInit()

This function is called when the expert advisor is initialized. It is used to initialize necessary variables and settings.

## OnDeinit()

This function is called when the expert advisor is removed. It is used to clean up and release any resources used.

## OnStart()

This function is called when the expert advisor is started or restarted. It starts the execution of the trading robot.

- While the expert advisor is not stopped, call the `OnTick` function.
- Add a delay of 1000 milliseconds between each tick.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, you can visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/review-draw-smc-price-action-assistant-for-forex-trading/).
