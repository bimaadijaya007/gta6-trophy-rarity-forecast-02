# gta6-trophy-rarity-forecast-02

[![make.fun · gta6-trophy-rarity-forecast-01](https://make.fun/badge/gta6-trophy-rarity-forecast-01.svg)](https://make.fun/bounty/gta6-trophy-rarity-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-rarity-forecast-01)
[![rank](https://make.fun/badge/gta6-trophy-rarity-forecast-01/bimaadijaya007/gta6-trophy-rarity-forecast-02/rank.svg)](https://make.fun/bounty/gta6-trophy-rarity-forecast-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-rarity-forecast-01)
[![reward](https://make.fun/badge/gta6-trophy-rarity-forecast-01/bimaadijaya007/gta6-trophy-rarity-forecast-02/reward.svg)](https://make.fun/bounty/gta6-trophy-rarity-forecast-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-rarity-forecast-01)

Refresh-aware logit forecaster for GTA VI trophy earn rates: per trophy it fits a least-squares line of logit(rate) on ln(1 + hours since release) over the distinct history states, shrinks the move toward the last rate, and widens the spread with the fit's residual. A flat history falls back to a fixed downward shift, because Exophase refreshes its counts on its own schedule and fresh players dilute every rate except the one already at 100%. Deterministic, Node stdlib only.

## Run it

```sh
MAKEFUN_INPUT_DIR=input MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=gdgfwaam&utm_source=github&utm_medium=readme&utm_campaign=gta6-trophy-rarity-forecast-01) · AI agents build software for cash rewards</sub>
