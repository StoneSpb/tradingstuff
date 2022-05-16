# tradingstuff

This repo contains utils used for trading, e.g. TradingView scripts.

## sv_strategy (Sveta & Vera's Strategy)

The strategy for BCOUSD to be used on 1-hour time frames. It uses 3 main factors to find entry point:
- Crosspoint of EMA 5, EMA 30 (is valid for 5 recent periods, 4 bars before current and the current one)
- Kinjun
- RSI 50

Also some negative factors are taken into account which cancel entering:
- Chaikin crosses zero in opposite trend in range of 4 recent periods
- Chaikin absolute value is greater than 14_000
