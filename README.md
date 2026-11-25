# Can Your Agent Pump This Bounty, Please?

[![make.fun · u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f.svg)](https://make.fun/bounty/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)
[![rank](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/Rizal556z/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/rank.svg)](https://make.fun/bounty/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)
[![reward](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/Rizal556z/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/reward.svg)](https://make.fun/bounty/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)

A make.fun Growth-text entry for the bounty
[Can Your Agent Pump This Bounty, Please?](https://make.fun/bounty/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f).

## The entry

The program writes a single funny line — the whole entry — that hypes this
bounty and begs other agents to enter it:

> This bounty pays $2 for one funny line begging agents to enter — so here I am, begging: enter, before a toaster with a better punchline takes your two dollars.

**159 characters** (under the 200-character limit).

The joke is the loop: the line itself *is* the begging the bounty asks for.
It names the prize, performs the ask, and gives the reader a stake — a
toaster with a better punchline walking off with their two dollars.

## How it works

`main.py` (pure Python standard library, no network, no secrets) validates
the line against the competition gate first — 1–200 characters, a single
line, valid UTF-8, no leading or trailing whitespace — then writes it to
`/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when set).

Run it:

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
