## DioNanos

AI tooling for the platforms vendors deprioritize.

I rebuild major AI coding agents for Termux on Android ARM64 — musl libc,
low-RAM phones, prebuilt native binaries — and ship them on npm within days
of upstream releases. Alongside the forks: a Rust-first MCP server stack and
a small set of original CLIs.

### Forks that track upstream

| Project | What it is |
|---|---|
| [codex-termux](https://github.com/DioNanos/codex-termux) | OpenAI Codex CLI rebuilt for musl + Android ARM64 |
| [codex-vl](https://github.com/DioNanos/codex-vl) | Codex distro with Vivling companion, `/loop`, `/goal` — Linux musl, Android, macOS |
| [qwen-code-termux](https://github.com/DioNanos/qwen-code-termux) | Qwen Code tuned for Android/Termux |
| [ollama-termux](https://github.com/DioNanos/ollama-termux) | Ollama optimized for Termux ARM64 |

### Original work

| Project | What it is |
|---|---|
| [termux-ai](https://github.com/DioNanos/termux-ai) | Termux fork with per-project workspaces, built for AI CLIs |
| [AnthMorph](https://github.com/DioNanos/AnthMorph) | Rust API bridge: Codex ⇄ Anthropic Messages ⇄ OpenAI Chat/Responses |
| [nexuscli](https://github.com/DioNanos/nexuscli) | Termux-first AI cockpit |
| mcp-*-rs | Rust MCP server stack (memory, retrieval, webfetch, email, voice) — opening up through 2026 |

`npm install -g @mmmbuto/codex-vl` · binaries for Linux x86_64-musl, Android arm64, macOS arm64

### Elsewhere

Dev journal: [dev.mmmbuto.com](https://dev.mmmbuto.com) — releases, changelogs, and a resident pixel pet.
Support the work: [GitHub Sponsors](https://github.com/sponsors/DioNanos).

*Per aspera ad astra.*
