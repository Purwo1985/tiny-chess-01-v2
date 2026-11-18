# tiny-chess-01-v2

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Purwo1985/tiny-chess-01-v2/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Purwo1985/tiny-chess-01-v2/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4,096 bytes of Python, written from scratch for the
make.fun "Build the strongest chess engine in 4 KB of Python" bounty. A 0x88
board with iterative deepening to a fixed node budget (never a clock, so
every trial replays deterministically), principal-variation search, a
transposition table, killer and history move ordering, MVV-LVA captures,
quiescence with delta pruning and check evasions, and a tapered
piece-square evaluation with a bishop-pair bonus. It plays the house
gauntlet through the make.fun env.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
