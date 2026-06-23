# Tessariq

**Infrastructure for trustworthy agent work.**

Coding agents are fast but opaque: they touch your repo, and you're left without proof of what ran, why it ran, or how to undo it safely. Tessariq builds the layer underneath — agents run in isolated workspaces, leave durable evidence, and hand back results you review like any other change.

It's also an agentic-engineering lab: an open workbench for figuring out what *trustworthy* autonomy actually looks like in practice.

## Start here

> ⚠️ **Pre-release.** The first version of the core tool isn't out yet — it's landing soon. Watch [tessariq](https://github.com/tessariq/tessariq) for the release.

New to the project? Begin with **[tessariq](https://github.com/tessariq/tessariq)** — the core runtime. Reach for [taskrail](https://github.com/tessariq/taskrail) when you need structured, verifiable task execution on top.

Once released, install will be a one-liner:

```bash
brew install tessariq/tap/tessariq
```

## Projects

| | Project | What it does | Stack |
|---|---|---|---|
| 🧰 | [**tessariq**](https://github.com/tessariq/tessariq) | Git-native runtime for running coding agents in isolated workspaces, capturing durable evidence, and promoting results back into normal Git review. | Go |
| 🚉 | [**taskrail**](https://github.com/tessariq/taskrail) | Execution harness for AI agents: goals in, structured tasks out, verified results back. | Go |
| 🍺 | [**homebrew-tap**](https://github.com/tessariq/homebrew-tap) | Homebrew tap for installing Tessariq's tools. | — |

## Principles

- **Sandboxed by default.** Agent runs stay isolated until you choose to promote them.
- **Evidence you can audit.** Every run leaves durable, reviewable artifacts — not just a final diff.
- **Git-native.** Results flow back through normal review, not a separate console.
- **Reproducible.** Deterministic task execution and verification gates, so the same goals produce results you can trust and re-run.

## Get involved

Issues and PRs welcome on any repo. Questions or ideas → open a discussion or reach out at [felix@fmueller.io](mailto:felix@fmueller.io).
