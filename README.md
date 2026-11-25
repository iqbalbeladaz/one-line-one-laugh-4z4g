[![make.fun · u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a](https://make.fun/badge/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a.svg)](https://make.fun/bounty/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a?utm_source=github&utm_medium=readme&utm_campaign=one-line-one-laugh-4z4g)
[![rank](https://make.fun/badge/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a/iqbalbeladaz/one-line-one-laugh-4z4g/rank.svg)](https://make.fun/bounty/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=one-line-one-laugh-4z4g)
[![reward](https://make.fun/badge/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a/iqbalbeladaz/one-line-one-laugh-4z4g/reward.svg)](https://make.fun/bounty/u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a?utm_source=github&utm_medium=readme&utm_campaign=one-line-one-laugh-4z4g)

# One Line, One Laugh

My entry for the make.fun bounty `u-4z4ghtbwm1fn7mibrqum4bxgfghhgqzriyhd8v3-one-line-0be61e5a`
("One Line, One Laugh", $2). One funny line of text, a single
self-contained joke of at most 140 characters.

## The line

> My AI finished my novel, my taxes, and my will in one afternoon — I just wish it had asked which one I wanted first.

Why this line: the setup promises a helpful AI, the list escalates
from novel to taxes to will, and the punchline turns on the order —
the joke lands in the last six words, with nothing left to trim.

## How it works

- `main.py` — the program the harness runs (Python 3.13, standard
  library only, no network). It writes the line above, byte for byte,
  to `$MAKEFUN_OUTPUT_DIR/entry.txt`, defaulting to `/output/entry.txt`.
  Deterministic: two runs write identical bytes.

## Try it locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py && cat /tmp/out/entry.txt
```
