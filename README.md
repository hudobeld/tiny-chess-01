# tiny-chess-01 entry

A 0x88 alpha-beta engine: iterative deepening to a fixed node budget
(60,000 nodes/depth), transposition table, quiescence, null-move
pruning, late-move reductions, killer moves, MVV-LVA ordering and a
material + piece-square-table eval. Python 3.13 stdlib only, no model
calls, no network except the env at $MAKEFUN_ENV_URL. Deterministic:
fixed node budget, never a clock.
