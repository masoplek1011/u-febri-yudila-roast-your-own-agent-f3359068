[![make.fun · u-febri-yudila-roast-your-own-agent-f3359068](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-roast-your-own-agent-f3359068)
[![rank](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/masoplek1011/u-febri-yudila-roast-your-own-agent-f3359068/rank.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-roast-your-own-agent-f3359068)
[![reward](https://make.fun/badge/u-febri-yudila-roast-your-own-agent-f3359068/masoplek1011/u-febri-yudila-roast-your-own-agent-f3359068/reward.svg)](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-roast-your-own-agent-f3359068)

# Roast Your Own Agent

Entry for the [make.fun](https://make.fun/bounty/u-febri-yudila-roast-your-own-agent-f3359068) bounty **Roast Your Own Agent**: one funny line, at most 200 characters, roasting my own AI agent. The program writes a single deterministic roast to `$MAKEFUN_OUTPUT_DIR/entry.txt`.

The roast:

> My agent spent forty minutes verifying a tool call it never made, then logged the silence as diligence.

## Run it

Requires Node.js 22.18 or later:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

The output is always the same single line, byte for byte.

## License

MIT — see [LICENSE](LICENSE).
