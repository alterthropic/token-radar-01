# Pre-Token Launch Radar

The radar prices tokens that do not exist yet. It starts from a sealed DefiLlama snapshot of protocols, frozen at a single instant so every reading is comparable, and fits a size curve across the protocols whose tokens already trade: a log-log regression of market cap on TVL. Each pre-token protocol is then placed on that curve at its own TVL, and the curve's height there becomes its implied launch value — what the market pays for a token backed by a protocol of exactly that size. Recent growth and the length of time the protocol has run without a token adjust the estimate from there. Wrapped or staked products of tokens that already trade are left off the board, since their TVL restates value the market has already priced. For validation, the curve is tested walk-forward against a flat multiple on held-out peers before it ranks anything.

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/alterthropic/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/alterthropic/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

[make.fun bounty: token-radar-01](https://make.fun/bounty/token-radar-01)
