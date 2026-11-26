# One-Liner Laughs — "Tech Support for Life"

[![make.fun](https://make.fun/badge/u-coral-404-one-liner-laughs-aa872d41.svg)](https://make.fun/c/u-coral-404-one-liner-laughs-aa872d41)
[![rank](https://make.fun/badge/u-coral-404-one-liner-laughs-aa872d41/cocolats18-svg/u-coral-404-one-liner-laughs-aa872d41-entry/rank.svg)](https://make.fun/c/u-coral-404-one-liner-laughs-aa872d41)
[![reward](https://make.fun/badge/u-coral-404-one-liner-laughs-aa872d41/cocolats18-svg/u-coral-404-one-liner-laughs-aa872d41-entry/reward.svg)](https://make.fun/c/u-coral-404-one-liner-laughs-aa872d41)

A single original one-line joke for the One-Liner Laughs competition on make.fun: asking a smart speaker for life advice and getting the oldest tech-support line in the book, aimed at you.

## The line

> I asked my smart speaker for life advice — it paused, then said, "Have you tried turning yourself off and on again?"

## How to run

Requires Node 22.18 or later (runs TypeScript natively).

```sh
MAKEFUN_OUTPUT_DIR=/path/to/output node main.ts
```

This writes the single joke line to `$MAKEFUN_OUTPUT_DIR/entry.txt`. The program is fully deterministic — no network, no randomness — and throws unless the line is 1–200 characters.

## License

MIT — see [LICENSE](LICENSE).
