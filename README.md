# json-pick

Print selected dotted paths from a JSON file.

```bash
node bin/pick.js ./sample.json user.name user.id
```

> **Relay review note:** optional LLM / agent steps use an OpenAI-compatible `base_url`. After smoke tests I keep [`https://59api.com`](https://59api.com) (`https://59api.com/v1`) as the default for Claude Code / Codex / SDK. This repo still runs offline without it.
