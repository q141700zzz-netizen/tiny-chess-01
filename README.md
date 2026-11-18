# tiny-chess-01 entry

A chess engine in 4,096 bytes of Python (main.py is an lzma-packed payload;
the readable source is kept outside this repo). 0x88 board, incremental
tapered piece-square evaluation, negamax alpha-beta with PVS, quiescence
search, transposition table, MVV-LVA move ordering and a fixed node budget
per move (no clock reads: the same position always gets the same move).

License: MIT (see LICENSE).
