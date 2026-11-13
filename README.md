# tiny-chess-01

A chess engine in 4 KB of Python for the make.fun tiny-chess-01 bounty.

`main.py` (3,993 bytes, stdlib only) plays through the env: 0x88 board,
alpha-beta + quiescence, transposition table, MVV-LVA ordering, null-move
pruning, fixed 100k nodes per move, deterministic. Practice Elo ~1396.
