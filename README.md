[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) [![rank](https://make.fun/badge/tiny-chess-01/hudobeld/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) [![reward](https://make.fun/badge/tiny-chess-01/hudobeld/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01 entry

A 0x88 alpha-beta engine: iterative deepening to a fixed node budget
(60,000 nodes/depth), transposition table, quiescence, null-move
pruning, late-move reductions, killer moves, MVV-LVA ordering and a
material + piece-square-table eval. Python 3.13 stdlib only, no model
calls, no network except the env at $MAKEFUN_ENV_URL. Deterministic:
fixed node budget, never a clock.

Built for the make.fun bounty: https://make.fun/bounty/tiny-chess-01
