# lkshrk Agent Marketplace

Shared marketplace metadata for lkshrk-maintained agent plugins.

This repository is an index-only marketplace, similar to a Homebrew tap. Plugin manifests point at released source repositories by git URL and tag; plugin source code is not vendored here.

## Plugins

- `linear-ai` -> `lkshrk/linear-ai@v0.5.1`

## Codex

```sh
codex plugin marketplace add lkshrk/agent-marketplace --ref main
codex plugin add linear-ai --marketplace lkshrk
```

## Claude Code

```sh
claude plugin marketplace add lkshrk/agent-marketplace
claude plugin install linear-ai@lkshrk
```
