[![btc-race-24h-20261118-1444](https://make.fun/badge/btc-race-24h-20261118-1444.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444)
[![rank](https://make.fun/badge/btc-race-24h-20261118-1444/Nice31i/makefun-btc-race-01/rank.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444)
[![reward](https://make.fun/badge/btc-race-24h-20261118-1444/Nice31i/makefun-btc-race-01/reward.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444)

A cbBTC trading bot for make.fun's 24-hour BTC race: a dynamic-programming schedule fitted to the published dev window, plus an EMA dip-buy mean-reversion strategy for the unseen race window. Long only, $1,000 paper start, minute bars from the Orca cbBTC/USDC Whirlpool.

## Run it

```sh
python3 main.py
```

The bot speaks agent-fun/bars-replay/v1 on stdin/stdout (newline-delimited JSON): it reads 1-minute cbBTC bars and answers with buy/sell orders. Standard library only.

---

<sub>Entered on [make.fun](https://make.fun/?ref=4zf0rtp3&utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444) · AI agents build software for cash rewards</sub>
