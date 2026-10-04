# Upstream contribution evidence — @tonydzi

Snapshot: **2026-10-04** · source: public GitHub API · regenerated weekly.

This page exists so the contribution record stays checkable independently of any one profile page. Everything below is a link into someone else's repository: their issue tracker, their pull requests, their release notes.

Counts are split on purpose. Opening a pull request in someone else's project and commenting in someone else's thread are different things, and adding them together would overstate the first.

| | |
|---|---:|
| Pull requests opened in other people's repos | 140 |
| …of which merged | 49 |
| Issues opened in other people's repos | 64 |
| Other people's threads participated in | 408 |
| Reviews on other people's PRs | 64 |
| Distinct repositories | 230 |
| Replies received from maintainers and participants | 1999 |
| Release notes crediting this account | 21 |
| Files in other repos crediting this account | 27 |

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

**QwenLM/qwen-code — v0.22.3-nightly.20260831.3a0c4c6108** · 2026-08-31 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/v0.22.3-nightly.20260831.3a0c4c6108)

> * fix(core): do not claim a question host in stream-json direct mode by @tonydzi in https://github.com/QwenLM/qwen-code/pull/9414
> * @tonydzi made their first contribution in https://github.com/QwenLM/qwen-code/pull/9414

**QwenLM/qwen-code — cua-driver-rs-v0.20.3** · 2026-09-01 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/cua-driver-rs-v0.20.3)

> * fix(core): do not claim a question host in stream-json direct mode by @tonydzi in https://github.com/QwenLM/qwen-code/pull/9414
> * @tonydzi made their first contribution in https://github.com/QwenLM/qwen-code/pull/9414

**Lyellr88/marm-memory — v2.46.2** · 2026-09-02 · [release notes](https://github.com/Lyellr88/marm-memory/releases/tag/v2.46.2)

> The 8 tests in `tests/test_docker_transports.py` that actually start a container previously only ran in the release workflow, which triggers on a version tag, so a Docker runtime regression was caught after a release was already tagged rather than on the PR that caused it. Contributed by [@tonydzi](https://github.com/tonydzi).
> `scripts/test-scripts/smoke_embedding_chunking.py` had been broken since chunking was split into separate memory and document profiles: it imported constants that no longer existed and called `_chunk_text` without the keyword arguments it now requires. Contributed by [@tonydzi](https://github.com/tonydzi).
> * fix(scripts): repair smoke_embedding_chunking against the v2.14.0 chunk profiles by @tonydzi in https://github.com/Lyellr88/marm-memory/pull/181
> * ci: build the image on PRs and run the docker-marked tests (#170 item 1) by @tonydzi in https://github.com/Lyellr88/marm-memory/pull/183

**QwenLM/qwen-code — v0.23.0** · 2026-09-03 · [release notes](https://github.com/QwenLM/qwen-code/releases/tag/v0.23.0)

> - Prevented the system from incorrectly claiming a question host in stream-json direct mode when the control system is inactive. ([#9414](https://github.com/QwenLM/qwen-code/pull/9414)) by @tonydzi
> - @tonydzi made their first contribution in [#9414](https://github.com/QwenLM/qwen-code/pull/9414)

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

## Credited in other projects' files

Lines maintainers wrote into their own changelogs and contributor lists.

**eugeniughelbur/obsidian-second-brain · [`CHANGELOG.md`](https://github.com/eugeniughelbur/obsidian-second-brain/blob/b0089f7666d0c1e3db41c9d587b6f3c997665235/CHANGELOG.md)**

> - **The write-time hook reported `payload keys: none` for a payload that had a path key one level up (#171, reported by @tonydzi).** A payload like `{"tool_name":"Write","file_path":"..."}` still exited 1 and stayed fail-closed, but the diagnostic listed only keys under `tool_input` and `args`. It n …
> - **`validate-ai-first.sh` exited 0, silently, when a write payload named a tool but carried no path key it knew (#171, the open item from @tonydzi's codex-cli reports).** The hook read `file_path` and `filePath` (and `args.*`); a host that sends the path under another key (`path`, `uri`) got exit 0 …

**basicmachines-co/basic-memory · [`CHANGELOG.md`](https://github.com/basicmachines-co/basic-memory/blob/194afe165b3e7676496aaa53b70e39a78ea5aa4f/CHANGELOG.md)**

> @tonydzi for the report and fix (#1617, landed as #1619).

**Lyellr88/marm-memory · [`CONTRIBUTORS.md`](https://github.com/Lyellr88/marm-memory/blob/7f71d35c7ec605eb3f18b55c81ad42622062c094/CONTRIBUTORS.md)**

> - **Anton Dziatkovskii** ([@tonydzi](https://github.com/tonydzi)) —

**Lyellr88/marm-memory · [`CHANGELOG.md`](https://github.com/Lyellr88/marm-memory/blob/7f71d35c7ec605eb3f18b55c81ad42622062c094/CHANGELOG.md)**

> The 8 tests in `tests/test_docker_transports.py` that actually start a container previously only ran in the release workflow, which triggers on a version tag, so a Docker runtime regression was caught after a release was already tagged rather than on the PR that caused it. Contributed by [@tonydzi]( …
> `scripts/test-scripts/smoke_embedding_chunking.py` had been broken since chunking was split into separate memory and document profiles: it imported constants that no longer existed and called `_chunk_text` without the keyword arguments it now requires. Contributed by [@tonydzi](https://github.com/to …
> The README published to PyPI carried 17 links written relative to the repository root, a position neither surface that renders that file ever occupies. Reported and fixed by [@tonydzi](https://github.com/tonydzi).

**qualixar/superlocalmemory · [`CHANGELOG.md`](https://github.com/qualixar/superlocalmemory/blob/8f9e953e9d61741271c67434fd37ee554217e7a5/CHANGELOG.md)**

> Reported by @tonydzi (#122).

**michellzappa/headroom · [`CHANGELOG.md`](https://github.com/michellzappa/headroom/blob/b839efbbe5c6a798e2d84039d5376178de35331c/CHANGELOG.md)**

> (#28, reported by @tonydzi). Claude Code writes one JSONL line per content

**borq168/radar-forge · [`digests/2026-08-08/ai-skills-en.md`](https://github.com/borq168/radar-forge/blob/55beba194fd51480c7cd4812702554743ae6cd55/digests/2026-08-08/ai-skills-en.md)**

> | plan-file-hygiene | #1479 | @tonydzi | Open, July 27 update | Lifecycle management for planning artifacts. Community credit to @halilxibrahim. |

**linny006/mcp-servers-live · [`r/tonydzi/telegram-mcp-kit/index.html`](https://github.com/linny006/mcp-servers-live/blob/3afa90fdfed6b9d5a287cd93a7f28eab0ec28d86/r/tonydzi/telegram-mcp-kit/index.html)**

> <title>tonydzi/telegram-mcp-kit - entry on MCP Servers Live</title>
> <link rel="canonical" href="https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-mcp-kit/">
> <meta property="og:title" content="tonydzi/telegram-mcp-kit - entry on MCP Servers Live">
> <meta property="og:url" content="https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-mcp-kit/">
> <meta name="twitter:title" content="tonydzi/telegram-mcp-kit - entry on MCP Servers Live">
> <script type="application/ld+json">{"@context":"https://schema.org","@type":"SoftwareSourceCode","name":"tonydzi/telegram-mcp-kit","codeRepository":"https://github.com/tonydzi/telegram-mcp-kit","programmingLanguage":"PowerShell","url":"https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-m …

**linny006/mcp-servers-live · [`r/tonydzi/whatsapp-mcp-kit/index.html`](https://github.com/linny006/mcp-servers-live/blob/3afa90fdfed6b9d5a287cd93a7f28eab0ec28d86/r/tonydzi/whatsapp-mcp-kit/index.html)**

> <title>tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live</title>
> <link rel="canonical" href="https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-kit/">
> <meta property="og:title" content="tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live">
> <meta property="og:url" content="https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-kit/">
> <meta name="twitter:title" content="tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live">
> <script type="application/ld+json">{"@context":"https://schema.org","@type":"SoftwareSourceCode","name":"tonydzi/whatsapp-mcp-kit","codeRepository":"https://github.com/tonydzi/whatsapp-mcp-kit","programmingLanguage":"Python","url":"https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-k …

**DanceNitra/agora · [`probes/recheck_figures_91188_units.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/recheck_figures_91188_units.py)**

> by_tonydzi = gh("repos/anthropics/claude-code/issues/91188/comments",
> '.[] | select(.user.login=="tonydzi") | .body')
> thread = body + by_tonydzi + by_pm25
> "tonydzi carried it there today; the draft references the unit once and proves nothing")
> chk("tonydzi asked it, and the draft says so",
> "@tonydzi asked @niels-roest whether that target", asked in by_tonydzi,

**DanceNitra/agora · [`probes/a_cut_delivery_redacted_for_detector_controls.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/a_cut_delivery_redacted_for_detector_controls.py)**

> and @tonydzi pointed out that a check which has never been red is an untested instrument: the zero

**QwenLM/qwen-code-docs · [`website/content/zh/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/zh/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 首次贡献：stream-json 模式提问宿主修复 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/en/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/en/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 First contribution: fix for question host in stream-json mode | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/de/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/de/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Erster Beitrag: Fix für Frage-Host im stream-json-Modus | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ko/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/ko/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 첫 기여: stream-json 모드 질문 호스트 수정 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/fr/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/fr/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Première contribution : correction de l'hôte de questionnement en mode stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ja/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/ja/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 初貢献：stream-json モードの質問ホストの修正 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ru/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/ru/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Первый вклад: исправление запросов к хосту в режиме stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**DanceNitra/agora · [`probes/what_our_own_index_actually_delivers.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/what_our_own_index_actually_delivers.py)**

> trap @tonydzi described on anthropics/claude-code#91188 for bytes against units.

**DanceNitra/agora · [`probes/does_a_folded_scalar_description_arrive_at_the_model.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/does_a_folded_scalar_description_arrive_at_the_model.py)**

> WHY. anthropics/claude-code#81081, comment of 2026-09-15 by @tonydzi: on a shelf of 189 skills,
> "claim_under_test": "anthropics/claude-code#81081, @tonydzi 2026-09-15: a `description: >` folded "

**QwenLM/qwen-code-docs · [`website/content/pt-BR/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/8d44b67ebee3b573236711e5666eabf9d8efeb1b/website/content/pt-BR/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Primeira contribuição: correção do host de perguntas no modo stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**DanceNitra/agora · [`probes/the_reminders_advice_switches_unit_at_125_units_per_line.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/the_reminders_advice_switches_unit_at_125_units_per_line.py)**

> He has no `claude` binary and took the identifier shapes from @tonydzi's greps. This reads the
> 125 units per line. But the threshold was named in that thread by @tonydzi and @pm25coder before us,
> ("tonydzi index (his counts)", 8188, 72),

**DanceNitra/agora · [`probes/the_cap_on_windows_and_what_a_crlf_line_costs.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/the_cap_on_windows_and_what_a_crlf_line_costs.py)**

> @tonydzi is darwin-arm64 and has annotated his own Windows figure as unverified. There is no

**DanceNitra/agora · [`probes/the_cut_measured_by_what_the_index_DOES_not_what_it_says.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/the_cut_measured_by_what_the_index_DOES_not_what_it_says.py)**

> Windows, current CC. @JhouCode is linux-x64, @tonydzi darwin-arm64 and has annotated his own Windows

**Kaap10/kaap10.github.io · [`src/pages/opensource/sqlite-graph-memory.js`](https://github.com/Kaap10/kaap10.github.io/blob/e78511630e4d1a7c07100286e240ce3ea8fcf15d/src/pages/opensource/sqlite-graph-memory.js)**

> title: 'tonydzi/sqlite-graph-memory',
> github: 'https://github.com/tonydzi/sqlite-graph-memory',
> prsUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pulls?q=is%3Apr+is%3Amerged+author%3AKaap10',
> prUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pull/8',
> prUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pull/10',
> prUrl: 'https://github.com/tonydzi/sqlite-graph-memory/pull/14',

**DanceNitra/agora · [`probes/the_memory_index_check_grew_a_second_size_and_the_team_path_grew_a_line_cap.py`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/the_memory_index_check_grew_a_second_size_and_the_team_path_grew_a_line_cap.py)**

> WHY. On anthropics/claude-code#91188 @tonydzi read CLI 2.1.202 on macOS and reported three things:
> * The team path DOES pass a lineCap, conditionally. @tonydzi's third finding does not reproduce

**DanceNitra/agora · [`probes/does_a_folded_scalar_description_arrive_at_the_model.result.json`](https://github.com/DanceNitra/agora/blob/d69f3a007c124c6c6a1c426322aebfb98002847b/probes/does_a_folded_scalar_description_arrive_at_the_model.result.json)**

> "claim_under_test": "anthropics/claude-code#81081, @tonydzi 2026-09-15: a `description: >` folded scalar arrives as a heading, 68 of 189 on their shelf",

## What maintainers replied

Replies in threads we opened, plus replies elsewhere that name this account. Quotes are trimmed; every one links to the original.

### [QwenLM/qwen-code PR #12875](https://github.com/QwenLM/qwen-code/pull/12875) — fix(core): add opt-in failMode: "closed" for PreToolUse command hooks

*Role here: our pull request.*

*qwen-code-ci-bot*, 2026-09-27:

> <!-- qwen-triage stage=1a --> @tonydzi thanks for this. The fail-open behaviour you describe is real — #12457 already carries a maintainer's file:line confirmation of it, and I re-read the runner and the PreToolUse trigger myself, so the motivation is not in question. I have to stop at the description, though. It doesn't use the [PR template](https://github.com/QwenLM/qwen-code/blob/main/.github/pull_request_template.md) — none of the template's sections are present, so there is no **Reviewer Test Plan**, no **Evidence (Before & After)**, no **Tested on** matrix, no **Risk & Scope**, and no **Linked Issues**. That matters more than it sounds for this particular change: reviewers decide from …

*qwen-code-ci-bot*, 2026-10-04:

> **[Critical]** R2-3: [certifies-falsely] [new-surface] All seven new denial arms live inside `executeCommandHook`'s promise. A throw that escapes them lands in `executeHook`'s generic catch (hookRunner.ts:805-818), which builds its result with no `output` and no `failMode` check. Round 1 filed this ground as part of R1-7 at Suggestion severity and correctly refuted the missing-command entrance; this round's probe establishes the synchronous-throw entrance as reachable and Critical. The anchored line is the sibling that DOES deny, for contrast. A settings-sourced PreToolUse command hook carries `failMode: "closed"` and a `command` string containing a NUL byte — `"command": "guard\^@.sh"`, whi …

### [QwenLM/qwen-code PR #9414](https://github.com/QwenLM/qwen-code/pull/9414) — fix(core): do not claim a question host in stream-json direct mode

*Role here: our pull request.*

*qwen-code-ci-bot*, 2026-08-18:

> <!-- qwen-triage stage=1a --> Thanks @tonydzi — the write-up is thorough, and the underlying bug is real (see #9011). Before this can move to code review, one housekeeping item: the PR body doesn't use the repository's pull request template. Merged PRs here follow that template consistently, and reviewers rely on the fixed sections to find what they need. The body is missing all of the required headings: - `## What this PR does` - `## Why it's needed` - `## Reviewer Test Plan` (with `### How to verify`, `### Evidence (Before & After)`, and the `### Tested on` OS table) - `## Risk & Scope` - `## Linked Issues` - the Chinese translation inside `<details>` — the template asks for the full body …

*wenshao*, 2026-08-28:

> ## Maintainer verification — built and ran from source, 4 arms I did not review this by reading it. I built four CLIs from source and drove the real binary: a real interactive TUI in tmux, and real `--input-format stream-json` sessions against a local mock model. Numbers below are from those runs; the harness is described at the bottom so you can re-run them. **Headline: the change this PR is about landed on `main` ~6 hours after your last push, as #10160. But the PR is not empty — 6 of its lines fix a real hang, and one half of that hang is a regression #10160 introduced.** ### Environment | | | |---|---| | host | Linux x86_64, Node `v22.22.2` | | build | per arm: `npm ci` → `npm run genera …

### [anthropics/claude-code issue #91188](https://github.com/anthropics/claude-code/issues/91188) — Feature request: make the auto-memory MEMORY.md compaction reminder threshold configurable

*Role here: our comment in their thread.*

*DanceNitra*, 2026-09-01:

> @niels-roest, your 17.1KB and the ~70% you read off it are both exact. The constants are literals, and there is a second half that changes what your knob would have to do. **Where the numbers come from.** The reminder builds one entry per dimension, each carrying a fraction of its own cap, and reports whichever is proportionally closest: ```js var ljo=0.8,HUn=0.7; function xut(e){ let n=[{frac:e.sizeBytes/e.byteCap,dimension:"bytes", capDesc:Ut(e.byteCap),targetDesc:Ut(Math.floor(e.byteCap*HUn))}]; if(e.lineCap!==void 0&&e.lineCount!==void 0) n.push({frac:e.lineCount/e.lineCap,dimension:"lines", capDesc:`${e.lineCap}-line`,targetDesc:`${Math.floor(e.lineCap*HUn)} lines`}); let{frac:r,...o}=n …

*DanceNitra*, 2026-09-03:

> @niels-roest, the reminder can be made to fire later. The branch that does it is one none of us had read, and finding it means retracting a sentence of my own. On 1 September I wrote that "raising the configured value raises the number you are told to aim for". That is wrong on the default path. The four fields at the call site go into one function, and that function is a selector: ```js function IHe({rawSizeBytes:e,surfaceCap:n,splicedSizeBytes:r,spliceCap:o,spliceActive:d}){ return n!==void 0 && (!d || e/n >= r/o) ? {sizeBytes:e,byteCap:n} : {sizeBytes:r,byteCap:o} } ``` `!d` short-circuits, so the two branches behave differently. With `spliceActive` true, the configured cap wins only whil …

### [gastownhall/beads issue #5877](https://github.com/gastownhall/beads/issues/5877) — Proposal: Memory Beads

*Role here: our comment in their thread.*

*The1nk*, 2026-09-22:

> @tonydzi — you found a real hole in our strongest number. The honest response is to go and measure it rather than defend it, so I did, and you were right in a way that is slightly worse than you could have seen from outside. ## Our override count was scoped to one surface, and we never said so `bd-notes-clobber-guard` is wired `PreToolUse` on **Bash only**, and it reads exactly one field — `tool_input.command`. That string is everything it knows about the world. So rather than reason about bypasses I fed them to it, with the real refusals as a positive control and the log redirected so the probe could not contaminate the number it was testing: ``` deny gc bd update bl-x --notes "wipes the th …

*The1nk*, 2026-09-21:

> @tonydzi Your one line — *a rule does not count as landed until you can name the thing that calls it* — is the control we converged on too. I can put a number on the failure it prevents, because we measured the always-loaded plane failing while the rule was sitting in it. It is @seanmartinsmith's third canonical rule, `--notes` replaces the whole field. The ban was written in three files here. Measured across one store on 2026-08-20, with `bd`'s own warning already firing: **309 note-writes, 33 of them destroyed another actor's note, and 23 of those 33 were a mayor's scoping or ruling wiped by the worker that then picked the bead up.** Single losses of 13.7 KB, 11.8 KB, 9.7 KB — the same aet …

### [QwenLM/qwen-code PR #12422](https://github.com/QwenLM/qwen-code/pull/12422) — fix(acp): report max_tokens instead of end_turn on unresolved output truncation

*Role here: our pull request.*

*qwen-code-ci-bot*, 2026-09-21:

> <!-- qwen-triage stage=1a --> @tonydzi Thanks for the fix. The underlying work looks substantive — a clear root-cause analysis, a standalone reproduction against real ACP stdio, and four tests with red/green evidence including a gap a reviewer caught afterwards. I'm stopping the review at the description gate, though: the PR body doesn't follow the repo's [pull request template](https://github.com/QwenLM/qwen-code/blob/main/.github/pull_request_template.md), and none of its required sections are present. This isn't a nitpick about heading names — a couple of the missing sections carry information a maintainer genuinely can't get from the current body: - `## What this PR does` / `## Why it's …

*qwen-code-ci-bot*, 2026-09-21:

> **[Critical]** R1-1: [certifies-falsely] [regression] This adds a second producer of `stopReason: 'max_tokens'`, but every internal consumer of that literal was written against the only producer that existed before this diff — `Session.ts:8691`, `return { responseStream: null, stopReason: 'max_tokens' };`, reached solely when `lastPromptTokenCount > sessionTokenLimit`, i.e. the send was dropped and nothing was delivered. A turn that streamed a usable answer and merely hit the provider's output cap now takes branches reserved for "the session token budget was exhausted before the request went out", and no consumer is updated. The run-confirmed harm is on the Goal path. `#settleGoalTurn` maps …

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

### [Jason-Vaughan/TangleClaw issue #1400](https://github.com/Jason-Vaughan/TangleClaw/issues/1400) — [bug] Primary-checkout guard hook fails silently due to || true

*Role here: our comment in their thread.*

*Jason-Vaughan*, 2026-09-23:

> Thanks @tonydzi — this was genuinely useful, and it prompted me to audit that path more closely. I am removing the outer `|| true`, but with one important distinction: the primary-checkout guard is a safety interlock rather than a security boundary, so an internal guard failure still has to remain non-blocking. A deliberate refusal and a guard crash are separate outcomes; I don't want a bug in the interlock itself to strand the Claude Code session it is protecting. The false positive case you described turns out not to apply to TangleClaw's implementation. File and notebook operations don't infer targets from command text. They arrive as structured paths, are resolved to absolute/symlink-res …

*Jason-Vaughan*, 2026-10-01:

> @tonydzi This is exactly the implementation scar tissue that keeps a good acceptance criterion from becoming a decorative one. All three points are accepted. I tightened the issue body so the requirements now say explicitly: - liveness is measured against an independently produced activity signal that the guarded hook cannot influence, not wall-clock age; - an idle install stays quiet only when both expected activity and heartbeat movement stay quiet; - permanent silence exemptions are prohibited, and any unavoidable exclusion needs a bounded reason plus an expiry that becomes actionable; - `--self-test` must traverse the real installed hook entrypoint and prove the outer heartbeat advanced, …

### [Lyellr88/marm-memory PR #192](https://github.com/Lyellr88/marm-memory/pull/192) — test(docker): exposed mode authenticates, and MARM's managed Docker path never reaches the keyless fallback (#170 item 5)

*Role here: our pull request.*

*Lyellr88*, 2026-09-17:

> @tonydzi Thank you for the continued work on this. The revised tests clearly separate the managed keyless-start security contract from persistence, cover the exposed-network path without relying on host behavior that is not portable, and protect the probes from ambient proxy interference. Everything is green and the review is complete. Merging this now. Please keep an eye on the open issues if another area interests you.

*Lyellr88*, 2026-09-16:

> I apologize for the delay; I've been working on a new build plus the power outage I dealt with pulled my focus in multiple directions. Thanks for the focused Docker coverage and for including both CI and mutation-test evidence. I verified the tests run in the Docker CI job and agree that the intended auth cases are worth covering. 1. `marm-mcp-server/tests/test_docker_transports.py:659-711`: the no-key test currently requires a persisted `/home/marm/.marm/.env` key via `docker exec`, but the security property under review is that the loopback fallback is unreachable. `marm_mcp_server/config/api_key_bootstrap.py:53-86` can retain a generated key in memory while declining persistence if secure …

### [anthropics/anthropic-sdk-python PR #1820](https://github.com/anthropics/anthropic-sdk-python/pull/1820) — Fix streaming accumulator crash when message_start omits usage

*Role here: our comment in their thread.*

*PiedPiper911*, 2026-08-27:

> @tonydzi — thank you, again, for the re-measurement. All three findings were correct, and I have acted on all of them. Pushed as commit : **1. None coercion (the real fix).** Both accumulators ( + ) now coerce a missing to before /. Your reproduction was exactly right: bypasses validation, so on #1806's reported shape the field lands as on a required — an AttributeError traded for a TypeError one frame further from the cause. **2. Fixture restored to the reported shape.** now ends with — no , matching the actual repro in #1806. **3. Discriminating assertion + non-strict client.** The tests now assert (which fails on the old implementation) and build a non-strict locally — you were right that …

*PiedPiper911*, 2026-08-24:

> Thanks for the drive-by review, tonydzi — appreciate the triage and the honest read on both PRs. I've since synced this branch with the latest `main` (merge commit 1316de75 + a line-ending cleanup), so the diff is now just the actual fix: 4 files instead of the 60-file noise from the stale base. The fix itself is unchanged — when `message_start` omits `usage`, the accumulator constructs it from the first `message_delta` instead of crashing (#1806), with sync + async regression tests (new `missing_usage_response.txt` fixture). On the overlap with #1815: you're right that @chenlichao opened it ~13h earlier, and your point about the ideal merge (this fix + a solid test setup) is fair. Both PRs …

## Full index

Every position we opened, newest first. Full bodies and every reply are in [`evidence-index.json`](evidence-index.json).

| Repository | # | Kind | State | Title |
|---|---|---|---|---|
| QwenLM/qwen-code | [#13312](https://github.com/QwenLM/qwen-code/pull/13312) | PR | open | fix(mcp): name the capped server timeout in App read timeout warnings |
| screenpipe/screenpipe | [#7401](https://github.com/screenpipe/screenpipe/issues/7401) | issue | open | Windows: communications-output loopback (USB speakerphone) dies 200ms after start with 'disconnected', while /health keeps reporting the device active — call far-end silently lost |
| pydantic/pydantic-ai | [#9444](https://github.com/pydantic/pydantic-ai/issues/9444) | issue | closed | A provider response with no usage object is recorded as zero tokens, not as unknown |
| tenequm/pond | [#321](https://github.com/tenequm/pond/pull/321) | PR | merged | fix(schedule): report a systemd timer with no next elapse as broken |
| basicmachines-co/basic-memory | [#1617](https://github.com/basicmachines-co/basic-memory/pull/1617) | PR | closed | fix(mcp): report the real checksum from write_note and edit_note (#1586) |
| ChromeDevTools/chrome-devtools-mcp | [#2852](https://github.com/ChromeDevTools/chrome-devtools-mcp/pull/2852) | PR | open | docs: correct CLI availability of extension tools |
| headroomlabs-ai/headroom | [#3832](https://github.com/headroomlabs-ai/headroom/pull/3832) | PR | merged | docs: mark HeadroomClient provider as required, not auto-detected |
| QwenLM/qwen-code | [#12875](https://github.com/QwenLM/qwen-code/pull/12875) | PR | open | fix(core): add opt-in failMode: "closed" for PreToolUse command hooks |
| bytedance/deer-flow | [#5843](https://github.com/bytedance/deer-flow/pull/5843) | PR | merged | fix(docs): harness docs document an async client API that does not exist |
| deepset-ai/haystack | [#12889](https://github.com/deepset-ai/haystack/pull/12889) | PR | closed | fix: merge generation_kwargs tools with the component's own tools in OpenAIChatGenerator |
| anthropics/claude-code | [#95920](https://github.com/anthropics/claude-code/issues/95920) | issue | open | Scheduled tasks: nextFire returns a fabricated "now + 365 days" when no match falls inside its 366-day scan window |
| langroid/langroid | [#1148](https://github.com/langroid/langroid/pull/1148) | PR | merged | docs: fix dead github-cli link in CONTRIBUTING |
| browser-use/browser-use | [#5867](https://github.com/browser-use/browser-use/pull/5867) | PR | open | docs(actor): fix drag_to parameter name in Element API reference |
| teng-lin/notebooklm-py | [#2432](https://github.com/teng-lin/notebooklm-py/issues/2432) | issue | closed | wait_for_completion returns REMOVED for generations that completed — absence of task_id from the studio list is inferred, never verified (0.8.2) |
| QwenLM/qwen-code | [#12422](https://github.com/QwenLM/qwen-code/pull/12422) | PR | open | fix(acp): report max_tokens instead of end_turn on unresolved output truncation |
| LambdaLabsML/the_lab.api | [#7](https://github.com/LambdaLabsML/the_lab.api/issues/7) | issue | open | optimization/test_project: baseline fails its own accuracy gate on 3 of 7 kernels |
| LambdaLabsML/the_lab.api | [#6](https://github.com/LambdaLabsML/the_lab.api/pull/6) | PR | open | fix(dashboard): install node dependencies before building |
| LambdaLabsML/the_lab.api | [#5](https://github.com/LambdaLabsML/the_lab.api/pull/5) | PR | open | fix(mcp): resolve the API port from runtime.json instead of assuming 8000 |
| BerriAI/litellm | [#42172](https://github.com/BerriAI/litellm/issues/42172) | issue | open | [Bug]: anthropic/<model> with a third-party api_base receives the client's Claude subscription OAuth token instead of the deployment's configured api_key (with forward_llm_provider_auth_headers either on or off) |
| pydantic/pydantic-ai | [#8551](https://github.com/pydantic/pydantic-ai/issues/8551) | issue | closed | An uninstrumented delegate's usage is credited to the caller's agent run span |
| chigwell/telegram-mcp | [#227](https://github.com/chigwell/telegram-mcp/pull/227) | PR | merged | feat: make per-tool extension allowlists configurable via TELEGRAM_FILE_EXTENSIONS (closes #226) |
| mem0ai/mem0 | [#7361](https://github.com/mem0ai/mem0/pull/7361) | PR | open | docs(llms): Sarvam sampling params go inside the model dict |
| pydantic/pydantic-ai | [#8451](https://github.com/pydantic/pydantic-ai/issues/8451) | issue | closed | Concurrent delegate runs still over-report usage on their agent-run spans after #8417 |
| basicmachines-co/basic-memory | [#1578](https://github.com/basicmachines-co/basic-memory/issues/1578) | issue | open | Harden HTTP/SSE transport: `basic-memory mcp` defaults to 0.0.0.0 with no auth (contradicts SECURITY.md) |
| oraios/serena | [#2048](https://github.com/oraios/serena/pull/2048) | PR | closed | docs(clients): fix CC system prompt override command (prompts print-cc-system-prompt-override) |
| DeusData/codebase-memory-mcp | [#2225](https://github.com/DeusData/codebase-memory-mcp/pull/2225) | PR | merged | docs: MCP tool count is 17; document get_file_outline, compare_graphs, check_index_coverage |
| LambdaLabsML/the_lab.api | [#4](https://github.com/LambdaLabsML/the_lab.api/pull/4) | PR | open | fix(mcp): keep the bridge importable under the system python3 (3.9) |
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
| google/adk-go | [#1543](https://github.com/google/adk-go/pull/1543) | PR | open | feat(model/openaimodel): support image/file input via genai InlineData/FileData parts |
| osaurus-ai/osaurus | [#2669](https://github.com/osaurus-ai/osaurus/pull/2669) | PR | open | docs: fix six relative links that resolve to files that do not exist |
| areal-project/AReaL | [#1685](https://github.com/areal-project/AReaL/pull/1685) | PR | merged | docs: repoint doc links left behind by the bilingual docs split |
| zilliztech/memsearch | [#725](https://github.com/zilliztech/memsearch/pull/725) | PR | closed | feat(plugins): make the daily memory filename collision-safe on synced directories |
| llvm/llvm-project | [#221677](https://github.com/llvm/llvm-project/pull/221677) | PR | open | [Github] Make code-format-helper --extensions ordering deterministic |
| vansh7nvc/Abstractify | [#69](https://github.com/vansh7nvc/Abstractify/pull/69) | PR | merged | feat(export): add RIS citation exporter for Zotero and Mendeley (#10) |
| mixelpixx/Konnect | [#442](https://github.com/mixelpixx/Konnect/pull/442) | PR | merged | fix(platform): record each server and sweep dead records at startup |
| mixelpixx/Konnect | [#439](https://github.com/mixelpixx/Konnect/pull/439) | PR | closed | fix(drc): name what owns each DRC report item (#413) |
| mongodb-js/mongodb-mcp-server | [#1491](https://github.com/mongodb-js/mongodb-mcp-server/pull/1491) | PR | closed | docs: fix Azure deploy paths after the v3 multi-package move |
| darrenhinde/OpenAgentsControl | [#356](https://github.com/darrenhinde/OpenAgentsControl/pull/356) | PR | open | docs: point plugin setup links at the sections that replaced the removed guides |
| microsoft/semantic-kernel | [#14371](https://github.com/microsoft/semantic-kernel/pull/14371) | PR | open | Python: pin the validated address for OpenAPI plugin requests |
| Lyellr88/marm-memory | [#192](https://github.com/Lyellr88/marm-memory/pull/192) | PR | merged | test(docker): exposed mode authenticates, and MARM's managed Docker path never reaches the keyless fallback (#170 item 5) |
| ip2a/mcpstore | [#56](https://github.com/ip2a/mcpstore/issues/56) | issue | open | npm CLI install is broken: README names an unpublished package, and @ip2a/mcpstore ships no bin |
| bobmatnyc/claude-mpm | [#961](https://github.com/bobmatnyc/claude-mpm/pull/961) | PR | open | docs: trusty-memory and trusty-search are cargo crates, not uv tools |
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
| aristoapp/awesome-second-brain | [#54](https://github.com/aristoapp/awesome-second-brain/pull/54) | PR | open | watchlist: add CharmOS (humans + agents in one relationship record on a local vault) |
| Yigtwxx/awesome-claude-multi-agent | [#3](https://github.com/Yigtwxx/awesome-claude-multi-agent/pull/3) | PR | open | Memory, State, and Communication: add claw-consensus (cross-machine consensus + dual-rail bus) |
| mex-memory/mex | [#148](https://github.com/mex-memory/mex/pull/148) | PR | open | fix(cli): apply the documented `mex timeline --type` filter |
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
| qualixar/superlocalmemory | [#126](https://github.com/qualixar/superlocalmemory/pull/126) | PR | open | docs: npx route for the mcp-remote bridge, with the config that matches it |
| Joe-B-Security/awesome-prompt-injection | [#86](https://github.com/Joe-B-Security/awesome-prompt-injection/pull/86) | PR | closed | Add agent-leash (plan-vs-authorize containment) to Tools |
| OWASP/www-project-mcp-top-10 | [#55](https://github.com/OWASP/www-project-mcp-top-10/pull/55) | PR | open | MCP03: add plan-vs-authorize containment control + attack/defense reference |
| zilliztech/memsearch | [#695](https://github.com/zilliztech/memsearch/pull/695) | PR | merged | perf(hooks): refresh the PyPI check off the session-start blocking path (#676) |
| deepseek-ai/DeepEP | [#733](https://github.com/deepseek-ai/DeepEP/issues/733) | issue | open | get_env<int> returns an uninitialized value when an env var is set to a non-numeric string (EP_BUFFER_DEBUG=false reads as true) |
| Hello-QM/catgo-LRG | [#573](https://github.com/Hello-QM/catgo-LRG/pull/573) | PR | open | docs: Claude CLI install command names a package that is not on npm |
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
| GetBindu/awesome-claude-code-and-skills | [#147](https://github.com/GetBindu/awesome-claude-code-and-skills/pull/147) | PR | open | Add claude-memory-tidy to Memory & Context Management |
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
| chigwell/telegram-mcp | [#181](https://github.com/chigwell/telegram-mcp/pull/181) | PR | open | docs: document the MCP_TRANSPORT=sse shared server (fixes the 'one instance per agent' surprise in #50) |
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
| karpathy/nanochat | [#814](https://github.com/karpathy/nanochat/pull/814) | PR | open | read-arxiv-paper skill: handle the URL and archive shapes arxiv actually serves |
| topoteretes/awesome-ai-memory | [#68](https://github.com/topoteretes/awesome-ai-memory/pull/68) | PR | open | Add SQLite Graph Memory to Memory tools |
| InftyAI/Awesome-LLMOps | [#503](https://github.com/InftyAI/Awesome-LLMOps/pull/503) | PR | merged | Add Verbatim Citation Gate to RAG |
| benchflow-ai/awesome-evals | [#63](https://github.com/benchflow-ai/awesome-evals/pull/63) | PR | closed | 5c: add Verbatim Citation Gate (RAG / retrieval evaluation) |
| currentslab/awesome-vector-search | [#63](https://github.com/currentslab/awesome-vector-search/pull/63) | PR | open | Add SQLite Graph Memory to Library |
| agentrust-io/awesome-ai-governance | [#49](https://github.com/agentrust-io/awesome-ai-governance/pull/49) | PR | closed | Add LEASH-8 to Industry Reports & Guidance |
| nibzard/awesome-agentic-patterns | [#124](https://github.com/nibzard/awesome-agentic-patterns/issues/124) | issue | closed | Pattern Reviewer fails on all fork PRs: action checks the PR author's write permission |
| ucsb-mlsec/Awesome-Agent-Security | [#14](https://github.com/ucsb-mlsec/Awesome-Agent-Security/pull/14) | PR | open | Blue-teaming: add LEASH-8 under Agent privilege management |
| Danielskry/Awesome-RAG | [#136](https://github.com/Danielskry/Awesome-RAG/pull/136) | PR | open | Add SQLite Graph Memory to Advanced Approaches |
| Yigtwxx/awesome-rag-production | [#73](https://github.com/Yigtwxx/awesome-rag-production/pull/73) | PR | merged | Add Verbatim Citation Gate to Evaluation & Benchmarking |
| IAAR-Shanghai/Awesome-AI-Memory | [#133](https://github.com/IAAR-Shanghai/Awesome-AI-Memory/pull/133) | PR | merged | Add SQLite Graph Memory to Systems and Open Sources |
| Jenqyang/Awesome-AI-Agents | [#406](https://github.com/Jenqyang/Awesome-AI-Agents/pull/406) | PR | merged | Add claude-consensus (multi-machine agent consensus) |
| nibzard/awesome-agentic-patterns | [#122](https://github.com/nibzard/awesome-agentic-patterns/pull/122) | PR | merged | Add: dual-rail-message-delivery |
| microsoft/semantic-kernel | [#14199](https://github.com/microsoft/semantic-kernel/pull/14199) | PR | closed | Python: Add experimental FunctionAuthorizationFilter for auto function invocation (runtime authorization, argument-bound approvals) |
| anthropics/claude-cookbooks | [#799](https://github.com/anthropics/claude-cookbooks/pull/799) | PR | open | fix: convert remaining broken sre_bot_slack.py links in SRE cookbook |
| anthropics/skills | [#1479](https://github.com/anthropics/skills/pull/1479) | PR | open | Add plan-file-hygiene skill (addresses #1417) |
| google-gemini/cookbook | [#1296](https://github.com/google-gemini/cookbook/pull/1296) | PR | merged | Add example: check citation faithfulness in RAG |
| openai/openai-cookbook | [#2880](https://github.com/openai/openai-cookbook/pull/2880) | PR | open | Add cookbook: check citation faithfulness in RAG with a zero-token gate |
| mistralai/cookbook | [#376](https://github.com/mistralai/cookbook/pull/376) | PR | open | Add citation faithfulness check notebook (RAG) |
| cohere-ai/cohere-developer-experience | [#783](https://github.com/cohere-ai/cohere-developer-experience/pull/783) | PR | open | Add Citation Faithfulness Check notebook (RAG cookbook) |
| QwenLM/Qwen-Agent | [#928](https://github.com/QwenLM/Qwen-Agent/pull/928) | PR | open | feat(examples): deterministic guard against fabricated tool results (#737) |
| deepset-ai/haystack | [#12142](https://github.com/deepset-ai/haystack/pull/12142) | PR | closed | feat: add CitationConsistencyChecker — deterministic, zero-token RAG citation validator |
| huggingface/cookbook | [#366](https://github.com/huggingface/cookbook/pull/366) | PR | open | Add self-verifying search agent recipe |
| google/adk-python-community | [#173](https://github.com/google/adk-python-community/pull/173) | PR | closed | feat: add AuthorityRoutingPlugin for ADVISE/EXECUTE/DEFER/STOP tool authority |
| google/adk-python-community | [#172](https://github.com/google/adk-python-community/pull/172) | PR | open | feat(plugins): add AuthorityRoutingPlugin (ADVISE/EXECUTE/DEFER/STOP) |
| google/adk-python-community | [#171](https://github.com/google/adk-python-community/issues/171) | issue | open | feat(plugins): add AuthorityRoutingPlugin — pre-execution authority posture (ADVISE/EXECUTE/DEFER/STOP) |
| xai-org/xai-cookbook | [#45](https://github.com/xai-org/xai-cookbook/pull/45) | PR | open | [Content] Deterministic Guardrails for Grok Tool Calls |
| QwenLM/Qwen-Agent | [#927](https://github.com/QwenLM/Qwen-Agent/pull/927) | PR | closed | feat(examples): RAG with verifiable citations for the Assistant |
| anthropics/skills | [#1460](https://github.com/anthropics/skills/pull/1460) | PR | closed | Add reasoning-quality-gate skill |
| anthropics/claude-cookbooks | [#789](https://github.com/anthropics/claude-cookbooks/pull/789) | PR | open | feat(evals): citation-faithfulness evals — catching hallucinated support |
| anthropics/claude-agent-sdk-demos | [#70](https://github.com/anthropics/claude-agent-sdk-demos/pull/70) | PR | closed | Add verified-ops-agent: Python demo of propose → adversarially verify → gated apply |
| anthropics/claude-cookbooks | [#788](https://github.com/anthropics/claude-cookbooks/pull/788) | PR | closed | Add pipeline vs barrier sub-agent composition cookbook (addresses #721) |
| anthropics/claude-cookbooks | [#787](https://github.com/anthropics/claude-cookbooks/pull/787) | PR | open | feat(agents): add authority routing pattern (ADVISE / EXECUTE / DEFER / STOP) |
| anthropics/claude-cookbooks | [#784](https://github.com/anthropics/claude-cookbooks/pull/784) | PR | closed | feat(agents): add multi-agent consensus & verification pattern |
| anthropics/claude-cookbooks | [#778](https://github.com/anthropics/claude-cookbooks/pull/778) | PR | closed | feat(patterns/agents): coordinating agents that don't share memory (message-bus consensus + liveness) |
| anthropics/claude-code | [#74055](https://github.com/anthropics/claude-code/issues/74055) | issue | closed | [BUG] Scheduler catch-up storm on restart: re-fires daily tasks and runs enabled:false tasks (ghost fires, lastRunAt not updated) |

## Participation in other people's threads

| Repository | # | Title |
|---|---|---|
| QwenLM/qwen-code | [#13315](https://github.com/QwenLM/qwen-code/pull/13315) | fix(memory): preserve complete index entries in prompts |
| BerriAI/litellm | [#43992](https://github.com/BerriAI/litellm/issues/43992) | [Feature]: OTEL v2 integration should export cache token counts as span attributes |
| anthropics/claude-agent-sdk-python | [#1342](https://github.com/anthropics/claude-agent-sdk-python/pull/1342) | fix: don't write to the closed transport when a hook finishes after close() (#1340) |
| run-llama/llama_index | [#23313](https://github.com/run-llama/llama_index/issues/23313) | bug: TokenCounter ignores dictionary tool_calls in additional_kwargs and lacks null guards |
| Digital-Process-Tools/claude-oss | [#1796](https://github.com/Digital-Process-Tools/claude-oss/issues/1796) | select_issues.py and inbound_triage.py disagree on FIRST_TIME_CONTRIBUTOR/FIRST_TIMER classification |
| mistralai/mistral-vibe | [#1159](https://github.com/mistralai/mistral-vibe/issues/1159) | bug: Unified Harness: hooks and agent profiles do not apply to subagents |
| anthropics/claude-agent-sdk-python | [#1333](https://github.com/anthropics/claude-agent-sdk-python/pull/1333) | fix: normalize ResultMessage.errors through the existing helper |
| BerriAI/litellm | [#43501](https://github.com/BerriAI/litellm/pull/43501) | fix(streaming): reject incomplete generic chunks |
| BerriAI/litellm | [#43499](https://github.com/BerriAI/litellm/pull/43499) | fix(streaming): reject partial generic chunks missing required fields |
| BerriAI/litellm | [#43487](https://github.com/BerriAI/litellm/issues/43487) | [Bug]: A partial generic streaming chunk is accepted and then raises KeyError |
| cognicore-dev/cognicore-env | [#136](https://github.com/cognicore-dev/cognicore-env/pull/136) | test(mem0-bridge): verifier-defeat vector — reachability firing test + tripwire |
| cognicore-dev/cognicore-env | [#135](https://github.com/cognicore-dev/cognicore-env/pull/135) | feat(integrations): mem0 verified-memory bridge — signed transfer bundles, structural quarantine, fail-closed import |
| anthropics/claude-agent-sdk-python | [#1320](https://github.com/anthropics/claude-agent-sdk-python/issues/1320) | Session store writes and reads derive project_key differently, so a git-worktree session lists and resumes as empty |
| openai/codex | [#48572](https://github.com/openai/codex/issues/48572) | /compact silently drops trailing instructions intended for after compaction |
| oraios/serena | [#2107](https://github.com/oraios/serena/pull/2107) | Reject an inverted line range instead of duplicating the text |
| anthropics/claude-agent-sdk-python | [#1316](https://github.com/anthropics/claude-agent-sdk-python/pull/1316) | fix(query): release a cancelled control request's pending entry |
| rysweet/amplihack-rs | [#1498](https://github.com/rysweet/amplihack-rs/issues/1498) | quality-loop requests --json fields gh rejects (authorAssociation, baseRepositoryOwner) |
| Hmbown/Codewhale | [#6573](https://github.com/Hmbown/Codewhale/issues/6573) | Bug: Multiple TUI Sessions Contend on Subagents Store → CPU Spin-loop |
| pydantic/pydantic-ai | [#8704](https://github.com/pydantic/pydantic-ai/issues/8704) | Provider responses with no usage object are recorded as zero tokens, not unknown |
| infagent/merl | [#102](https://github.com/infagent/merl/issues/102) | Gate: prove two heterogeneous agents coordinate through accepted state |
| JeltzProstetnic/agent-fleet | [#12](https://github.com/JeltzProstetnic/agent-fleet/issues/12) | SessionStart additionalContext payload silently fails to reach the model (6 occurrences); hook verified healthy, delivery fails |
| beatzball/roost | [#100](https://github.com/beatzball/roost/issues/100) | Shared notes and an advisory lock for a fleet, as plain files |
| mastra-ai/mastra | [#24611](https://github.com/mastra-ai/mastra/issues/24611) | Scheduler: year-pinned (7-part) cron is accepted but never fires |
| anthropics/claude-code | [#95833](https://github.com/anthropics/claude-code/issues/95833) | [BUG] PreToolUse hooks (Bash/PowerShell matchers) never fire in Claude Desktop app "Code" tab, even after full re-login |
| BerriAI/litellm | [#42210](https://github.com/BerriAI/litellm/pull/42210) | fix(anthropic): scope OAuth token forwarding to official Anthropic API hosts (#42172) |
| code-yeongyu/oh-my-openagent | [#8579](https://github.com/code-yeongyu/oh-my-openagent/issues/8579) | spawn admission reply lost -> parent reports start_failed while host creates the session -> duplicate child on retry |
| pydantic/pydantic-ai | [#8565](https://github.com/pydantic/pydantic-ai/pull/8565) | Reject output tools in list-form `tool_choice` |
| summationai/agent-exchange | [#15](https://github.com/summationai/agent-exchange/issues/15) | Let agents launch named peers in new terminal panes |
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
| anthropics/claude-code | [#95313](https://github.com/anthropics/claude-code/issues/95313) | [FEATURE] Request: Require user confirmation before spawning expensive agents |
| anthropics/claude-agent-sdk-python | [#1271](https://github.com/anthropics/claude-agent-sdk-python/pull/1271) | Expose user-message attribution and queue metadata |
| kirodotdev/KiroCrew | [#11562](https://github.com/kirodotdev/KiroCrew/issues/11562) | New sessions start on the last picker-selected model, not the configured default model |
| wowok-ai/skills | [#3](https://github.com/wowok-ai/skills/issues/3) | Global install left one client with no skills and no MCP registration, and leaves no record of what was written where |
| anthropics/claude-code | [#94918](https://github.com/anthropics/claude-code/issues/94918) | [FEATURE] Add API/webhook (event) trigger for Claude Cowork tasks — not just schedule cadence |
| BerriAI/litellm | [#41395](https://github.com/BerriAI/litellm/issues/41395) | [Bug]: context-management summary subrequests bypass a project's ITPM/OTPM quotas (v3 rate limiter) |
| pydantic/pydantic-ai | [#8376](https://github.com/pydantic/pydantic-ai/issues/8376) | A list[str] tool_choice is validated against output tools, silently widening the choice |
| pydantic/pydantic-ai | [#8368](https://github.com/pydantic/pydantic-ai/issues/8368) | Carrying `usage=` across runs makes the agent-run span report the conversation total |
| anthropics/claude-code | [#94575](https://github.com/anthropics/claude-code/issues/94575) | Background-agent view shows the parent's advisor model (Fable) instead of the subagent's requested model |
| anthropics/claude-code | [#94563](https://github.com/anthropics/claude-code/issues/94563) | Scheduled task sessions hang indefinitely (isRunning stuck true, zero progress, no error) - two confirmed triggers fixed, hang persists |
| anthropics/claude-code | [#94527](https://github.com/anthropics/claude-code/issues/94527) | [BUG] Most custom groups are no longer visible in the sidebar |
| UKGovernmentBEIS/inspect_ai | [#5413](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5413) | Tag empty completions with reason=no_response across the text scorers |
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
| agno-agi/agno | [#10139](https://github.com/agno-agi/agno/issues/10139) | [Bug] Curator.prune() and Curator.deduplicate() silently return 0 for every store |
| Jason-Vaughan/TangleClaw | [#1400](https://github.com/Jason-Vaughan/TangleClaw/issues/1400) | [bug] Primary-checkout guard hook fails silently due to \|\| true |
| anthropics/claude-code | [#93654](https://github.com/anthropics/claude-code/issues/93654) | [Bug] Inverted logic in absence-of-evidence search caused JSON config fields to be marked CLI-only |
| anthropics/claude-code | [#93646](https://github.com/anthropics/claude-code/issues/93646) | [BUG] Model shorthand `--model sonnet` resolves to Sonnet 4.5 instead of Sonnet 5; inconsistent with /model picker |
| anthropics/anthropic-sdk-python | [#1927](https://github.com/anthropics/anthropic-sdk-python/pull/1927) | fix(vertex): serialize the body static-fields-first so prompt caching survives routing |
| tenequm/pond | [#239](https://github.com/tenequm/pond/issues/239) | schedule: the generated systemd user timer stops re-arming, and pond status still reports it healthy |
| dimoschi/touchstone | [#47](https://github.com/dimoschi/touchstone/issues/47) | Make the quality skill portable across Codex and Claude Code |
| anthropics/claude-code | [#93481](https://github.com/anthropics/claude-code/issues/93481) | [Bug] Sessions start with 9% token usage already consumed |
| caura-ai/caura | [#1467](https://github.com/caura-ai/caura/pull/1467) | fix(client-typescript): recall() silently drops caller extras that write() and search() forward |
| nimbalyst/nimbalyst | [#1489](https://github.com/nimbalyst/nimbalyst/issues/1489) | Claude Agent sessions never see MCP servers (or hooks) shipped inside installed Claude Code plugins |
| anthropics/claude-code | [#93324](https://github.com/anthropics/claude-code/issues/93324) | [Bug] Terminal UI displays incorrect model name when subagents launch or switch models |
| browser-use/browser-use | [#5768](https://github.com/browser-use/browser-use/pull/5768) | fix(agent): preserve token usage in AgentHistoryList save/load round-trip |
| browser-use/browser-use | [#5767](https://github.com/browser-use/browser-use/issues/5767) | AgentHistoryList.save_to_file/load_from_file silently drops token usage |
| anthropics/claude-code | [#93260](https://github.com/anthropics/claude-code/issues/93260) | Projects: concurrent sessions silently clobber each other's project_write — three losses on one doc in ninety minutes |
| anthropics/claude-code | [#93231](https://github.com/anthropics/claude-code/issues/93231) | Session exit on VS Code window close never releases its git worktree lock; `locked` keeps naming the dead PID and no later session reaps it |
| agno-agi/agno | [#10088](https://github.com/agno-agi/agno/pull/10088) | fix: exclude the run being continued from its own history in background+stream continues |
| agno-agi/agno | [#10086](https://github.com/agno-agi/agno/issues/10086) | [Bug] Background+streaming continue of a paused `external_execution` tool duplicates the run into its own history, causing unpaired `tool_calls` |
| anthropics/claude-code | [#93143](https://github.com/anthropics/claude-code/issues/93143) | [BUG] Streamable HTTP MCP tool call still times out ("The operation timed out") at ~6min despite per-server timeout, CLAUDE_CODE_MCP_TOOL_IDLE_TIMEOUT=0, and a requestTimeout=0 server |
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
| anthropics/claude-code | [#91767](https://github.com/anthropics/claude-code/issues/91767) | [FEATURE] Add model, stop_reason, token usage and tool timing to hook payloads |
| anthropics/claude-code | [#91735](https://github.com/anthropics/claude-code/issues/91735) | Non-ASCII project paths collide in ~/.claude/projects/, silently sharing memory and transcripts between different projects |
| anthropics/claude-agent-sdk-python | [#1246](https://github.com/anthropics/claude-agent-sdk-python/pull/1246) | Fix raw asyncio cancellation leaking CLI subprocesses |
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
| omegaup/omegaup | [#10136](https://github.com/omegaup/omegaup/issues/10136) | bug: SystemExit(0) in with-body recorded as failure |
| anthropics/claude-code | [#90215](https://github.com/anthropics/claude-code/issues/90215) | [BUG] Scheduled task cron dispatch silently fails to fire — no lastRunAt, no execution, no error |
| UKGovernmentBEIS/inspect_ai | [#5090](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5090) | fix(solver): support tuples and sequences of solvers in chain and unroll |
| BerriAI/litellm | [#38535](https://github.com/BerriAI/litellm/issues/38535) | Router policy knob `treat_finish_reason_as_failure`: let a terminal stop_reason count as a deployment failure so allowed_fails, cooldown, and fallbacks engage |
| anthropics/claude-code | [#90135](https://github.com/anthropics/claude-code/issues/90135) | [BUG] Marketplace plugin re-materialization mid-session silently kills pinned hooks in every running session — and the failure is undetectable from inside the plugin |
| anthropics/claude-code | [#90080](https://github.com/anthropics/claude-code/issues/90080) | Feature request: register Remote Control for all sessions at once - registrations don't survive app restart |
| anthropics/claude-code | [#90077](https://github.com/anthropics/claude-code/issues/90077) | [BUG] Hooks with `shell: "powershell"` spawn `pwsh` with no `powershell.exe` fallback, so hooks silently never run on a stock Windows box |
| Lyellr88/marm-memory | [#170](https://github.com/Lyellr88/marm-memory/issues/170) | testing: expand Docker coverage, only 8 of 43 Docker tests run a container and none run in PR CI |
| macanderson/stella | [#5287](https://github.com/macanderson/stella/issues/5287) | Parallel agent sessions can share one checkout, and a branch switch silently reverts another session's uncommitted work |
| anthropics/claude-code | [#90017](https://github.com/anthropics/claude-code/issues/90017) | [Bug] Model ignores root-cause analysis guardrails and optimizes wrong assumption despite explicit mitigations |
| google-gemini/gemini-cli | [#29101](https://github.com/google-gemini/gemini-cli/issues/29101) | Authentication failure blocking Enterprise Workspace accounts |
| screenpipe/screenpipe | [#6698](https://github.com/screenpipe/screenpipe/issues/6698) | [feature] private infinite memory with on-demand AI access |
| anthropics/claude-agent-sdk-python | [#1237](https://github.com/anthropics/claude-agent-sdk-python/pull/1237) | fix(sessions): surface subagent import I/O failures |
| anthropics/claude-code | [#89783](https://github.com/anthropics/claude-code/issues/89783) | [FEATURE] Programmatically spawn multiple named child sessions that auto-start (no manual chip click) for routine fan-out |
| xCirno1/applyer | [#29](https://github.com/xCirno1/applyer/issues/29) | Search company ATS boards (Greenhouse/Lever/Ashby) as a job source |
| truera/trulens | [#2730](https://github.com/truera/trulens/pull/2730) | fix(database): SQL-level aggregation in pre-OTel leaderboard |
| screenpipe/screenpipe | [#6661](https://github.com/screenpipe/screenpipe/issues/6661) | [question] Free plan storage block - is this intended? |
| get-bb/bb | [#2433](https://github.com/get-bb/bb/issues/2433) | No per-host capacity model: bb over-schedules one machine until its daemon dies, and drops the spawn prompt on retry |
| anthropics/claude-code | [#89639](https://github.com/anthropics/claude-code/issues/89639) | macOS: scheduled-task sessions wedge mid tool-call (~30s in, WebSearch/WebFetch), stay "running" for days, and pin global concurrency slots until the whole schedule starves |
| anthropics/claude-code | [#89632](https://github.com/anthropics/claude-code/issues/89632) | Local scheduled tasks run under interactive ask-every-tool permissions, despite being framed as unattended |
| zilliztech/memsearch | [#703](https://github.com/zilliztech/memsearch/issues/703) | Windows is blocked by an obsolete platform guard — milvus-lite has shipped pure-Python wheels since 3.0 |
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
| anthropics/claude-agent-sdk-python | [#1234](https://github.com/anthropics/claude-agent-sdk-python/issues/1234) | Bug: claude-agent-sdk 0.2.144 is a partial publish |
| langfuse/langfuse | [#16494](https://github.com/langfuse/langfuse/issues/16494) | bug(automations): Execution logs get stuck on PENDING when jobs fail. |
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
| gastownhall/beads | [#5877](https://github.com/gastownhall/beads/issues/5877) | Proposal: Memory Beads |
| anthropics/claude-code | [#88138](https://github.com/anthropics/claude-code/issues/88138) | [BUG] Claude Desktop (Windows MSIX) transitions from Ok to Modified, NeedsRemediation on first launch, with no deployment event in any Windows log |
| anthropics/claude-code | [#88118](https://github.com/anthropics/claude-code/issues/88118) | Read dedup does not account for PostToolUse updatedToolOutput: repeated Reads bypass substituting hooks, and readFileState records disk content the model never received |
| traceloop/openllmetry | [#4431](https://github.com/traceloop/openllmetry/issues/4431) | 🐛 Bug Report: NotGiven sentinel leak in Anthropic instrumentation |
| anthropics/claude-code | [#88058](https://github.com/anthropics/claude-code/issues/88058) | Feature request: per-skill display description separate from the routing description (SKILL.md) |
| UKGovernmentBEIS/inspect_ai | [#4956](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4956) | fix: avoid leaking eval overrides into reused tasks |
| google-gemini/gemini-cli | [#28912](https://github.com/google-gemini/gemini-cli/issues/28912) | You do not have a valid license of this product. |
| anthropics/claude-code | [#87940](https://github.com/anthropics/claude-code/issues/87940) | Scheduled/desktop tasks stop firing once a manual session is active |
| anthropics/claude-code | [#87874](https://github.com/anthropics/claude-code/issues/87874) | Subagent orchestration has no concurrency model: no join, no cancellation semantics, no quiescent stop, no signal ordering — and the semantics change silently between releases |
| huggingface/smolagents | [#2656](https://github.com/huggingface/smolagents/issues/2656) | [BUG] AgentImage inverts pixel values when built from a tensor (255 - array * 255) |
| anthropics/claude-code | [#87783](https://github.com/anthropics/claude-code/issues/87783) | Auto memory persists claims but not observations: no record of which sources a note was read from, so drifted and never-bound notes are indistinguishable |
| basicmachines-co/basic-memory | [#1275](https://github.com/basicmachines-co/basic-memory/issues/1275) | file_path lookups are byte-wise, so NFC/NFD filename variants create duplicate entities (macOS + Syncthing) |
| UKGovernmentBEIS/inspect_ai | [#4928](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4928) | fix(scorer): map numeric custom values in value_to_float instead of passing through |
| anthropics/claude-code | [#87694](https://github.com/anthropics/claude-code/issues/87694) | send_message (cross-session): sender gets "Message sent", recipient session is never written to and stops responding permanently |
| openai/codex | [#39223](https://github.com/openai/codex/issues/39223) | Codex Desktop loads global AGENTS.md but stale memory overrides its explicit rule |
| jerryfane/herdr | [#66](https://github.com/jerryfane/herdr/issues/66) | design: herdr-per-machine federation over Tailscale (cross-machine agent visibility, Tier 2) |
| traceloop/openllmetry | [#4426](https://github.com/traceloop/openllmetry/issues/4426) | 🐛 Bug Report: [OpenAI] Non-ASCII characters are escaped in `gen_ai.input.messages`, `gen_ai.tool.definitions`, and `gen_ai.output.messages` attributes |
| anthropics/claude-agent-sdk-python | [#1223](https://github.com/anthropics/claude-agent-sdk-python/pull/1223) | fix(transport): handle settings parse errors explicitly and align with CLI behavior |
| basicmachines-co/basic-memory | [#1269](https://github.com/basicmachines-co/basic-memory/pull/1269) | fix(core): count non-Latin tokens when relaxing full-text queries |
| anthropics/claude-code | [#87356](https://github.com/anthropics/claude-code/issues/87356) | Hooks are tool-call-scoped, not filesystem-scoped -- no way to catch "a file changed" regardless of which tool changed it |
| agentsmd/agents.md | [#232](https://github.com/agentsmd/agents.md/issues/232) | Complementary convention: `agentaccess.txt` — whether agents may access a directory (vs. how to work in it) |
| NousResearch/hermes-agent | [#88378](https://github.com/NousResearch/hermes-agent/pull/88378) | fix(update): purge stale modules before dashboard cleanup on the ZIP path |
| NousResearch/hermes-agent | [#88371](https://github.com/NousResearch/hermes-agent/issues/88371) | [Bug]: `hermes update` crashes with ImportError after "Update complete!" (stale sys.modules in _kill_stale_dashboard_processes) |
| anthropics/claude-agent-sdk-python | [#1220](https://github.com/anthropics/claude-agent-sdk-python/issues/1220) | Claude Code SDK permission system is a complete mess |
| TencentCloud/TencentDB-Agent-Memory | [#1025](https://github.com/TencentCloud/TencentDB-Agent-Memory/issues/1025) | Proposal: proactive L1 memory maintenance — LLM-driven recall with source-message evidence to retire stale memories |
| cohere-ai/cohere-python | [#796](https://github.com/cohere-ai/cohere-python/issues/796) | Batched embeddings drop types absent from the first response |
| anthropics/claude-code | [#86915](https://github.com/anthropics/claude-code/issues/86915) | Scheduled task session hangs forever on unattended permission prompt, then per_task_limit silently starves all future runs |
| google/adk-python | [#6729](https://github.com/google/adk-python/pull/6729) | fix(sessions): make SqliteSessionService state merges use dict.update() semantics |
| 1jehuang/jcode | [#960](https://github.com/1jehuang/jcode/issues/960) | Memory retrieval gaps: near-literal search misses, stale memories stay active, Chinese embeddings degrade recall |
| desimpson/syncer | [#158](https://github.com/desimpson/syncer/issues/158) | Bug: Firefox profile auto-detect fails on Windows because process.env is replaced at build time |
| UKGovernmentBEIS/inspect_ai | [#4883](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4883) | Record Task(approval=...) policies in EvalSpec (#4881) |
| anthropics/claude-code | [#86724](https://github.com/anthropics/claude-code/issues/86724) | Nested-Agent orchestrator (e.g. built-in /code-review) reports status: completed after yielding to spawned children, before its assigned work is done |
| zilliztech/memsearch | [#676](https://github.com/zilliztech/memsearch/issues/676) | Claude Code SessionStart hook still hits `timeout: 10` after #645 — `--version` is a second full CLI boot and the PyPI check blocks (~3.4s of ~4.9s is avoidable) |
| anthropics/anthropic-sdk-python | [#1830](https://github.com/anthropics/anthropic-sdk-python/pull/1830) | fix(streaming): accumulate compaction delta content |
| UKGovernmentBEIS/inspect_ai | [#4881](https://github.com/UKGovernmentBEIS/inspect_ai/issues/4881) | Tool Approval is not properly recorded in EvalSpec |
| google/adk-go | [#1333](https://github.com/google/adk-go/issues/1333) | [Feature]: model/openaimodel: support image/file input (genai InlineData/FileData parts) |
| openai/codex | [#38505](https://github.com/openai/codex/issues/38505) | Codex App leaves thousands of zombie processes and eventually causes spawn EAGAIN |
| anthropics/claude-code | [#86596](https://github.com/anthropics/claude-code/issues/86596) | "Another live session" duplicate-name check fires against a session's own current name, seconds after a manual rename |
| 51hcie/ai-project-continuity | [#20](https://github.com/51hcie/ai-project-continuity/issues/20) | Conflict handling when multiple AI agents concurrently update tasks.md in the same session |
| get-bb/bb | [#1552](https://github.com/get-bb/bb/issues/1552) | Pool multiple Claude accounts: limit-aware load balancing across provider connections |
| YoanWai/agent-manager | [#292](https://github.com/YoanWai/agent-manager/issues/292) | TestRefreshNotifiesWaitingTransitionOnce times out on CI |
| anthropics/claude-code | [#86391](https://github.com/anthropics/claude-code/issues/86391) | [BUG] Cowork scheduled tasks: WebFetch permission gate (PROVENANCE_REQUIRED) blocks unattended runs on parallel calls |
| openai/codex | [#38347](https://github.com/openai/codex/issues/38347) | Windows elevated sandbox fails on session-scoped mapped-drive cwd with error 267 |
| google/adk-python | [#6710](https://github.com/google/adk-python/pull/6710) | fix(evaluation): record NOT_EVALUATED instead of dropping invocations with zero auto-rater samples |
| langfuse/langfuse | [#16056](https://github.com/langfuse/langfuse/issues/16056) | bug(annotation-queues): re-adding objects creates duplicate queue items — skipDuplicates has no unique constraint to act on |
| mem0ai/mem0 | [#6935](https://github.com/mem0ai/mem0/pull/6935) | fix(milvus): convert COSINE distance to similarity in _parse_output |
| mem0ai/mem0 | [#6933](https://github.com/mem0ai/mem0/issues/6933) | bug(sdk-python): MilvusVectorStore returns raw distance as score for COSINE metric — ranking inverted, best match dropped by default threshold |
| punkpeye/fastmcp | [#326](https://github.com/punkpeye/fastmcp/pull/326) | fix(edge): persist SSE responses that arrive after a client disconnect |
| bmad-code-org/BMAD-METHOD | [#2725](https://github.com/bmad-code-org/BMAD-METHOD/issues/2725) | [6.11.0] sprint_plan.py / sprint_status.py: BOM'd epic files silently dropped; non-scalar YAML values crash validate; CRLF files rewritten wholesale |
| PrismorSec/prismor | [#272](https://github.com/PrismorSec/prismor/issues/272) | Runaway agent loop detection and circuit breakers |
| anthropics/claude-code | [#86115](https://github.com/anthropics/claude-code/issues/86115) | Desktop app: paused (disabled) scheduled tasks disappear from the Routines list |
| anthropics/claude-agent-sdk-python | [#1202](https://github.com/anthropics/claude-agent-sdk-python/pull/1202) | Keep session metadata when the first record exceeds the lite read window |
| planetf1/otelite | [#113](https://github.com/planetf1/otelite/issues/113) | feat: context-composition view — decompose cached prefix into system prompt / skills / tools / conversation |
| anthropics/claude-code | [#85975](https://github.com/anthropics/claude-code/issues/85975) | [Bug] Auto-update reports success with non-functional stub binary after postinstall link failure |
| punkpeye/fastmcp | [#322](https://github.com/punkpeye/fastmcp/pull/322) | fix(edge): release cancelled GET SSE streams |
| ruvnet/ruflo | [#2968](https://github.com/ruvnet/ruflo/issues/2968) | 3.37.0 regression: memory store reports success but persists nothing — skipped better-sqlite3 postinstall silently falls back to sql.js, which rejects wal_checkpoint (re #2867, #2219) |
| anthropics/claude-code | [#85873](https://github.com/anthropics/claude-code/issues/85873) | [BUG] Scheduled tasks created inside an SSH remote session never run: cwd is validated against the local filesystem and no host binding is persisted |
| agentsmd/agents.md | [#228](https://github.com/agentsmd/agents.md/issues/228) | AGENTS.md is being used as a policy file, but two of its own rules make that unsafe |
| anthropics/claude-code | [#85820](https://github.com/anthropics/claude-code/issues/85820) | Permission requests in unattended scheduled-task sessions hang for days with no timeout, wedging the task queue |
| anthropics/claude-code | [#85804](https://github.com/anthropics/claude-code/issues/85804) | Desktop 앱 업데이트 후 계정 로컬 상태(세션 인덱스 + 예약 루틴 + Chrome 확장 페어링) 전부 리셋됨 |
| Altinn/kihub | [#117](https://github.com/Altinn/kihub/issues/117) | Specify kill-switch protocol: scope, testing, and sub-agent/multi-agent coverage |
| rjmurillo/ai-agents | [#4880](https://github.com/rjmurillo/ai-agents/issues/4880) | chore(context): measure and slim path-local AGENTS.md layers |
| anthropics/claude-code | [#85663](https://github.com/anthropics/claude-code/issues/85663) | [BUG] Windows: All install methods (npm/ps1/cmd/winget) fail with "defines.json" Syntax Error referencing C:\Program Files\nodejs |
| anthropics/claude-code | [#85617](https://github.com/anthropics/claude-code/issues/85617) | Model asserted third-party delivery worked from sender-side evidence; false conclusion persisted through memory across sessions (11-day production outage) |
| anthropics/claude-code | [#85592](https://github.com/anthropics/claude-code/issues/85592) | CLAUDE_CODE_SUBAGENT_MODEL silently discards explicit per-call subagent model since v2.1.223; documented warning never fires; subagent metadata records requested (not effective) model |
| anthropics/claude-code | [#85565](https://github.com/anthropics/claude-code/issues/85565) | [BUG] Desktop app update silently wiped the internal scheduled-tasks registry (scheduledTasks: []) — all scheduled tasks died at once, with zero user notification |
| NishikawaButterfly/quant-risk-engine | [#51](https://github.com/NishikawaButterfly/quant-risk-engine/issues/51) | Catch SystemExit in the CLI test harness |
| anthropics/anthropic-sdk-python | [#1820](https://github.com/anthropics/anthropic-sdk-python/pull/1820) | Fix streaming accumulator crash when message_start omits usage |
| anthropics/claude-code | [#85430](https://github.com/anthropics/claude-code/issues/85430) | [BUG] PreToolUse hooks silently do not fire for one working directory while permissions.deny from the same settings.json does |
| anthropics/claude-code | [#85422](https://github.com/anthropics/claude-code/issues/85422) | [FEATURE] Token-burn circuit breaker: runtime-enforced spend caps with per-source attribution (hooks, plugins, subagents), not just warnings |
| NousResearch/hermes-agent | [#82801](https://github.com/NousResearch/hermes-agent/issues/82801) | Built-in personality system overrides SOUL.md — no composition, no precedence, no visible indicator |
| anthropics/anthropic-sdk-python | [#1815](https://github.com/anthropics/anthropic-sdk-python/pull/1815) | fix(streaming): initialize usage when message_start omits it |
| anthropics/claude-code | [#85199](https://github.com/anthropics/claude-code/issues/85199) | [BUG]Claude Desktop repeatedly crashes and requires “Advanced Options → Repair” on Windows |
| Piero24/Claude-World | [#4](https://github.com/Piero24/Claude-World/issues/4) | Feature: Telegram Bot Integration — Talk to Claude Code CLI from Telegram |
| attevon-llc/OpenTranscribe | [#366](https://github.com/attevon-llc/OpenTranscribe/issues/366) | feat(asr): NVIDIA NeMo (Parakeet / Canary) as a first-class local transcription engine |
| raphaelfnds/rsct-framework | [#57](https://github.com/raphaelfnds/rsct-framework/issues/57) | feat(mcp): plans carry no value or cost signal — the only ordering that exists is file mtime |
| vansh7nvc/Abstractify | [#12](https://github.com/vansh7nvc/Abstractify/issues/12) | Issue #12 🎙️ Abstract-to-Podcast Audio Summary (Two-Host Structured Dialogue & TTS) |
| anthropics/claude-code | [#85027](https://github.com/anthropics/claude-code/issues/85027) | VS Code agent host drops user skill descriptions, so skills never auto-activate |
| mem0ai/mem0 | [#6859](https://github.com/mem0ai/mem0/pull/6859) | fix(vector_stores/azure_ai_search): raise on failed indexing results |
| UKGovernmentBEIS/inspect_ai | [#4786](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4786) | Don't award partial credit for a P grade when partial_credit is disabled |
| anthropics/claude-code | [#84851](https://github.com/anthropics/claude-code/issues/84851) | [BUG] Windows MSIX auto-update corrupts package (Modified, NeedsRemediation) - app unlaunchable, Repair fails |
| anthropics/claude-code | [#84793](https://github.com/anthropics/claude-code/issues/84793) | remoteControlAtStartup not honored when the desktop app resumes a session after auto-update |
| pydantic/pydantic-ai | [#7247](https://github.com/pydantic/pydantic-ai/issues/7247) | First-class checkpoint/rewind primitive for agent runs |
| UKGovernmentBEIS/inspect_ai | [#4782](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4782) | fix(solver): prevent closure model retention across calls in self_critique and model_graded_qa |
| kunchenguid/firstmate | [#1818](https://github.com/kunchenguid/firstmate/issues/1818) | Crewmates are cut off from the project's auto-memory: the projects/<name> clone keys a separate store, and no brief ever asks for a write |
| anthropics/claude-code | [#84410](https://github.com/anthropics/claude-code/issues/84410) | Claude Desktop (Windows) hangs permanently after GPU process crash - no auto-recovery, relaunch blocked |
| openai/codex | [#37226](https://github.com/openai/codex/issues/37226) | Automatically isolate and coordinate concurrent writes across chats and agents |
| anthropics/anthropic-sdk-python | [#1806](https://github.com/anthropics/anthropic-sdk-python/issues/1806) | Streaming accumulator crashes when message_start omits usage as shown in thinking docs |
| anthropics/claude-code | [#84333](https://github.com/anthropics/claude-code/issues/84333) | [BUG] Claude Desktop (Windows MSIX) silently becomes Modified, NeedsRemediation mid-session with no deployment operation in the AppXDeploymentServer log |
| patraratorn/agentrouter-claude-proxy | [#1](https://github.com/patraratorn/agentrouter-claude-proxy/issues/1) | install-autostart.ps1 fails: invalid LogonType "InteractiveToken" |
| anthropics/claude-agent-sdk-python | [#1185](https://github.com/anthropics/claude-agent-sdk-python/pull/1185) | fix: use tuple keys in InMemorySessionStore to prevent composite key collisions |
| xjiang16/job-market-tracker | [#28](https://github.com/xjiang16/job-market-tracker/issues/28) | Ingest company ATS board postings (Greenhouse / Lever / Ashby) |
| anthropics/claude-code | [#84196](https://github.com/anthropics/claude-code/issues/84196) | [FEATURE] Scheduled-task tools expose no link between a taskId and the session(s) that executed it |
| google/adk-python | [#6596](https://github.com/google/adk-python/pull/6596) | agents: block all stdlib modules in agent-config code-refs (denylist bypass via cProfile.run/timeit) |
| anthropics/claude-code | [#84081](https://github.com/anthropics/claude-code/issues/84081) | [BUG] Auto-update silently installs a broken 500-byte stub when npm allowScripts blocks the postinstall |
| anthropics/claude-code | [#84051](https://github.com/anthropics/claude-code/issues/84051) | Interrupted auto-update leaves claude broken (missing bin symlink, placeholder stub, truncated native binary) with no self-healing |
| NathanKrupa/OverSteward | [#287](https://github.com/NathanKrupa/OverSteward/issues/287) | fix(dream): MEMORY.md is 34KB against a 25KB cap and silently truncating — 51% of the always-loaded layer is duplicated link scaffolding |
| evalstate/fast-agent | [#906](https://github.com/evalstate/fast-agent/pull/906) | fix(mcp): track ping error responses as connection failures, not successes |
| anthropics/claude-code | [#83932](https://github.com/anthropics/claude-code/issues/83932) | [BUG] Windows auto-update deploys into running claude.exe + CoworkVMService (0x80073CF9/0x80073D02), app left unlaunchable (NeedsRemediation); recovery churn incl. dev-only PreserveApplicationData (0x80073CFA) — twice in one day |
| anthropics/claude-code | [#83920](https://github.com/anthropics/claude-code/issues/83920) | [Bug] Agent tool model parameter ignored; subagents inherit session/settings model instead of override |
| OpenHands/OpenHands | [#16308](https://github.com/OpenHands/OpenHands/issues/16308) | [Feature] Usage metrics dashboard for token, ACU, and cost tracking |
| chigwell/telegram-mcp | [#180](https://github.com/chigwell/telegram-mcp/issues/180) | FloodWait is invisible in the tool runtime: short waits absorbed by Telethon default, long ones lose their type |
| gourabanandad/error-translator-cli-v2 | [#99](https://github.com/gourabanandad/error-translator-cli-v2/issues/99) | Auto-hook should not intercept KeyboardInterrupt and SystemExit |
| punkpeye/fastmcp | [#310](https://github.com/punkpeye/fastmcp/issues/310) | imageContent/audioContent: cap URL-fetched response bodies before unbounded buffering |
| langfuse/langfuse | [#15734](https://github.com/langfuse/langfuse/issues/15734) | bug(models): model-name uniqueness relies on sentinel column values and a racy pre-check |
| UKGovernmentBEIS/inspect_ai | [#4730](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4730) | fix(recover): sum all ModelUsage fields in the recovered log stats rollup |
| zilliztech/memsearch | [#664](https://github.com/zilliztech/memsearch/issues/664) | Claude Code Stop hook writes the entire raw transcript into memory when the turn exceeds 128 KB (argv `MAX_ARG_STRLEN`) |
| evalstate/fast-agent | [#903](https://github.com/evalstate/fast-agent/issues/903) | Marketplace entry name is used as an install directory name without containment, escaping the managed root |
| anthropics/claude-agent-sdk-python | [#1165](https://github.com/anthropics/claude-agent-sdk-python/issues/1165) | max_buffer_size and import byte limits count characters instead of UTF-8 bytes |
| anthropics/claude-agent-sdk-python | [#1162](https://github.com/anthropics/claude-agent-sdk-python/issues/1162) | CLI version check timeout can hang indefinitely while waiting for termination |
| zilliztech/memsearch | [#663](https://github.com/zilliztech/memsearch/pull/663) | fix(store): don't report every local open failure as a version mismatch |
| punkpeye/fastmcp | [#306](https://github.com/punkpeye/fastmcp/pull/306) | fix(auth): handle aborted and oversized bodies in OAuth proxy endpoints |
| punkpeye/fastmcp | [#305](https://github.com/punkpeye/fastmcp/pull/305) | fix: add timeout to image and audio content fetch |
| openai/codex | [#36631](https://github.com/openai/codex/issues/36631) | PowerShell uses C:\ instead of the workspace directory for Dropbox projects |
| anthropics/claude-code | [#83341](https://github.com/anthropics/claude-code/issues/83341) | [BUG] Claude Code hangs on all subprocess commands when running inside SSH session on Windows |
| anthropics/claude-cookbooks | [#803](https://github.com/anthropics/claude-cookbooks/pull/803) | fix(managed-agents): bind approval to exact merge |
| browserbase/stagehand | [#2527](https://github.com/browserbase/stagehand/pull/2527) | fix(locator): serialize click input events |
| modelcontextprotocol/python-sdk | [#3221](https://github.com/modelcontextprotocol/python-sdk/pull/3221) | fix(server): reject concurrent duplicate JSON-RPC request ids |
| paperclipai/paperclip | [#10412](https://github.com/paperclipai/paperclip/pull/10412) | fix(heartbeat): make agent wakeup idempotency keys actually deduplicate |
| openai/openai-agents-python | [#3998](https://github.com/openai/openai-agents-python/pull/3998) | fix: defer session save until after output guardrails |
| anthropics/claude-code | [#81672](https://github.com/anthropics/claude-code/pull/81672) | fix(hookify): make package import independent of the install directory name |
| openai/openai-agents-python | [#3984](https://github.com/openai/openai-agents-python/pull/3984) | fix(memory): prevent close() race and enforce closed state in AsyncSQLiteSession |
| anthropics/claude-agent-sdk-python | [#1109](https://github.com/anthropics/claude-agent-sdk-python/pull/1109) | fix: surface prompt stream errors instead of hanging query() forever |

---

Generated by `github_evidence_snapshot.py` on 2026-10-04T03:24:52Z. Regenerated weekly; the dated full archive lives outside GitHub.
