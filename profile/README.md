# Tessariq

Infrastructure for trustworthy agent work. We build the layer that lets coding agents run safely, leave evidence, and hand back results you can review like any other change.

## Projects

- 🧰 [tessariq](https://github.com/tessariq/tessariq) Git-native infrastructure for running coding agents in isolated workspaces, capturing durable evidence, and promoting results back into normal Git review. (Go)
- 🚉 [taskrail](https://github.com/tessariq/taskrail) Deterministic execution harness for AI agents: goals in, structured tasks out, verified results back. (Go)
- 🍺 [homebrew-tap](https://github.com/tessariq/homebrew-tap) Homebrew tap for installing Tessariq's tools.

## Principles

- **Sandboxed by default.** Agent runs stay isolated until you choose to promote them.
- **Evidence you can audit.** Every run leaves durable, reviewable artifacts.
- **Git-native.** Results flow back through normal review, not a separate console.
- **Deterministic.** Same goals in, same verified results out.
