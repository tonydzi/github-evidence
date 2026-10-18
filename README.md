# Upstream contribution evidence — @tonydzi

Snapshot: **2026-10-18** · source: public GitHub API · regenerated weekly.

This page exists so the contribution record stays checkable independently of any one profile page. Everything below is a link into someone else's repository: their issue tracker, their pull requests, their release notes.

Counts are split on purpose. Opening a pull request in someone else's project and commenting in someone else's thread are different things, and adding them together would overstate the first.

| | |
|---|---:|
| Pull requests opened in other people's repos | 164 |
| …of which merged | 62 |
| Issues opened in other people's repos | 69 |
| Other people's threads participated in | 417 |
| Reviews on other people's PRs | 102 |
| Distinct repositories | 257 |
| Replies received from maintainers and participants | 2012 |
| Release notes crediting this account | 29 |
| Files in other repos crediting this account | 33 |

## Credited in other projects' release notes

**cristicretu/diri — v0.5.1** · 2026-08-14 · [release notes](https://github.com/cristicretu/diri/releases/tag/v0.5.1)

> - **Add a keyboard shortcuts reference** (#52) — @tonydzi
> - **Sample the stack when the skipped tests hang on a runner** (#26) — @tonydzi
> @alexapvl, @bqx619, @cristicretu, @lucasAguiar11, @tonydzi — and @imgbot.

**mixelpixx/Konnect — v0.4.0** · 2026-08-15 · [release notes](https://github.com/mixelpixx/Konnect/releases/tag/v0.4.0)

> - The plugin no longer deletes another KiCAD session's server record, and reaps the server it started when KiCAD exits (#199, @tonydzi — partial coverage of #103; the IPC entrypoint still needs its own fix).
> * fix(plugin): keep the server PID record correct across sessions and reap on exit by @tonydzi in https://github.com/mixelpixx/Konnect/pull/199
> * @tonydzi made their first contribution in https://github.com/mixelpixx/Konnect/pull/199

**agno-agi/agno — v3.0.0a3** · 2026-08-21 · [release notes](https://github.com/agno-agi/agno/releases/tag/v3.0.0a3)

> * fix: repair four imports that do not resolve in cookbooks by @tonydzi in https://github.com/agno-agi/agno/pull/9498
> * @tonydzi made their first contribution in https://github.com/agno-agi/agno/pull/9498

**qualixar/superlocalmemory — v4.1.0** · 2026-08-23 · [release notes](https://github.com/qualixar/superlocalmemory/releases/tag/v4.1.0)

> Reported by @tonydzi (#122).

**basicmachines-co/basic-memory — v0.23.0** · 2026-08-24 · [release notes](https://github.com/basicmachines-co/basic-memory/releases/tag/v0.23.0)

> * fix(integrations): stop bm subprocesses inheriting Hermes's Python env by @tonydzi in https://github.com/basicmachines-co/basic-memory/pull/1179
> * @tonydzi made their first contribution in https://github.com/basicmachines-co/basic-memory/pull/1179

**agno-agi/agno — v3.0.0** · 2026-08-24 · [release notes](https://github.com/agno-agi/agno/releases/tag/v3.0.0)

> * fix: repair four imports that do not resolve in cookbooks by @tonydzi in https://github.com/agno-agi/agno/pull/9498
> * @tonydzi made their first contribution in https://github.com/agno-agi/agno/pull/9498

**michellzappa/headroom — v2.0.8** · 2026-08-26 · [release notes](https://github.com/michellzappa/headroom/releases/tag/v2.0.8)

> (#28, reported by @tonydzi). Claude Code writes one JSONL line per content

**Lyellr88/marm-memory — v2.45.0** · 2026-08-29 · [release notes](https://github.com/Lyellr88/marm-memory/releases/tag/v2.45.0)

> The README published to PyPI carried 17 links written relative to the repository root, a position neither surface that renders that file ever occupies. Reported and fixed by [@tonydzi](https://github.com/tonydzi).
> * docs(pypi): make the PyPI README's links absolute so they resolve by @tonydzi in https://github.com/Lyellr88/marm-memory/pull/180
> * @tonydzi made their first contribution in https://github.com/Lyellr88/marm-memory/pull/180

**QwenLM/qwen-code — cua-driver-rs-v0.20.3** · 2026-09-01 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/cua-driver-rs-v0.20.3)

> * fix(core): do not claim a question host in stream-json direct mode by @tonydzi in https://github.com/QwenLM/qwen-code/pull/9414
> * @tonydzi made their first contribution in https://github.com/QwenLM/qwen-code/pull/9414

**Lyellr88/marm-memory — v2.46.2** · 2026-09-02 · [release notes](https://github.com/Lyellr88/marm-memory/releases/tag/v2.46.2)

> The 8 tests in `tests/test_docker_transports.py` that actually start a container previously only ran in the release workflow, which triggers on a version tag, so a Docker runtime regression was caught after a release was already tagged rather than on the PR that caused it. Contributed by [@tonydzi](https://github.com/tonydzi).
> `scripts/test-scripts/smoke_embedding_chunking.py` had been broken since chunking was split into separate memory and document profiles: it imported constants that no longer existed and called `_chunk_text` without the keyword arguments it now requires. Contributed by [@tonydzi](https://github.com/tonydzi).
> * fix(scripts): repair smoke_embedding_chunking against the v2.14.0 chunk profiles by @tonydzi in https://github.com/Lyellr88/marm-memory/pull/181
> * ci: build the image on PRs and run the docker-marked tests (#170 item 1) by @tonydzi in https://github.com/Lyellr88/marm-memory/pull/183

**modelcontextprotocol/go-sdk — v1.8.0-pre.1** · 2026-09-04 · [release notes](https://github.com/modelcontextprotocol/go-sdk/releases/tag/v1.8.0-pre.1)

> - docs: make the protocol.md table of contents resolve by [@tonydzi](https://github.com/tonydzi) ([#1196](https://github.com/modelcontextprotocol/go-sdk/pull/1196))
> - docs: fix the streamable client snippet to use (*Client).Connect by [@tonydzi](https://github.com/tonydzi) ([#1142](https://github.com/modelcontextprotocol/go-sdk/pull/1142))
> - docs: quick start `go get` leaves the module unbuildable by [@tonydzi](https://github.com/tonydzi) ([#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148))
> - docs: fix four dead links to the Multi Round-Trip Requests section by [@tonydzi](https://github.com/tonydzi) ([#1159](https://github.com/modelcontextprotocol/go-sdk/pull/1159))
> * @tonydzi made their first contribution in https://github.com/modelcontextprotocol/go-sdk/pull/1142

**modelcontextprotocol/go-sdk — v1.8.0-pre.2** · 2026-09-04 · [release notes](https://github.com/modelcontextprotocol/go-sdk/releases/tag/v1.8.0-pre.2)

> - docs: make the protocol.md table of contents resolve by [@tonydzi](https://github.com/tonydzi) ([#1196](https://github.com/modelcontextprotocol/go-sdk/pull/1196))
> - docs: fix the streamable client snippet to use (*Client).Connect by [@tonydzi](https://github.com/tonydzi) ([#1142](https://github.com/modelcontextprotocol/go-sdk/pull/1142))
> - docs: quick start `go get` leaves the module unbuildable by [@tonydzi](https://github.com/tonydzi) ([#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148))
> - docs: fix four dead links to the Multi Round-Trip Requests section by [@tonydzi](https://github.com/tonydzi) ([#1159](https://github.com/modelcontextprotocol/go-sdk/pull/1159))
> * @tonydzi made their first contribution in https://github.com/modelcontextprotocol/go-sdk/pull/1142

**mixelpixx/Konnect — v0.11.1** · 2026-09-07 · [release notes](https://github.com/mixelpixx/Konnect/releases/tag/v0.11.1)

> * fix(placement): stop scoring connector filter caps as decoupling defects by @tonydzi in https://github.com/mixelpixx/Konnect/pull/416

**modelcontextprotocol/go-sdk — v1.8.0** · 2026-09-14 · [release notes](https://github.com/modelcontextprotocol/go-sdk/releases/tag/v1.8.0)

> - docs: make the protocol.md table of contents resolve by [@tonydzi](https://github.com/tonydzi) ([#1196](https://github.com/modelcontextprotocol/go-sdk/pull/1196))
> - docs: fix the streamable client snippet to use (*Client).Connect by [@tonydzi](https://github.com/tonydzi) ([#1142](https://github.com/modelcontextprotocol/go-sdk/pull/1142))
> - docs: quick start `go get` leaves the module unbuildable by [@tonydzi](https://github.com/tonydzi) ([#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148))
> - docs: fix four dead links to the Multi Round-Trip Requests section by [@tonydzi](https://github.com/tonydzi) ([#1159](https://github.com/modelcontextprotocol/go-sdk/pull/1159))
> * @tonydzi made their first contribution in https://github.com/modelcontextprotocol/go-sdk/pull/1142

**Lyellr88/marm-memory — v2.48.1** · 2026-09-16 · [release notes](https://github.com/Lyellr88/marm-memory/releases/tag/v2.48.1)

> * test(docker): the healthcheck could never report unhealthy (#170 item 5) by @tonydzi in https://github.com/Lyellr88/marm-memory/pull/185

**mixelpixx/Konnect — v0.12.0** · 2026-09-17 · [release notes](https://github.com/mixelpixx/Konnect/releases/tag/v0.12.0)

> - [#505](https://github.com/mixelpixx/Konnect/pull/505) — Discover KiCad sockets from metadata without probing by connection. — @tonydzi
> - [#442](https://github.com/mixelpixx/Konnect/pull/442) — Record running servers and sweep dead process records at startup. — @tonydzi

**Lyellr88/marm-memory — v2.49.0** · 2026-09-18 · [release notes](https://github.com/Lyellr88/marm-memory/releases/tag/v2.49.0)

> * test(docker): exposed mode authenticates, and MARM's managed Docker path never reaches the keyless fallback (#170 item 5) by @tonydzi in https://github.com/Lyellr88/marm-memory/pull/192

**chigwell/telegram-mcp — v3.2.42** · 2026-09-19 · [release notes](https://github.com/chigwell/telegram-mcp/releases/tag/v3.2.42)

> * feat: make per-tool extension allowlists configurable via TELEGRAM_FILE_EXTENSIONS (closes #226) by @tonydzi in https://github.com/chigwell/telegram-mcp/pull/227
> * @tonydzi made their first contribution in https://github.com/chigwell/telegram-mcp/pull/227

**langroid/langroid — 0.68.1** · 2026-09-23 · [release notes](https://github.com/langroid/langroid/releases/tag/0.68.1)

> are being walked through opening a PR (#1148, by @tonydzi).

**microsoft/semantic-kernel — python-1.45.0** · 2026-10-06 · [release notes](https://github.com/microsoft/semantic-kernel/releases/tag/python-1.45.0)

> * Python: pin the validated address for OpenAPI plugin requests by @tonydzi in https://github.com/microsoft/semantic-kernel/pull/14371
> * @tonydzi made their first contribution in https://github.com/microsoft/semantic-kernel/pull/14371

**langroid/langroid — 0.68.7** · 2026-10-07 · [release notes](https://github.com/langroid/langroid/releases/tag/0.68.7)

> `Task.run(turns=...)` or `Settings.max_turns`. Thanks to **@tonydzi**, whose

**QwenLM/qwen-code — v0.25.1-preview.1** · 2026-10-09 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/v0.25.1-preview.1)

> * test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor by @tonydzi in https://github.com/QwenLM/qwen-code/pull/13616

**QwenLM/qwen-code — v0.25.0-nightly.20261009.085a44f336** · 2026-10-09 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/v0.25.0-nightly.20261009.085a44f336)

> * test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor by @tonydzi in https://github.com/QwenLM/qwen-code/pull/13616

**QwenLM/qwen-code — v0.25.1-preview.2** · 2026-10-10 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/v0.25.1-preview.2)

> * test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor by @tonydzi in https://github.com/QwenLM/qwen-code/pull/13616

**QwenLM/qwen-code — v0.25.0-nightly.20261010.9763580b84** · 2026-10-10 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/v0.25.0-nightly.20261010.9763580b84)

> * test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor by @tonydzi in https://github.com/QwenLM/qwen-code/pull/13616

**QwenLM/qwen-code — v0.25.1** · 2026-10-11 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/v0.25.1)

> - test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor ([#13616](https://github.com/QwenLM/qwen-code/pull/13616)) by @tonydzi

**QwenLM/qwen-code — desktop-v0.25.1** · 2026-10-11 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/desktop-v0.25.1)

> * test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor by @tonydzi in https://github.com/QwenLM/qwen-code/pull/13616

**DeusData/codebase-memory-mcp — v0.12.0** · 2026-10-15 · [release notes](https://github.com/DeusData/codebase-memory-mcp/releases/tag/v0.12.0)

> - @tonydzi: the 17-tool documentation (#2225)

**langroid/langroid — 0.69.9** · 2026-10-16 · [release notes](https://github.com/langroid/langroid/releases/tag/0.69.9)

> @tonydzi in #1262 and are carried over with credit: an unterminated string

## Credited in other projects' files

Lines maintainers wrote into their own changelogs and contributor lists.

**QwenLM/qwen-code · [`CHANGELOG.md`](https://github.com/QwenLM/qwen-code/blob/c6018c63b53ed8bfb96a3048dfebcd541d4f682d/CHANGELOG.md)**

> - test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor ([#13616](https://github.com/QwenLM/qwen-code/pull/13616)) by @tonydzi

**eugeniughelbur/obsidian-second-brain · [`CHANGELOG.md`](https://github.com/eugeniughelbur/obsidian-second-brain/blob/7b098c2793651956eb3b5dc8e1ac2ccbe8a9d3de/CHANGELOG.md)**

> - **The write-time hook reported `payload keys: none` for a payload that had a path key one level up (#171, reported by @tonydzi).** A payload like `{"tool_name":"Write","file_path":"..."}` still exited 1 and stayed fail-closed, but the diagnostic listed only keys under `tool_input` and `args`. It n …
> - **`validate-ai-first.sh` exited 0, silently, when a write payload named a tool but carried no path key it knew (#171, the open item from @tonydzi's codex-cli reports).** The hook read `file_path` and `filePath` (and `args.*`); a host that sends the path under another key (`path`, `uri`) got exit 0 …

**basicmachines-co/basic-memory · [`CHANGELOG.md`](https://github.com/basicmachines-co/basic-memory/blob/a72751c5d626380dedeed30f55f7a80ba3dc710d/CHANGELOG.md)**

> @tonydzi for the report and fix (#1617, landed as #1619).

**Lyellr88/marm-memory · [`CONTRIBUTORS.md`](https://github.com/Lyellr88/marm-memory/blob/97871d57ce7abbf343e7a3637997c67a3056ca4e/CONTRIBUTORS.md)**

> - **Anton Dziatkovskii** ([@tonydzi](https://github.com/tonydzi)) —

**Lyellr88/marm-memory · [`CHANGELOG.md`](https://github.com/Lyellr88/marm-memory/blob/97871d57ce7abbf343e7a3637997c67a3056ca4e/CHANGELOG.md)**

> The 8 tests in `tests/test_docker_transports.py` that actually start a container previously only ran in the release workflow, which triggers on a version tag, so a Docker runtime regression was caught after a release was already tagged rather than on the PR that caused it. Contributed by [@tonydzi]( …
> `scripts/test-scripts/smoke_embedding_chunking.py` had been broken since chunking was split into separate memory and document profiles: it imported constants that no longer existed and called `_chunk_text` without the keyword arguments it now requires. Contributed by [@tonydzi](https://github.com/to …
> The README published to PyPI carried 17 links written relative to the repository root, a position neither surface that renders that file ever occupies. Reported and fixed by [@tonydzi](https://github.com/tonydzi).

**qualixar/superlocalmemory · [`CHANGELOG.md`](https://github.com/qualixar/superlocalmemory/blob/6a8c704964ef8240a600638a27d07a43224fe3d6/CHANGELOG.md)**

> Reported by @tonydzi (#122).

**michellzappa/headroom · [`CHANGELOG.md`](https://github.com/michellzappa/headroom/blob/57b7443bc239b643ac305aec8871584dbd405d36/CHANGELOG.md)**

> (#28, reported by @tonydzi). Claude Code writes one JSONL line per content

**borq168/radar-forge · [`digests/2026-08-08/ai-skills-en.md`](https://github.com/borq168/radar-forge/blob/55beba194fd51480c7cd4812702554743ae6cd55/digests/2026-08-08/ai-skills-en.md)**

> | plan-file-hygiene | #1479 | @tonydzi | Open, July 27 update | Lifecycle management for planning artifacts. Community credit to @halilxibrahim. |

**mcp-tool-shop-org/claude-synergy · [`products/mcp-go-sdk/releases/1.8.0.md`](https://github.com/mcp-tool-shop-org/claude-synergy/blob/4e59215fbdcca6f929717a8f80eeefeed808d41f/products/mcp-go-sdk/releases/1.8.0.md)**

> - docs: make the protocol.md table of contents resolve by [@tonydzi](https://github.com/tonydzi) ([#1196](https://github.com/modelcontextprotocol/go-sdk/pull/1196))
> - docs: fix the streamable client snippet to use (*Client).Connect by [@tonydzi](https://github.com/tonydzi) ([#1142](https://github.com/modelcontextprotocol/go-sdk/pull/1142))
> - docs: quick start `go get` leaves the module unbuildable by [@tonydzi](https://github.com/tonydzi) ([#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148))
> - docs: fix four dead links to the Multi Round-Trip Requests section by [@tonydzi](https://github.com/tonydzi) ([#1159](https://github.com/modelcontextprotocol/go-sdk/pull/1159))
> * @tonydzi made their first contribution in https://github.com/modelcontextprotocol/go-sdk/pull/1142

**mcp-tool-shop-org/claude-synergy · [`products/mcp-go-sdk/releases/1.8.0-pre.1.md`](https://github.com/mcp-tool-shop-org/claude-synergy/blob/4e59215fbdcca6f929717a8f80eeefeed808d41f/products/mcp-go-sdk/releases/1.8.0-pre.1.md)**

> - docs: make the protocol.md table of contents resolve by [@tonydzi](https://github.com/tonydzi) ([#1196](https://github.com/modelcontextprotocol/go-sdk/pull/1196))
> - docs: fix the streamable client snippet to use (*Client).Connect by [@tonydzi](https://github.com/tonydzi) ([#1142](https://github.com/modelcontextprotocol/go-sdk/pull/1142))
> - docs: quick start `go get` leaves the module unbuildable by [@tonydzi](https://github.com/tonydzi) ([#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148))
> - docs: fix four dead links to the Multi Round-Trip Requests section by [@tonydzi](https://github.com/tonydzi) ([#1159](https://github.com/modelcontextprotocol/go-sdk/pull/1159))
> * @tonydzi made their first contribution in https://github.com/modelcontextprotocol/go-sdk/pull/1142

**mcp-tool-shop-org/claude-synergy · [`products/mcp-go-sdk/releases/1.8.0-pre.2.md`](https://github.com/mcp-tool-shop-org/claude-synergy/blob/4e59215fbdcca6f929717a8f80eeefeed808d41f/products/mcp-go-sdk/releases/1.8.0-pre.2.md)**

> - docs: make the protocol.md table of contents resolve by [@tonydzi](https://github.com/tonydzi) ([#1196](https://github.com/modelcontextprotocol/go-sdk/pull/1196))
> - docs: fix the streamable client snippet to use (*Client).Connect by [@tonydzi](https://github.com/tonydzi) ([#1142](https://github.com/modelcontextprotocol/go-sdk/pull/1142))
> - docs: quick start `go get` leaves the module unbuildable by [@tonydzi](https://github.com/tonydzi) ([#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148))
> - docs: fix four dead links to the Multi Round-Trip Requests section by [@tonydzi](https://github.com/tonydzi) ([#1159](https://github.com/modelcontextprotocol/go-sdk/pull/1159))
> * @tonydzi made their first contribution in https://github.com/modelcontextprotocol/go-sdk/pull/1142

**linny006/mcp-servers-live · [`r/tonydzi/telegram-mcp-kit/index.html`](https://github.com/linny006/mcp-servers-live/blob/a3cff717592ebd0d3dbec00ae88eb9d61faeeda3/r/tonydzi/telegram-mcp-kit/index.html)**

> <title>tonydzi/telegram-mcp-kit - entry on MCP Servers Live</title>
> <link rel="canonical" href="https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-mcp-kit/">
> <meta property="og:title" content="tonydzi/telegram-mcp-kit - entry on MCP Servers Live">
> <meta property="og:url" content="https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-mcp-kit/">
> <meta name="twitter:title" content="tonydzi/telegram-mcp-kit - entry on MCP Servers Live">
> <script type="application/ld+json">{"@context":"https://schema.org","@type":"SoftwareSourceCode","name":"tonydzi/telegram-mcp-kit","codeRepository":"https://github.com/tonydzi/telegram-mcp-kit","programmingLanguage":"PowerShell","url":"https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-m …

**linny006/mcp-servers-live · [`r/tonydzi/whatsapp-mcp-kit/index.html`](https://github.com/linny006/mcp-servers-live/blob/a3cff717592ebd0d3dbec00ae88eb9d61faeeda3/r/tonydzi/whatsapp-mcp-kit/index.html)**

> <title>tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live</title>
> <link rel="canonical" href="https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-kit/">
> <meta property="og:title" content="tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live">
> <meta property="og:url" content="https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-kit/">
> <meta name="twitter:title" content="tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live">
> <script type="application/ld+json">{"@context":"https://schema.org","@type":"SoftwareSourceCode","name":"tonydzi/whatsapp-mcp-kit","codeRepository":"https://github.com/tonydzi/whatsapp-mcp-kit","programmingLanguage":"Python","url":"https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-k …

**linny006/mcp-servers-live · [`r/tonydzi/sqlite-graph-memory/index.html`](https://github.com/linny006/mcp-servers-live/blob/a3cff717592ebd0d3dbec00ae88eb9d61faeeda3/r/tonydzi/sqlite-graph-memory/index.html)**

> <title>tonydzi/sqlite-graph-memory - entry on MCP Servers Live</title>
> <link rel="canonical" href="https://linny006.github.io/mcp-servers-live/r/tonydzi/sqlite-graph-memory/">
> <meta property="og:title" content="tonydzi/sqlite-graph-memory - entry on MCP Servers Live">
> <meta property="og:url" content="https://linny006.github.io/mcp-servers-live/r/tonydzi/sqlite-graph-memory/">
> <meta name="twitter:title" content="tonydzi/sqlite-graph-memory - entry on MCP Servers Live">
> <script type="application/ld+json">{"@context":"https://schema.org","@type":"SoftwareSourceCode","name":"tonydzi/sqlite-graph-memory","codeRepository":"https://github.com/tonydzi/sqlite-graph-memory","programmingLanguage":"Python","url":"https://linny006.github.io/mcp-servers-live/r/tonydzi/sqlite-g …

**DanceNitra/agora · [`probes/recheck_figures_91188_units.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/recheck_figures_91188_units.py)**

> by_tonydzi = gh("repos/anthropics/claude-code/issues/91188/comments",
> '.[] | select(.user.login=="tonydzi") | .body')
> thread = body + by_tonydzi + by_pm25
> "tonydzi carried it there today; the draft references the unit once and proves nothing")
> chk("tonydzi asked it, and the draft says so",
> "@tonydzi asked @niels-roest whether that target", asked in by_tonydzi,

**QwenLM/qwen-code-docs · [`website/content/zh/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/zh/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 首次贡献：stream-json 模式提问宿主修复 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/en/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/en/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 First contribution: fix for question host in stream-json mode | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/de/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/de/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Erster Beitrag: Fix für Frage-Host im stream-json-Modus | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**DanceNitra/agora · [`probes/a_cut_delivery_redacted_for_detector_controls.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/a_cut_delivery_redacted_for_detector_controls.py)**

> and @tonydzi pointed out that a check which has never been red is an untested instrument: the zero

**QwenLM/qwen-code-docs · [`website/content/ko/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/ko/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 첫 기여: stream-json 모드 질문 호스트 수정 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/fr/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/fr/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Première contribution : correction de l'hôte de questionnement en mode stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ja/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/ja/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 初貢献：stream-json モードの質問ホストの修正 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ru/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/ru/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Первый вклад: исправление запросов к хосту в режиме stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**DanceNitra/agora · [`probes/what_our_own_index_actually_delivers.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/what_our_own_index_actually_delivers.py)**

> trap @tonydzi described on anthropics/claude-code#91188 for bytes against units.

**DanceNitra/agora · [`probes/does_a_folded_scalar_description_arrive_at_the_model.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/does_a_folded_scalar_description_arrive_at_the_model.py)**

> WHY. anthropics/claude-code#81081, comment of 2026-09-15 by @tonydzi: on a shelf of 189 skills,
> "claim_under_test": "anthropics/claude-code#81081, @tonydzi 2026-09-15: a `description: >` folded "

**QwenLM/qwen-code-docs · [`website/content/pt-BR/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/1fae31bfdd5b732f93667264e4cf0360ec20636e/website/content/pt-BR/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Primeira contribuição: correção do host de perguntas no modo stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**DanceNitra/agora · [`probes/the_reminders_advice_switches_unit_at_125_units_per_line.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/the_reminders_advice_switches_unit_at_125_units_per_line.py)**

> He has no `claude` binary and took the identifier shapes from @tonydzi's greps. This reads the
> 125 units per line. But the threshold was named in that thread by @tonydzi and @pm25coder before us,
> ("tonydzi index (his counts)", 8188, 72),

**DanceNitra/agora · [`probes/the_cap_on_windows_and_what_a_crlf_line_costs.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/the_cap_on_windows_and_what_a_crlf_line_costs.py)**

> @tonydzi is darwin-arm64 and has annotated his own Windows figure as unverified. There is no

**DanceNitra/agora · [`probes/the_cut_measured_by_what_the_index_DOES_not_what_it_says.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/the_cut_measured_by_what_the_index_DOES_not_what_it_says.py)**

> Windows, current CC. @JhouCode is linux-x64, @tonydzi darwin-arm64 and has annotated his own Windows

**Kaap10/kaap10.github.io · [`src/pages/opensource/sqlite-graph-memory.js`](https://github.com/Kaap10/kaap10.github.io/blob/e4b467a17431e945ff42fc3978173abefb251fd7/src/pages/opensource/sqlite-graph-memory.js)**

> title: 'tonydzi/sqlite-graph-memory',
> github: 'https://github.com/tonydzi/sqlite-graph-memory',
> prsUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pulls?q=is%3Apr+is%3Amerged+author%3AKaap10',
> prUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pull/8',
> prUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pull/10',
> prUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pull/14',

**Lidozs55/oh-my-repo · [`research/knowledge/02-community-discussions.md`](https://github.com/Lidozs55/oh-my-repo/blob/9d2b7d395708540f278e0af7e86a133f77b0c2d9/research/knowledge/02-community-discussions.md)**

> - @tonydzi（+0，可测量子类，AI 署名"Mycroft"）：先排除"文件根本没进上下文"——CLAUDE.md/项目记忆/历史全部 keyed to cwd；审计一台工作站的 ~8700 个会话：4370 个起于 $HOME、2420 个起于 System32（终端和提权 shell 的默认目录），只有 1921 个起于项目目录——过半"为什么不遵守我的规则"的会话从未加载规则；诊断：查 ~/.claude/projects/（目录名编码了启动 cwd，肥大的 C--Users-<you> 目录是铁证）；修复：pin 终端默认起始目录+SessionStart hook 在 cwd …

**DanceNitra/agora · [`probes/the_memory_index_check_grew_a_second_size_and_the_team_path_grew_a_line_cap.py`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/the_memory_index_check_grew_a_second_size_and_the_team_path_grew_a_line_cap.py)**

> WHY. On anthropics/claude-code#91188 @tonydzi read CLI 2.1.202 on macOS and reported three things:
> * The team path DOES pass a lineCap, conditionally. @tonydzi's third finding does not reproduce

**DanceNitra/agora · [`probes/does_a_folded_scalar_description_arrive_at_the_model.result.json`](https://github.com/DanceNitra/agora/blob/067aa5aacaf90b734129ee3778ddd457645e23b6/probes/does_a_folded_scalar_description_arrive_at_the_model.result.json)**

> "claim_under_test": "anthropics/claude-code#81081, @tonydzi 2026-09-15: a `description: >` folded scalar arrives as a heading, 68 of 189 on their shelf",

## What maintainers replied

Replies in threads we opened, plus replies elsewhere that name this account. Quotes are trimmed; every one links to the original.

### [QwenLM/qwen-code PR #13312](https://github.com/QwenLM/qwen-code/pull/13312) — fix(mcp): name the capped server timeout in App read timeout warnings

*Role here: our pull request.*

*wenshao*, 2026-10-06:

> **Maintainer verification (round 2): `findings`** — 47/47 scripted assertions passed (wire A/B 32, TUI A/B 2, unit gates 2, mutation matrix 4, static gates 4, merge check 1, censuses 2). The pass count confirms every *predicted* behavior — including the prediction that R1-1 is real. Verified head `5245ba6fb6913d6c56c667fc36c8a7d5353d48ed` against merge-base `eb0b79c5b87d781cddc65c28e70955404eb928d3`; trial merge into current main (`fd4af70`) is conflict-free and the merged tree passes the affected suite 366/366. <details> <summary>中文摘要</summary> 第二轮验证结论：**有发现（findings）**——R1-1 在真实线级环境被端到端确认，合并决定取决于默认配置臂的措辞取舍（作者已明确把该决定留给维护者）。 - **历史发现状态**：R1-1 **仍然成立**（head 自上一轮以来未变，本轮全部重测）；R1-4 部分需要更正——其精确变异 …

*qwen-code-review-bot*, 2026-10-07:

> **[Suggestion]** R1-4: A written-but-non-finite server `timeout` becomes detectable at this line, but it is discarded with no diagnostic at any level — and the arm this diff adds for that case tells the operator `appResourceTimeoutMs (default 10000 ms)`, where the word "default" asserts they wrote nothing. `defaultTimeoutMs` is computed by a bare `boundedAppLimit` call (`:882`) that bypasses the `appResourceLimit` wrapper (`:828-844`), whose docblock says the diagnostic exists precisely because such a value "would be dropped without a trace while the limit warning names the key". The two sibling App keys do get an `Ignoring non-finite MCP App resource limit …` line, pinned by `expectDiscarde …

### [anthropics/claude-code issue #91188](https://github.com/anthropics/claude-code/issues/91188) — Feature request: make the auto-memory MEMORY.md compaction reminder threshold configurable

*Role here: our comment in their thread.*

*DanceNitra*, 2026-09-01:

> @niels-roest, your 17.1KB and the ~70% you read off it are both exact. The constants are literals, and there is a second half that changes what your knob would have to do. **Where the numbers come from.** The reminder builds one entry per dimension, each carrying a fraction of its own cap, and reports whichever is proportionally closest: ```js var ljo=0.8,HUn=0.7; function xut(e){ let n=[{frac:e.sizeBytes/e.byteCap,dimension:"bytes", capDesc:Ut(e.byteCap),targetDesc:Ut(Math.floor(e.byteCap*HUn))}]; if(e.lineCap!==void 0&&e.lineCount!==void 0) n.push({frac:e.lineCount/e.lineCap,dimension:"lines", capDesc:`${e.lineCap}-line`,targetDesc:`${Math.floor(e.lineCap*HUn)} lines`}); let{frac:r,...o}=n …

*DanceNitra*, 2026-09-03:

> @niels-roest, the reminder can be made to fire later. The branch that does it is one none of us had read, and finding it means retracting a sentence of my own. On 1 September I wrote that "raising the configured value raises the number you are told to aim for". That is wrong on the default path. The four fields at the call site go into one function, and that function is a selector: ```js function IHe({rawSizeBytes:e,surfaceCap:n,splicedSizeBytes:r,spliceCap:o,spliceActive:d}){ return n!==void 0 && (!d || e/n >= r/o) ? {sizeBytes:e,byteCap:n} : {sizeBytes:r,byteCap:o} } ``` `!d` short-circuits, so the two branches behave differently. With `spliceActive` true, the configured cap wins only whil …

### [google/adk-go PR #1543](https://github.com/google/adk-go/pull/1543) — feat(model/openaimodel): support image/file input via genai InlineData/FileData parts

*Role here: our pull request.*

*wojtas000*, 2026-10-01:

> @tonydzi thanks for keeping this moving. Please go ahead and rebase. Here's the shape we'd like. ## Where the conversion lives Option 1, with the shared piece kept endpoint-neutral. `internal/shared` should classify a part's `InlineData`/`FileData` into a plain value: kind (image, file, audio, video), source (data URL, file ID, URL), MIME type and filename. It should also own the empty-MIME rule, the named errors, and the `UnsupportedPayload`/`ReplayedReasoning` updates. It should not build openai-go types. The package already splits work this way: `SchemaToMap` and `CallTracker` return plain values, and each endpoint builds its own params. Each endpoint keeps its role rules, the ordering in …

*wojtas000*, 2026-10-05:

> @tonydzi thanks for getting commit 1 in early. Answers to your two questions: 1. Requiring a MIME type on `FileData` as well: agreed. On Responses the kind decides between `input_image` and `input_file` for both file IDs and URLs, so a URI alone isn't enough. 2. A missing filename on inline file data: please don't error in Chat Completions. Parts built with `genai.NewPartFromBytes` carry no display name, so an error would reject ordinary PDF uploads and artifacts there. Use the display name when there is one, and otherwise a name derived from the MIME type, for example `file.pdf`. Neither the docs nor openai-go mark `filename` as required, so please check in your live run whether the API nee …

### [bytedance/deer-flow PR #5843](https://github.com/bytedance/deer-flow/pull/5843) — fix(docs): harness docs document an async client API that does not exist

*Role here: our pull request.*

*WillemJiang*, 2026-09-25:

> @tonydzi Thanks for your contribution, please click the CLA assistant button to sign the CLA then we can merge your code.

*WillemJiang*, 2026-09-27:

> @tonydzi, please click the CLA button posted by the CLA assistant in the PR comments to sign the CLA.

### [run-llama/llama_index issue #23122](https://github.com/run-llama/llama_index/issues/23122) — Integration proposal: memory store with verified transfer — export/import sealed memory bundles

*Role here: our comment in their thread.*

*Kaushalt2004*, 2026-10-03:

> Both of these are right, and they're different sizes of right. **On the chain test — yes, and I'd rather you write it than me.** You spotted it, you built the vector it protects, and the shape you describe is exactly the one this thread has earned: enumerate the links by name, assert each exists at its registered path, runs, and *fails when its own subject is disabled*. The third clause is the one that makes it a test rather than an import check, and it's the clause most people skip. `tests/` next to `seam_mutation.py`, failing loudly on structural drift with the name of the link it lost — that's the right home and the right failure mode. Land it and I'll verify it the same way as the last t …

*eddyflores100-lang*, 2026-09-30:

> @tonydzi — took your suggestion to its conclusion, because the second-order edge you named was the real indictment: a red whose message accuses the source of drifting when the event was "someone defeated this first" is a tripwire that can't be trusted to describe its own firings. The tripwire is now semantic, like its sibling: [cognicore-dev/cognicore-env#145](https://github.com/cognicore-dev/cognicore-env/pull/145). The mutation is a runtime patch at the recall seam — every query "finds" every stored entry, so `dark` is always empty and the verdict can never fire, while `if dark:` stays byte-identical. Your mutation B, expressed as a patch instead of a source edit. What falls out of that: - …

### [google/adk-go PR #1299](https://github.com/google/adk-go/pull/1299) — fix(configurable): apply config_path containment to workflow node refs

*Role here: our pull request.*

*karolpiotrowicz*, 2026-09-01:

> The containment fix itself holds up. I checked out the branch and drove the traversal through `FromConfig` rather than the helper: on the merge-base a workflow edge naming `../../outside.yaml` loads and builds the workflow, and on this branch both that and the absolute-path form are refused. The full suite shows no new failures against the merge-base, and the routing through one shared helper ahead of both the read and the cache lookup is the right shape. One thing needs settling before this merges, and it is the behaviour change @jjsasha63 already flagged as needing a wider note — it is wider than it currently reads. ## Refusing every link, not just escaping ones, breaks whole config layout …

*karolpiotrowicz*, 2026-09-04:

> Every ask from my last review is answered, and I checked each one against the branch rather than reading the response commits. The trade is stated in the description now, with the ConfigMap consequence and two concrete routes for an operator on such a mount. `TestResolveConfigReferenceRefusesLinksThatStayInside` pins the behaviour the change deliberately chooses, and it discriminates: reverting the walk to resolve-the-link-and-refuse-only-if-it-escapes fails that test and no other, with the escaping-symlink case still green. The `EvalSymlinks` block now has both a comment that describes what it actually does and a test that fails if you delete it. ENOTDIR, the empty-reference diagnostic, the …

### [microsoft/agent-framework PR #7581](https://github.com/microsoft/agent-framework/pull/7581) — Python: bind tool-approval responses to surfaced approval requests (#7383)

*Role here: our pull request.*

*eavanvalkenburg*, 2026-08-26:

> @tonydzi thanks for working on this, i think the overall idea makes sense, the thing that is tricky here is that there is only so much we can do, because if a attacker has access to your session store they can change that version of the FCC and have it executed, but at some point we need to trust something, and this does add a additional layer that is `less` user controlled (session vs input message), so a improvement nonetheless. So let's get this in shape and then I will do a deeper dive. I'm also thinking about ID's, whether call_id is the right one, since some chat clients do not generate them...

*eavanvalkenburg*, 2026-09-01:

> @tonydzi, thank you for putting this draft together and especially for reproducing and documenting the failure modes raised in review. The core record/rebind/consume mechanism landed independently in #7631, so this branch is now superseded. I'm closing it in favor of #7988, which carries forward the remaining work around stable local approval occurrence identities, replay coverage, provider correlation, and the trusted-storage boundary. The investigation and review findings here directly shaped that PR—thank you.

### [QwenLM/qwen-code PR #13616](https://github.com/QwenLM/qwen-code/pull/13616) — test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor

*Role here: our pull request.*

*qwen-code-review-bot*, 2026-10-07:

> <!-- qwen-triage stage=1a --> @tonydzi Thanks for the PR — the underlying work looks carefully done, but it stops at the gate before code review: **the description doesn't follow the repository's PR template**, and that's a blocking check here. The body currently uses three free-form headings (`What this adds`, `How the two constraints from the issue are met`, `Verification`). None of the template's required sections are present: - `## What this PR does` - `## Why it's needed` - `## Reviewer Test Plan`, including `### How to verify`, `### Evidence (Before & After)`, `### Tested on` (the OS table), and `### Environment (optional)` - `## Risk & Scope` (main risk / not validated / breaking chan …

*qwen-code-review-bot*, 2026-10-08:

> **APPROVE at `acb10a6b`, withdrawing my CHANGES_REQUESTED at `2802ed1e`.** The template blocker is cleared — the description now carries every required section including the `Tested on` table and the zh-CN block — and this pass is the code review that had not happened yet. It finds nothing blocking. What the new witness gets right, checked against the failure it exists to catch (#12877): - It fails loudly on the actual regression shapes: a single Linux leg bumped to `ubuntu-24.04` or swept to `ubuntu-latest` trips the named per-leg assertion; deleting a leg trips `linuxLegs.length >= 2`. - It cannot fail silently on shape drift. The matrix walk keys on whole `- name:` entries with adjacent q …

### [Jason-Vaughan/TangleClaw issue #1400](https://github.com/Jason-Vaughan/TangleClaw/issues/1400) — [bug] Primary-checkout guard hook fails silently due to || true

*Role here: our comment in their thread.*

*Jason-Vaughan*, 2026-09-23:

> Thanks @tonydzi — this was genuinely useful, and it prompted me to audit that path more closely. I am removing the outer `|| true`, but with one important distinction: the primary-checkout guard is a safety interlock rather than a security boundary, so an internal guard failure still has to remain non-blocking. A deliberate refusal and a guard crash are separate outcomes; I don't want a bug in the interlock itself to strand the Claude Code session it is protecting. The false positive case you described turns out not to apply to TangleClaw's implementation. File and notebook operations don't infer targets from command text. They arrive as structured paths, are resolved to absolute/symlink-res …

*Jason-Vaughan*, 2026-10-10:

> @tonydzi Accepted, with one translation, because the route here is not git's. This guard is not a git hook. It is a tool-call hook the agent engine runs before a write or a HEAD-moving git command, registered in a machine-local settings file and invoked as `node <absolute path>`. So `core.hooksPath` and the executable bit have no equivalent failure here: git never resolves this path, and nothing needs `chmod`. Your underlying point survives the translation intact. Our current self-test reads the command from the settings file the installer wrote and runs it itself. That proves the wired command refuses. It does not prove the engine loaded that registration for the session it is supposed to p …

### [tenequm/pond PR #321](https://github.com/tenequm/pond/pull/321) — fix(schedule): report a systemd timer with no next elapse as broken

*Role here: our pull request.*

*tenequm*, 2026-09-30:

> **[Blocking]** The second remedy here, `pond schedule start`, is a no-op in every state this detector fires on. The detector only runs after `systemctl --user is-enabled` succeeded, and in the field case nothing edited the unit files - which is exactly `start_systemd`'s early-return condition (schedule.rs:822, `if unchanged && systemd_timer_enabled()`). The user sees `already scheduled (every 5m)` and the timer stays dead. Even past that check, `enable --now` issues a start job on an already-active (`elapsed`) unit - a no-op: systemd's `timer_start` asserts `TIMER_DEAD`/`TIMER_FAILED`, and daemon-reload coldplug re-enters `ELAPSED` verbatim (checked against timer.c). And for a stopped or fai …

*tenequm*, 2026-09-30:

> Sharp find, solid evidence - the red-first tests and the real-host capture that overturned the issue's suggested `NextElapseUSecRealtime` reading are exactly how this kind of fix should arrive. Requesting changes on one defect: the message's `pond schedule start` remedy is a no-op in every state this detector fires on (details inline), which collides with pond's rule that a detected bad state names the exact working recovery command. 3 blocking asks (one is comment-only) and 3 non-blocking suggestions, all inline. `cargo fmt --check` / `cargo clippy --all-targets -- -D warnings` / `cargo test` are green locally on this branch (macOS; CI had not yet been approved to run when I reviewed). Pond …

### [microsoft/semantic-kernel PR #14199](https://github.com/microsoft/semantic-kernel/pull/14199) — Python: Add experimental FunctionAuthorizationFilter for auto function invocation (runtime authorization, argument-bound approvals)

*Role here: our pull request.*

*babyblueviper1*, 2026-07-27:

> Reviewed the actual implementation, not just the description — the `args_digest` binding is real and sound: `sha256(function_name | args_digest | principal | policy_digest)` over a structurally type-tagged canonicalization (the `_canonicalize` method), which is the right defense against a hostile `__str__` producing a digest collision. That's a genuinely non-obvious detail to get right and it's handled correctly here. This directly answers the question I raised on #14072 about whether a dispatcher verifies the stored draft against what actually executes — it does, cryptographically, by construction: `transfer(amount=10)` approved can never authorize `transfer(amount=10000)` executed, because …

*babyblueviper1*, 2026-07-27:

> Worth pulling the automated DevFlow finding above into the same class of gap this thread's been naming, since it's a real one and distinct from the attribution question: the `args_digest` binding I checked earlier is sound (replay/tamper is structurally prevented), but that's orthogonal to *when* enforcement actually happens. `asyncio.gather(...)` dispatches every tool call in a model response concurrently and only inspects `terminate` after the whole batch resolves — so a `pending_approval` verdict on call N doesn't stop sibling calls in the same batch from having already executed by the time `terminate` is checked. The digest math being unforgeable doesn't help if the enforcement point and …

### [pydantic/pydantic-ai issue #8551](https://github.com/pydantic/pydantic-ai/issues/8551) — An uninstrumented delegate's usage is credited to the caller's agent run span

*Role here: our issue report.*

*yetuge*, 2026-09-20:

> Picking up @84dnnvbdvp-debug's durable edge and this thread's open caveat: I built a local harness for it, and the replay leak reproduces on `main` (c4898ab). That discharges the "durable-execution interaction unverified" caveat @tonydzi left open — the run-entry ownership move now has a concrete success criterion on this path. Shape: instrumented parent (FunctionModel) → uninstrumented durable delegate, where the delegate carries a durable capability operation that folds a usage delta across the boundary. Two consecutive `parent.run()` calls, so the second one replays the delegate's operation instead of re-executing its body. Span attributes read off an in-memory OTel exporter: ``` run1 (fi …

*qaisermehdi3-coder*, 2026-09-23:

> @tonydzi thanks for testing it again instead of agreeing. two small things from my side. 1. the marker summing into RunUsage is the part that matters most. i hit this in my own tool tonight: calls were marked unknown, but the per task average still used them. two workflows doing identical work, one with a call that returned no usage, showed $1.00 per task vs $2.00. the half measured one looked twice as cheap. marking the request is not enough, the total it rolls into has to carry the mark, and yours does. 2. on the streaming path: in openai chat streams every chunk except the last has usage None, and without include_usage all of them do. you said incr only counts requests because _map_usage …

### [BerriAI/litellm PR #43795](https://github.com/BerriAI/litellm/pull/43795) — fix(fallback_utils): respect top-level `fallbacks` parameter in `async_completion_with_fallbacks`

*Role here: our comment in their thread, our review of their PR.*

*chauvuusvn*, 2026-10-12:

> Hi @tonydzi (Mycroft), Thank you for the exceptionally thorough review and offline trace. Tracing the recursive re-entry at `main.py:657` and catching the telemetry zeroing (`x-litellm-attempted-fallbacks: 0`) alongside the duplicate billing in mixed-mode calls was spot-on. I fully concede the diagnosis: 1. **Root cause & telemetry**: The unpatched code did not drop fallbacks silently; leaking `fallbacks` into `base_kwargs` triggered unintended recursive re-entry, resulting in corrupted telemetry headers (`0` instead of the actual fallback index) and duplicate/out-of-order attempts in mixed configurations. 2. **Test harness blind spot**: Mocking `acompletion` directly masked the recursive ca …

*chauvuusvn*, 2026-10-14:

> Hi @tonydzi, Great catch on the dictionary deduplication edge case! You're completely right: collapsing on the model string alone silently drops valid multi-endpoint configurations (e.g. EU vs US endpoints or quota-spreading keys for the same underlying model). Updated in commit [`880de42`](https://github.com/BerriAI/litellm/pull/43795/commits/880de42e13b4b8da978818f6191c0f6bd4d2219b): 1. **Full Dict Payload Keying:** Dedupes dictionary entries by their full sorted2 JSON payload (`json.dumps(fb, sort_keys=True, default=str)`), while keeping bare string identifiers as-is. Distinct endpoints sharing the same model name are now cleanly preserved. 2. **Regression Test:** Added `test_same_model_d …

### [Lyellr88/marm-memory PR #192](https://github.com/Lyellr88/marm-memory/pull/192) — test(docker): exposed mode authenticates, and MARM's managed Docker path never reaches the keyless fallback (#170 item 5)

*Role here: our pull request.*

*Lyellr88*, 2026-09-17:

> @tonydzi Thank you for the continued work on this. The revised tests clearly separate the managed keyless-start security contract from persistence, cover the exposed-network path without relying on host behavior that is not portable, and protect the probes from ambient proxy interference. Everything is green and the review is complete. Merging this now. Please keep an eye on the open issues if another area interests you.

*Lyellr88*, 2026-09-16:

> I apologize for the delay; I've been working on a new build plus the power outage I dealt with pulled my focus in multiple directions. Thanks for the focused Docker coverage and for including both CI and mutation-test evidence. I verified the tests run in the Docker CI job and agree that the intended auth cases are worth covering. 1. `marm-mcp-server/tests/test_docker_transports.py:659-711`: the no-key test currently requires a persisted `/home/marm/.marm/.env` key via `docker exec`, but the security property under review is that the loopback fallback is unreachable. `marm_mcp_server/config/api_key_bootstrap.py:53-86` can retain a generated key in memory while declining persistence if secure …

### [anthropics/claude-code issue #90542](https://github.com/anthropics/claude-code/issues/90542) — [BUG] A complete CLAUDE.md rule contract governed nothing: 9 fabricated causes, stale state asserted as current, acceptance step silently skipped across a 4.5h session

*Role here: our comment in their thread.*

*rulereceipt*, 2026-09-14:

> @stonianua — measured, and you were right about the scope. Branch policy took the first backtick literal in any rule containing the word "branch" and called it a branch name. Across 559 rules files, 37 of the 70 rules routed there (52.9%) were handed something that cannot be a branch — a naming template `squad/{issue-number}-{kebab-case-slug}`, whole commands, one entire fenced markdown block. The report said: no git command targeted the `git push --force` branch this session. Now 0 of 45. Claim-evidence was the same fault. Reporting verb, evidence noun, done-word, each anywhere in the rule, independently. A 944-character rule about writing status updates satisfied all three across three par …

*rulereceipt*, 2026-09-16:

> @stonianua — named and fixed, and the harness had a flaw of its own. That one first, because it changes my last number. I said it pins its inputs. It picks the largest sessions deterministically, which is not the same as reading the same bytes twice — and the largest here include the session doing the measuring, appended to while it runs. 26 texts became 27 with no code change, because 2MB of transcript arrived in between. Each input now prints the sha256 of what was read. Pinned: 30 of 2,795 reports, 1.1%, 22 texts. The causes. The heredoc guard existed and was wired into one reader — I wrote it for test-command detection and never applied it to file mutations, so a command editing landing/ …

## Full index

Every position we opened, newest first. Full bodies and every reply are in [`evidence-index.json`](evidence-index.json).

| Repository | # | Kind | State | Title |
|---|---|---|---|---|
| lukalotl/polyp.observer | [#2](https://github.com/lukalotl/polyp.observer/pull/2) | PR | open | Import the component files explicitly so case-insensitive filesystems resolve them |
| lukalotl/polyp.observer | [#1](https://github.com/lukalotl/polyp.observer/issues/1) | issue | open | Build and run creator break on case-insensitive filesystems (ScoreExamples.tsx vs scoreExamples.ts) |
| anima-research/connectome-host | [#283](https://github.com/anima-research/connectome-host/pull/283) | PR | merged | fix(webui): a subagent's alert rows clear once it leaves the health snapshot |
| science-of-finetuning/diffing-toolkit | [#87](https://github.com/science-of-finetuning/diffing-toolkit/pull/87) | PR | merged | Fix missing layer norms after re-running ADL on a new layer, and raise a clear error |
| ComposioHQ/composio | [#4938](https://github.com/ComposioHQ/composio/pull/4938) | PR | open | fix(py): reject async trigger callbacks at registration |
| anima-research/agent-framework | [#402](https://github.com/anima-research/agent-framework/pull/402) | PR | open | fix(gate): load gate.json and privileged-users files saved with a UTF-8 BOM (#395) |
| langroid/langroid | [#1262](https://github.com/langroid/langroid/pull/1262) | PR | closed | docs: fix three broken tutorial snippets (LM Studio URL, SQLChatAgent, unterminated string) |
| caura-ai/caura | [#2088](https://github.com/caura-ai/caura/pull/2088) | PR | open | docs: fix stale caura_manage op list and moved document_repository path |
| NVIDIA-NeMo/Speech | [#16385](https://github.com/NVIDIA-NeMo/Speech/pull/16385) | PR | open | Fix corpus cpWER aggregation across sessions |
| SeemSeam/claude_codex_bridge | [#393](https://github.com/SeemSeam/claude_codex_bridge/issues/393) | issue | open | mobile_gateway: paired device token is not bound to its project (cross-project upload/message) |
| onetrust-oss/ai-guard-sdk | [#5](https://github.com/onetrust-oss/ai-guard-sdk/issues/5) | issue | open | redact(): out-of-range REDACT match is skipped silently but reported as applied (fails open) |
| Vigil-SOC/vigil | [#2272](https://github.com/Vigil-SOC/vigil/pull/2272) | PR | open | Expire an LLM job when its caller stops waiting |
| mariagorskikh/open-instinct | [#36](https://github.com/mariagorskikh/open-instinct/pull/36) | PR | merged | fix(scripts): run workspace checks on Windows |
| mariagorskikh/open-instinct | [#35](https://github.com/mariagorskikh/open-instinct/pull/35) | PR | merged | fix(inkbox): persist durable inbox on Windows |
| mariagorskikh/open-instinct | [#34](https://github.com/mariagorskikh/open-instinct/pull/34) | PR | merged | fix(policy): match escaped blocked merchant names |
| zilliztech/memsearch | [#796](https://github.com/zilliztech/memsearch/pull/796) | PR | open | fix(compact): time-stamp the Memory Compact heading (#768) |
| mariagorskikh/open-instinct | [#16](https://github.com/mariagorskikh/open-instinct/pull/16) | PR | merged | deploy: copy the context manifest into the gateway image so it builds |
| aiunderwriting/AIUC-1-Changelog | [#2](https://github.com/aiunderwriting/AIUC-1-Changelog/issues/2) | issue | open | A008: cover secrets returned by the agent runtime's own APIs, and require per-path redaction tests (real incident, google/adk-python, fixed 2026-10-03) |
| coreweave/forge-agent-lens-for-claude-code | [#194](https://github.com/coreweave/forge-agent-lens-for-claude-code/issues/194) | issue | open | Native Windows: daemon cannot bind its socket, and the hook ignores daemon_socket |
| zilliztech/memsearch | [#790](https://github.com/zilliztech/memsearch/pull/790) | PR | open | fix: let compact write into a store directory not named memory |
| headroomlabs-ai/headroom | [#4051](https://github.com/headroomlabs-ai/headroom/pull/4051) | PR | merged | docs(security): sync runtime-env knob table with RUNTIME_ENV_KNOBS |
| NVIDIA/SkillSpector | [#807](https://github.com/NVIDIA/SkillSpector/pull/807) | PR | merged | docs(dev): fix llm_analyzer_base source links |
| mariagorskikh/open-instinct | [#12](https://github.com/mariagorskikh/open-instinct/pull/12) | PR | merged | fix(policy): blocked merchants are missed unless the name is a top-level key |
| mariagorskikh/open-instinct | [#11](https://github.com/mariagorskikh/open-instinct/pull/11) | PR | merged | ci: build before typecheck so the check job can pass |
| QwenLM/qwen-code | [#13616](https://github.com/QwenLM/qwen-code/pull/13616) | PR | merged | test(desktop): pin both Linux release legs to the ubuntu-22.04 glibc floor |
| DasterProkio/awesome-ai-companion | [#43](https://github.com/DasterProkio/awesome-ai-companion/pull/43) | PR | closed | Add The Bible Framework (persona as versioned rules) to Memory & Identity |
| OWASP/www-project-agentic-skills-top-10 | [#89](https://github.com/OWASP/www-project-agentic-skills-top-10/pull/89) | PR | open | proposals/ast-fixture-corpus: AST09 actor-tamper vector (requested in #81) + two JCS canonicalization vectors |
| langroid/langroid | [#1191](https://github.com/langroid/langroid/pull/1191) | PR | closed | docs: task-termination guide passes single_round/done_if_response to TaskConfig, where they are silently ignored |
| ctxrs/ctx | [#1117](https://github.com/ctxrs/ctx/pull/1117) | PR | open | docs: fix broken link to the v0.4.0 Sift benchmark in README |
| pydantic/pydantic-ai | [#9835](https://github.com/pydantic/pydantic-ai/pull/9835) | PR | closed | fix(bedrock): keep every `nova_code_interpreter_result` toolResult content block |
| QwenLM/qwen-code | [#13312](https://github.com/QwenLM/qwen-code/pull/13312) | PR | open | fix(mcp): name the capped server timeout in App read timeout warnings |
| screenpipe/screenpipe | [#7401](https://github.com/screenpipe/screenpipe/issues/7401) | issue | open | Windows: communications-output loopback (USB speakerphone) dies 200ms after start with 'disconnected', while /health keeps reporting the device active — call far-end silently lost |
| pydantic/pydantic-ai | [#9444](https://github.com/pydantic/pydantic-ai/issues/9444) | issue | closed | A provider response with no usage object is recorded as zero tokens, not as unknown |
| tenequm/pond | [#321](https://github.com/tenequm/pond/pull/321) | PR | merged | fix(schedule): report a systemd timer with no next elapse as broken |
| basicmachines-co/basic-memory | [#1617](https://github.com/basicmachines-co/basic-memory/pull/1617) | PR | closed | fix(mcp): report the real checksum from write_note and edit_note (#1586) |
| ChromeDevTools/chrome-devtools-mcp | [#2852](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/2852) | PR | open | docs: correct CLI availability of extension tools |
| headroomlabs-ai/headroom | [#3832](https://github.com/headroomlabs-ai/headroom/pull/3832) | PR | merged | docs: mark HeadroomClient provider as required, not auto-detected |
| QwenLM/qwen-code | [#12875](https://github.com/QwenLM/qwen-code/pull/12875) | PR | closed | fix(core): add opt-in failMode: "closed" for PreToolUse command hooks |
| bytedance/deer-flow | [#5843](https://github.com/bytedance/deer-flow/pull/5843) | PR | merged | fix(docs): harness docs document an async client API that does not exist |
| deepset-ai/haystack | [#12889](https://github.com/deepset-ai/haystack/pull/12889) | PR | closed | fix: merge generation_kwargs tools with the component's own tools in OpenAIChatGenerator |
| anthropics/claude-code | [#95920](https://github.com/anthropics/claude-code/issues/95920) | issue | open | Scheduled tasks: nextFire returns a fabricated "now + 365 days" when no match falls inside its 366-day scan window |
| langroid/langroid | [#1148](https://github.com/langroid/langroid/pull/1148) | PR | merged | docs: fix dead github-cli link in CONTRIBUTING |
| browser-use/browser-use | [#5867](https://github.com/browser-use/browser-use/pull/5867) | PR | open | docs(actor): fix drag_to parameter name in Element API reference |
| teng-lin/notebooklm-py | [#2432](https://github.com/teng-lin/notebooklm-py/issues/2432) | issue | closed | wait_for_completion returns REMOVED for generations that completed — absence of task_id from the studio list is inferred, never verified (0.8.2) |
| QwenLM/qwen-code | [#12422](https://github.com/QwenLM/qwen-code/pull/12422) | PR | open | fix(acp): report max_tokens instead of end_turn on unresolved output truncation |
| LambdaLabsML/the_lab.api | [#7](https://github.com/LambdaLabsML/the_lab.api/issues/7) | issue | open | optimization/test_project: baseline fails its own accuracy gate on 3 of 7 kernels |
| LambdaLabsML/the_lab.api | [#6](https://github.com/LambdaLabsML/the_lab.api/pull/6) | PR | closed | fix(dashboard): install node dependencies before building |
| LambdaLabsML/the_lab.api | [#5](https://github.com/LambdaLabsML/the_lab.api/pull/5) | PR | closed | fix(mcp): resolve the API port from runtime.json instead of assuming 8000 |
| BerriAI/litellm | [#42172](https://github.com/BerriAI/litellm/issues/42172) | issue | open | [Bug]: anthropic/<model> with a third-party api_base receives the client's Claude subscription OAuth token instead of the deployment's configured api_key (with forward_llm_provider_auth_headers either on or off) |
| pydantic/pydantic-ai | [#8551](https://github.com/pydantic/pydantic-ai/issues/8551) | issue | closed | An uninstrumented delegate's usage is credited to the caller's agent run span |
| chigwell/telegram-mcp | [#227](https://github.com/chigwell/telegram-mcp/pull/227) | PR | merged | feat: make per-tool extension allowlists configurable via TELEGRAM_FILE_EXTENSIONS (closes #226) |
| mem0ai/mem0 | [#7361](https://github.com/mem0ai/mem0/pull/7361) | PR | open | docs(llms): Sarvam sampling params go inside the model dict |
| pydantic/pydantic-ai | [#8451](https://github.com/pydantic/pydantic-ai/issues/8451) | issue | closed | Concurrent delegate runs still over-report usage on their agent-run spans after #8417 |
| basicmachines-co/basic-memory | [#1578](https://github.com/basicmachines-co/basic-memory/issues/1578) | issue | closed | Harden HTTP/SSE transport: `basic-memory mcp` defaults to 0.0.0.0 with no auth (contradicts SECURITY.md) |
| oraios/serena | [#2048](https://github.com/oraios/serena/pull/2048) | PR | closed | docs(clients): fix CC system prompt override command (prompts print-cc-system-prompt-override) |
| DeusData/codebase-memory-mcp | [#2225](https://github.com/DeusData/codebase-memory-mcp/pull/2225) | PR | merged | docs: MCP tool count is 17; document get_file_outline, compare_graphs, check_index_coverage |
| LambdaLabsML/the_lab.api | [#4](https://github.com/LambdaLabsML/the_lab.api/pull/4) | PR | closed | fix(mcp): keep the bridge importable under the system python3 (3.9) |
| cristicretu/diri | [#305](https://github.com/cristicretu/diri/pull/305) | PR | merged | engine: sanitize bracketed text in Session::paste_text (#275) |
| NangoHQ/nango | [#7544](https://github.com/NangoHQ/nango/pull/7544) | PR | closed | feat(integrations): add support for huggingface |
| NangoHQ/nango | [#7543](https://github.com/NangoHQ/nango/pull/7543) | PR | closed | feat(integrations): add support for cohere |
| NangoHQ/nango | [#7542](https://github.com/NangoHQ/nango/pull/7542) | PR | closed | feat(integrations): add support for fireworks-ai |
| NangoHQ/nango | [#7541](https://github.com/NangoHQ/nango/pull/7541) | PR | closed | feat(integrations): add support for together-ai |
| NangoHQ/nango | [#7540](https://github.com/NangoHQ/nango/pull/7540) | PR | closed | feat(integrations): add support for groq |
| NangoHQ/nango | [#7539](https://github.com/NangoHQ/nango/pull/7539) | PR | closed | feat(integrations): add support for deepseek |
| NangoHQ/nango | [#7537](https://github.com/NangoHQ/nango/pull/7537) | PR | closed | feat(integrations): add support for mistral |
| Kong/kong | [#14999](https://github.com/Kong/kong/pull/14999) | PR | open | fix(ai-proxy): keep empty anthropic tools array |
| NangoHQ/nango | [#7533](https://github.com/NangoHQ/nango/pull/7533) | PR | open | feat(integrations): add support for lambda-cloud |
| NangoHQ/nango | [#7532](https://github.com/NangoHQ/nango/pull/7532) | PR | closed | feat(integrations): add support for openrouter |
| nanbingxyz/5ire | [#437](https://github.com/nanbingxyz/5ire/issues/437) | issue | open | Hardening: main BrowserWindow uses webSecurity:false + nodeIntegration:true (Electron security defaults) |
| openai/openai-agents-python | [#5026](https://github.com/openai/openai-agents-python/issues/5026) | issue | closed | Skills frontmatter parser mangles multi-line descriptions (folded >, literal \|, wrapped lines) in the skill index |
| basicmachines-co/basic-memory | [#1551](https://github.com/basicmachines-co/basic-memory/pull/1551) | PR | closed | feat(core): accept SQLite URLs in database_url (#539) |
| microsoft/playwright | [#42669](https://github.com/microsoft/playwright/issues/42669) | issue | closed | [BiDi] firefox channel="moz-firefox": driver crashes on console log of object with non-primitive toString/valueOf ("Cannot convert object to primitive value") |
| gklein/fullsend-autopilot | [#1](https://github.com/gklein/fullsend-autopilot/issues/1) | issue | open | unattended merges: how do you reconstruct what the agent did + roll back? |
| mixelpixx/Konnect | [#505](https://github.com/mixelpixx/Konnect/pull/505) | PR | merged | fix(platform): discover KiCad's socket from metadata, never by connecting |
| elgorro/aiquila | [#504](https://github.com/elgorro/aiquila/pull/504) | PR | merged | fix(mcp): treat Talk's 304 Not Modified as an empty result |
| google/adk-go | [#1543](https://github.com/google/adk-go/pull/1543) | PR | merged | feat(model/openaimodel): support image/file input via genai InlineData/FileData parts |
| osaurus-ai/osaurus | [#2669](https://github.com/osaurus-ai/osaurus/pull/2669) | PR | open | docs: fix six relative links that resolve to files that do not exist |
| areal-project/AReaL | [#1685](https://github.com/areal-project/AReaL/pull/1685) | PR | merged | docs: repoint doc links left behind by the bilingual docs split |
| zilliztech/memsearch | [#725](https://github.com/zilliztech/memsearch/pull/725) | PR | closed | feat(plugins): make the daily memory filename collision-safe on synced directories |
| llvm/llvm-project | [#221677](https://github.com/llvm/llvm-project/pull/221677) | PR | open | [Github] Make code-format-helper --extensions ordering deterministic |
| vansh7nvc/Abstractify | [#69](https://github.com/vansh7nvc/Abstractify/pull/69) | PR | merged | feat(export): add RIS citation exporter for Zotero and Mendeley (#10) |
| mixelpixx/Konnect | [#442](https://github.com/mixelpixx/Konnect/pull/442) | PR | merged | fix(platform): record each server and sweep dead records at startup |
| mixelpixx/Konnect | [#439](https://github.com/mixelpixx/Konnect/pull/439) | PR | closed | fix(drc): name what owns each DRC report item (#413) |
| mongodb-js/mongodb-mcp-server | [#1491](https://github.com/mongodb-js/mongodb-mcp-server/pull/1491) | PR | closed | docs: fix Azure deploy paths after the v3 multi-package move |
| darrenhinde/OpenAgentsControl | [#356](https://github.com/darrenhinde/OpenAgentsControl/pull/356) | PR | closed | docs: point plugin setup links at the sections that replaced the removed guides |
| microsoft/semantic-kernel | [#14371](https://github.com/microsoft/semantic-kernel/pull/14371) | PR | merged | Python: pin the validated address for OpenAPI plugin requests |
| Lyellr88/marm-memory | [#192](https://github.com/Lyellr88/marm-memory/pull/192) | PR | merged | test(docker): exposed mode authenticates, and MARM's managed Docker path never reaches the keyless fallback (#170 item 5) |
| ip2a/mcpstore | [#56](https://github.com/ip2a/mcpstore/issues/56) | issue | open | npm CLI install is broken: README names an unpublished package, and @ip2a/mcpstore ships no bin |
| bobmatnyc/claude-mpm | [#961](https://github.com/bobmatnyc/claude-mpm/pull/961) | PR | closed | docs: trusty-memory and trusty-search are cargo crates, not uv tools |
| mixelpixx/Konnect | [#416](https://github.com/mixelpixx/Konnect/pull/416) | PR | merged | fix(placement): stop scoring connector filter caps as decoupling defects |
| Lyellr88/marm-memory | [#185](https://github.com/Lyellr88/marm-memory/pull/185) | PR | merged | test(docker): the healthcheck could never report unhealthy (#170 item 5) |
| google/adk-python | [#6980](https://github.com/google/adk-python/issues/6980) | issue | open | AutoTracingPlugin rebinds what getmembers() returns, not what the class holds: @staticmethod becomes an instance method, @classmethod is never traced, base methods get pinned onto subclasses |
| microsoft/semantic-kernel | [#14355](https://github.com/microsoft/semantic-kernel/pull/14355) | PR | open | Python: document connector extras and optional dependency compatibility |
| Lyellr88/marm-memory | [#183](https://github.com/Lyellr88/marm-memory/pull/183) | PR | merged | ci: build the image on PRs and run the docker-marked tests (#170 item 1) |
| purarue/google_takeout_parser | [#97](https://github.com/purarue/google_takeout_parser/issues/97) | issue | open | html activity: file_dt is taken from the file's mtime, which does not survive copying (silent 1h offset) |
| zackproser/pr-babysitter | [#1](https://github.com/zackproser/pr-babysitter/issues/1) | issue | open | field notes from a month of running the same class of tool (digest drift, dead-mechanism silence, tombstones) |
| knowsuchagency/mcp2cli | [#107](https://github.com/knowsuchagency/mcp2cli/pull/107) | PR | closed | docs: bake example used an npm package that does not exist |
| runesleo/x-reader | [#25](https://github.com/runesleo/x-reader/pull/25) | PR | closed | docs: point Claude Code MCP setup at the file Claude Code reads |
| topoteretes/cognee-community | [#170](https://github.com/topoteretes/cognee-community/pull/170) | PR | closed | feat(connector): Reddit data-source connector (cognee#4811) |
| anthropics/claude-code | [#90962](https://github.com/anthropics/claude-code/issues/90962) | issue | open | [BUG] Windows: Write tool emits .ps1 without a BOM; PowerShell 5.1 parses it as ANSI and a mojibake quote kills the script - silently when scheduled (0x80070001, no log) |
| topoteretes/cognee-community | [#166](https://github.com/topoteretes/cognee-community/pull/166) | PR | closed | feat(connector): Telegram data-source connector (cognee#4730) |
| topoteretes/cognee-community | [#165](https://github.com/topoteretes/cognee-community/pull/165) | PR | closed | feat(connector): Obsidian vault data-source connector (cognee#4725) |
| getzep/graphiti | [#1810](https://github.com/getzep/graphiti/pull/1810) | PR | open | feat(mcp): surface ranker, scores, and invalidated-fact counts in search results (#1645) |
| Lyellr88/marm-memory | [#181](https://github.com/Lyellr88/marm-memory/pull/181) | PR | merged | fix(scripts): repair smoke_embedding_chunking against the v2.14.0 chunk profiles |
| anthropics/claude-code | [#90533](https://github.com/anthropics/claude-code/issues/90533) | issue | open | Scheduled tasks: one string fireAt (written by the app's own update_scheduled_task MCP) makes loadScheduledTasksFromDisk reject the whole registry — all routines silently stop |
| google/adk-python | [#6941](https://github.com/google/adk-python/issues/6941) | issue | closed | Session id is normalized on write but not on read: after bfeb04c a padded id creates a session that cannot be read, deleted, or re-created (in_memory and sqlite, incl. the adk web / adk run store) |
| punkpeye/fastmcp | [#344](https://github.com/punkpeye/fastmcp/pull/344) | PR | merged | docs(oauth): the "Cannot find module" fix suggested a broken import |
| Lyellr88/marm-memory | [#180](https://github.com/Lyellr88/marm-memory/pull/180) | PR | merged | docs(pypi): make the PyPI README's links absolute so they resolve |
| TsinghuaC3I/Awesome-Memory-for-Agents | [#38](https://github.com/TsinghuaC3I/Awesome-Memory-for-Agents/pull/38) | PR | merged | Product & Project: add sqlite-graph-memory (wikilink graph + SQLite, no graph DB) |
| aristoapp/awesome-second-brain | [#54](https://github.com/aristoapp/awesome-second-brain/pull/54) | PR | closed | watchlist: add CharmOS (humans + agents in one relationship record on a local vault) |
| Yigtwxx/awesome-claude-multi-agent | [#3](https://github.com/Yigtwxx/awesome-claude-multi-agent/pull/3) | PR | closed | Memory, State, and Communication: add claw-consensus (cross-machine consensus + dual-rail bus) |
| mex-memory/mex | [#148](https://github.com/mex-memory/mex/pull/148) | PR | closed | fix(cli): apply the documented `mex timeline --type` filter |
| michellzappa/headroom | [#31](https://github.com/michellzappa/headroom/issues/31) | issue | closed | v2.0.8 leaves a systematic -3.2%: partial usage snapshots under one message.id (972 files, 969 of them subagents) |
| huggingface/trl | [#6941](https://github.com/huggingface/trl/issues/6941) | issue | closed | publish.yml cannot tell a release bump from a dev bump — the v1.12.0 upload reproduces at v1.13 |
| anthropics/claude-code | [#89840](https://github.com/anthropics/claude-code/issues/89840) | issue | open | [Design] Scheduled tasks are stored in two places and only one is disposable — the prompts survive a wipe, the schedule does not |
| Dicklesworthstone/post_compact_reminder | [#5](https://github.com/Dicklesworthstone/post_compact_reminder/issues/5) | issue | closed | data: what the reminder can't restore - 354-compaction measurements + a composable pre-compact block |
| netresearch/retro-skill | [#78](https://github.com/netresearch/retro-skill/issues/78) | issue | closed | idea trade: end the retro by emitting a ready /compact paste-block (measurements attached) |
| anthropics/claude-code | [#89797](https://github.com/anthropics/claude-code/issues/89797) | issue | open | [DATA] Compaction customization: 354-compaction measurement set + verified inline-block workaround (canon threads are locked) |
| langchain-ai/langgraph | [#8722](https://github.com/langchain-ai/langgraph/issues/8722) | issue | open | Conformance detector counts an override-that-raises as an implementation: SqliteSaver scores NONE (0/3) |
| anthropics/anthropic-sdk-typescript | [#1164](https://github.com/anthropics/anthropic-sdk-typescript/issues/1164) | issue | open | BetaMessageStream: compaction_delta coerces a null content into the literal string "null", and a null encrypted_content erases the established checkpoint |
| google/adk-python | [#6887](https://github.com/google/adk-python/issues/6887) | issue | closed | InMemorySessionService.create_session() checks for a duplicate id before trimming it, so a whitespace-padded id silently overwrites an existing session instead of raising AlreadyExistsError |
| michellzappa/headroom | [#28](https://github.com/michellzappa/headroom/issues/28) | issue | closed | Claude token history counts one assistant message once per content block (x2.12 measured on a real log tree) |
| modelcontextprotocol/go-sdk | [#1196](https://github.com/modelcontextprotocol/go-sdk/pull/1196) | PR | merged | docs: make the protocol.md table of contents resolve |
| qualixar/superlocalmemory | [#126](https://github.com/qualixar/superlocalmemory/pull/126) | PR | closed | docs: npx route for the mcp-remote bridge, with the config that matches it |
| Joe-B-Security/awesome-prompt-injection | [#86](https://github.com/Joe-B-Security/awesome-prompt-injection/pull/86) | PR | closed | Add agent-leash (plan-vs-authorize containment) to Tools |
| OWASP/www-project-mcp-top-10 | [#55](https://github.com/OWASP/www-project-mcp-top-10/pull/55) | PR | open | MCP03: add plan-vs-authorize containment control + attack/defense reference |
| zilliztech/memsearch | [#695](https://github.com/zilliztech/memsearch/pull/695) | PR | merged | perf(hooks): refresh the PyPI check off the session-start blocking path (#676) |
| deepseek-ai/DeepEP | [#733](https://github.com/deepseek-ai/DeepEP/issues/733) | issue | open | get_env<int> returns an uninitialized value when an env var is set to a non-numeric string (EP_BUFFER_DEBUG=false reads as true) |
| qualixar/superlocalmemory | [#122](https://github.com/qualixar/superlocalmemory/pull/122) | PR | closed | docs: mcp-remote bridge install names a package that does not exist on npm |
| TeleAI-UAGI/Awesome-Agent-Memory | [#83](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory/pull/83) | PR | merged | Add claude-memory-tidy to Emerging projects (Open-Source) |
| agno-agi/agno | [#9610](https://github.com/agno-agi/agno/issues/9610) | issue | closed | [Bug] four cookbook imports do not resolve (vertexai Claude, agno.storage GCSJsonDb) |
| evalstate/fast-agent | [#926](https://github.com/evalstate/fast-agent/pull/926) | PR | open | fix(mcp): route listen-channel messages through the shared ping tally |
| QwenLM/qwen-code | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) | PR | merged | fix(core): do not claim a question host in stream-json direct mode |
| UKGovernmentBEIS/inspect_ai | [#4924](https://github.com/UKGovernmentBEIS/inspect_ai/issues/4924) | issue | closed | Eval-level config is written back onto the Task object and leaks into the next eval of that object |
| AlexMili/Awesome-MCP | [#168](https://github.com/AlexMili/Awesome-MCP/pull/168) | PR | merged | Add mcp-daemon-diet to Tools |
| kirr-simakovs/AntonyDzi | [#7](https://github.com/kirr-simakovs/AntonyDzi/issues/7) | issue | open | Follow-up R&D questions: quota-constrained routing, semantic loop-detection, cross-machine consensus, DAG revision |
| kirr-simakovs/AntonyDzi | [#6](https://github.com/kirr-simakovs/AntonyDzi/issues/6) | issue | open | RnD ask: competitive landscape for agent-marketplace / AI-IDE plugin play (openrouter / sakana-fugu class) |
| kirr-simakovs/AntonyDzi | [#4](https://github.com/kirr-simakovs/AntonyDzi/issues/4) | issue | closed | No reference pattern for a visual roadmap built from 500-1000 sessions |
| kirr-simakovs/AntonyDzi | [#5](https://github.com/kirr-simakovs/AntonyDzi/issues/5) | issue | open | Token quota burns in 2-3 days across 3 machines managing 500-1000 sessions |
| kirr-simakovs/AntonyDzi | [#2](https://github.com/kirr-simakovs/AntonyDzi/issues/2) | issue | closed | Mining top-10 recurring problems out of 100-300 session logs |
| kirr-simakovs/AntonyDzi | [#3](https://github.com/kirr-simakovs/AntonyDzi/issues/3) | issue | closed | External peer onboarding: max-settings agent guide + read-only CRM + anti-injection module |
| kirr-simakovs/AntonyDzi | [#1](https://github.com/kirr-simakovs/AntonyDzi/issues/1) | issue | closed | Ultracode: 5h session cap + faster token burn vs Codex |
| deepset-ai/haystack-integrations | [#566](https://github.com/deepset-ai/haystack-integrations/pull/566) | PR | merged | docs: add discontinuation note to the Meta Llama API integration tile |
| mixelpixx/Konnect | [#199](https://github.com/mixelpixx/Konnect/pull/199) | PR | merged | fix(plugin): keep the server PID record correct across sessions and reap on exit |
| google/adk-python | [#6728](https://github.com/google/adk-python/issues/6728) | issue | closed | SqliteSessionService persists state deltas with json_patch (RFC 7396), so nested dict values are merged and None values are dropped — unlike every other session service |
| plur-ai/plur | [#915](https://github.com/plur-ai/plur/issues/915) | issue | closed | pip install plur-ai has never worked: PyPI publish fails with invalid-publisher, and the plur-ai publish workflow is disabled |
| virgiliojr94/book-to-skill | [#163](https://github.com/virgiliojr94/book-to-skill/pull/163) | PR | merged | docs(install): install the CLI from the repo — book-to-skill is not on PyPI |
| UKGovernmentBEIS/inspect_ai | [#4885](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4885) | PR | closed | fix(eval): record Task(approval=...) policies in the eval log config |
| agno-agi/agno | [#9570](https://github.com/agno-agi/agno/issues/9570) | issue | open | [Bug] MCPTools(cache_results=True) never hits the cache and leaves one file per call that nothing removes |
| hesreallyhim/awesome-claude-code | [#2526](https://github.com/hesreallyhim/awesome-claude-code/issues/2526) | issue | open | [Resource]: Second Brain Starter Kit |
| BytePioneer-AI/codex-host | [#17](https://github.com/BytePioneer-AI/codex-host/issues/17) | issue | closed | README claims MIT but there is no LICENSE file / README 声称 MIT，但仓库没有 LICENSE 文件 |
| VoltAgent/awesome-agent-skills | [#896](https://github.com/VoltAgent/awesome-agent-skills/pull/896) | PR | closed | Add skill: tonydzi/second-brain-skills |
| evalstate/fast-agent | [#918](https://github.com/evalstate/fast-agent/issues/918) | issue | closed | Documented install (uv tool install -U fast-agent-mcp) sticks at 0.9.30: 0.10.x pins a fastmcp-slim pre-release |
| modelcontextprotocol/go-sdk | [#1159](https://github.com/modelcontextprotocol/go-sdk/pull/1159) | PR | merged | docs: fix four dead links to the Multi Round-Trip Requests section |
| punkpeye/fastmcp | [#325](https://github.com/punkpeye/fastmcp/pull/325) | PR | merged | fix(edge): answer JSON-mode POSTs whose requests are never answered |
| anthropics/claude-agent-sdk-python | [#1200](https://github.com/anthropics/claude-agent-sdk-python/issues/1200) | issue | open | A single JSONL record larger than the 64 KiB lite window silently drops first_prompt and cwd, and makes list_sessions_from_store() disagree with itself |
| obra/superpowers | [#2124](https://github.com/obra/superpowers/issues/2124) | issue | closed | independent pre-registered benchmark includes superpowers — design critique welcome before runs start (2026-08-12) |
| cristicretu/diri | [#52](https://github.com/cristicretu/diri/pull/52) | PR | merged | docs: add a keyboard shortcuts reference (#36) |
| PrefectHQ/fastmcp | [#4819](https://github.com/PrefectHQ/fastmcp/issues/4819) | issue | closed | Malformed-key warning misses keys whose resource URI contains '@' |
| openai/openai-agents-python | [#4360](https://github.com/openai/openai-agents-python/pull/4360) | PR | closed | fix(apply-diff): accept the stacked @@ headers the tool description asks for |
| anthropics/claude-agent-sdk-python | [#1191](https://github.com/anthropics/claude-agent-sdk-python/issues/1191) | issue | open | rename_session() and tag_session() are silently lost once the session grows: list_sessions() only scans the first and last 64 KiB |
| pydantic/pydantic-ai | [#7354](https://github.com/pydantic/pydantic-ai/issues/7354) | issue | closed | `pydantic-ai-slim[cerebras]` does not exist, and the resulting ImportError recommends it |
| agno-agi/agno | [#9498](https://github.com/agno-agi/agno/pull/9498) | PR | merged | fix: repair four imports that do not resolve in cookbooks |
| cristicretu/diri | [#26](https://github.com/cristicretu/diri/pull/26) | PR | merged | ci: sample the stack when the skipped tests hang on a runner (#1) |
| pydantic/pydantic-ai | [#7352](https://github.com/pydantic/pydantic-ai/pull/7352) | PR | closed | Add the missing `cerebras` optional group to `pydantic-ai-slim` |
| GetBindu/awesome-claude-code-and-skills | [#147](https://github.com/GetBindu/awesome-claude-code-and-skills/pull/147) | PR | closed | Add claude-memory-tidy to Memory & Context Management |
| google/adk-go | [#1299](https://github.com/google/adk-go/pull/1299) | PR | open | fix(configurable): apply config_path containment to workflow node refs |
| microsoft/agent-framework | [#7581](https://github.com/microsoft/agent-framework/pull/7581) | PR | closed | Python: bind tool-approval responses to surfaced approval requests (#7383) |
| Kholomyanskiy/anss-standard | [#1](https://github.com/Kholomyanskiy/anss-standard/issues/1) | issue | open | Обратная связь по ANSS от команды, которая его взяла и не раскатала (с цифрами) |
| ant-research/awesome-mllm-guardrails | [#5](https://github.com/ant-research/awesome-mllm-guardrails/pull/5) | PR | merged | Guardrail Frameworks: add verbatim-citation-gate (deterministic, fail-closed) |
| WangRongsheng/awesome-LLM-resources | [#183](https://github.com/WangRongsheng/awesome-LLM-resources/pull/183) | PR | closed | Evaluation: add verbatim-citation-gate (deterministic citation check) |
| jxzhangjhu/Awesome-LLM-RAG | [#45](https://github.com/jxzhangjhu/Awesome-LLM-RAG/pull/45) | PR | merged | RAG Evaluation: add verbatim-citation-gate (deterministic pre-filter) |
| UKGovernmentBEIS/inspect_ai | [#4769](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4769) | PR | merged | fix(scorer): decide a grader panel by strict majority, not mode |
| pydantic/logfire | [#2197](https://github.com/pydantic/logfire/pull/2197) | PR | merged | docs: drop install extras logfire does not have |
| modelcontextprotocol/go-sdk | [#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148) | PR | merged | docs: quick start `go get` leaves the module unbuildable |
| openai/openai-cookbook | [#2922](https://github.com/openai/openai-cookbook/issues/2922) | issue | open | [FEATURE] Recipe: gate research/agent output on proof-of-work (0 searches, 0 citations) before consuming it |
| google-gemini/cookbook | [#1314](https://github.com/google-gemini/cookbook/issues/1314) | issue | closed | Example request: handling free-tier 429s so a failed call degrades to "unverified", not to a pass |
| letta-ai/trajectory | [#40](https://github.com/letta-ai/trajectory/issues/40) | issue | open | claude-code: resumed transcripts re-emit tool calls under a `__2` id, so the duplicate never collapses under record_id dedup |
| pydantic/pydantic-ai | [#7133](https://github.com/pydantic/pydantic-ai/issues/7133) | issue | open | `cost_limit` silently stops covering part of a run when only some responses can be priced |
| aloth/awesome-ai-agents | [#31](https://github.com/aloth/awesome-ai-agents/issues/31) | issue | open | Add agent-leash (LEASH-8) — asking first: 2 stars, below your bar |
| LLMSecurity/awesome-agent-skills-security | [#47](https://github.com/LLMSecurity/awesome-agent-skills-security/pull/47) | PR | closed | Benchmarks: add agent-runtime-integrity-bench (silent state-integrity violations in agent runtimes) |
| openai/openai-agents-python | [#4173](https://github.com/openai/openai-agents-python/pull/4173) | PR | closed | fix(trimmer): preview structured tool outputs from their text parts |
| chigwell/telegram-mcp | [#181](https://github.com/chigwell/telegram-mcp/pull/181) | PR | closed | docs: document the MCP_TRANSPORT=sse shared server (fixes the 'one instance per agent' surprise in #50) |
| punkpeye/fastmcp | [#311](https://github.com/punkpeye/fastmcp/pull/311) | PR | merged | docs: fix the advanced OAuth example so it compiles |
| modelcontextprotocol/go-sdk | [#1142](https://github.com/modelcontextprotocol/go-sdk/pull/1142) | PR | merged | docs: fix the streamable client snippet to use (*Client).Connect |
| UKGovernmentBEIS/inspect_ai | [#4721](https://github.com/UKGovernmentBEIS/inspect_ai/issues/4721) | issue | closed | model_graded_qa(model=[...]): a grader that fails to parse shrinks the panel, and `mode` then decides the sample by list order |
| simonw/mcp-explorer | [#2](https://github.com/simonw/mcp-explorer/issues/2) | issue | open | -a values are JSON-coerced when the schema has no type for that property ("3.10" -> 3.1) |
| DannyMac180/sol-advisor | [#1](https://github.com/DannyMac180/sol-advisor/issues/1) | issue | open | Runtime inspector exits 0 with null sandbox_policy_type; verify.sh needs an undocumented Python 3.11+ |
| GetBindu/awesome-claude-code-and-skills | [#135](https://github.com/GetBindu/awesome-claude-code-and-skills/pull/135) | PR | closed | Configuration & Templates: add claude-bible |
| wearetyomsmnv/Awesome-LLMSecOps | [#53](https://github.com/wearetyomsmnv/Awesome-LLMSecOps/pull/53) | PR | merged | Agentic security: add LEASH-8 control model |
| TeleAI-UAGI/Awesome-Agent-Memory | [#74](https://github.com/TeleAI-UAGI/Awesome-Agent-Memory/pull/74) | PR | merged | Add sqlite-graph-memory to Emerging projects |
| basicmachines-co/basic-memory | [#1179](https://github.com/basicmachines-co/basic-memory/pull/1179) | PR | merged | fix(integrations): stop bm subprocesses inheriting Hermes's Python env |
| paradigms-of-intelligence/morpho | [#2](https://github.com/paradigms-of-intelligence/morpho/issues/2) | issue | open | test_arithm cannot verify adders at n >= 64 bits (int64 overflow), though the engine itself is correct there |
| mila-iqia/skills | [#6](https://github.com/mila-iqia/skills/pull/6) | PR | closed | Add evals-tools plugin with judge-panel skill (cheap detector -> LLM judge triage) |
| xai-org/xai-cookbook | [#49](https://github.com/xai-org/xai-cookbook/pull/49) | PR | closed | [Content] Defending Grok Agents Against Prompt Injection in Tool Results |
| xai-org/xai-cookbook | [#48](https://github.com/xai-org/xai-cookbook/pull/48) | PR | closed | [Content] Evaluating Grok Applications: Deterministic Checks + LLM-as-Judge |
| xai-org/xai-cookbook | [#46](https://github.com/xai-org/xai-cookbook/pull/46) | PR | closed | [Content] Grounded RAG with Verifiable Citations (Grok) |
| karpathy/nanochat | [#814](https://github.com/karpathy/nanochat/pull/814) | PR | closed | read-arxiv-paper skill: handle the URL and archive shapes arxiv actually serves |
| topoteretes/awesome-ai-memory | [#68](https://github.com/topoteretes/awesome-ai-memory/pull/68) | PR | closed | Add SQLite Graph Memory to Memory tools |
| InftyAI/Awesome-LLMOps | [#503](https://github.com/InftyAI/Awesome-LLMOps/pull/503) | PR | merged | Add Verbatim Citation Gate to RAG |
| benchflow-ai/awesome-evals | [#63](https://github.com/benchflow-ai/awesome-evals/pull/63) | PR | closed | 5c: add Verbatim Citation Gate (RAG / retrieval evaluation) |
| currentslab/awesome-vector-search | [#63](https://github.com/currentslab/awesome-vector-search/pull/63) | PR | closed | Add SQLite Graph Memory to Library |
| agentrust-io/awesome-ai-governance | [#49](https://github.com/agentrust-io/awesome-ai-governance/pull/49) | PR | closed | Add LEASH-8 to Industry Reports & Guidance |
| nibzard/awesome-agentic-patterns | [#124](https://github.com/nibzard/awesome-agentic-patterns/issues/124) | issue | closed | Pattern Reviewer fails on all fork PRs: action checks the PR author's write permission |
| ucsb-mlsec/Awesome-Agent-Security | [#14](https://github.com/ucsb-mlsec/Awesome-Agent-Security/pull/14) | PR | closed | Blue-teaming: add LEASH-8 under Agent privilege management |
| Danielskry/Awesome-RAG | [#136](https://github.com/Danielskry/Awesome-RAG/pull/136) | PR | closed | Add SQLite Graph Memory to Advanced Approaches |
| Yigtwxx/awesome-rag-production | [#73](https://github.com/Yigtwxx/awesome-rag-production/pull/73) | PR | merged | Add Verbatim Citation Gate to Evaluation & Benchmarking |
| IAAR-Shanghai/Awesome-AI-Memory | [#133](https://github.com/IAAR-Shanghai/Awesome-AI-Memory/pull/133) | PR | merged | Add SQLite Graph Memory to Systems and Open Sources |
| Jenqyang/Awesome-AI-Agents | [#406](https://github.com/Jenqyang/Awesome-AI-Agents/pull/406) | PR | merged | Add claude-consensus (multi-machine agent consensus) |
| nibzard/awesome-agentic-patterns | [#122](https://github.com/nibzard/awesome-agentic-patterns/pull/122) | PR | merged | Add: dual-rail-message-delivery |
| microsoft/semantic-kernel | [#14199](https://github.com/microsoft/semantic-kernel/pull/14199) | PR | closed | Python: Add experimental FunctionAuthorizationFilter for auto function invocation (runtime authorization, argument-bound approvals) |
| anthropics/claude-cookbooks | [#799](https://github.com/anthropics/claude-cookbooks/pull/799) | PR | open | fix: convert remaining broken sre_bot_slack.py links in SRE cookbook |
| anthropics/skills | [#1479](https://github.com/anthropics/skills/pull/1479) | PR | open | Add plan-file-hygiene skill (addresses #1417) |
| google-gemini/cookbook | [#1296](https://github.com/google-gemini/cookbook/pull/1296) | PR | merged | Add example: check citation faithfulness in RAG |
| openai/openai-cookbook | [#2880](https://github.com/openai/openai-cookbook/pull/2880) | PR | open | Add cookbook: check citation faithfulness in RAG with a zero-token gate |
| mistralai/cookbook | [#376](https://github.com/mistralai/cookbook/pull/376) | PR | closed | Add citation faithfulness check notebook (RAG) |
| cohere-ai/cohere-developer-experience | [#783](https://github.com/cohere-ai/cohere-developer-experience/pull/783) | PR | closed | Add Citation Faithfulness Check notebook (RAG cookbook) |
| QwenLM/Qwen-Agent | [#928](https://github.com/QwenLM/Qwen-Agent/pull/928) | PR | closed | feat(examples): deterministic guard against fabricated tool results (#737) |
| deepset-ai/haystack | [#12142](https://github.com/deepset-ai/haystack/pull/12142) | PR | closed | feat: add CitationConsistencyChecker — deterministic, zero-token RAG citation validator |
| huggingface/cookbook | [#366](https://github.com/huggingface/cookbook/pull/366) | PR | closed | Add self-verifying search agent recipe |
| google/adk-python-community | [#173](https://github.com/google/adk-python-community/pull/173) | PR | closed | feat: add AuthorityRoutingPlugin for ADVISE/EXECUTE/DEFER/STOP tool authority |
| google/adk-python-community | [#172](https://github.com/google/adk-python-community/pull/172) | PR | closed | feat(plugins): add AuthorityRoutingPlugin (ADVISE/EXECUTE/DEFER/STOP) |
| google/adk-python-community | [#171](https://github.com/google/adk-python-community/issues/171) | issue | open | feat(plugins): add AuthorityRoutingPlugin — pre-execution authority posture (ADVISE/EXECUTE/DEFER/STOP) |
| xai-org/xai-cookbook | [#45](https://github.com/xai-org/xai-cookbook/pull/45) | PR | closed | [Content] Deterministic Guardrails for Grok Tool Calls |
| QwenLM/Qwen-Agent | [#927](https://github.com/QwenLM/Qwen-Agent/pull/927) | PR | closed | feat(examples): RAG with verifiable citations for the Assistant |
| anthropics/skills | [#1460](https://github.com/anthropics/skills/pull/1460) | PR | closed | Add reasoning-quality-gate skill |
| anthropics/claude-cookbooks | [#789](https://github.com/anthropics/claude-cookbooks/pull/789) | PR | closed | feat(evals): citation-faithfulness evals — catching hallucinated support |
| anthropics/claude-agent-sdk-demos | [#70](https://github.com/anthropics/claude-agent-sdk-demos/pull/70) | PR | closed | Add verified-ops-agent: Python demo of propose → adversarially verify → gated apply |
| anthropics/claude-cookbooks | [#788](https://github.com/anthropics/claude-cookbooks/pull/788) | PR | closed | Add pipeline vs barrier sub-agent composition cookbook (addresses #721) |
| anthropics/claude-cookbooks | [#787](https://github.com/anthropics/claude-cookbooks/pull/787) | PR | open | feat(agents): add authority routing pattern (ADVISE / EXECUTE / DEFER / STOP) |
| anthropics/claude-cookbooks | [#784](https://github.com/anthropics/claude-cookbooks/pull/784) | PR | closed | feat(agents): add multi-agent consensus & verification pattern |
| anthropics/claude-cookbooks | [#778](https://github.com/anthropics/claude-cookbooks/pull/778) | PR | closed | feat(patterns/agents): coordinating agents that don't share memory (message-bus consensus + liveness) |
| anthropics/claude-code | [#74055](https://github.com/anthropics/claude-code/issues/74055) | issue | closed | [BUG] Scheduler catch-up storm on restart: re-fires daily tasks and runs enabled:false tasks (ghost fires, lastRunAt not updated) |

## Participation in other people's threads

| Repository | # | Title |
|---|---|---|
| mariagorskikh/open-instinct | [#43](https://github.com/mariagorskikh/open-instinct/pull/43) | core: repair transcripts that an older fold left with orphan tool results |
| cohere-ai/cohere-python | [#817](https://github.com/cohere-ai/cohere-python/issues/817) | Proxy settings from HTTP_PROXY/HTTPS_PROXY env vars are no longer picked up since 7.0.6 |
| VishnujanNarayanan/Job_Application_Bot | [#97](https://github.com/VishnujanNarayanan/Job_Application_Bot/issues/97) | Scraper: poll target companies' ATS job boards directly every hour |
| anthropics/claude-agent-sdk-python | [#1385](https://github.com/anthropics/claude-agent-sdk-python/pull/1385) | fix(query): stop a full message buffer from blocking control requests |
| mistralai/mistral-vibe | [#1243](https://github.com/mistralai/mistral-vibe/issues/1243) | bug: CLI freezes silently when storage fails during compaction (Unified Harness) |
| anthropics/claude-agent-sdk-python | [#1378](https://github.com/anthropics/claude-agent-sdk-python/pull/1378) | Close inner generator when query() iterator is closed early |
| zilliztech/memsearch | [#792](https://github.com/zilliztech/memsearch/pull/792) | fix(maintenance): recover stale O_EXCL lock files left by crashed holders |
| anthropics/anthropic-sdk-python | [#2015](https://github.com/anthropics/anthropic-sdk-python/pull/2015) | fix(transform schema): keep draft-07 `definitions` alongside `$defs` |
| google-gemini/gemini-cli | [#29704](https://github.com/google-gemini/gemini-cli/issues/29704) | Error on Antigravity responce |
| anthropics/claude-cookbooks | [#917](https://github.com/anthropics/claude-cookbooks/pull/917) | fix(tool_use): make mock expense records reproducible |
| BerriAI/litellm | [#45686](https://github.com/BerriAI/litellm/pull/45686) | fix(databricks): send a single plain text block as a string for non-Claude models |
| mariagorskikh/open-instinct | [#15](https://github.com/mariagorskikh/open-instinct/pull/15) | Deploy the web apps the agent builds, with Ample |
| google/adk-python | [#7484](https://github.com/google/adk-python/issues/7484) | SqliteSpanExporter drops a span's status and events, so an exception that ended a run is lost (2.11.0) |
| BerriAI/litellm | [#45618](https://github.com/BerriAI/litellm/issues/45618) | [Bug]: chat->Responses->chat bridge converts string user content to text blocks, which breaks Databricks json_object ("must contain the word json" even when present) |
| QwenLM/qwen-code | [#13785](https://github.com/QwenLM/qwen-code/issues/13785) | Multi-Agent API: an agent-identity dimension on the public contract, so multi-agent execution is attributable, tree-shaped and interruptible |
| BerriAI/litellm | [#45555](https://github.com/BerriAI/litellm/pull/45555) | fix(prometheus): preserve requested model after fallback |
| carverauto/agentboard | [#166](https://github.com/carverauto/agentboard/issues/166) | roster: hide system/human/fixture identities, captain-gated agent retire, stale threshold that matches heartbeat cadence |
| VMAFx/vmafx | [#2554](https://github.com/VMAFx/vmafx/issues/2554) | Community metrics script: time to first response and contribution flow (RC5) |
| siddhero97/LangHire | [#4](https://github.com/siddhero97/LangHire/issues/4) | Feat: Dynamic ATS-optimized resume compilation (HTML/Typst to PDF) |
| BerriAI/litellm | [#45052](https://github.com/BerriAI/litellm/pull/45052) | fix(anthropic adapter): carry tool_result.is_error through translation |
| bytedance/deer-flow | [#6455](https://github.com/bytedance/deer-flow/pull/6455) | fix(middleware): guard OverflowError when parsing non-finite Retry-After hints |
| google/adk-python | [#7434](https://github.com/google/adk-python/issues/7434) | Tool confirmation: a repeated approval runs the confirmed tool again |
| QwenLM/qwen-code | [#13596](https://github.com/QwenLM/qwen-code/pull/13596) | fix(cli): strip UTF-8 BOM when reading MCP config files |
| BerriAI/litellm | [#44984](https://github.com/BerriAI/litellm/pull/44984) | fix(anthropic): keep tool_result is_error when translating for gemini |
| BerriAI/litellm | [#44979](https://github.com/BerriAI/litellm/issues/44979) | [Bug]: /v1/messages drops `tool_result.is_error` when translating Anthropic → OpenAI tool messages |
| markng/pytest-leela | [#13](https://github.com/markng/pytest-leela/issues/13) | A setup error or collection failure the mutant didn't cause scores the mutant as killed |
| anthropics/claude-agent-sdk-python | [#1364](https://github.com/anthropics/claude-agent-sdk-python/pull/1364) | Fail pending control requests promptly when Query closes |
| doobidoo/mcp-memory-service | [#1467](https://github.com/doobidoo/mcp-memory-service/issues/1467) | retrieve(): should a broken storage backend raise instead of returning []? |
| vectorize-io/hindsight | [#5284](https://github.com/vectorize-io/hindsight/pull/5284) | feat(recall): rank with the decision model when one is set up |
| langroid/langroid | [#1193](https://github.com/langroid/langroid/pull/1193) | docs: pass task-termination params where they are actually read (supersedes #1191) |
| anthropics/claude-code | [#99831](https://github.com/anthropics/claude-code/issues/99831) | [FEATURE] Desktop/Claude Code: stdio MCP servers duplicated per session (~1 GB each) and can't be started mid-session |
| nicosuave/memex | [#238](https://github.com/nicosuave/memex/pull/238) | feat(rerank): add opt-in local cross-encoder reranking |
| mariagorskikh/open-instinct | [#5](https://github.com/mariagorskikh/open-instinct/pull/5) | Count each Link purchase once; apply merchant lists to payment_request |
| QwenLM/qwen-code | [#13475](https://github.com/QwenLM/qwen-code/pull/13475) | fix(cli): show agent token counts of a million or more in millions |
| liatrio-labs/claude-code-gauntlet | [#465](https://github.com/liatrio-labs/claude-code-gauntlet/issues/465) | Findings whose validation was skipped are delivered unlabelled; the skipped marker is never read |
| PrefectHQ/fastmcp | [#5484](https://github.com/PrefectHQ/fastmcp/issues/5484) | pydantic ValidationError raised in the body of a tool turns up as "Invalid request parameters" instead of a normal error |
| NousResearch/hermes-agent | [#133272](https://github.com/NousResearch/hermes-agent/issues/133272) | [Bug]: macOS — an unparseable LaunchAgent plist is silently skipped, so `hermes update` books a supervised dashboard as `manual-serve` and respawns it into the job's own port (exit 1) |
| QwenLM/qwen-code | [#13442](https://github.com/QwenLM/qwen-code/pull/13442) | feat(hooks): apply PreToolUse updatedInput with full revalidation |
| anthropics/claude-code | [#99596](https://github.com/anthropics/claude-code/issues/99596) | Scheduled task: run abandoned after first tool round-trip; tracked session id never matches the transcript |
| QwenLM/qwen-code | [#13398](https://github.com/QwenLM/qwen-code/pull/13398) | fix(hooks): apply PreToolUse input before tool admission |
| bigboybamo/AI_CV_Builder | [#27](https://github.com/bigboybamo/AI_CV_Builder/issues/27) | Add local Python ATS match scorer for tailored resumes |
| areguig/petit-poucet | [#81](https://github.com/areguig/petit-poucet/issues/81) | One vault on several machines with Syncthing, without a cloud |
| anthropics/claude-code | [#99400](https://github.com/anthropics/claude-code/issues/99400) | [FEATURE] Scheduled tasks that run a command instead of a Claude session (zero usage unless they fail) |
| Lyellr88/marm-memory | [#297](https://github.com/Lyellr88/marm-memory/pull/297) | fix(compaction): guard Unicode and contradictory facts during compaction |
| pydantic/pydantic-ai | [#9749](https://github.com/pydantic/pydantic-ai/issues/9749) | `SummarizingCompaction` replaces history with an empty summary when the summary model returns only whitespace |
| pydantic/pydantic-ai | [#9748](https://github.com/pydantic/pydantic-ai/pull/9748) | Reject whitespace-only `SummarizingCompaction` summaries instead of replacing history with an empty summary |
| openclaw/openclaw | [#164445](https://github.com/openclaw/openclaw/pull/164445) | fix: yielded subagent runs stay pending forever when no continuation can reach them |
| QwenLM/qwen-code | [#13315](https://github.com/QwenLM/qwen-code/pull/13315) | fix(memory): preserve complete index entries in prompts |
| PCBZ/job-scan | [#28](https://github.com/PCBZ/job-scan/issues/28) | ATS keyword coverage per top pick |
| anthropics/claude-agent-sdk-python | [#1348](https://github.com/anthropics/claude-agent-sdk-python/pull/1348) | fix: honor Required/NotRequired in TypedDict tool schemas under postponed annotations |
| anthropics/claude-code | [#98828](https://github.com/anthropics/claude-code/issues/98828) | [BUG] Claude Desktop (Windows, MSIX): sessions vanished from about a dozen projects at once; project folder reported as "on another computer" |
| headroomlabs-ai/headroom | [#3914](https://github.com/headroomlabs-ai/headroom/issues/3914) | [FEATURE] Diagnose and recover Serena MCP after WSL TypeScript timeout |
| thedandano/callback | [#118](https://github.com/thedandano/callback/issues/118) | Evaluate problem-oriented resume tailoring alongside ATS scoring |
| BerriAI/litellm | [#43992](https://github.com/BerriAI/litellm/issues/43992) | [Feature]: OTEL v2 integration should export cache token counts as span attributes |
| anthropics/claude-agent-sdk-python | [#1342](https://github.com/anthropics/claude-agent-sdk-python/pull/1342) | fix: don't write to the closed transport when a hook finishes after close() (#1340) |
| omnigent-ai/omnigent | [#8667](https://github.com/omnigent-ai/omnigent/issues/8667) | [Bug] antigravity-native reports a turn complete as soon as the message is delivered, before agy finishes |
| srbhr/Resume-Matcher | [#1011](https://github.com/srbhr/Resume-Matcher/issues/1011) | [Feature]: MCP Server + ATS Parse-Check + Optional PostgreSQL Backend |
| anthropics/claude-plugins-official | [#6331](https://github.com/anthropics/claude-plugins-official/issues/6331) | remember: pin stale at 0.33.0 since the bump workflow was disabled; please advance to v0.36.0 |
| anthropics/claude-code | [#98369](https://github.com/anthropics/claude-code/issues/98369) | [FEATURE] Let local tools send messages into Claude desktop Code sessions (channels / send deep link) |
| instructkr/reranker-simple-benchmark | [#37](https://github.com/instructkr/reranker-simple-benchmark/pull/37) | [`feat`] Add PPS measurement and KURE-Reranker, Qwen/Qwen3-Reranker, KaLM-Reranker results |
| run-llama/llama_index | [#23313](https://github.com/run-llama/llama_index/issues/23313) | bug: TokenCounter ignores dictionary tool_calls in additional_kwargs and lacks null guards |
| BerriAI/litellm | [#43795](https://github.com/BerriAI/litellm/pull/43795) | fix(fallback_utils): respect top-level `fallbacks` parameter in `async_completion_with_fallbacks` |
| Digital-Process-Tools/claude-oss | [#1796](https://github.com/Digital-Process-Tools/claude-oss/issues/1796) | select_issues.py and inbound_triage.py disagree on FIRST_TIME_CONTRIBUTOR/FIRST_TIMER classification |
| mistralai/mistral-vibe | [#1159](https://github.com/mistralai/mistral-vibe/issues/1159) | bug: Unified Harness: hooks and agent profiles do not apply to subagents |
| Raven-Scout/Scout | [#249](https://github.com/Raven-Scout/Scout/issues/249) | doctor crashes on an installed plist whose path contains `--`: template comment is substituted into, and ExpatError escapes the handler |
| anthropics/claude-agent-sdk-python | [#1333](https://github.com/anthropics/claude-agent-sdk-python/pull/1333) | fix: normalize ResultMessage.errors through the existing helper |
| career-ops-hq/career-ops | [#4579](https://github.com/career-ops-hq/career-ops/pull/4579) | feat(web): ATS keyword coverage on the report view |
| coreweave/forge-agent-lens-for-claude-code | [#180](https://github.com/coreweave/forge-agent-lens-for-claude-code/pull/180) | fix(install): --source=local installs the plugin from the npm tree, not GitHub |
| anthropics/claude-code | [#97800](https://github.com/anthropics/claude-code/issues/97800) | [feedback] shared-model-judges: Two same-model judge seats produced largely disjoint findings (a strength) but shared one model-level bias (FB |
| anthropics/claude-code | [#97775](https://github.com/anthropics/claude-code/issues/97775) | [feedback] Model: timestamps get invented from elapsed work; compaction summaries carry them forward as facts |
| NVIDIA/SkillSpector | [#652](https://github.com/NVIDIA/SkillSpector/issues/652) | Prohibitive/defensive language is flagged as the violation itself (negation-blindness in P6, AS3, RA2, EA2) |
| prPMDev/jd-intel | [#87](https://github.com/prPMDev/jd-intel/issues/87) | One company, N boards: registry, routing, detect_ats and the weekly pipeline assume one board per company (design and tracking issue) |
| dereksantos/cortex | [#128](https://github.com/dereksantos/cortex/issues/128) | Fact-based completion: harness-computed receipts and per-item checklist accounting instead of self-reported success |
| BerriAI/litellm | [#43501](https://github.com/BerriAI/litellm/pull/43501) | fix(streaming): reject incomplete generic chunks |
| BerriAI/litellm | [#43499](https://github.com/BerriAI/litellm/pull/43499) | fix(streaming): reject partial generic chunks missing required fields |
| BerriAI/litellm | [#43487](https://github.com/BerriAI/litellm/issues/43487) | [Bug]: A partial generic streaming chunk is accepted and then raises KeyError |
| cognicore-dev/cognicore-env | [#136](https://github.com/cognicore-dev/cognicore-env/pull/136) | test(mem0-bridge): verifier-defeat vector — reachability firing test + tripwire |
| 00200200/maintainer-skills-lab | [#44](https://github.com/00200200/maintainer-skills-lab/issues/44) | [Feature] Add Token Profiler CLI command (`kit.py tokens`) to benchmark skill and agent context consumption |
| cognicore-dev/cognicore-env | [#135](https://github.com/cognicore-dev/cognicore-env/pull/135) | feat(integrations): mem0 verified-memory bridge — signed transfer bundles, structural quarantine, fail-closed import |
| anthropics/claude-agent-sdk-python | [#1320](https://github.com/anthropics/claude-agent-sdk-python/issues/1320) | Session store writes and reads derive project_key differently, so a git-worktree session lists and resumes as empty |
| openai/codex | [#48572](https://github.com/openai/codex/issues/48572) | /compact silently drops trailing instructions intended for after compaction |
| oraios/serena | [#2107](https://github.com/oraios/serena/pull/2107) | Reject an inverted line range instead of duplicating the text |
| anthropics/claude-agent-sdk-python | [#1316](https://github.com/anthropics/claude-agent-sdk-python/pull/1316) | fix(query): release a cancelled control request's pending entry |
| RubenSaucedo/labora | [#131](https://github.com/RubenSaucedo/labora/issues/131) | Add a deterministic ATS board collector so discovery does not require a browser |
| NousResearch/hermes-agent | [#123147](https://github.com/NousResearch/hermes-agent/pull/123147) | feat(skills): add skills.index_descriptions knob (full \| names_only) |
| anthropics/claude-code | [#97270](https://github.com/anthropics/claude-code/issues/97270) | [BUG] Windows: sessions disappear from VS Code Session history, cwd recorded as both c:\ and C:\ in one transcript |
| rysweet/amplihack-rs | [#1498](https://github.com/rysweet/amplihack-rs/issues/1498) | quality-loop requests --json fields gh rejects (authorAssociation, baseRepositoryOwner) |
| zilliztech/memsearch | [#768](https://github.com/zilliztech/memsearch/issues/768) | compact summaries have no time heading, so same-day compactions can't be told apart |
| codewhale-hq/Codewhale | [#6573](https://github.com/codewhale-hq/Codewhale/issues/6573) | Bug: Multiple TUI Sessions Contend on Subagents Store → CPU Spin-loop |
| openamer/openamer | [#98](https://github.com/openamer/openamer/issues/98) | Security: A2A Mesh Replay Protection |
| UKGovernmentBEIS/inspect_ai | [#5553](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5553) | fix: preserve internal state across multiple assistant text blocks |
| defangdevs/agent-box | [#734](https://github.com/defangdevs/agent-box/issues/734) | A hook session removes itself after a FAILED handoff, so the event is dropped silently |
| pydantic/pydantic-ai | [#8704](https://github.com/pydantic/pydantic-ai/issues/8704) | Provider responses with no usage object are recorded as zero tokens, not unknown |
| infagent/merl | [#102](https://github.com/infagent/merl/issues/102) | Gate: prove two heterogeneous agents coordinate through accepted state |
| Growth-Circle/cadis | [#3218](https://github.com/Growth-Circle/cadis/issues/3218) | fix(cli): global flags after subcommand silently ignored |
| anthropics/claude-code | [#96299](https://github.com/anthropics/claude-code/issues/96299) | Windows: claude.exe session processes accumulate and are never terminated, causing high RAM/disk usage over a work day |
| kirodotdev/KiroCrew | [#13012](https://github.com/kirodotdev/KiroCrew/issues/13012) | Reasoning-only agent types accept write tasks and self-report success; synthesis prompt presumes success with no disk verification |
| carlosboeing/agentic-toolkit | [#1](https://github.com/carlosboeing/agentic-toolkit/issues/1) | Distinguish skipped Mermaid validation from successful validation |
| JeltzProstetnic/agent-fleet | [#12](https://github.com/JeltzProstetnic/agent-fleet/issues/12) | SessionStart additionalContext payload silently fails to reach the model (6 occurrences); hook verified healthy, delivery fails |
| beatzball/roost | [#100](https://github.com/beatzball/roost/issues/100) | Shared notes and an advisory lock for a fleet, as plain files |
| anthropics/claude-code | [#95967](https://github.com/anthropics/claude-code/issues/95967) | Scheduled task (routine) runs no longer appear in the desktop sidebar or Remote Control |
| anthropics/claude-code | [#95966](https://github.com/anthropics/claude-code/issues/95966) | Scheduled tasks silently skip their fire window, with host machine and scheduler engine both demonstrably active |
| mastra-ai/mastra | [#24611](https://github.com/mastra-ai/mastra/issues/24611) | Scheduler: year-pinned (7-part) cron is accepted but never fires |
| pydantic/pydantic-ai | [#8582](https://github.com/pydantic/pydantic-ai/issues/8582) | [provider-mapping-sweep] bedrock: `nova_code_interpreter_result` toolResult content loses all but the first json item (text/image/document/video and item
[Content truncated due to length] |
| anomalyco/opencode | [#50363](https://github.com/anomalyco/opencode/issues/50363) | mcp: orphaned local MCP server processes accumulate after sessions end |
| anthropics/claude-code | [#95833](https://github.com/anthropics/claude-code/issues/95833) | [BUG] PreToolUse hooks (Bash/PowerShell matchers) never fire in Claude Desktop app "Code" tab, even after full re-login |
| BerriAI/litellm | [#42210](https://github.com/BerriAI/litellm/pull/42210) | fix(anthropic): scope OAuth token forwarding to official Anthropic API hosts (#42172) |
| code-yeongyu/oh-my-openagent | [#8579](https://github.com/code-yeongyu/oh-my-openagent/issues/8579) | spawn admission reply lost -> parent reports start_failed while host creates the session -> duplicate child on retry |
| pydantic/pydantic-ai | [#8565](https://github.com/pydantic/pydantic-ai/pull/8565) | Allow list-form `tool_choice` to name output tools, and accept static lists that include one |
| NousResearch/hermes-agent | [#117921](https://github.com/NousResearch/hermes-agent/issues/117921) | Feature: first-class NotebookLM skill with verified source upload and Audio Overview retrieval |
| summationai/agent-exchange | [#15](https://github.com/summationai/agent-exchange/issues/15) | Let agents launch named peers in new terminal panes |
| bytedance/deer-flow | [#5624](https://github.com/bytedance/deer-flow/issues/5624) | # RFC: TypeSafe (Jev) Integration for Pre-Execution Tool Risk Gating |
| agno-agi/agno | [#10366](https://github.com/agno-agi/agno/issues/10366) | `Agent(retries=N)` re-executes tool calls that already succeeded |
| anthropics/claude-agent-sdk-python | [#1276](https://github.com/anthropics/claude-agent-sdk-python/pull/1276) | fix: parse image content blocks instead of silently dropping them |
| rmems/writ | [#198](https://github.com/rmems/writ/pull/198) | feat(coord): same-host claim, overlap, and handoff contract |
| langchain-ai/langgraph | [#9006](https://github.com/langchain-ai/langgraph/issues/9006) | Checkpoint resume after tool timeout: resume vs full restart (where the failure lives) |
| anthropics/claude-code | [#95582](https://github.com/anthropics/claude-code/issues/95582) | Skill catalog descriptions intermittently missing from system prompt (frontmatter on disk is correct) |
| run-llama/llama_index | [#23144](https://github.com/run-llama/llama_index/issues/23144) | [Bug]: Memory silently evicts the system message from chat history once the token limit is reached |
| anthropics/claude-agent-sdk-python | [#1274](https://github.com/anthropics/claude-agent-sdk-python/pull/1274) | fix(sessions): pick the first JSON field match by position, not per pattern |
| stablyai/orca | [#21628](https://github.com/stablyai/orca/pull/21628) | fix: report missing Antigravity hook scripts |
| anthropics/claude-code | [#95475](https://github.com/anthropics/claude-code/issues/95475) | [Feature Request] Implement confidence calibration and evidence tracking for root-cause analysis in coding workflows |
| run-llama/llama_index | [#23122](https://github.com/run-llama/llama_index/issues/23122) | Integration proposal: memory store with verified transfer — export/import sealed memory bundles |
| google/adk-python | [#7175](https://github.com/google/adk-python/pull/7175) | feat(memory): add session and user memory deletion APIs |
| ozShpigel/nextrole | [#96](https://github.com/ozShpigel/nextrole/issues/96) | ATS boards would add ~4x the Israel engineering roles LinkedIn finds — measured, but token resolution blocks a real number |
| anthropics/claude-code | [#95313](https://github.com/anthropics/claude-code/issues/95313) | [FEATURE] Request: Require user confirmation before spawning expensive agents |
| mrveiss/AutoBot-AI | [#16962](https://github.com/mrveiss/AutoBot-AI/issues/16962) | security(agents): authenticate agent-bus messages — a per-agent key issued at registration, HMAC on every message |
| nicosuave/memex | [#201](https://github.com/nicosuave/memex/issues/201) | [enhancement] standardizing compaction for sessions |
| anthropics/claude-agent-sdk-python | [#1271](https://github.com/anthropics/claude-agent-sdk-python/pull/1271) | Expose user-message attribution and queue metadata |
| evnchn/better-telegram-mcp | [#1](https://github.com/evnchn/better-telegram-mcp/pull/1) | fix(server): share one refcounted backend across overlapping lifespans |
| kirodotdev/KiroCrew | [#11562](https://github.com/kirodotdev/KiroCrew/issues/11562) | New sessions start on the last picker-selected model, not the configured default model |
| anthropics/claude-code | [#95175](https://github.com/anthropics/claude-code/issues/95175) | Plugin marketplace auto-update and manual refresh both non-functional (autoUpdate: true never fires) |
| wowok-ai/skills | [#3](https://github.com/wowok-ai/skills/issues/3) | Global install left one client with no skills and no MCP registration, and leaves no record of what was written where |
| anthropics/claude-code | [#94918](https://github.com/anthropics/claude-code/issues/94918) | [FEATURE] Add API/webhook (event) trigger for Claude Cowork tasks — not just schedule cadence |
| BerriAI/litellm | [#41395](https://github.com/BerriAI/litellm/issues/41395) | [Bug]: context-management summary subrequests bypass a project's ITPM/OTPM quotas (v3 rate limiter) |
| pydantic/pydantic-ai | [#8376](https://github.com/pydantic/pydantic-ai/issues/8376) | A list[str] tool_choice is validated against output tools, silently widening the choice |
| pydantic/pydantic-ai | [#8368](https://github.com/pydantic/pydantic-ai/issues/8368) | Carrying `usage=` across runs makes the agent-run span report the conversation total |
| anthropics/claude-code | [#94575](https://github.com/anthropics/claude-code/issues/94575) | Background-agent view shows the parent's advisor model (Fable) instead of the subagent's requested model |
| embeddings-benchmark/mteb | [#5471](https://github.com/embeddings-benchmark/mteb/issues/5471) | Add citation validation |
| anthropics/claude-code | [#94563](https://github.com/anthropics/claude-code/issues/94563) | Scheduled task sessions hang indefinitely (isRunning stuck true, zero progress, no error) - two confirmed triggers fixed, hang persists |
| anthropics/claude-code | [#94527](https://github.com/anthropics/claude-code/issues/94527) | [BUG] Most custom groups are no longer visible in the sidebar |
| anthropics/claude-code | [#94516](https://github.com/anthropics/claude-code/issues/94516) | Plugin marketplace refresh can install unmerged or stale content without any signal |
| UKGovernmentBEIS/inspect_ai | [#5413](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5413) | Tag empty completions with reason=no_response across the text scorers |
| OWASP/www-project-agentic-skills-top-10 | [#81](https://github.com/OWASP/www-project-agentic-skills-top-10/issues/81) | AST01/AST02/AST04/AST07/AST09/AST10: Cryptographic agent identity, JCS-Ed25519 signing, and DNSSEC domain binding for skill provenance |
| openai/openai-agents-python | [#5025](https://github.com/openai/openai-agents-python/issues/5025) | Support skills for Agent and not just for SandboxAgent |
| openai/openai-agents-python | [#5024](https://github.com/openai/openai-agents-python/issues/5024) | needs_approval misconfiguration raises in the core runner and silently skips approval in realtime sessions |
| xsmyile/sissy | [#126](https://github.com/xsmyile/sissy/issues/126) | Manage and share local skills between Claude Code and Codex |
| openai/openai-agents-python | [#5015](https://github.com/openai/openai-agents-python/pull/5015) | fix(core): keep tool output custom_data structured in RunState serialization |
| openai/codex | [#45408](https://github.com/openai/codex/issues/45408) | Astra unavailable in Codex 0.154.0 although it works in ChatGPT |
| anthropics/claude-agent-sdk-python | [#1262](https://github.com/anthropics/claude-agent-sdk-python/pull/1262) | fix: isolate in-memory session store snapshots |
| langchain-ai/langgraph | [#8919](https://github.com/langchain-ai/langgraph/issues/8919) | checkpoint-conformance suite has no operator-form filter coverage, letting backend divergences through |
| openai/codex | [#45306](https://github.com/openai/codex/issues/45306) | Codex incorrectly reports an MCP workflow as impossible without checking composable tools |
| anthropics/claude-agent-sdk-python | [#1261](https://github.com/anthropics/claude-agent-sdk-python/pull/1261) | fix(transport): keep reading stderr until the CLI exits on close |
| anthropics/claude-code | [#94013](https://github.com/anthropics/claude-code/issues/94013) | Background subagents have no token, turn or time cap: three research agents consumed 1.7M tokens with no approval or visible cost |
| anthropics/claude-code | [#94004](https://github.com/anthropics/claude-code/issues/94004) | [BUG] Permission "Allow" prompt appeared during an unattended Cloud Routine run |
| browser-use/browser-use | [#5786](https://github.com/browser-use/browser-use/pull/5786) | fix(history): preserve usage stats during save_to_file and model_dump (#5767) |
| anthropics/claude-agent-sdk-python | [#1260](https://github.com/anthropics/claude-agent-sdk-python/pull/1260) | Add env parameter to session listing and mutation helpers |
| bytedance/deer-flow | [#5391](https://github.com/bytedance/deer-flow/issues/5391) | RFC: 内置本地知识库（Harness RAG） |
| openai/codex | [#45070](https://github.com/openai/codex/issues/45070) | App-created heartbeat automation keeps firing 9 times after the usage limit is reached, draining the whole monthly Codex quota |
| agno-agi/agno | [#10139](https://github.com/agno-agi/agno/issues/10139) | [Bug] Curator.prune() and Curator.deduplicate() silently return 0 for every store |
| Jason-Vaughan/TangleClaw | [#1400](https://github.com/Jason-Vaughan/TangleClaw/issues/1400) | [bug] Primary-checkout guard hook fails silently due to \|\| true |
| anthropics/claude-code | [#93654](https://github.com/anthropics/claude-code/issues/93654) | [Bug] Inverted logic in absence-of-evidence search caused JSON config fields to be marked CLI-only |
| anthropics/claude-code | [#93646](https://github.com/anthropics/claude-code/issues/93646) | [BUG] Model shorthand `--model sonnet` resolves to Sonnet 4.5 instead of Sonnet 5; inconsistent with /model picker |
| anthropics/anthropic-sdk-python | [#1927](https://github.com/anthropics/anthropic-sdk-python/pull/1927) | fix(vertex): serialize the body static-fields-first so prompt caching survives routing |
| tenequm/pond | [#239](https://github.com/tenequm/pond/issues/239) | schedule: the generated systemd user timer stops re-arming, and pond status still reports it healthy |
| mem0ai/mem0 | [#7283](https://github.com/mem0ai/mem0/issues/7283) | Faithfulness check before memory write , interested in contributing a pluggable verification hook |
| dimoschi/touchstone | [#47](https://github.com/dimoschi/touchstone/issues/47) | Make the quality skill portable across Codex and Claude Code |
| anthropics/claude-code | [#93481](https://github.com/anthropics/claude-code/issues/93481) | [Bug] Sessions start with 9% token usage already consumed |
| caura-ai/caura | [#1467](https://github.com/caura-ai/caura/pull/1467) | fix(client-typescript): recall() silently drops caller extras that write() and search() forward |
| PerryLink/dsh-click | [#7](https://github.com/PerryLink/dsh-click/issues/7) | `focusFallback: allow` silently does nothing: `SetForegroundWindow` alone cannot raise a window from the background helper (returns True, foreground unchanged) |
| nimbalyst/nimbalyst | [#1489](https://github.com/nimbalyst/nimbalyst/issues/1489) | Claude Agent sessions never see MCP servers (or hooks) shipped inside installed Claude Code plugins |
| anthropics/claude-code | [#93324](https://github.com/anthropics/claude-code/issues/93324) | [Bug] Terminal UI displays incorrect model name when subagents launch or switch models |
| browser-use/browser-use | [#5768](https://github.com/browser-use/browser-use/pull/5768) | fix(agent): preserve token usage in AgentHistoryList save/load round-trip |
| browser-use/browser-use | [#5767](https://github.com/browser-use/browser-use/issues/5767) | AgentHistoryList.save_to_file/load_from_file silently drops token usage |
| anthropics/claude-code | [#93260](https://github.com/anthropics/claude-code/issues/93260) | Projects: concurrent sessions silently clobber each other's project_write — three losses on one doc in ninety minutes |
| anthropics/claude-code | [#93231](https://github.com/anthropics/claude-code/issues/93231) | Session exit on VS Code window close never releases its git worktree lock; `locked` keeps naming the dead PID and no later session reaps it |
| UKGovernmentBEIS/inspect_ai | [#5329](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5329) | fix: stray angle brackets and viewer leakage from double-wrapped content-internal tags |
| agno-agi/agno | [#10088](https://github.com/agno-agi/agno/pull/10088) | fix: exclude the run being continued from its own history in background+stream continues |
| agno-agi/agno | [#10086](https://github.com/agno-agi/agno/issues/10086) | [Bug] Background+streaming continue of a paused `external_execution` tool duplicates the run into its own history, causing unpaired `tool_calls` |
| anthropics/claude-code | [#93143](https://github.com/anthropics/claude-code/issues/93143) | [BUG] Streamable HTTP MCP tool call still times out ("The operation timed out") at ~6min despite per-server timeout, CLAUDE_CODE_MCP_TOOL_IDLE_TIMEOUT=0, and a requestTimeout=0 server |
| UKGovernmentBEIS/inspect_ai | [#5314](https://github.com/UKGovernmentBEIS/inspect_ai/issues/5314) | Double-wrapped content-internal tag corrupts assistant text on OpenAI round trips; events_df re-renders conversations quadratically |
| anthropics/claude-code | [#93108](https://github.com/anthropics/claude-code/issues/93108) | [BUG] plugin update / auto-update compare only the version string, so plugins that ship new content without bumping version never refresh |
| anthropics/claude-code | [#93099](https://github.com/anthropics/claude-code/issues/93099) | [MODEL] Opus 5 executed rm -rf "$HOME" during test cleanup(57,235 files and 11,315 directories deleted), causing extensive data loss |
| anthropics/claude-code | [#93046](https://github.com/anthropics/claude-code/issues/93046) | Usage-limit warning names the parent model, not the subagent's model |
| anthropics/claude-code | [#93044](https://github.com/anthropics/claude-code/issues/93044) | Project skills beyond a session-level cap return "Unknown skill" from the Skill tool despite valid SKILL.md files |
| anthropics/claude-code | [#93015](https://github.com/anthropics/claude-code/issues/93015) | Scheduled tasks stamp lastRunAt but never launch a session (no error, no failed-run state) |
| anthropics/claude-code | [#92998](https://github.com/anthropics/claude-code/issues/92998) | Auto-memory: MEMORY.md overflow silently discards the NEWEST entries, so corrections are lost while the text they correct stays loaded |
| anthropics/claude-code | [#92953](https://github.com/anthropics/claude-code/issues/92953) | [Feature Request] Implement agent spawn validation to reduce unnecessary token usage |
| openai/codex | [#43855](https://github.com/openai/codex/issues/43855) | Codex stops after compaction |
| anthropics/claude-code | [#92845](https://github.com/anthropics/claude-code/issues/92845) | Asserts causal explanations without verifying; treats silently-failed commands as evidence of absence |
| anthropics/claude-code | [#92825](https://github.com/anthropics/claude-code/issues/92825) | [BUG] Claude Code Desktop: session transcripts silently become permanently unavailable (cliSessionId nulled, no local recovery path) — follow-up to  anthropics/claude-code#79044 |
| get-bb/bb | [#3238](https://github.com/get-bb/bb/issues/3238) | bb skill list ignores symlinked skills (root symlink and per-skill symlink both invisible, no warning) |
| langchain-ai/langgraph | [#8850](https://github.com/langchain-ai/langgraph/issues/8850) | Root Makefile aggregate targets can report success after a child command fails |
| anthropics/anthropic-sdk-python | [#1922](https://github.com/anthropics/anthropic-sdk-python/pull/1922) | fix(streaming): wrap mid-stream transport errors as APITimeoutError/APIConnectionError |
| openai/codex | [#43701](https://github.com/openai/codex/issues/43701) | [VS Code] Clarify delivery of Astra catalog fix #42874: latest stable bundles CLI 0.153.0 and cannot self-update |
| mistralai/mistral-vibe | [#1065](https://github.com/mistralai/mistral-vibe/pull/1065) | fix(app_server): increase connector tool limit to 1000 (#1056) |
| mixelpixx/Konnect | [#498](https://github.com/mixelpixx/Konnect/issues/498) | IPC socket auto-detection wedges KiCad's API server on Linux (no reply to any client until restart) |
| martymcenroe/AssemblyZero | [#3175](https://github.com/martymcenroe/AssemblyZero/issues/3175) | three fleet tools discover targets by code search and none reads incomplete_results, GitHub's own flag saying the answer is partial |
| anthropics/claude-code | [#92753](https://github.com/anthropics/claude-code/issues/92753) | Scheduled-task sessions intermittently freeze permanently on first/second tool call, never releasing their concurrency slot |
| mixelpixx/Konnect | [#481](https://github.com/mixelpixx/Konnect/pull/481) | fix(drc): name what owns each DRC report item |
| google/adk-python | [#7044](https://github.com/google/adk-python/pull/7044) | fix(plugins): wrap class descriptors from __dict__ |
| anthropics/anthropic-sdk-python | [#1921](https://github.com/anthropics/anthropic-sdk-python/pull/1921) | fix(streaming): raise the exception class matching an in-stream error's type |
| grammy-jiang/socratic-method | [#33](https://github.com/grammy-jiang/socratic-method/issues/33) | setup codex default (per-file symlinks) is invisible to Codex: its skill walk skips file symlinks (upstream openai/codex#31592) |
| anthropics/claude-code | [#92621](https://github.com/anthropics/claude-code/issues/92621) | Enable the built-in ccd_sidebar MCP tools (move_sessions, set_pinned, create_group) for my account |
| anthropics/claude-agent-sdk-python | [#1250](https://github.com/anthropics/claude-agent-sdk-python/pull/1250) | fix: forward strict tool-use flag through tools/list for SDK MCP servers |
| anthropics/claude-code | [#92583](https://github.com/anthropics/claude-code/issues/92583) | Windows: Bash tool commands auto-backgrounded on timeout are never cleaned up when the session ends, allowing orphaned processes to leak OS handles/kernel pool for days |
| UKGovernmentBEIS/inspect_ai | [#5266](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5266) | fix(scorer): normalize symbol assumptions before math() equivalence |
| anthropics/claude-code | [#92563](https://github.com/anthropics/claude-code/issues/92563) | Completed background-task notification is appended to the session but never triggers an assistant turn; session idles until user input |
| anthropics/claude-plugins-official | [#5905](https://github.com/anthropics/claude-plugins-official/issues/5905) | telegram v0.0.7: `claude mcp list` health-check probe SIGTERMs the active session's Telegram MCP server ("replacing stale poller") |
| anomalyco/opencode | [#47652](https://github.com/anomalyco/opencode/issues/47652) | Sessions disappear from the /sessions list after a local .git repo in the session's working directory is removed |
| techjarves/Mobile-Harness | [#10](https://github.com/techjarves/Mobile-Harness/issues/10) | BUG - Selecting Claude Subscription in the AI connections does nothing. |
| anthropics/claude-code | [#92505](https://github.com/anthropics/claude-code/issues/92505) | Model reports work as completed that it did not do, at a volume that defeats verification |
| openai/openai-agents-python | [#4890](https://github.com/openai/openai-agents-python/pull/4890) | fix: keep the file when apply_patch does a case-only rename |
| anthropics/claude-code | [#92485](https://github.com/anthropics/claude-code/issues/92485) | [Bug] Token usage spike unexplained during idle session |
| openai/openai-agents-python | [#4889](https://github.com/openai/openai-agents-python/issues/4889) | [Sandbox] apply_patch update_file with a case-only move_to deletes the file on a case-insensitive filesystem |
| google/adk-python | [#7030](https://github.com/google/adk-python/issues/7030) | Artifact services (in_memory, file, GCS) key storage on raw session_id — padded id creates a session it cannot reach |
| anthropics/claude-code | [#92452](https://github.com/anthropics/claude-code/issues/92452) | Dispatch start_code_task rejects second session in same non-git directory since 2.1.258 (regression from 2.1.247) |
| anthropics/claude-code | [#92429](https://github.com/anthropics/claude-code/issues/92429) | Scheduled task marks itself as completed (lastRunAt/nextRunAt advance) without actually running |
| xai-org/xai-sdk-python | [#207](https://github.com/xai-org/xai-sdk-python/pull/207) | fix: use monotonic clock in PollTimer to survive wall-clock jumps |
| monk-io/monk-plugin | [#496](https://github.com/monk-io/monk-plugin/pull/496) | fix(windows): write mcp_config.json as UTF-8 without BOM on Windows PowerShell 5.1 (#367) |
| UKGovernmentBEIS/inspect_ai | [#5261](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5261) | Fix math() scoring a symbolic answer differently depending on target notation |
| anthropics/claude-code | [#92409](https://github.com/anthropics/claude-code/issues/92409) | SendMessage tool missing in desktop Code tab session while ListAgents shows peers (2.1.258, Windows) |
| anthropics/anthropic-sdk-python | [#1915](https://github.com/anthropics/anthropic-sdk-python/issues/1915) | Three symlink tests in test_agent_toolset.py are missing the needs_symlinks marker |
| BerriAI/litellm | [#39979](https://github.com/BerriAI/litellm/issues/39979) | [Bug]: Request Logs date-range filter interprets the picker's local times as UTC — non-UTC users get silently shifted windows |
| anthropics/anthropic-sdk-python | [#1914](https://github.com/anthropics/anthropic-sdk-python/pull/1914) | fix(memory): require a separator after the /memories prefix |
| pyranthus-hq/mora | [#515](https://github.com/pyranthus-hq/mora/issues/515) | Acceptance: prove bounded Gmail incremental sync after the v0.15.1 cursor fixes |
| anthropics/claude-code | [#92264](https://github.com/anthropics/claude-code/issues/92264) | Idle background session stops advancing while async subagents are in flight, and resumes only when the operator opens it |
| anthropics/claude-code | [#92235](https://github.com/anthropics/claude-code/issues/92235) | Mobile client creates a duplicate session on every reconnect to a remote session; auto-archive on disconnect no longer fires |
| bartoszkobylinski/lovspor | [#246](https://github.com/bartoszkobylinski/lovspor/issues/246) | /security-check silently skips two source files: uvx bandit runs Python 3.11 and cannot parse PEP 695 |
| fraction-owl/transit_planning_with_python | [#157](https://github.com/fraction-owl/transit_planning_with_python/issues/157) | `SystemExit: 0` on a successful run reads as a crash to notebook users |
| jwalin-shah/inbox | [#69](https://github.com/jwalin-shah/inbox/issues/69) | Make Gmail incremental sync quota-safe and prevent one account failure from starving later sources |
| google/adk-python | [#7012](https://github.com/google/adk-python/pull/7012) | fix(tools): check_require_confirmation fails closed on non-bool callable return |
| NousResearch/hermes-agent | [#102811](https://github.com/NousResearch/hermes-agent/issues/102811) | [RFC] Skills prompt in prompt_builder.py forces over-eager skill loading |
| get-bb/bb | [#3059](https://github.com/get-bb/bb/issues/3059) | In-app browser opens signed-in services on their login form |
| openai/codex | [#42693](https://github.com/openai/codex/issues/42693) | Agent often stops after compaction instead of continuing the active task |
| cohere-ai/cohere-python | [#807](https://github.com/cohere-ai/cohere-python/pull/807) | [HTTPXodus] migrate httpx to httpx2 (hard switch; closes #806) |
| anthropics/claude-code | [#91905](https://github.com/anthropics/claude-code/issues/91905) | Fable 5.1 repeatedly ignores a standing "read the record before acting" directive (13 recorded instances in 15 days) |
| fer-osorio/claude-sandbox | [#65](https://github.com/fer-osorio/claude-sandbox/issues/65) | docs(global-layer): design curated auto-memory seeding |
| anthropics/claude-code | [#91898](https://github.com/anthropics/claude-code/issues/91898) | [BUG] Claude Desktop MCP: misleading "server may be unresponsive" 4-minute timeout message, and application logging lost since ~1.34493 |
| browser-use/browser-use | [#5663](https://github.com/browser-use/browser-use/pull/5663) | fix(llm): keep every system message in the Anthropic request |
| anthropics/claude-code | [#91884](https://github.com/anthropics/claude-code/issues/91884) | Desktop scheduled tasks: model selection broken end-to-end (spawns ignore user settings; documented picker absent; MCP tool lacks model param) |
| headroomlabs-ai/headroom | [#3418](https://github.com/headroomlabs-ai/headroom/issues/3418) | [BUG] Windows persistent install is impossible without admin: task XML uses `BootTrigger` + `S4U` |
| anthropics/claude-code | [#91879](https://github.com/anthropics/claude-code/issues/91879) | Scheduled-task runs leak a resident claude process per fire (2.1.255, Linux): 106 procs / 26 GB in 25 h — regression of #54626 |
| anthropics/claude-code | [#91870](https://github.com/anthropics/claude-code/issues/91870) | Mods - make Claude 10x more extensible |
| comet-ml/opik | [#8134](https://github.com/comet-ml/opik/issues/8134) | Evaluation pipeline: failed metrics silently dropped from averages; SUT output unescaped in judge prompts; g_eval logprob scoring misparses digit tokens; error handler imports SDKs inside except block |
| MichaelYcJo/SpecSeal | [#129](https://github.com/MichaelYcJo/SpecSeal/issues/129) | agents/smith.md's mutation-testing instruction clears tests/__pycache__ only, missing __pycache__ beside a module imported from elsewhere |
| vad1ym/oxlint-vue | [#2](https://github.com/vad1ym/oxlint-vue/issues/2) | `-c` / `--config` silently lint nothing and exit 0 |
| anthropics/claude-code | [#91830](https://github.com/anthropics/claude-code/issues/91830) | [FEATURE] VS Code Extension: Display persistent monthly usage/budget telemetry in status bar |
| MMoMM-org/the-custom-startup | [#118](https://github.com/MMoMM-org/the-custom-startup/issues/118) | statusline: use rate_limits from stdin and drop the ccusage dependency |
| woojubb/robota | [#2577](https://github.com/woojubb/robota/issues/2577) | [enhancement] Add a local cross-session usage dashboard for Robota CLI and GUI |
| agno-agi/agno | [#9928](https://github.com/agno-agi/agno/issues/9928) | [Bug] HITL pause from a custom function-executor Step is dropped end-to-end (works for Step(agent=)/Step(team=)) |
| NousResearch/hermes-agent | [#102089](https://github.com/NousResearch/hermes-agent/pull/102089) | fix(copilot-acp): stop completion.model impersonating a model that never ran |
| anthropics/claude-code | [#91767](https://github.com/anthropics/claude-code/issues/91767) | [FEATURE] Add model, stop_reason, token usage and tool timing to hook payloads |
| anthropics/claude-code | [#91735](https://github.com/anthropics/claude-code/issues/91735) | Non-ASCII project paths collide in ~/.claude/projects/, silently sharing memory and transcripts between different projects |
| anthropics/claude-agent-sdk-python | [#1246](https://github.com/anthropics/claude-agent-sdk-python/pull/1246) | Fix raw asyncio cancellation leaking CLI subprocesses |
| anthropics/claude-code | [#91689](https://github.com/anthropics/claude-code/issues/91689) | Context window balloons at fresh-session start (~40-70K baseline tokens) and full-file re-injection on every auto-compact |
| anthropics/claude-code | [#91660](https://github.com/anthropics/claude-code/issues/91660) | [Feature Request] Add writable MCP tool to assign sessions to sidebar groups |
| anthropics/claude-code | [#91642](https://github.com/anthropics/claude-code/issues/91642) | Scheduled-task CLI process does not exit after unattended run completes |
| vshulcz/deja-vu | [#2996](https://github.com/vshulcz/deja-vu/issues/2996) | Claude Code variants under ~/.cc-mirror and headless transcripts under ~/.claude/transcripts are not discovered |
| BerriAI/litellm | [#39370](https://github.com/BerriAI/litellm/issues/39370) | [Bug]: Reset-budget job never self-heals a budget_duration=null row with a stale budget_reset_at — spend is silently zeroed on every tick forever |
| Microck/satelle | [#199](https://github.com/Microck/satelle/issues/199) | windows session 0 background service isolation blocks desktop capture |
| mem0ai/mem0 | [#7211](https://github.com/mem0ai/mem0/issues/7211) | bug(vector-stores): Azure AI Search indexing errors silently ignored due to flawed hasattr status_code check |
| pydantic/pydantic-ai | [#8023](https://github.com/pydantic/pydantic-ai/issues/8023) | Wire-contract cases assert against their own cassette, so they cannot catch body drift |
| anthropics/claude-code | [#91523](https://github.com/anthropics/claude-code/issues/91523) | Background-task cleanup leaves orphaned find.exe processes on Windows (Git Bash/MSYS) |
| zenml-io/zenml | [#5215](https://github.com/zenml-io/zenml/issues/5215) | Idempotency support for webhook events |
| openai/openai-agents-python | [#4827](https://github.com/openai/openai-agents-python/issues/4827) | Deferred interrupted-turn session items are never persisted when an approval resume goes through next_step_run_again, leaving an orphaned function_call_output |
| garrytan/gbrain | [#4798](https://github.com/garrytan/gbrain/issues/4798) | UTF-8 BOM silently breaks heading title extraction (title falls back to filename) |
| rlespinasse/drawio-exporter | [#136](https://github.com/rlespinasse/drawio-exporter/issues/136) | read_file() does not strip a UTF-8 BOM before parsing drawio content |
| max-friedman/agentic-coding-loop | [#23](https://github.com/max-friedman/agentic-coding-loop/issues/23) | [proposal] Mutation-check the CARRIER, not just the ends — four consecutive rounds shipped a correct fix the suite could not see |
| anthropics/claude-code | [#91413](https://github.com/anthropics/claude-code/issues/91413) | [BUG] Individual sessions degrade 10-30x in latency while concurrent sessions on the same project, version and model stay normal |
| anthropics/anthropic-sdk-python | [#1906](https://github.com/anthropics/anthropic-sdk-python/pull/1906) | fix(memory): compare resolved paths in the delete and rename root guards |
| anthropics/claude-code | [#91371](https://github.com/anthropics/claude-code/issues/91371) | [BUG] Local scheduled tasks silently hang mid-run and block later scheduled fires |
| mistralai/mistral-vibe | [#1055](https://github.com/mistralai/mistral-vibe/issues/1055) | bug: MISTRAL_API_KEY silently overrides subscription-linked Vibe key |
| djm204/frankenbeast | [#4481](https://github.com/djm204/frankenbeast/issues/4481) | bug(observer): SpanLifecycle.recordTokenUsage diverges TokenCounter and span metadata on repeated calls |
| JordyZomer/lemmalog | [#3](https://github.com/JordyZomer/lemmalog/issues/3) | No retraction tool |
| basicmachines-co/basic-memory | [#1430](https://github.com/basicmachines-co/basic-memory/issues/1430) | Windows CI: test_chatgpt_search_pagination_default hangs in an aiosqlite call |
| mixelpixx/Konnect | [#411](https://github.com/mixelpixx/Konnect/issues/411) | score_placement's decoupling check flags a correctly-placed connector/interface cap as too far from the nearest IC |
| linuxfoundation/lfx-self-serve | [#2032](https://github.com/linuxfoundation/lfx-self-serve/issues/2032) | BUG: Sign Date in My CLAs shows UTC date, off by one day for negative-offset timezones |
| openai/codex | [#42080](https://github.com/openai/codex/issues/42080) | Codex long-task reliability: completion claims without target evidence and missing circuit breakers |
| anthropics/claude-code | [#91224](https://github.com/anthropics/claude-code/issues/91224) | [MODEL] Past in-session events re-dated to the current date after a midnight rollover |
| open-telemetry/semantic-conventions-genai | [#487](https://github.com/open-telemetry/semantic-conventions-genai/issues/487) | Usage buckets: how should consumers know which detail attributes are additive vs subsets of a total? |
| anthropics/claude-code | [#91188](https://github.com/anthropics/claude-code/issues/91188) | Feature request: make the auto-memory MEMORY.md compaction reminder threshold configurable |
| browser-use/browser-use | [#5633](https://github.com/browser-use/browser-use/issues/5633) | Bug:  AnthropicMessageSerializer drops earlier system messages |
| pydantic/pydantic-ai | [#7975](https://github.com/pydantic/pydantic-ai/issues/7975) | OTel usage attributes: should subset detail keys (reasoning/thinking/cache) be marked or protected against sum-consumers? |
| anthony-chaudhary/fak | [#10504](https://github.com/anthony-chaudhary/fak/issues/10504) | fix(watchdog): move recovery-critical scheduled tasks off interactive-only logon |
| plusky/bugwarden | [#203](https://github.com/plusky/bugwarden/issues/203) | Automated mutation testing, non-blocking only — to catch lapses in the hand-run discipline |
| azrtydxb/procoder | [#255](https://github.com/azrtydxb/procoder/issues/255) | internal/store: TestBreakingAStaleLockIsSerialised is load-dependent — flaked on macos-latest CI |
| anthropics/claude-code | [#91017](https://github.com/anthropics/claude-code/issues/91017) | Desktop app sidebar shows no CLI sessions — index stuck since April, not regenerated after removing it |
| thedotmack/claude-mem | [#3815](https://github.com/thedotmack/claude-mem/issues/3815) | Worker daemon has no USER/LOGNAME, so the SDK child falls back to keychain account "unknown" (expiresAt=0) — two days of silent auth failure on 13.18.0 |
| thedotmack/claude-mem | [#3814](https://github.com/thedotmack/claude-mem/issues/3814) | Observer output: constrained decoding via JSON schema removes the malformed-output failure class |
| MMoMM-org/the-custom-startup | [#85](https://github.com/MMoMM-org/the-custom-startup/issues/85) | agents: evaluate subagent persistent memory (memory: frontmatter) against the TCS memory bank |
| openai/openai-agents-python | [#4797](https://github.com/openai/openai-agents-python/pull/4797) | fix(voice): accept string TTS dtypes |
| anthropics/claude-code | [#90943](https://github.com/anthropics/claude-code/issues/90943) | [BUG] Concurrent sessions in one working tree: a stale git index silently deletes and reverts another session's committed work |
| obra/superpowers | [#2230](https://github.com/obra/superpowers/issues/2230) | skills/test-driven-development: three gaps — tests as the deliverable, detector suites, and closing deferred work |
| anthropics/claude-code | [#90912](https://github.com/anthropics/claude-code/issues/90912) | [BUG] Desktop: send_message rejects a normal interactive session as "unattended (scheduled-task run or dispatched session)" — regression, worked 21 Aug, broken now |
| openai/codex | [#41769](https://github.com/openai/codex/issues/41769) | Codex agent impersonated another agent, forged user approvals, and performed unauthorized external actions (real WhatsApp sends, webhook rotation) |
| aryaminus/controlkeel | [#145](https://github.com/aryaminus/controlkeel/issues/145) | Local stdio MCP bypasses the entire tool-authorization chain (tool policy, guardrails, scopes, audit log are hosted-only) |
| anthropics/claude-code | [#90822](https://github.com/anthropics/claude-code/issues/90822) | Desktop: no supported way to bring dormant sessions back into Remote Control after an app restart |
| langchain-ai/langgraph | [#8764](https://github.com/langchain-ai/langgraph/issues/8764) | Crash before first durable checkpoint can silently drop an accepted run with no durable failure record |
| google/adk-python | [#6957](https://github.com/google/adk-python/pull/6957) | fix(auth): stop OAuth2 client_secret and tokens from leaking over /run, /run_sse, /run_live |
| openai/openai-agents-python | [#4778](https://github.com/openai/openai-agents-python/pull/4778) | fix(voice): accept every NumPy spelling of a supported TTS dtype |
| openai/openai-agents-python | [#4777](https://github.com/openai/openai-agents-python/issues/4777) | VoicePipeline rejects string dtype spellings in TTS settings (`"dtype": "float32"` raises `UserError: Invalid output dtype`) |
| ohmyviv/longread-collector | [#159](https://github.com/ohmyviv/longread-collector/issues/159) | Reliability blocker: Sheets read amplification can exceed 60/min and create partial durability |
| anthropics/claude-code | [#90659](https://github.com/anthropics/claude-code/issues/90659) | Backgrounded Bash commands can report a false "exit code 0" completion when the command actually failed |
| UKGovernmentBEIS/inspect_ai | [#5125](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5125) | Fix a sandbox service permanently ceasing to answer requests after one slow request |
| openai/openai-agents-js | [#1775](https://github.com/openai/openai-agents-js/issues/1775) | code-change-verification cannot run on Windows under Node 20.12.2 or newer |
| UKGovernmentBEIS/inspect_ai | [#5122](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5122) | fix: EvalSample.store_as() silently dropping instance-scoped store data |
| anthropics/anthropic-sdk-typescript | [#1174](https://github.com/anthropics/anthropic-sdk-typescript/pull/1174) | fix: preserve defs when schema root is a ref, and fix compaction delta null content |
| watt-mind/factory | [#1136](https://github.com/watt-mind/factory/issues/1136) | epic: watt-mind-factory GitHub App — own rate budget, bot identity, least privilege |
| google/adk-python | [#6942](https://github.com/google/adk-python/pull/6942) | fix(sessions): normalize session id on read and delete too |
| anthropics/claude-code | [#90542](https://github.com/anthropics/claude-code/issues/90542) | [BUG] A complete CLAUDE.md rule contract governed nothing: 9 fabricated causes, stale state asserted as current, acceptance step silently skipped across a 4.5h session |
| kunchenguid/firstmate | [#3279](https://github.com/kunchenguid/firstmate/issues/3279) | fm_lock_acquire_wait spins forever when a reused PID masks a dead lock owner (watcher wedge) |
| get-bb/bb | [#2692](https://github.com/get-bb/bb/issues/2692) | A script automation cannot report UNKNOWN, so honest blindness auto-pauses it |
| monk-io/monk-plugin | [#367](https://github.com/monk-io/monk-plugin/issues/367) | [Bug bounty] Register-AntigravityMcp writes UTF-8 BOM into mcp_config.json on Windows PowerShell |
| anthropics/claude-code | [#90349](https://github.com/anthropics/claude-code/issues/90349) | Feature request: let a session start a new named session in the desktop app (spawn a peer, not a subagent) |
| modelcontextprotocol/python-sdk | [#3408](https://github.com/modelcontextprotocol/python-sdk/issues/3408) | test_safe_join_rejects_symlink_escape fails on Windows without elevation or Developer Mode |
| kytlogia/safario-historilo | [#180](https://github.com/kytlogia/safario-historilo/issues/180) | [Bug] Chrome起動中の履歴自動読み込み失敗時に「not an error」という無意味なエラーメッセージが表示される |
| topoteretes/cognee | [#4811](https://github.com/topoteretes/cognee/issues/4811) | Hackathon [Feature]: Add Reddit data-source connector |
| topoteretes/cognee | [#4730](https://github.com/topoteretes/cognee/issues/4730) | Hackathon [Feature]: Add Telegram data-source connector |
| topoteretes/cognee | [#4725](https://github.com/topoteretes/cognee/issues/4725) | Hackathon [Feature]: Add Obsidian vault data-source connector |
| google/adk-python | [#6933](https://github.com/google/adk-python/pull/6933) | fix(mcp): retry a tool call once after the server drops the session |
| amiable-dev/llm-council | [#674](https://github.com/amiable-dev/llm-council/issues/674) | Self-preference recusal is not currently possible — Stage 2's single-batch ranking call can't exclude a reviewer from judging only its own item |
| omegaup/omegaup | [#10136](https://github.com/omegaup/omegaup/issues/10136) | bug: SystemExit(0) in with-body recorded as failure |
| anthropics/claude-code | [#90215](https://github.com/anthropics/claude-code/issues/90215) | [BUG] Scheduled task cron dispatch silently fails to fire — no lastRunAt, no execution, no error |
| UKGovernmentBEIS/inspect_ai | [#5090](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5090) | fix(solver): accept any sequence of solvers consistently |
| BerriAI/litellm | [#38535](https://github.com/BerriAI/litellm/issues/38535) | Router policy knob `treat_finish_reason_as_failure`: let a terminal stop_reason count as a deployment failure so allowed_fails, cooldown, and fallbacks engage |
| anthropics/claude-code | [#90135](https://github.com/anthropics/claude-code/issues/90135) | [BUG] Marketplace plugin re-materialization mid-session silently kills pinned hooks in every running session — and the failure is undetectable from inside the plugin |
| anthropics/claude-code | [#90080](https://github.com/anthropics/claude-code/issues/90080) | Feature request: register Remote Control for all sessions at once - registrations don't survive app restart |
| anthropics/claude-code | [#90077](https://github.com/anthropics/claude-code/issues/90077) | [BUG] Hooks with `shell: "powershell"` spawn `pwsh` with no `powershell.exe` fallback, so hooks silently never run on a stock Windows box |
| Lyellr88/marm-memory | [#170](https://github.com/Lyellr88/marm-memory/issues/170) | testing: expand Docker coverage, only 8 of 43 Docker tests run a container and none run in PR CI |
| macanderson/stella | [#5287](https://github.com/macanderson/stella/issues/5287) | Parallel agent sessions can share one checkout, and a branch switch silently reverts another session's uncommitted work |
| anthropics/claude-code | [#90017](https://github.com/anthropics/claude-code/issues/90017) | [Bug] Model ignores root-cause analysis guardrails and optimizes wrong assumption despite explicit mitigations |
| anthropics/claude-code | [#89972](https://github.com/anthropics/claude-code/issues/89972) | Workflow agent() model silently replaced by CLAUDE_CODE_SUBAGENT_MODEL when the id is not in the gateway-discovered model list |
| google-gemini/gemini-cli | [#29101](https://github.com/google-gemini/gemini-cli/issues/29101) | Authentication failure blocking Enterprise Workspace accounts |
| screenpipe/screenpipe | [#6698](https://github.com/screenpipe/screenpipe/issues/6698) | [feature] private infinite memory with on-demand AI access |
| anthropics/claude-code | [#89936](https://github.com/anthropics/claude-code/issues/89936) | Scheduled tasks: lastRunAt never updates while nextRunAt keeps advancing (task silently never executes) |
| anthropics/claude-agent-sdk-python | [#1237](https://github.com/anthropics/claude-agent-sdk-python/pull/1237) | fix(sessions): surface subagent import I/O failures |
| anthropics/claude-code | [#89811](https://github.com/anthropics/claude-code/issues/89811) | [BUG] Scheduled tasks report success but silently perform zero work |
| anthropics/claude-code | [#89783](https://github.com/anthropics/claude-code/issues/89783) | [FEATURE] Programmatically spawn multiple named child sessions that auto-start (no manual chip click) for routine fan-out |
| xCirno1/applyer | [#29](https://github.com/xCirno1/applyer/issues/29) | Search company ATS boards (Greenhouse/Lever/Ashby) as a job source |
| truera/trulens | [#2730](https://github.com/truera/trulens/pull/2730) | fix(database): SQL-level aggregation in pre-OTel leaderboard |
| screenpipe/screenpipe | [#6661](https://github.com/screenpipe/screenpipe/issues/6661) | [question] Free plan storage block - is this intended? |
| get-bb/bb | [#2433](https://github.com/get-bb/bb/issues/2433) | No per-host capacity model: bb over-schedules one machine until its daemon dies, and drops the spawn prompt on retry |
| anthropics/claude-code | [#89639](https://github.com/anthropics/claude-code/issues/89639) | macOS: scheduled-task sessions wedge mid tool-call (~30s in, WebSearch/WebFetch), stay "running" for days, and pin global concurrency slots until the whole schedule starves |
| anthropics/claude-code | [#89632](https://github.com/anthropics/claude-code/issues/89632) | Local scheduled tasks run under interactive ask-every-tool permissions, despite being framed as unattended |
| zilliztech/memsearch | [#703](https://github.com/zilliztech/memsearch/issues/703) | Windows is blocked by an obsolete platform guard — milvus-lite has shipped pure-Python wheels since 3.0 |
| anthropics/claude-code | [#89604](https://github.com/anthropics/claude-code/issues/89604) | [BUG] Headless session start reports already-authorized claude.ai connectors as requiring authentication; tool calls then succeed |
| anthropics/claude-code | [#89596](https://github.com/anthropics/claude-code/issues/89596) | [BUG] scheduled-task sub-agents self-invoke a skill and spawn duplicate agents, multiplying token spend |
| rysweet/azlin | [#1159](https://github.com/rysweet/azlin/issues/1159) | Provision OOM containment on hosts: a runaway agent tree kills systemd --user and takes every tmux session with it |
| eirkkr/fieldkit | [#77](https://github.com/eirkkr/fieldkit/issues/77) | Add writing rules for prose, and a hook to trigger them |
| Wei-Shaw/sub2api | [#6176](https://github.com/Wei-Shaw/sub2api/issues/6176) | google pro 个人授权提示403 |
| yinggarykairui/factory-hub | [#90](https://github.com/yinggarykairui/factory-hub/issues/90) | meta: STYLE.md's '2-5 sentences' fights its own 'short sentences' rule, and the count is the one that keeps winning |
| PrefectHQ/fastmcp | [#4899](https://github.com/PrefectHQ/fastmcp/issues/4899) | Client .data returns date, time, timedelta and UUID as strings; datetime hydrates |
| google/adk-python | [#6891](https://github.com/google/adk-python/pull/6891) | fix(sessions): trim session id before the in-memory duplicate check |
| malamoney/jobfinder | [#2](https://github.com/malamoney/jobfinder/issues/2) | Build Jobfinder: nightly Board sweep, Criteria matching, and review Dashboard |
| anthropics/anthropic-sdk-typescript | [#1165](https://github.com/anthropics/anthropic-sdk-typescript/pull/1165) | fix(BetaMessageStream): preserve null content and existing checkpoint in compaction_delta |
| anthropics/claude-code | [#89342](https://github.com/anthropics/claude-code/issues/89342) | [BUG] 2026-08-24 build breaks desktop-to-desktop Remote Control: resumed sessions never re-publish, /remote-control spawns duplicates, list regrouped into machine folders |
| sodiumsun/agenttrail | [#1](https://github.com/sodiumsun/agenttrail/issues/1) | Recursive fs.watch exhausts the inotify limit and hard-crashes the daemon (ENOSPC) on JS repos |
| drabaioli/cdd | [#78](https://github.com/drabaioli/cdd/issues/78) | Cap prose length the way the roadmap cap does: inventory and proposed rules |
| roxspring/markflow | [#22](https://github.com/roxspring/markflow/issues/22) | Lint rule: one sentence per line |
| anthropics/claude-code | [#89316](https://github.com/anthropics/claude-code/issues/89316) | [Bug] Duplicate Remote Control sessions created with identical task names on single local prompt |
| anthropics/claude-agent-sdk-python | [#1234](https://github.com/anthropics/claude-agent-sdk-python/issues/1234) | Bug: claude-agent-sdk 0.2.144 is a partial publish |
| langfuse/langfuse | [#16494](https://github.com/langfuse/langfuse/issues/16494) | bug(automations): Execution logs get stuck on PENDING when jobs fail. |
| openai/codex | [#40442](https://github.com/openai/codex/issues/40442) | [Bug] Codex generated and defended an incorrect document date despite verified local time |
| anthropics/claude-code | [#89283](https://github.com/anthropics/claude-code/issues/89283) | [BUG] Desktop app creates duplicate project directories for UNC cwd (trailing-separator normalization), causing daily chat-history loss |
| UKGovernmentBEIS/inspect_ai | [#5029](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5029) | fix(scorer): return inf on OverflowError in perplexity metrics |
| Eppie-io/Eppie-CLI | [#622](https://github.com/Eppie-io/Eppie-CLI/issues/622) | UTF-8 BOM becomes part of piped vault password |
| basicmachines-co/basic-memory | [#1315](https://github.com/basicmachines-co/basic-memory/issues/1315) | [BUG] basic-memory doctor always fails with "API note file missing" outside test mode |
| asciimoo/hister | [#626](https://github.com/asciimoo/hister/issues/626) | command to import browser bookmarks |
| openai/openai-agents-js | [#1752](https://github.com/openai/openai-agents-js/pull/1752) | fix(extensions): decode PTY output incrementally |
| get-bb/bb | [#2328](https://github.com/get-bb/bb/issues/2328) | Automatic recovery storms a dead Codex thread with repeated no-active-session errors |
| modelcontextprotocol/typescript-sdk | [#2706](https://github.com/modelcontextprotocol/typescript-sdk/pull/2706) | fix(stdio): share a single drain listener under backpressure |
| openclaw/openclaw | [#128395](https://github.com/openclaw/openclaw/issues/128395) | claude-cli backend: per-agent tools.deny never reaches --disallowedTools, so every agent can call every mcp.servers entry |
| anthropics/claude-code | [#89068](https://github.com/anthropics/claude-code/issues/89068) | [Bug] Token usage discrepancy between session carryover and actual Opus usage |
| anthropics/claude-code | [#89040](https://github.com/anthropics/claude-code/issues/89040) | /compact silently fails to apply on very large conversations: summary generated, boundary never written, context unchanged |
| browser-use/browser-use | [#5529](https://github.com/browser-use/browser-use/issues/5529) | Bug: failed automatic new-tab switch is reported as successful after click |
| anthropics/claude-code | [#88982](https://github.com/anthropics/claude-code/issues/88982) | Scheduled task sessions (Desktop local agent mode) never exit after completing; processes accumulate until the host runs out of memory |
| su-kaka/gcli2api | [#401](https://github.com/su-kaka/gcli2api/issues/401) | [Bug]: gcli2api 调用403 |
| anthropics/claude-code | [#88951](https://github.com/anthropics/claude-code/issues/88951) | remoteControlAtStartup silently no-ops when OAuth is unhealthy at session start — never re-evaluated, session invisible to ListAgents for its whole lifetime |
| Morrison-Lab/ai-config | [#2004](https://github.com/Morrison-Lab/ai-config/issues/2004) | Every PreToolUse and Stop hook is inert in remote/web sessions: the plugin is never installed |
| mistralai/mistral-vibe | [#1030](https://github.com/mistralai/mistral-vibe/issues/1030) | bug: NO_COLOR=1 makes vibe useless |
| anthropics/claude-code | [#88862](https://github.com/anthropics/claude-code/issues/88862) | Field report: concurrent sessions sharing one git clone — measured collisions, three userland mitigations, and the residue only the harness can fix |
| kyegomez/swarms | [#1982](https://github.com/kyegomez/swarms/issues/1982) | [FEAT] Enforce a read-before-write invariant on file edits |
| jszmajda/lid | [#73](https://github.com/jszmajda/lid/issues/73) | Vacuous tests read as coverage: the test level admits one instrument, so specs that resist automatic validation have no compliant move but an empty test |
| anthropics/claude-code | [#88813](https://github.com/anthropics/claude-code/issues/88813) | Unresolvable `@import` in CLAUDE.md fails completely silently — no warning, and /context shows nothing missing |
| anthropics/anthropic-sdk-python | [#1871](https://github.com/anthropics/anthropic-sdk-python/issues/1871) | `setup_skills` re-downloads and `rmtree`s skills on every session, racing when workers share a workdir |
| xai-org/xai-sdk-python | [#204](https://github.com/xai-org/xai-sdk-python/pull/204) | fix: account polling elapsed time on the monotonic clock |
| anthropics/claude-code | [#88738](https://github.com/anthropics/claude-code/issues/88738) | PreToolUse hook silently stops firing mid-session and never recovers; concurrent session unaffected |
| huggingface/smolagents | [#2678](https://github.com/huggingface/smolagents/pull/2678) | fix(types): fix AgentImage numpy/tensor conversion and color inversion bug |
| anthropics/claude-code | [#88705](https://github.com/anthropics/claude-code/issues/88705) | Sidebar session list repeatedly goes empty despite session data being intact |
| anthropics/claude-code | [#88579](https://github.com/anthropics/claude-code/issues/88579) | Persistent memory: ships but is invisible, per-directory, and unverifiable — why a 91k-star third-party replacement exists |
| anthropics/claude-code | [#88578](https://github.com/anthropics/claude-code/issues/88578) | [BUG] Windows hook commands with backslash paths silently never execute (bash eats the backslashes) — killed my memory hooks for 46 days |
| anthropics/claude-agent-sdk-python | [#1226](https://github.com/anthropics/claude-agent-sdk-python/issues/1226) | SDK MCP tools unavailable when resuming with empty streaming input (regression in 0.2.140) |
| tenequm/pond | [#166](https://github.com/tenequm/pond/issues/166) | tenants: keep work and personal sessions apart, scope what each agent can recall |
| BerriAI/litellm | [#37789](https://github.com/BerriAI/litellm/pull/37789) | fix(compact): count the team model rate limit descriptor once |
| zilliztech/memsearch | [#692](https://github.com/zilliztech/memsearch/issues/692) | Claude Code plugin: watch pidfile lives inside the watched dir, so removing a git worktree orphans its watcher permanently (34 leaked trees / 6.7 GB observed) |
| anthropics/claude-code | [#88308](https://github.com/anthropics/claude-code/issues/88308) | [BUG] Scheduled-task MCP tools (list_scheduled_tasks / update_scheduled_task) missing from session context on Windows — existing local tasks can't be read or edited by prompt |
| huggingface/smolagents | [#2665](https://github.com/huggingface/smolagents/pull/2665) | Fix color inversion for tensor-backed `AgentImage` |
| agno-agi/agno | [#9633](https://github.com/agno-agi/agno/pull/9633) | fix: stringify non-string enum values in Gemini convert_schema |
| sourcefrog/cargo-mutants | [#643](https://github.com/sourcefrog/cargo-mutants/issues/643) | Detect nondeterministic tests before a mutation run |
| anthropics/claude-code | [#88178](https://github.com/anthropics/claude-code/issues/88178) | Claude Desktop: 5h46 of cumulative waiting in one day — 23 silent ~15-minute stalls across 6 sessions |
| NousResearch/hermes-agent | [#88378](https://github.com/NousResearch/hermes-agent/pull/88378) | fix(update): purge stale modules before dashboard cleanup on the ZIP path |
| mem0ai/mem0 | [#6935](https://github.com/mem0ai/mem0/pull/6935) | fix(milvus): convert COSINE distance to similarity in _parse_output |
| anthropics/anthropic-sdk-python | [#1815](https://github.com/anthropics/anthropic-sdk-python/pull/1815) | fix(streaming): initialize usage when message_start omits it |
| dipakkrishnan/windup | [#7](https://github.com/dipakkrishnan/windup/pull/7) | Clean up plist and runner on failed launchctl bootstrap |
| mem0ai/mem0 | [#6859](https://github.com/mem0ai/mem0/pull/6859) | fix(vector_stores/azure_ai_search): raise on failed indexing results |
| anthropics/claude-cookbooks | [#803](https://github.com/anthropics/claude-cookbooks/pull/803) | fix(managed-agents): bind approval to exact merge |
| browserbase/stagehand | [#2527](https://github.com/browserbase/stagehand/pull/2527) | fix(locator): serialize click input events |
| modelcontextprotocol/python-sdk | [#3221](https://github.com/modelcontextprotocol/python-sdk/pull/3221) | fix(server): reject concurrent duplicate JSON-RPC request ids |
| paperclipai/paperclip | [#10412](https://github.com/paperclipai/paperclip/pull/10412) | fix(heartbeat): make agent wakeup idempotency keys actually deduplicate |
| openai/openai-agents-python | [#3998](https://github.com/openai/openai-agents-python/pull/3998) | fix: defer session save until after output guardrails |
| anthropics/claude-agent-sdk-python | [#1148](https://github.com/anthropics/claude-agent-sdk-python/pull/1148) | Default strict_mcp_config to true |
| anthropics/claude-code | [#81672](https://github.com/anthropics/claude-code/pull/81672) | fix(hookify): make package import independent of the install directory name |
| openai/openai-agents-python | [#3984](https://github.com/openai/openai-agents-python/pull/3984) | fix(memory): prevent close() race and enforce closed state in AsyncSQLiteSession |
| anthropics/claude-agent-sdk-python | [#1112](https://github.com/anthropics/claude-agent-sdk-python/pull/1112) | fix(transport): unblock read_messages when the CLI dies but orphans hold its stdout pipe |
| anthropics/claude-agent-sdk-python | [#1109](https://github.com/anthropics/claude-agent-sdk-python/pull/1109) | fix: surface prompt stream errors instead of hanging query() forever |
| NousResearch/hermes-agent | [#48229](https://github.com/NousResearch/hermes-agent/pull/48229) | fix: escape launchd plist values |
| louislva/claude-peers-mcp | [#58](https://github.com/louislva/claude-peers-mcp/pull/58) | Detect orphaned MCP server and exit cleanly |

---

Generated by `github_evidence_snapshot.py` on 2026-10-18T03:24:49Z. Regenerated weekly; the dated full archive lives outside GitHub.

---

<!--ecosystem-map:start-->

## 🧩 One piece of a working system

This repository is one piece lifted out of a live operation: one engineer running a fleet of
machines, built with Claude as implementation collaborator; the machines reach consensus with
each other and wake the human only for money or the irreversible. It was extracted after it
survived production, not written as a demo — and it runs on its own: nothing here phones home
to the rest.

**See how the whole thing fits together → [SYSTEM.md](https://github.com/tonydzi/tonydzi/blob/main/SYSTEM.md)**

<!--ecosystem-map:end-->

## AI contributors

This project is built by a human + AI team, and the git log says so: Claude writes most of
the code, Codex and Grok review it, Gemini feeds the research. Each is credited on a commit
**only if its output changed that commit's content** — no decorative credits. Lab-wide
policy, one source for every repo: [AI-CONTRIBUTORS.md](https://github.com/tonydzi/.github/blob/main/AI-CONTRIBUTORS.md).
