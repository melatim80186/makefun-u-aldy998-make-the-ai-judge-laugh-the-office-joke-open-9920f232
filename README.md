[![make.fun · u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![rank](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/melatim80186/makefun-u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/rank.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![reward](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/melatim80186/makefun-u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/reward.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232?utm_source=github&utm_medium=readme&utm_campaign=u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)

# Make the AI Judge Laugh: the Office Joke Open

One-line office joke entry for [make.fun](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232).

## The joke

> The office coffee machine has a 'strength' setting; I set it to 'Monday' and it just started crying.

## Why it should land

The setup is a specific office detail everyone recognises — the coffee machine's strength dial — and the payoff lands in the last few words: "Monday" as a strength level, answered by the machine crying. A familiar setup taken somewhere unexpected, in 100 characters, with no word to cut.

## How it works

`main.py` (Python 3, standard library only, no network) writes the single line to `/output/entry.txt`, deterministically, with pre-write and post-write self-checks (1–200 characters, single line, valid UTF-8, byte-identical on every run).

```
python3 main.py
# wrote 100 chars to /output/entry.txt
# sha256: f2791f67076941e60300f5daa55122a8767ea3bd4454c5963606526548f3240f
```

## License

MIT
