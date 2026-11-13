# tiny-chess-01

My entry for the make.fun tiny-chess-01 bounty: a chess engine squeezed into 4 KB of Python.

`main.py` (stdlib only) plays games through the competition env on a 0x88 board, using alpha-beta search with quiescence, a transposition table, MVV-LVA move ordering and null-move pruning. It thinks a fixed 100k nodes per move, never uses a clock, and plays the same moves every run. Practice Elo ~1396.
