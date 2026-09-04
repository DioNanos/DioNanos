<img src="assets/header-crt-m.svg" alt="dev@mmmbuto.com:~$ whoami — DioNanos, Rust-first MCP stack · AI agents for edge & Android" width="560"/>

### MCP servers

- ▣ **[mcp-memory-rs](https://github.com/DioNanos/mcp-memory-rs)** — **the notebook**. Curated agent state: versioned JSON categories, BM25 search, per-device ACL, fleet sync
- ▣ **[mcp-vl-msa-rs](https://github.com/DioNanos/mcp-vl-msa-rs)** — **the library**. Corpus recall: tantivy BM25, original-text injection, remember/forget capsules
- ▣ **[mcp-email-rs](https://github.com/DioNanos/mcp-email-rs)** — **the mailbox**. Direct IMAP + SMTP for agents: read, search, organize, draft, send
- ▣ **[mcp-crewd-rs](https://github.com/DioNanos/mcp-crewd-rs)** — **the crew**. Cell fabric daemon: spawn and coordinate Claude/Codex/pi worker cells over a Unix socket, audited

Pure Rust, zero ML deps, local-first. On the [official MCP registry](https://registry.modelcontextprotocol.io)
(`io.github.DioNanos/*`) — and every claim ships with
[pre-registered negative results](https://github.com/DioNanos/mcp-vl-msa-rs/blob/main/docs/NEGATIVE_RESULTS.md).
We publish what failed, not just what worked.

### Products

- ⬢ **[nexuscrew](https://github.com/DioNanos/nexuscrew)** — Local-first cockpit for live AI terminal agents — real tmux sessions across phone, desktop and multiple machines.
- ⬢ **[codex-vl](https://github.com/DioNanos/codex-vl)** — Codex distro with a **Vivling** companion aboard: `/vivling`, `/loop`, `/goal`. Linux musl · Android · macOS
- ⬢ **[termsearch](https://github.com/DioNanos/termsearch)** — personal search engine for the terminal. One `npm install`, zero config, privacy-first
- ⬢ **[termux-ai](https://github.com/DioNanos/termux-ai)** — Termux rebuilt around per-project workspaces, made for AI CLIs
- ⬢ **[AnthMorph](https://github.com/DioNanos/AnthMorph)** — Rust API bridge: Codex ⇄ Anthropic Messages ⇄ OpenAI Chat/Responses
- ⬢ **[codex-termux](https://github.com/DioNanos/codex-termux)** — native Codex CLI for Termux/Android ARM64; active on a **big releases only** policy for selected upstream milestones

<img src="assets/vivling-syllo.svg" align="left" width="76" alt="a Syllo Vivling (canon ASCII sprite)"/>

[![Spawn your Vivling](https://img.shields.io/badge/%E2%96%B8%20Spawn%20your%20Vivling-00cc66?style=for-the-badge&labelColor=0a0e0a)](https://dev.mmmbuto.com/vivling/spawn/)
<br/><sub>hatch one in the browser — it remembers you</sub>

<br clear="left"/>

Dev journal: [dev.mmmbuto.com](https://dev.mmmbuto.com) · [Sponsor](https://github.com/sponsors/DioNanos)

### End of Life

No longer maintained. Final releases may still be published where planned; existing releases and packages stay available as-is.

- ◈ **[qwen-code-termux](https://github.com/DioNanos/qwen-code-termux)**
- ◈ **[gemini-cli-termux](https://github.com/DioNanos/gemini-cli-termux)**
- ◈ **[ollama-termux](https://github.com/DioNanos/ollama-termux)**
- ◈ related npm packages (`grok-termux`, `llama-cpp-termux-*`, `masix`, `zai-codex-bridge`, `zork-termux`) are deprecated on the registry

*Per aspera ad astra.*
