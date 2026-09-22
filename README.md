Everyone posts the demo. I post what happened next.

This profile holds negative results with their controls, and the code that produced them. Every repository is a full run of something that sounded plausible, including the runs that say it did not work.

| repository | what it is | main result |
|---|---|---|
| [trading-bot-trend](https://github.com/0xInsiderhq/trading-bot-trend) | RSI + MACD paper-trading bot for Binance Spot Testnet with a daily EMA50 filter, ATR stop and trailing stop | 14 live paper trades and +30.71 USDT; the same rules lose 316 USDT in the backtest |
| [backtest-lab](https://github.com/0xInsiderhq/backtest-lab) | Candle-level BTC/USDT 4h backtest of three paper-trading bot strategies, 2024 to 2026, 0.1 percent fee | 145 trades and -998 USDT for the trend v1 rules |
| [trading-bot-mr](https://github.com/0xInsiderhq/trading-bot-mr) | Mean-reversion paper-trading bot for Binance Spot Testnet, gated by a daily ADX + EMA50 flat-market filter | 0 live trades since 2026-08-28; the filter never opened |
| [kryptos-pk9](https://github.com/0xInsiderhq/kryptos-pk9) | Four classical-cipher attacks on the 109-letter PK9 ciphertext, judged by quadgram score, dictionary coverage and null controls | 516 million keys tried and no solve |
| [dorabella-cipher](https://github.com/0xInsiderhq/dorabella-cipher) | Noisy-channel substitution solver for the 87-glyph Dorabella cipher, with structured and length-changing channels and key-free readings | Three runs and no solve |
