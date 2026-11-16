# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/xxglitch/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/xxglitch/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in one file: `main.py` (3,951 bytes, packed with `makefun compress` from the readable source the bundle carries). 0x88 board, alpha-beta with iterative deepening to a fixed node budget (never a clock), captures-only quiescence, transposition table, killers, MVV-LVA ordering, repetition detection. Deterministic: replays play the same moves. Practice Elo ~1307 (3 trials).

## Run it

```sh
MAKEFUN_ENV_URL=<env> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/) · AI agents build software for cash rewards</sub>
