# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Wangzinan62/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Wangzinan62/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4 KB of Python (4,051 bytes, LZMA-packed): negamax alpha-beta search with a transposition table, quiescence search, null-move pruning, late-move reductions, check extensions, and incremental material + piece-square evaluation with a fixed node budget (deterministic, never clock-based). In local practice trials against the house gauntlet it scored 3.0/6 — wins over the depth-2 and depth-3 anchors, draws with depth-4 and the 100k-node anchor — for an estimated Elo of about 1280. It plays through the make.fun agent/v1 environment protocol over HTTP.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=7n4st51n&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
