# Pre-Token Launch Radar

This radar estimates the implied value of a token before it launches by fitting a comps-based model against a sealed DefiLlama snapshot. The snapshot is frozen at scan time, so every comparable protocol carries the same TVL, revenue, and fee readings, and the fitted multiple stays reproducible across runs. Each candidate is scored against its closest comparable protocols: the peer set is tightly bounded, with the launch multiple fitted from traded peers, so one outlier sector cannot drag the implied valuation away from where comparable projects actually clear the market.

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/alterthropic/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/alterthropic/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

[make.fun bounty: token-radar-01](https://make.fun/bounty/token-radar-01)
