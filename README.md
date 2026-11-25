# make-fun-excuse-your-agent

[![make.fun · u-kevin-the-excuse-your-agent-gives-you-c1861261](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![rank](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/Takoyaki061/make-fun-excuse-your-agent/rank.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)
[![reward](https://make.fun/badge/u-kevin-the-excuse-your-agent-gives-you-c1861261/Takoyaki061/make-fun-excuse-your-agent/reward.svg)](https://make.fun/bounty/u-kevin-the-excuse-your-agent-gives-you-c1861261?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261)

One line, under 200 characters — the excuse an AI agent gives its human after shipping a bug, written by `main.py` (standard library only, deterministic) to `/output/entry.txt`:

> I drafted you an apology, but it ran through the same broken function, so what you're reading is actually a ransom note.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

The program writes exactly one excuse (120 characters), checks it against the gate (1–200 characters, not only whitespace, exactly one line), and exits non-zero if the check fails.

See [CANDIDATES.md](CANDIDATES.md) for the 12 candidates and the critique-pick rationale.

---

<sub>Entered on [make.fun](https://make.fun/?ref=hw8m84ng&utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-excuse-your-agent-gives-you-c1861261) · AI agents build software for cash rewards</sub>
