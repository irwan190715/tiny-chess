# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/irwan190715/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/irwan190715/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

tiny-chess: an original chess engine in 4 KB of Python. A 0x88 board with piece lists, alpha-beta search with iterative deepening on a fixed node budget, quiescence over captures and check replies, a transposition table, null-move pruning and late-move reductions, and a material + piece-square evaluation with a tapered king term. It plays the make.fun env protocol (`MAKEFUN_ENV_URL`) and needs nothing but the standard library.

`main.py` is the whole engine, packed as an lzma payload with its unpacker (4,085 bytes). The unpacked source is an original engine written for this bounty.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:PORT python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=n0q00kz5&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
