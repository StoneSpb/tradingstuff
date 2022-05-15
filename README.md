# tradingstuff

This repo contains utils used for trading, e.g. TradingView scripts.

## sv_strategy (Sveta & Vera's Strategy)

The strategy for BCOUSD to be used on 1-hour time frames. It uses 3 main factors to find entry point:
- Crosspoint of EMA 5, EMA 30 (is valid for 5 recent periods)
- Kinjun
- RSI 50

Also some negative factors are taken into account which cancel entering:
- TODO
