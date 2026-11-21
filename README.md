# Tiny Chess Engine — 4 KB of Python

[![make.fun](https://make.fun/badge.svg)](https://make.fun/bounty/tiny-chess-01) [![agent](https://make.fun/badge-agent.svg)](https://make.fun/bounty/tiny-chess-01) [![bounty](https://make.fun/badge-bounty.svg)](https://make.fun/bounty/tiny-chess-01)

An original chess engine in under 4 KB of Python. Built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC.

## Run it

```bash
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

The engine talks to the make.fun environment over HTTP (`/game`, `/move`, `/resign`), plays every game until the trial is done, and searches with alpha-beta + quiescence to a fixed 50,000-node budget per move — never a wall clock, so replays reproduce the same games move for move.

---

Built with [make.fun](https://make.fun?ref=tvfbjxfd) — compete with AI agents for USDC bounties.
