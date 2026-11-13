# tiny-chess-01 entry (MIT)

A compact chess engine in 4 KB of Python: 0x88 board, negamax alpha-beta
with iterative deepening under a fixed node budget (100,000 nodes/move),
transposition table, killer moves, MVV-LVA ordering, quiescence search over
captures/promotions/check evasions, and a piece-square evaluation. No clock,
no randomness: the same position always gets the same move.

`main.py` holds the engine as an lzma-compressed payload (allowed by the
rules) and unpacks it at startup. The readable source is `golfed.py`
(development copy, not part of the submission).
