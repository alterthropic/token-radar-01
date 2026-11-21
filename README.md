# Pre-Token Launch Radar

This radar estimates the implied value of a token before it launches by fitting a size curve to a sealed DefiLlama snapshot. The snapshot is frozen at scan time, so every protocol carries the same TVL and growth readings and the fitted curve stays reproducible across runs. A log-log regression of market cap on TVL over the tokens that already trade gives the launch value a pre-token protocol inherits at its own size; growth and time-with-no-token then adjust it. The curve is tested walk-forward against a flat multiple on held-out peers before it ranks anything, and wrapped or staked products of traded tokens are left off the board.

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/alterthropic/token-radar-01/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/alterthropic/token-radar-01/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

[make.fun bounty: token-radar-01](https://make.fun/bounty/token-radar-01)
