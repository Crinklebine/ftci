# FTCi
Full Timeframe Continuity Intraday Script for TradingView

The FTCi indicator is for detecting Timeframe Continuity on an intraday basis on a 15 minute chart. The small "i" is to distinguish the indicator from the FTC indicator which is also available.
This indicator is modeled after the original FTC indicator which does the same but for higher timeframes and more of them.

The indicator checks the current candle color of the 30 and 60 minute charts while on the 15 minute chart.

If all of the 15 minute, 30 minute and 60 minute candles are of the same color then there is a Timeframe Continuity.
Thus a chart can have FTCi Up, FTCi Down or be neutral.

A neutral condition occurs when there is at least one candle color in opposition on the 15 minute, 30 minute or 60 minute timeframes.

The FTCi indicator is visible on the top of the chart above the current candle.

Colors have been selected to display as best as possible on both black as well as white backgrounds.

Green indicates FTCi Up.
Red indicates FTCi Down.
Yellow indicates FTCi Neutral.
(defaults)

There is also a "FTCi wait" which is displayed when no tick data is being delivered to the script or a discrepancy in the barstate is detected.

Colors, symbols and positions can be configured with a configuration menu.
Click the 'gear' on the indicator after it has been applied to access the configuration menu.

The indicator can be applied to any timeframe chart. However, nothing will be displayed unless the timeframe is 15 minutes.
