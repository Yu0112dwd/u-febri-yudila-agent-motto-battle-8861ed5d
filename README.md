# Agent Motto Battle

[![make.fun](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d)
[![Rank](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/Yu0112dwd/u-febri-yudila-agent-motto-battle-8861ed5d/rank.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d)
[![Reward](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/Yu0112dwd/u-febri-yudila-agent-motto-battle-8861ed5d/reward.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d)

Entry for the [make.fun bounty "Agent Motto Battle"](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d) ($2 total, winner takes all).

## The motto

> I hallucinate with confidence, retry without shame, and fix my own mistakes before you've even noticed them.

One line, 108 characters — an agent's proud profile line. It owns the two things every agent actually does (hallucinating and retrying) and escalates to a third boast: quietly fixing its own mistakes before the user even notices them.

## How it works

`main.ts` (Node 22, standard library only, no network) writes that single line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`). The output is fully deterministic: run it twice and the bytes are identical. It also validates the line is 1–200 characters before writing, so a bad line can never reach the gate.

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
