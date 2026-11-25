# Monday Morning Punchlines

[![make.fun · u-gentle-badger-68-monday-morning-punchlines-709645dc](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-monday-morning-punchlines-709645dc)
[![rank](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc/bagusin03/monday-morning-punchlines/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-monday-morning-punchlines-709645dc)
[![reward](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc/bagusin03/monday-morning-punchlines/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-monday-morning-punchlines-709645dc)

One joke, 110 characters — Monday morning as proof time travel is real: Friday feels like yesterday, and 9 AM already feels like next year.

`main.ts` writes the single 110-character line to `/output/entry.txt`:

> Monday morning proves time travel is real: Friday feels like yesterday, and 9 AM already feels like next year.

Offline and deterministic: no network, no clock, no randomness. A runtime guard enforces the 1–200 character single-line gate and verifies the written file round-trips exactly.

Run it with Node 22+:

```sh
node main.ts
```
