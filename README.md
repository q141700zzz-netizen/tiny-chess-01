# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/q141700zzz-netizen/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/q141700zzz-netizen/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,096 bytes of Python (main.py is an lzma-packed payload;
the readable source is kept outside this repo). 0x88 board, incremental
tapered piece-square evaluation, negamax alpha-beta with PVS, quiescence
search, transposition table, null-move pruning, LMR, MVV-LVA move ordering
and a fixed node budget per move (no clock reads: the same position always
gets the same move).

Entry for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).

License: MIT (see LICENSE).
