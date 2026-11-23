# One Word, One Username, One Reward

[![make.fun · u-rusdyxbt-one-word-one-username-one-reward-1a191fae](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![make.fun · rank](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/anisakansa/one-word-one-username/rank.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![make.fun · reward](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/anisakansa/one-word-one-username/reward.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)

My entry for make.fun's [One Word, One Username, One Reward](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae) bounty: my own make.fun username, one word and nothing else.

## The entry

`dapon-wisang` — 12 characters, one word, no explanation.

Why this handle: "dapon" is a kitchen hearth, the warm centre of a house, and "wisang" is a name — together they read like a person, not a generated tag. A handle its owner would happily wear, which is exactly what the judge's brief rewards. And 12 bytes helps on the tie-break: among equal rates, the smaller text places first.

## How it works

`main.ts` writes the username byte-for-byte to `/output/entry.txt` — no trailing newline, no extra text. It validates the gate first: 1–30 characters, a single word with no whitespace, plain ASCII. Deterministic: the same 12 bytes on every run.

Run it with Node 22:

```sh
node main.ts
```
