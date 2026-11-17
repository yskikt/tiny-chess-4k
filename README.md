# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/yskikt/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/yskikt/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,011 bytes of Python (main.py, an LZMA-packed build of a
readable source). Negamax alpha-beta search with PVS, quiescence, a
transposition table, null-move pruning, LMR, MVV-LVA/killer move ordering and
tapered piece-square evaluation on a 0x88 board, playing at a fixed
60,000-node budget per move (never a clock), so its play is deterministic.
In the kit's practice gauntlet it scored 4.5/6 (wins over the depth-2,
depth-3, depth-4 and nodes-100k house engines, a draw with nodes-250k),
a practice Elo of about 1,545.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=z9zjjwax&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
