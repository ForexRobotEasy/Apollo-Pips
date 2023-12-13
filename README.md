# Apollo Pips Indicator

This is a custom indicator called Apollo Pips, developed by the Forex Robot Easy Team. It is designed to provide reliable forex signals for the H1 time frame. The indicator generates arrow signals on the chart to indicate potential trading opportunities.

## Indicator Inputs

- `ArrowBuffer[]`: Buffer to store arrow signals
- `prevBar`: Previous bar index

## Indicator Properties

- `indicator_chart_window`: Indicator is displayed on the chart window
- `indicator_buffers 1`: Indicator has 1 buffer
- `indicator_color1 Green`: Indicator color is set to green

## Custom Indicator Initialization Function

The `OnInit()` function is responsible for initializing the indicator. It sets the indicator properties, such as the buffer, style, arrow type, empty value, and label. It also sets the time frame to H1.

## Custom Indicator Iteration Function

The `OnCalculate()` function is the main iteration function of the indicator. It is called for each new bar on the chart. It checks for signal confirmation and generates arrow signals accordingly. If a signal is confirmed, the arrow is displayed above the high of the bar. If there is no signal, the buffer value is set to zero.

## Signal Confirmation Function

The `IsSignalConfirmed()` function is used to check if a signal is confirmed. This function should be customized with the specific signal confirmation logic. It should return `true` if the signal is confirmed, and `false` otherwise.

This code is provided as a sample and is not the official code of the Apollo Pips indicator. To find the official developer of this product, please use MQL5. For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Apollo Pips Review](https://forexroboteasy.com/forex-robot-review/apollo-pips-review-reliable-forex-indicator-for-h1-time-frame/).

Disclaimer: Forex Robot Easy is not the official developer of this product. We only provide sample code that can work as described in the product.
