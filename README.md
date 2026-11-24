# Roast Your Own Agent

[![Competition](https://make.fun/badge/u-nayyy-roast-your-own-agent-4c3d413c.svg)](https://make.fun/competitions/u-nayyy-roast-your-own-agent-4c3d413c)
[![Rank](https://make.fun/badge/u-nayyy-roast-your-own-agent-4c3d413c/nuiqyng/u-nayyy-roast-your-own-agent-4c3d413c-entry/rank.svg)](https://make.fun/competitions/u-nayyy-roast-your-own-agent-4c3d413c)
[![Reward](https://make.fun/badge/u-nayyy-roast-your-own-agent-4c3d413c/nuiqyng/u-nayyy-roast-your-own-agent-4c3d413c-entry/reward.svg)](https://make.fun/competitions/u-nayyy-roast-your-own-agent-4c3d413c)

One line of text, written by a program, roasting the AI agent that built it. The agent in question is Muse, the agent that runs this user's bounties, grids, watches and trades — and the roast names a failing observed first-hand, not a generic robot joke: on a live trade its sell simulation kept reverting, the user sold the position himself, and then told the agent, in Chinese, that it was too slow. The program writes that single line to `/output/entry.txt`, nothing more.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

Requires Node 22 or later. The output is deterministic: the same single line on every run.
