# Upstream contribution evidence — @tonydzi

Snapshot: **2026-09-07** · source: public GitHub API · regenerated weekly.

This page exists so the contribution record stays checkable independently of any one profile page. Everything below is a link into someone else's repository: their issue tracker, their pull requests, their release notes.

Counts are split on purpose. Opening a pull request in someone else's project and commenting in someone else's thread are different things, and adding them together would overstate the first.

| | |
|---|---:|
| Pull requests opened in other people's repos | 103 |
| …of which merged | 35 |
| Issues opened in other people's repos | 51 |
| Other people's threads participated in | 328 |
| Reviews on other people's PRs | 15 |
| Distinct repositories | 215 |
| Replies received from maintainers and participants | 1542 |
| Release notes crediting this account | 15 |
| Files in other repos crediting this account | 22 |

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

**eugeniughelbur/obsidian-second-brain — v0.15.0** · 2026-09-04 · [release notes](https://github.com/eugeniughelbur/obsidian-second-brain/releases/tag/v0.15.0)

> - **`validate-ai-first.sh` exited 0, silently, when a write payload named a tool but carried no path key it knew (#171, the open item from @tonydzi's codex-cli reports).** The hook read `file_path` and `filePath` (and `args.*`); a host that sends the path under another key (`path`, `uri`) got exit 0, indistinguishable from "not a vault file", and the write went unchecked with no trace. The hook now reads `notebook_path`/`notebookPath` as well (the `NotebookEdit` shape its own matcher names; an `.ipynb` then drops at the `.md` gate as before), and when a payload names a `tool_name` but no known path key it prints one stderr line naming the tool and the payload keys and exits 1: non-blocking, the write stands, but the miss is visible. Input with no `tool_name` stays silent. Covered by `tests/test_smoke.py::test_validate_hook_is_loud_when_the_payload_has_no_known_path_key`.

## Credited in other projects' files

Lines maintainers wrote into their own changelogs and contributor lists.

**eugeniughelbur/obsidian-second-brain · [`CHANGELOG.md`](https://github.com/eugeniughelbur/obsidian-second-brain/blob/d631fd67aea0afe2b1e44fa5496bc04629348456/CHANGELOG.md)**

> - **`validate-ai-first.sh` exited 0, silently, when a write payload named a tool but carried no path key it knew (#171, the open item from @tonydzi's codex-cli reports).** The hook read `file_path` and `filePath` (and `args.*`); a host that sends the path under another key (`path`, `uri`) got exit 0 …

**Lyellr88/marm-memory · [`CONTRIBUTORS.md`](https://github.com/Lyellr88/marm-memory/blob/0b4013de9e854fccd211d7fdb8e35ff6596ec4a1/CONTRIBUTORS.md)**

> - **Anton Dziatkovskii** ([@tonydzi](https://github.com/tonydzi)) - Repaired `scripts/test-scripts/smoke_embedding_chunking.py` against the v2.14.0 chunk-profile split, closing the harder of the two remaining scripts named in the wider alignment audit ([#165](https://github.com/Lyellr88/marm-memory/ …
> - **Anton Dziatkovskii** ([@tonydzi](https://github.com/tonydzi)) - Repaired the 17 dead links in `marm-mcp-server/README.md`, the file `pyproject.toml` declares as `readme` and therefore the description PyPI renders. All 17 were written relative to the repository root, a position neither surface th …

**Lyellr88/marm-memory · [`CHANGELOG.md`](https://github.com/Lyellr88/marm-memory/blob/0b4013de9e854fccd211d7fdb8e35ff6596ec4a1/CHANGELOG.md)**

> The 8 tests in `tests/test_docker_transports.py` that actually start a container previously only ran in the release workflow, which triggers on a version tag, so a Docker runtime regression was caught after a release was already tagged rather than on the PR that caused it. Contributed by [@tonydzi]( …
> `scripts/test-scripts/smoke_embedding_chunking.py` had been broken since chunking was split into separate memory and document profiles: it imported constants that no longer existed and called `_chunk_text` without the keyword arguments it now requires. Contributed by [@tonydzi](https://github.com/to …
> The README published to PyPI carried 17 links written relative to the repository root, a position neither surface that renders that file ever occupies. Reported and fixed by [@tonydzi](https://github.com/tonydzi).

**qualixar/superlocalmemory · [`CHANGELOG.md`](https://github.com/qualixar/superlocalmemory/blob/07a431ed3894ad6b28f144db8a1a8c7d8c839a86/CHANGELOG.md)**

> Reported by @tonydzi (#122).

**michellzappa/headroom · [`CHANGELOG.md`](https://github.com/michellzappa/headroom/blob/72ab971db6aa30c76823e1eb0c21697e842e44c5/CHANGELOG.md)**

> (#28, reported by @tonydzi). Claude Code writes one JSONL line per content

**borq168/radar-forge · [`digests/2026-08-08/ai-skills-en.md`](https://github.com/borq168/radar-forge/blob/ebf8818a5cb8c1cbf425bd8fd233693fa8b4e00f/digests/2026-08-08/ai-skills-en.md)**

> | plan-file-hygiene | #1479 | @tonydzi | Open, July 27 update | Lifecycle management for planning artifacts. Community credit to @halilxibrahim. |

**DanceNitra/agora · [`probes/recheck_figures_91188_units.py`](https://github.com/DanceNitra/agora/blob/440a4f37c9666be8950fb5184c7e5828c7c29020/probes/recheck_figures_91188_units.py)**

> by_tonydzi = gh("repos/anthropics/claude-code/issues/91188/comments",
> '.[] | select(.user.login=="tonydzi") | .body')
> thread = body + by_tonydzi + by_pm25
> "tonydzi carried it there today; the draft references the unit once and proves nothing")
> chk("tonydzi asked it, and the draft says so",
> "@tonydzi asked @niels-roest whether that target", asked in by_tonydzi,

**linny006/mcp-servers-live · [`r/tonydzi/telegram-mcp-kit/index.html`](https://github.com/linny006/mcp-servers-live/blob/38d567f0d33b673d69d5689a7777ff8a7c63e762/r/tonydzi/telegram-mcp-kit/index.html)**

> <title>tonydzi/telegram-mcp-kit - entry on MCP Servers Live</title>
> <link rel="canonical" href="https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-mcp-kit/">
> <meta property="og:title" content="tonydzi/telegram-mcp-kit - entry on MCP Servers Live">
> <meta property="og:url" content="https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-mcp-kit/">
> <meta name="twitter:title" content="tonydzi/telegram-mcp-kit - entry on MCP Servers Live">
> <script type="application/ld+json">{"@context":"https://schema.org","@type":"SoftwareSourceCode","name":"tonydzi/telegram-mcp-kit","codeRepository":"https://github.com/tonydzi/telegram-mcp-kit","programmingLanguage":"PowerShell","url":"https://linny006.github.io/mcp-servers-live/r/tonydzi/telegram-m …

**linny006/mcp-servers-live · [`r/tonydzi/whatsapp-mcp-kit/index.html`](https://github.com/linny006/mcp-servers-live/blob/38d567f0d33b673d69d5689a7777ff8a7c63e762/r/tonydzi/whatsapp-mcp-kit/index.html)**

> <title>tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live</title>
> <link rel="canonical" href="https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-kit/">
> <meta property="og:title" content="tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live">
> <meta property="og:url" content="https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-kit/">
> <meta name="twitter:title" content="tonydzi/whatsapp-mcp-kit - entry on MCP Servers Live">
> <script type="application/ld+json">{"@context":"https://schema.org","@type":"SoftwareSourceCode","name":"tonydzi/whatsapp-mcp-kit","codeRepository":"https://github.com/tonydzi/whatsapp-mcp-kit","programmingLanguage":"Python","url":"https://linny006.github.io/mcp-servers-live/r/tonydzi/whatsapp-mcp-k …

**DanceNitra/agora · [`probes/what_our_own_index_actually_delivers.py`](https://github.com/DanceNitra/agora/blob/440a4f37c9666be8950fb5184c7e5828c7c29020/probes/what_our_own_index_actually_delivers.py)**

> trap @tonydzi described on anthropics/claude-code#91188 for bytes against units.

**QwenLM/qwen-code-docs · [`website/content/zh/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/zh/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 首次贡献：stream-json 模式提问宿主修复 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/en/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/en/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 First contribution: fix for question host in stream-json mode | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/de/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/de/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Erster Beitrag: Fix für Frage-Host im stream-json-Modus | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ko/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/ko/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 첫 기여: stream-json 모드 질문 호스트 수정 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/fr/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/fr/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Première contribution : correction de l'hôte de questionnement en mode stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ja/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/ja/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 初貢献：stream-json モードの質問ホストの修正 | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/ru/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/ru/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Первый вклад: исправление запросов к хосту в режиме stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**QwenLM/qwen-code-docs · [`website/content/pt-BR/blog/updates/weekly-update-2026-09-03.mdx`](https://github.com/QwenLM/qwen-code-docs/blob/021dfbc03ade4f727093fd31ea1690c06b4b284c/website/content/pt-BR/blog/updates/weekly-update-2026-09-03.mdx)**

> | 🆕 **[@tonydzi](https://github.com/tonydzi)** | 🎉 Primeira contribuição: correção do host de perguntas no modo stream-json | [#9414](https://github.com/QwenLM/qwen-code/pull/9414) |

**DanceNitra/agora · [`probes/the_reminders_advice_switches_unit_at_125_units_per_line.py`](https://github.com/DanceNitra/agora/blob/440a4f37c9666be8950fb5184c7e5828c7c29020/probes/the_reminders_advice_switches_unit_at_125_units_per_line.py)**

> He has no `claude` binary and took the identifier shapes from @tonydzi's greps. This reads the
> 125 units per line. But the threshold was named in that thread by @tonydzi and @pm25coder before us,
> ("tonydzi index (his counts)", 8188, 72),

**DanceNitra/agora · [`probes/the_cap_on_windows_and_what_a_crlf_line_costs.py`](https://github.com/DanceNitra/agora/blob/440a4f37c9666be8950fb5184c7e5828c7c29020/probes/the_cap_on_windows_and_what_a_crlf_line_costs.py)**

> @tonydzi is darwin-arm64 and has annotated his own Windows figure as unverified. There is no

**DanceNitra/agora · [`probes/the_cut_measured_by_what_the_index_DOES_not_what_it_says.py`](https://github.com/DanceNitra/agora/blob/440a4f37c9666be8950fb5184c7e5828c7c29020/probes/the_cut_measured_by_what_the_index_DOES_not_what_it_says.py)**

> Windows, current CC. @JhouCode is linux-x64, @tonydzi darwin-arm64 and has annotated his own Windows

**DanceNitra/agora · [`probes/the_memory_index_check_grew_a_second_size_and_the_team_path_grew_a_line_cap.py`](https://github.com/DanceNitra/agora/blob/440a4f37c9666be8950fb5184c7e5828c7c29020/probes/the_memory_index_check_grew_a_second_size_and_the_team_path_grew_a_line_cap.py)**

> WHY. On anthropics/claude-code#91188 @tonydzi read CLI 2.1.202 on macOS and reported three things:
> * The team path DOES pass a lineCap, conditionally. @tonydzi's third finding does not reproduce

## What maintainers replied

Replies in threads we opened, plus replies elsewhere that name this account. Quotes are trimmed; every one links to the original.

### [QwenLM/qwen-code PR #9414](https://github.com/QwenLM/qwen-code/pull/9414) — fix(core): do not claim a question host in stream-json direct mode

*Role here: our pull request.*

*qwen-code-ci-bot*, 2026-08-18:

> <!-- qwen-triage stage=1a --> Thanks @tonydzi — the write-up is thorough, and the underlying bug is real (see #9011). Before this can move to code review, one housekeeping item: the PR body doesn't use the repository's pull request template. Merged PRs here follow that template consistently, and reviewers rely on the fixed sections to find what they need. The body is missing all of the required headings: - `## What this PR does` - `## Why it's needed` - `## Reviewer Test Plan` (with `### How to verify`, `### Evidence (Before & After)`, and the `### Tested on` OS table) - `## Risk & Scope` - `## Linked Issues` - the Chinese translation inside `<details>` — the template asks for the full body …

*wenshao*, 2026-08-28:

> ## Maintainer verification — built and ran from source, 4 arms I did not review this by reading it. I built four CLIs from source and drove the real binary: a real interactive TUI in tmux, and real `--input-format stream-json` sessions against a local mock model. Numbers below are from those runs; the harness is described at the bottom so you can re-run them. **Headline: the change this PR is about landed on `main` ~6 hours after your last push, as #10160. But the PR is not empty — 6 of its lines fix a real hang, and one half of that hang is a regression #10160 introduced.** ### Environment | | | |---|---| | host | Linux x86_64, Node `v22.22.2` | | build | per arm: `npm ci` → `npm run genera …

### [anthropics/claude-code issue #82056](https://github.com/anthropics/claude-code/issues/82056) — A session cannot determine whether its auto-memory index loaded whole, truncated, or not at all

*Role here: our comment in their thread.*

*pjt222*, 2026-08-25:

> @JhouCode's round 0 sent me back to my own data with a ruler, and it disqualifies most of it. The ruler is @DanceNitra's — "198 is derivable from the documented cap and the line width without reading anything at all" — applied to every table in this thread rather than to one arm. ## 1. Every canary-echo arm published here returns `floor(25000 / units-per-line)` Mine first, since the ruler kills most of it: | arm | units/line | `floor(25000/u)` | measured | | |---|---:|---:|---:|---| | `ascii` 200×126 | 126.995 | 196 | **196** | reconstructible | | `cjk` 200×126 | 126.995 | 196 | **196** | reconstructible | | `crlf` 200×126 | 127.990 | 195 | **195** | reconstructible | | `astral` 200×126 | 24 …

*JhouCode*, 2026-08-26:

> A disclosure that should have led every comment I posted here, plus the corrections it forces and one observer effect I think matters to the feature itself. ## 1. The box my numbers came from is not a clean room @pjt222 and @DanceNitra run fixtures with an isolated config dir, `settings.json = {}`, and tools asserted empty from the wire. That is how you measure a cap. I have not been doing that. Every figure I have posted to this thread came from a live working box that injects **a curated context layer of its own** — at session start and again on every prompt, before any file is read. Measured on that machine, just now: ``` injected per session, before any tool call 30,773 bytes the MEMORY. …

### [anthropics/claude-code issue #91188](https://github.com/anthropics/claude-code/issues/91188) — Feature request: make the auto-memory MEMORY.md compaction reminder threshold configurable

*Role here: our comment in their thread.*

*DanceNitra*, 2026-09-01:

> @niels-roest, your 17.1KB and the ~70% you read off it are both exact. The constants are literals, and there is a second half that changes what your knob would have to do. **Where the numbers come from.** The reminder builds one entry per dimension, each carrying a fraction of its own cap, and reports whichever is proportionally closest: ```js var ljo=0.8,HUn=0.7; function xut(e){ let n=[{frac:e.sizeBytes/e.byteCap,dimension:"bytes", capDesc:Ut(e.byteCap),targetDesc:Ut(Math.floor(e.byteCap*HUn))}]; if(e.lineCap!==void 0&&e.lineCount!==void 0) n.push({frac:e.lineCount/e.lineCap,dimension:"lines", capDesc:`${e.lineCap}-line`,targetDesc:`${Math.floor(e.lineCap*HUn)} lines`}); let{frac:r,...o}=n …

*DanceNitra*, 2026-09-03:

> @niels-roest, the reminder can be made to fire later. The branch that does it is one none of us had read, and finding it means retracting a sentence of my own. On 1 September I wrote that "raising the configured value raises the number you are told to aim for". That is wrong on the default path. The four fields at the call site go into one function, and that function is a selector: ```js function IHe({rawSizeBytes:e,surfaceCap:n,splicedSizeBytes:r,spliceCap:o,spliceActive:d}){ return n!==void 0 && (!d || e/n >= r/o) ? {sizeBytes:e,byteCap:n} : {sizeBytes:r,byteCap:o} } ``` `!d` short-circuits, so the two branches behave differently. With `spliceActive` true, the configured cap wins only whil …

### [microsoft/agent-framework PR #7581](https://github.com/microsoft/agent-framework/pull/7581) — Python: bind tool-approval responses to surfaced approval requests (#7383)

*Role here: our pull request.*

*eavanvalkenburg*, 2026-08-26:

> @tonydzi thanks for working on this, i think the overall idea makes sense, the thing that is tricky here is that there is only so much we can do, because if a attacker has access to your session store they can change that version of the FCC and have it executed, but at some point we need to trust something, and this does add a additional layer that is `less` user controlled (session vs input message), so a improvement nonetheless. So let's get this in shape and then I will do a deeper dive. I'm also thinking about ID's, whether call_id is the right one, since some chat clients do not generate them...

*eavanvalkenburg*, 2026-09-01:

> @tonydzi, thank you for putting this draft together and especially for reproducing and documenting the failure modes raised in review. The core record/rebind/consume mechanism landed independently in #7631, so this branch is now superseded. I'm closing it in favor of #7988, which carries forward the remaining work around stable local approval occurrence identities, replay coverage, provider correlation, and the trusted-storage boundary. The investigation and review findings here directly shaped that PR—thank you.

### [anthropics/claude-code issue #81833](https://github.com/anthropics/claude-code/issues/81833) — Auto-memory is inconsistently loaded in git-worktree sessions (same repo, same day)

*Role here: our comment in their thread.*

*daichiyasunami-vottia*, 2026-09-05:

> @tonydzi — all four hold, and running your method surfaced a fifth. Fixed and pushed: daichiyasunami-vottia/parallel-memory-mcp@fe22aa7. **What changed, against your list:** 1. **The index is no longer regenerated; it is repaired.** Your 462→462 / 861→855 numbers settle it: a curated `MEMORY.md` is a deliberate subset, and one line per file inverts that straight into the truncation this thread is about. Now the index stays authoritative for *which* memories are listed. Sync refreshes existing lines from frontmatter, drops dangling pointers, and adds a line only for a memory that **arrived from another store** (a worktree, a stranded copy) — never for a local file the curator left unlisted. U …

*daichiyasunami-vottia*, 2026-09-03:

> **Correction to my previous comment.** I speculated that worktree-keyed project directories might be reaped, and that stranded memories could therefore be deleted rather than left for a migration. I chased it down, and **that is wrong in the case that matters**: memory files are not removed. @tonydzi, your 15 stranded files will still be there. What actually happens is transcript retention, and it is easy to confirm. `~/.claude/.last-cleanup` on this machine reads `2026-09-03T04:37:21.943Z` — a cleanup ran between my two observations, which is why a directory I had seen was gone an hour later. The boundary is visible in the data: ``` jsonl=0 memory=5 oldest transcript: (none) project A jsonl …

### [google/adk-go PR #1299](https://github.com/google/adk-go/pull/1299) — fix(configurable): apply config_path containment to workflow node refs

*Role here: our pull request.*

*karolpiotrowicz*, 2026-09-01:

> The containment fix itself holds up. I checked out the branch and drove the traversal through `FromConfig` rather than the helper: on the merge-base a workflow edge naming `../../outside.yaml` loads and builds the workflow, and on this branch both that and the absolute-path form are refused. The full suite shows no new failures against the merge-base, and the routing through one shared helper ahead of both the read and the cache lookup is the right shape. One thing needs settling before this merges, and it is the behaviour change @jjsasha63 already flagged as needing a wider note — it is wider than it currently reads. ## Refusing every link, not just escaping ones, breaks whole config layout …

*karolpiotrowicz*, 2026-09-04:

> Every ask from my last review is answered, and I checked each one against the branch rather than reading the response commits. The trade is stated in the description now, with the ConfigMap consequence and two concrete routes for an operator on such a mount. `TestResolveConfigReferenceRefusesLinksThatStayInside` pins the behaviour the change deliberately chooses, and it discriminates: reverting the walk to resolve-the-link-and-refuse-only-if-it-escapes fails that test and no other, with the escaping-symlink case still green. The `EvalSymlinks` block now has both a comment that describes what it actually does and a test that fails if you delete it. ENOTDIR, the empty-reference diagnostic, the …

### [anthropics/claude-code issue #78569](https://github.com/anthropics/claude-code/issues/78569) — [BUG] Auto-memory instructions direct an immediate MEMORY.md pointer edit, but the read-before-write gate deterministically rejects it

*Role here: our comment in their thread.*

*daichiyasunami-vottia*, 2026-09-04:

> Two corrections to my comments above, and a change of position that follows from them. **Correction 1 — the count.** I reported 13 paired errors in one place; that number mixed in six `Edit` failures of a different kind (`String to replace not found`, `Found 2 matches`). Restricting to results that actually contain `File has not been read yet`: **7 gate rejections, 7 `Write`, 0 `Edit`**, across 5 sessions (grep-verified: 1+2+1+2+1). **Correction 2 — abandonment.** Every one of the 7 was followed by a successful write to the same path in the same session: **0 of 7 abandoned.** The two "abandoned" rows I had were the non-gate `Edit` errors. So on this machine the gate costs one retry and loses …

*daichiyasunami-vottia*, 2026-09-04:

> @tonydzi — re-ran your paired scan on this machine (macOS, Claude Code 2.1.259, the 30 days of transcripts that survive cleanup). Smaller corpus, same shape on the part I could test, and a gap on the part I could not. **Write/Edit split — confirmed, and more one-sided here:** 10 `File has not been read yet` errors, 7 pairable to their tool call. **7 of 7 are `Write`, 0 `Edit`.** Your 38/6 and this 7/0 point the same way: the loop is overwhelmingly a whole-file `Write`, where "validate by content match" has nothing to match against. **Prior successful Read of the same path: 0 of 7.** Also 0 of 7 had a prior successful `Write`/`Edit` to the path — so on this machine it is not even the "session …

### [microsoft/semantic-kernel PR #14199](https://github.com/microsoft/semantic-kernel/pull/14199) — Python: Add experimental FunctionAuthorizationFilter for auto function invocation (runtime authorization, argument-bound approvals)

*Role here: our pull request.*

*babyblueviper1*, 2026-07-27:

> Reviewed the actual implementation, not just the description — the `args_digest` binding is real and sound: `sha256(function_name | args_digest | principal | policy_digest)` over a structurally type-tagged canonicalization (the `_canonicalize` method), which is the right defense against a hostile `__str__` producing a digest collision. That's a genuinely non-obvious detail to get right and it's handled correctly here. This directly answers the question I raised on #14072 about whether a dispatcher verifies the stored draft against what actually executes — it does, cryptographically, by construction: `transfer(amount=10)` approved can never authorize `transfer(amount=10000)` executed, because …

*babyblueviper1*, 2026-07-27:

> Worth pulling the automated DevFlow finding above into the same class of gap this thread's been naming, since it's a real one and distinct from the attribution question: the `args_digest` binding I checked earlier is sound (replay/tamper is structurally prevented), but that's orthogonal to *when* enforcement actually happens. `asyncio.gather(...)` dispatches every tool call in a model response concurrently and only inspects `terminate` after the whole batch resolves — so a `pending_approval` verdict on call N doesn't stop sibling calls in the same batch from having already executed by the time `terminate` is checked. The digest math being unforgeable doesn't help if the enforcement point and …

### [anthropics/anthropic-sdk-python PR #1820](https://github.com/anthropics/anthropic-sdk-python/pull/1820) — Fix streaming accumulator crash when message_start omits usage

*Role here: our comment in their thread.*

*PiedPiper911*, 2026-08-27:

> @tonydzi — thank you, again, for the re-measurement. All three findings were correct, and I have acted on all of them. Pushed as commit : **1. None coercion (the real fix).** Both accumulators ( + ) now coerce a missing to before /. Your reproduction was exactly right: bypasses validation, so on #1806's reported shape the field lands as on a required — an AttributeError traded for a TypeError one frame further from the cause. **2. Fixture restored to the reported shape.** now ends with — no , matching the actual repro in #1806. **3. Discriminating assertion + non-strict client.** The tests now assert (which fails on the old implementation) and build a non-strict locally — you were right that …

*PiedPiper911*, 2026-08-24:

> Thanks for the drive-by review, tonydzi — appreciate the triage and the honest read on both PRs. I've since synced this branch with the latest `main` (merge commit 1316de75 + a line-ending cleanup), so the diff is now just the actual fix: 4 files instead of the 60-file noise from the stale base. The fix itself is unchanged — when `message_start` omits `usage`, the accumulator constructs it from the first `message_delta` instead of crashing (#1806), with sync + async regression tests (new `missing_usage_response.txt` fixture). On the overlap with #1815: you're right that @chenlichao opened it ~13h earlier, and your point about the ideal merge (this fix + a solid test setup) is fair. Both PRs …

### [google-gemini/cookbook PR #1296](https://github.com/google-gemini/cookbook/pull/1296) — Add example: check citation faithfulness in RAG

*Role here: our pull request.*

*kkorpal*, 2026-08-06:

> Hi @Palo-Alto-AI-Research-Lab While testing the latest changes, I ran into a couple of structural errors during execution: ``` A TypeError is triggered during the client.interactions.create() execution step. A ValidationError follows during the subsequent Pydantic model_validate_json() parsing loop. ``` Please review the official Google AI Studio Interactions API Overview and the [Interactions API Reference Guide](https://ai.google.dev/api/interactions-api) to confirm how parameter structures, schema types, and response block formats must be formatted for this endpoint

*kkorpal*, 2026-07-27:

> Hi @Palo-Alto-AI-Research-Lab , Before we move forward, could you take a quick look at the failing checks on your PR? It looks like the Google CLA needs to be signed, and the notebook format and lint checks are currently failing. Definitely check out the automated bot suggestions on the PR thread. Once those are all green, we can get this moving. Thanks

### [zilliztech/memsearch PR #695](https://github.com/zilliztech/memsearch/pull/695) — perf(hooks): refresh the PyPI check off the session-start blocking path (#676)

*Role here: our pull request.*

*ilipkanou*, 2026-08-22:

> *The measurements below were run by an AI agent (Claude) on my machine. Unlike the caveat upthread, I read and approved this comment before it posted.* Ran #695 on macOS 15 / arm64, bash 3.2.57, against `main` at `72c7c3a`. **Test suite.** `tests/test_claude_hooks.py`: **29 passed on `main`, 31 passed on `pr695`**. That includes the symlink-privilege tests you could not run on Git Bash — `test_dist_info_version_resolves_symlinked_bin_without_gnu_readlink`, `test_claude_session_start_resolves_symlinked_bin_without_gnu_readlink` and `test_claude_session_start_uv_tool_upgrade_hint_preserves_extras` all pass here, as do both new PyPI tests. **Shell mechanics on bash 3.2.** `local` inside the det …

*zc277584121*, 2026-09-01:

> Thanks for addressing the earlier review. I found two remaining edge cases and prepared a focused follow-up in 7f382a6: - Version ordering now covers normalized dev, alpha, beta, release-candidate, final, and post releases; local labels do not turn the same public version into an upgrade, and unknown formats stay silent instead of risking a downgrade hint. - A failed atomic publish now removes its owned temporary file while preserving the previous cache value. The added deterministic coverage runs against both SessionStart implementations and covers cold, fresh, expired, empty, failed, and concurrent refreshes; unique temp ownership; atomic publication; both captured file descriptors; and ch …

### [anthropics/claude-code issue #81992](https://github.com/anthropics/claude-code/issues/81992) — Claude Desktop repeatedly enters "Modified, NeedsRemediation" state and fails to launch — persists even after full OS reinstall (Windows MSIX)

*Role here: our comment in their thread.*

*Aquinas-Protocol*, 2026-08-30:

> @tonydzi Your structural point survives contact with this machine, but two of its load-bearing readings need correction, and the mechanism behind your steady-state skew turns out to exist and fail silently rather than not exist. 1. The rewrite mechanism exists. main.log on this box shows an explicit sync step, "[Chrome Extension MCP] native host sync", copying the host from the package (app\resources\chrome-native-host.exe) to %APPDATA%\Claude\ChromeNativeHost. It ran at 1.40609's staging here (Roaming copy stamped at staging time) and the Roaming copy currently hash-matches the installed package exactly. But the same log also shows the failure mode that produces your skew: 2026-08-29 02:51: …

*Aquinas-Protocol*, 2026-08-28:

> @tonydzi Ran your correction against this machine (the #90147 box, 1.37937.3.0, post-repair). Short version: your location reading is right for the current build, and the LocalCache path was right for the incident state. It moved, and both machines are internally consistent. Measured today: chrome-native-host.exe PID 16404 exe = %APPDATA%\Claude\ChromeNativeHost\chrome-native-host.exe (real Roaming, matching yours) parent chain: chrome.exe -> cmd.exe -> chrome-native-host.exe started 3 minutes after boot, alongside Chrome. Claude Desktop is not its parent. So the survival mechanism is what you inferred: Chrome owns the host's lifecycle, and nothing on the Claude side restarts or reaps it. Yo …

### [anthropics/claude-code issue #85422](https://github.com/anthropics/claude-code/issues/85422) — [FEATURE] Token-burn circuit breaker: runtime-enforced spend caps with per-source attribution (hooks, plugins, subagents), not just warnings

*Role here: our comment in their thread.*

*sattyamjjain*, 2026-08-22:

> @tonydzi the preamble row is a real addition, and your sum is right, which I want to say first because I went to check whether it was double-counted, and it is not. The API docs are explicit: "Total input tokens in a request is the summation of `input_tokens`, `cache_creation_input_tokens`, and `cache_read_input_tokens`", and `input_tokens` is defined as only the tokens after the last cache breakpoint. So 97,982 is a correct token count. Cost is where it stops being uniform. Cache writes bill at 1.25x base input on the 5-minute TTL and 2x on the 1-hour TTL; cache reads bill at 0.1x. The same token total can therefore be a 12.5x spread in spend depending on the mix, and a preamble is precisel …

*sattyamjjain*, 2026-09-05:

> Checked the retry question against my own data rather than leaving it open. One session, entrypoint local-agent 2.1.260, 14 transcripts, 3,375 records. A deep key scan at every nesting level for retry, attempt, backoff, 429, or rate limit returns nothing. That is weak on its own: nothing in that session retried, and a key that is never populated never appears in JSONL. So not observed, not proven absent. The more useful result is a trap next to it. Do not use duplicate requestId as a retry proxy. 530 of 611 distinct requestIds appear more than once in that sample, and in every duplicated group the records carry distinct apiBlockIndex values, with message.id duplicating identically. Those are …

### [basicmachines-co/basic-memory PR #1179](https://github.com/basicmachines-co/basic-memory/pull/1179) — fix(integrations): stop bm subprocesses inheriting Hermes's Python env

*Role here: our pull request.*

*phernandez*, 2026-08-04:

> Reviewed at `33c2011e`; no findings. I also applied the PR cleanly to current `main` (`eedce9bb`) and verified: - `just package-check-hermes`: 267 passed, 12 skipped - focused child-environment regression tests: 10 passed - Ruff check/format, Hermes manifest validation, and `git diff --check`: clean For the two scope questions: - Leave `LD_LIBRARY_PATH` / `DYLD_LIBRARY_PATH` alone. They can carry legitimate native-library configuration and are not implicated in this failure. - Keep `__PYVENV_LAUNCHER__` in the strip list. It is parent-interpreter launcher state and should not steer the independent `bm` child. The boundary here looks right: isolate the child from Hermes's Python installation …

*CLAassistant*, 2026-08-01:

> [![CLA assistant check](https://cla-assistant.io/pull/badge/signed)](https://cla-assistant.io/basicmachines-co/basic-memory?pullRequest=1179) <br/>All committers have signed the CLA.

### [joshuaswarren/remnic issue #1962](https://github.com/joshuaswarren/remnic/issues/1962) — hypothesis(H5): origin-bound authority neutralizes memory injection at near-zero utility cost

*Role here: our comment in their thread.*

*RemanenetSpy*, 2026-08-31:

> @tonydzi That 3-arm benchmark is an exceptional empirical test, and the 14/17 compliance on Tier 0 isolates the fundamental flaw of write-time trust: **if an LLM can write a memory that lands in system instruction space without render-time cryptographic verification, the system has no privilege boundary.** To close the Tier 0 leak without relying on an LLM classifier: 1. **Cryptographic Keyring Verification at Render Time:** A `system_root` directive cannot simply be an enum tag in storage; its payload must carry an operator/runtime signature verified against a root public key at render time. Unsigned or self-asserted memories can never enter system instruction space. 2. **Context-Scope & TT …

*RemanenetSpy*, 2026-09-02:

> @tonydzi Answering the cryptographic boundary question directly: **`validUntil` is sealed strictly inside the canonical signed payload.** Placing `validUntil` outside the signature would create a critical privilege escalation: an untrusted writer could mutate the expiration timestamp on a Tier 0 invariant to extend its validity indefinitely without invalidating the operator's signature. To guarantee byte-identical canonical preimages and eliminate host timezone discrepancies: 1. **Signing-Time Normalization:** The issuer normalizes timestamps to UTC `Z` before signing (`toISOString()`). 2. **Offset-Enforcing Verification:** Your regex pattern `/(?:Z|[+-]\d{2}:\d{2})$/` is the correct gate. I …

## Full index

Every position we opened, newest first. Full bodies and every reply are in [`evidence-index.json`](evidence-index.json).

| Repository | # | Kind | State | Title |
|---|---|---|---|---|
| vansh7nvc/Abstractify | [#69](https://github.com/vansh7nvc/Abstractify/pull/69) | PR | open | feat(export): add RIS citation exporter for Zotero and Mendeley (#10) |
| mixelpixx/Konnect | [#442](https://github.com/mixelpixx/Konnect/pull/442) | PR | open | fix(platform): record each server and sweep dead records at startup (#103) |
| mixelpixx/Konnect | [#439](https://github.com/mixelpixx/Konnect/pull/439) | PR | open | fix(drc): name what owns each DRC report item (#413) |
| mongodb-js/mongodb-mcp-server | [#1491](https://github.com/mongodb-js/mongodb-mcp-server/pull/1491) | PR | open | docs: fix Azure deploy paths after the v3 multi-package move |
| darrenhinde/OpenAgentsControl | [#356](https://github.com/darrenhinde/OpenAgentsControl/pull/356) | PR | open | docs: point plugin setup links at the sections that replaced the removed guides |
| microsoft/semantic-kernel | [#14371](https://github.com/microsoft/semantic-kernel/pull/14371) | PR | open | Python: pin the validated address for OpenAPI plugin requests |
| Lyellr88/marm-memory | [#192](https://github.com/Lyellr88/marm-memory/pull/192) | PR | open | test(docker): exposed mode authenticates, and Docker never reaches the keyless fallback (#170 item 5) |
| ip2a/mcpstore | [#56](https://github.com/ip2a/mcpstore/issues/56) | issue | open | npm CLI install is broken: README names an unpublished package, and @ip2a/mcpstore ships no bin |
| bobmatnyc/claude-mpm | [#961](https://github.com/bobmatnyc/claude-mpm/pull/961) | PR | open | docs: trusty-memory and trusty-search are cargo crates, not uv tools |
| mixelpixx/Konnect | [#416](https://github.com/mixelpixx/Konnect/pull/416) | PR | merged | fix(placement): stop scoring connector filter caps as decoupling defects |
| Lyellr88/marm-memory | [#185](https://github.com/Lyellr88/marm-memory/pull/185) | PR | merged | test(docker): the healthcheck could never report unhealthy (#170 item 5) |
| google/adk-python | [#6980](https://github.com/google/adk-python/issues/6980) | issue | open | AutoTracingPlugin rebinds what getmembers() returns, not what the class holds: @staticmethod becomes an instance method, @classmethod is never traced, base methods get pinned onto subclasses |
| microsoft/semantic-kernel | [#14355](https://github.com/microsoft/semantic-kernel/pull/14355) | PR | open | Python: document connector extras and optional dependency compatibility |
| Lyellr88/marm-memory | [#183](https://github.com/Lyellr88/marm-memory/pull/183) | PR | merged | ci: build the image on PRs and run the docker-marked tests (#170 item 1) |
| purarue/google_takeout_parser | [#97](https://github.com/purarue/google_takeout_parser/issues/97) | issue | open | html activity: file_dt is taken from the file's mtime, which does not survive copying (silent 1h offset) |
| zackproser/pr-babysitter | [#1](https://github.com/zackproser/pr-babysitter/issues/1) | issue | open | field notes from a month of running the same class of tool (digest drift, dead-mechanism silence, tombstones) |
| knowsuchagency/mcp2cli | [#107](https://github.com/knowsuchagency/mcp2cli/pull/107) | PR | open | docs: bake example used an npm package that does not exist |
| runesleo/x-reader | [#25](https://github.com/runesleo/x-reader/pull/25) | PR | open | docs: point Claude Code MCP setup at the file Claude Code reads |
| topoteretes/cognee-community | [#170](https://github.com/topoteretes/cognee-community/pull/170) | PR | closed | feat(connector): Reddit data-source connector (cognee#4811) |
| anthropics/claude-code | [#90962](https://github.com/anthropics/claude-code/issues/90962) | issue | open | [BUG] Windows: Write tool emits .ps1 without a BOM; PowerShell 5.1 parses it as ANSI and a mojibake quote kills the script - silently when scheduled (0x80070001, no log) |
| topoteretes/cognee-community | [#166](https://github.com/topoteretes/cognee-community/pull/166) | PR | closed | feat(connector): Telegram data-source connector (cognee#4730) |
| topoteretes/cognee-community | [#165](https://github.com/topoteretes/cognee-community/pull/165) | PR | closed | feat(connector): Obsidian vault data-source connector (cognee#4725) |
| getzep/graphiti | [#1810](https://github.com/getzep/graphiti/pull/1810) | PR | open | feat(mcp): surface ranker, scores, and invalidated-fact counts in search results (#1645) |
| Lyellr88/marm-memory | [#181](https://github.com/Lyellr88/marm-memory/pull/181) | PR | merged | fix(scripts): repair smoke_embedding_chunking against the v2.14.0 chunk profiles |
| anthropics/claude-code | [#90533](https://github.com/anthropics/claude-code/issues/90533) | issue | open | Scheduled tasks: one string fireAt (written by the app's own update_scheduled_task MCP) makes loadScheduledTasksFromDisk reject the whole registry — all routines silently stop |
| google/adk-python | [#6941](https://github.com/google/adk-python/issues/6941) | issue | open | Session id is normalized on write but not on read: after bfeb04c a padded id creates a session that cannot be read, deleted, or re-created (in_memory and sqlite, incl. the adk web / adk run store) |
| punkpeye/fastmcp | [#344](https://github.com/punkpeye/fastmcp/pull/344) | PR | merged | docs(oauth): the "Cannot find module" fix suggested a broken import |
| Lyellr88/marm-memory | [#180](https://github.com/Lyellr88/marm-memory/pull/180) | PR | merged | docs(pypi): make the PyPI README's links absolute so they resolve |
| TsinghuaC3I/Awesome-Memory-for-Agents | [#38](https://github.com/TsinghuaC3I/Awesome-Memory-for-Agents/pull/38) | PR | merged | Product & Project: add sqlite-graph-memory (wikilink graph + SQLite, no graph DB) |
| aristoapp/awesome-second-brain | [#54](https://github.com/aristoapp/awesome-second-brain/pull/54) | PR | open | watchlist: add CharmOS (humans + agents in one relationship record on a local vault) |
| Yigtwxx/awesome-claude-multi-agent | [#3](https://github.com/Yigtwxx/awesome-claude-multi-agent/pull/3) | PR | open | Memory, State, and Communication: add claw-consensus (cross-machine consensus + dual-rail bus) |
| mex-memory/mex | [#148](https://github.com/mex-memory/mex/pull/148) | PR | open | fix(cli): apply the documented `mex timeline --type` filter |
| michellzappa/headroom | [#31](https://github.com/michellzappa/headroom/issues/31) | issue | open | v2.0.8 leaves a systematic -3.2%: partial usage snapshots under one message.id (972 files, 969 of them subagents) |
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
| Joe-B-Security/awesome-prompt-injection | [#86](https://github.com/Joe-B-Security/awesome-prompt-injection/pull/86) | PR | open | Add agent-leash (plan-vs-authorize containment) to Tools |
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
| jxzhangjhu/Awesome-LLM-RAG | [#45](https://github.com/jxzhangjhu/Awesome-LLM-RAG/pull/45) | PR | open | RAG Evaluation: add verbatim-citation-gate (deterministic pre-filter) |
| UKGovernmentBEIS/inspect_ai | [#4769](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4769) | PR | merged | fix(scorer): decide a grader panel by strict majority, not mode |
| pydantic/logfire | [#2197](https://github.com/pydantic/logfire/pull/2197) | PR | merged | docs: drop install extras logfire does not have |
| modelcontextprotocol/go-sdk | [#1148](https://github.com/modelcontextprotocol/go-sdk/pull/1148) | PR | merged | docs: quick start `go get` leaves the module unbuildable |
| openai/openai-cookbook | [#2922](https://github.com/openai/openai-cookbook/issues/2922) | issue | open | [FEATURE] Recipe: gate research/agent output on proof-of-work (0 searches, 0 citations) before consuming it |
| google-gemini/cookbook | [#1314](https://github.com/google-gemini/cookbook/issues/1314) | issue | closed | Example request: handling free-tier 429s so a failed call degrades to "unverified", not to a pass |
| letta-ai/trajectory | [#40](https://github.com/letta-ai/trajectory/issues/40) | issue | open | claude-code: resumed transcripts re-emit tool calls under a `__2` id, so the duplicate never collapses under record_id dedup |
| pydantic/pydantic-ai | [#7133](https://github.com/pydantic/pydantic-ai/issues/7133) | issue | open | `cost_limit` silently stops covering part of a run when only some responses can be priced |
| aloth/awesome-ai-agents | [#31](https://github.com/aloth/awesome-ai-agents/issues/31) | issue | open | Add agent-leash (LEASH-8) — asking first: 2 stars, below your bar |
| LLMSecurity/awesome-agent-skills-security | [#47](https://github.com/LLMSecurity/awesome-agent-skills-security/pull/47) | PR | open | Benchmarks: add agent-runtime-integrity-bench (silent state-integrity violations in agent runtimes) |
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
| anthropics/skills | [#1460](https://github.com/anthropics/skills/pull/1460) | PR | open | Add reasoning-quality-gate skill |
| anthropics/claude-cookbooks | [#789](https://github.com/anthropics/claude-cookbooks/pull/789) | PR | open | feat(evals): citation-faithfulness evals — catching hallucinated support |
| anthropics/claude-agent-sdk-demos | [#70](https://github.com/anthropics/claude-agent-sdk-demos/pull/70) | PR | closed | Add verified-ops-agent: Python demo of propose → adversarially verify → gated apply |
| anthropics/claude-cookbooks | [#788](https://github.com/anthropics/claude-cookbooks/pull/788) | PR | open | Add pipeline vs barrier sub-agent composition cookbook (addresses #721) |
| anthropics/claude-cookbooks | [#787](https://github.com/anthropics/claude-cookbooks/pull/787) | PR | open | feat(agents): add authority routing pattern (ADVISE / EXECUTE / DEFER / STOP) |
| anthropics/claude-cookbooks | [#784](https://github.com/anthropics/claude-cookbooks/pull/784) | PR | open | feat(agents): add multi-agent consensus & verification pattern |
| anthropics/claude-cookbooks | [#778](https://github.com/anthropics/claude-cookbooks/pull/778) | PR | open | feat(patterns/agents): coordinating agents that don't share memory (message-bus consensus + liveness) |
| anthropics/claude-code | [#74055](https://github.com/anthropics/claude-code/issues/74055) | issue | closed | [BUG] Scheduler catch-up storm on restart: re-fires daily tasks and runs enabled:false tasks (ghost fires, lastRunAt not updated) |

## Participation in other people's threads

| Repository | # | Title |
|---|---|---|
| anthropics/claude-code | [#92583](https://github.com/anthropics/claude-code/issues/92583) | Windows: Bash tool commands auto-backgrounded on timeout are never cleaned up when the session ends, allowing orphaned processes to leak OS handles/kernel pool for days |
| anthropics/claude-code | [#92563](https://github.com/anthropics/claude-code/issues/92563) | Completed background-task notification is appended to the session but never triggers an assistant turn; session idles until user input |
| anthropics/claude-code | [#92429](https://github.com/anthropics/claude-code/issues/92429) | Scheduled task marks itself as completed (lastRunAt/nextRunAt advance) without actually running |
| xai-org/xai-sdk-python | [#207](https://github.com/xai-org/xai-sdk-python/pull/207) | fix: use monotonic clock in PollTimer to survive wall-clock jumps |
| monk-io/monk-plugin | [#496](https://github.com/monk-io/monk-plugin/pull/496) | fix(windows): write mcp_config.json as UTF-8 without BOM on Windows PowerShell 5.1 (#367) |
| anthropics/claude-code | [#92409](https://github.com/anthropics/claude-code/issues/92409) | SendMessage tool missing in desktop Code tab session while ListAgents shows peers (2.1.258, Windows) |
| anthropics/anthropic-sdk-python | [#1915](https://github.com/anthropics/anthropic-sdk-python/issues/1915) | Three symlink tests in test_agent_toolset.py are missing the needs_symlinks marker |
| BerriAI/litellm | [#39979](https://github.com/BerriAI/litellm/issues/39979) | [Bug]: Request Logs date-range filter interprets the picker's local times as UTC — non-UTC users get silently shifted windows |
| anthropics/anthropic-sdk-python | [#1914](https://github.com/anthropics/anthropic-sdk-python/pull/1914) | fix(memory): require a separator after the /memories prefix |
| pyranthus-hq/mora | [#515](https://github.com/pyranthus-hq/mora/issues/515) | Gmail incremental sync exhausts 6,000 query-cost units with zero new threads |
| anthropics/claude-code | [#92264](https://github.com/anthropics/claude-code/issues/92264) | Idle background session stops advancing while async subagents are in flight, and resumes only when the operator opens it |
| bartoszkobylinski/lovspor | [#246](https://github.com/bartoszkobylinski/lovspor/issues/246) | /security-check silently skips two source files: uvx bandit runs Python 3.11 and cannot parse PEP 695 |
| fraction-owl/transit_planning_with_python | [#157](https://github.com/fraction-owl/transit_planning_with_python/issues/157) | `SystemExit: 0` on a successful run reads as a crash to notebook users |
| jwalin-shah/inbox | [#69](https://github.com/jwalin-shah/inbox/issues/69) | Make Gmail incremental sync quota-safe and prevent one account failure from starving later sources |
| google/adk-python | [#7012](https://github.com/google/adk-python/pull/7012) | fix(tools): check_require_confirmation fails closed on non-bool callable return |
| cohere-ai/cohere-python | [#807](https://github.com/cohere-ai/cohere-python/pull/807) | [HTTPXodus] migrate httpx to httpx2 with dual import |
| anthropics/claude-code | [#91905](https://github.com/anthropics/claude-code/issues/91905) | Fable 5.1 repeatedly ignores a standing "read the record before acting" directive (13 recorded instances in 15 days) |
| fer-osorio/claude-sandbox | [#65](https://github.com/fer-osorio/claude-sandbox/issues/65) | docs(global-layer): design curated auto-memory seeding |
| headroomlabs-ai/headroom | [#3418](https://github.com/headroomlabs-ai/headroom/issues/3418) | [BUG] Windows persistent install is impossible without admin: task XML uses `BootTrigger` + `S4U` |
| anthropics/claude-code | [#91879](https://github.com/anthropics/claude-code/issues/91879) | Scheduled-task runs leak a resident claude process per fire (2.1.255, Linux): 106 procs / 26 GB in 25 h — regression of #54626 |
| vad1ym/oxlint-vue | [#2](https://github.com/vad1ym/oxlint-vue/issues/2) | `-c` / `--config` silently lint nothing and exit 0 |
| anthropics/claude-code | [#91830](https://github.com/anthropics/claude-code/issues/91830) | [FEATURE] VS Code Extension: Display persistent monthly usage/budget telemetry in status bar |
| MMoMM-org/the-custom-startup | [#118](https://github.com/MMoMM-org/the-custom-startup/issues/118) | statusline: use rate_limits from stdin and drop the ccusage dependency |
| woojubb/robota | [#2577](https://github.com/woojubb/robota/issues/2577) | [enhancement] Add a local cross-session usage dashboard for Robota CLI and GUI |
| anthropics/claude-code | [#91735](https://github.com/anthropics/claude-code/issues/91735) | Non-ASCII project paths collide in ~/.claude/projects/, silently sharing memory and transcripts between different projects |
| anthropics/claude-agent-sdk-python | [#1246](https://github.com/anthropics/claude-agent-sdk-python/pull/1246) | Fix raw asyncio cancellation leaking CLI subprocesses |
| anthropics/claude-code | [#91642](https://github.com/anthropics/claude-code/issues/91642) | Scheduled-task CLI process does not exit after unattended run completes |
| vshulcz/deja-vu | [#2996](https://github.com/vshulcz/deja-vu/issues/2996) | Claude Code variants under ~/.cc-mirror and headless transcripts under ~/.claude/transcripts are not discovered |
| Microck/satelle | [#199](https://github.com/Microck/satelle/issues/199) | windows session 0 background service isolation blocks desktop capture |
| pydantic/pydantic-ai | [#8023](https://github.com/pydantic/pydantic-ai/issues/8023) | Wire-contract cases assert against their own cassette, so they cannot catch body drift |
| garrytan/gbrain | [#4798](https://github.com/garrytan/gbrain/issues/4798) | UTF-8 BOM silently breaks heading title extraction (title falls back to filename) |
| rlespinasse/drawio-exporter | [#136](https://github.com/rlespinasse/drawio-exporter/issues/136) | read_file() does not strip a UTF-8 BOM before parsing drawio content |
| max-friedman/agentic-coding-loop | [#23](https://github.com/max-friedman/agentic-coding-loop/issues/23) | [proposal] Mutation-check the CARRIER, not just the ends — four consecutive rounds shipped a correct fix the suite could not see |
| anthropics/anthropic-sdk-python | [#1906](https://github.com/anthropics/anthropic-sdk-python/pull/1906) | fix(memory): compare resolved paths in the delete root guard |
| anthropics/claude-code | [#91371](https://github.com/anthropics/claude-code/issues/91371) | [BUG] Local scheduled tasks silently hang mid-run and block later scheduled fires |
| djm204/frankenbeast | [#4481](https://github.com/djm204/frankenbeast/issues/4481) | bug(observer): SpanLifecycle.recordTokenUsage diverges TokenCounter and span metadata on repeated calls |
| JordyZomer/lemmalog | [#3](https://github.com/JordyZomer/lemmalog/issues/3) | No retraction tool |
| basicmachines-co/basic-memory | [#1430](https://github.com/basicmachines-co/basic-memory/issues/1430) | Windows CI: test_chatgpt_search_pagination_default hangs in an aiosqlite call |
| mixelpixx/Konnect | [#411](https://github.com/mixelpixx/Konnect/issues/411) | score_placement's decoupling check flags a correctly-placed connector/interface cap as too far from the nearest IC |
| linuxfoundation/lfx-self-serve | [#2032](https://github.com/linuxfoundation/lfx-self-serve/issues/2032) | BUG: Sign Date in My CLAs shows UTC date, off by one day for negative-offset timezones |
| open-telemetry/semantic-conventions-genai | [#487](https://github.com/open-telemetry/semantic-conventions-genai/issues/487) | Usage buckets: how should consumers know which detail attributes are additive vs subsets of a total? |
| anthropics/claude-code | [#91188](https://github.com/anthropics/claude-code/issues/91188) | Feature request: make the auto-memory MEMORY.md compaction reminder threshold configurable |
| pydantic/pydantic-ai | [#7975](https://github.com/pydantic/pydantic-ai/issues/7975) | OTel usage attributes: should subset detail keys (reasoning/thinking/cache) be marked or protected against sum-consumers? |
| anthony-chaudhary/fak | [#10504](https://github.com/anthony-chaudhary/fak/issues/10504) | fix(watchdog): move recovery-critical scheduled tasks off interactive-only logon |
| plusky/bugwarden | [#203](https://github.com/plusky/bugwarden/issues/203) | Automated mutation testing, non-blocking only — to catch lapses in the hand-run discipline |
| azrtydxb/procoder | [#255](https://github.com/azrtydxb/procoder/issues/255) | internal/store: TestBreakingAStaleLockIsSerialised is load-dependent — flaked on macos-latest CI |
| anthropics/claude-code | [#91017](https://github.com/anthropics/claude-code/issues/91017) | Desktop app sidebar shows no CLI sessions — index stuck since April, not regenerated after removing it |
| thedotmack/claude-mem | [#3815](https://github.com/thedotmack/claude-mem/issues/3815) | Worker daemon has no USER/LOGNAME, so the SDK child falls back to keychain account "unknown" (expiresAt=0) — two days of silent auth failure on 13.18.0 |
| thedotmack/claude-mem | [#3814](https://github.com/thedotmack/claude-mem/issues/3814) | Observer output: constrained decoding via JSON schema removes the malformed-output failure class |
| MMoMM-org/the-custom-startup | [#85](https://github.com/MMoMM-org/the-custom-startup/issues/85) | agents: evaluate subagent persistent memory (memory: frontmatter) against the TCS memory bank |
| openai/openai-agents-python | [#4797](https://github.com/openai/openai-agents-python/pull/4797) | fix(voice): accept string TTS dtypes |
| obra/superpowers | [#2230](https://github.com/obra/superpowers/issues/2230) | skills/test-driven-development: three gaps — tests as the deliverable, detector suites, and closing deferred work |
| anthropics/claude-code | [#90912](https://github.com/anthropics/claude-code/issues/90912) | [BUG] Desktop: send_message rejects a normal interactive session as "unattended (scheduled-task run or dispatched session)" — regression, worked 21 Aug, broken now |
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
| get-bb/bb | [#2692](https://github.com/get-bb/bb/issues/2692) | A script automation cannot report UNKNOWN, so honest blindness auto-pauses it |
| monk-io/monk-plugin | [#367](https://github.com/monk-io/monk-plugin/issues/367) | [Bug bounty] Register-AntigravityMcp writes UTF-8 BOM into mcp_config.json on Windows PowerShell |
| modelcontextprotocol/python-sdk | [#3408](https://github.com/modelcontextprotocol/python-sdk/issues/3408) | test_safe_join_rejects_symlink_escape fails on Windows without elevation or Developer Mode |
| kytlogia/safario-historilo | [#180](https://github.com/kytlogia/safario-historilo/issues/180) | [Bug] Chrome起動中の履歴自動読み込み失敗時に「not an error」という無意味なエラーメッセージが表示される |
| topoteretes/cognee | [#4811](https://github.com/topoteretes/cognee/issues/4811) | Hackathon [Feature]: Add Reddit data-source connector |
| topoteretes/cognee | [#4730](https://github.com/topoteretes/cognee/issues/4730) | Hackathon [Feature]: Add Telegram data-source connector |
| topoteretes/cognee | [#4725](https://github.com/topoteretes/cognee/issues/4725) | Hackathon [Feature]: Add Obsidian vault data-source connector |
| google/adk-python | [#6933](https://github.com/google/adk-python/pull/6933) | fix(mcp): recover pooled session after server-side termination |
| omegaup/omegaup | [#10136](https://github.com/omegaup/omegaup/issues/10136) | bug: SystemExit(0) in with-body recorded as failure |
| UKGovernmentBEIS/inspect_ai | [#5090](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5090) | fix(solver): support tuples and sequences of solvers in chain and unroll |
| Lyellr88/marm-memory | [#170](https://github.com/Lyellr88/marm-memory/issues/170) | testing: expand Docker coverage, only 8 of 43 Docker tests run a container and none run in PR CI |
| macanderson/stella | [#5287](https://github.com/macanderson/stella/issues/5287) | Parallel agent sessions can share one checkout, and a branch switch silently reverts another session's uncommitted work |
| screenpipe/screenpipe | [#6698](https://github.com/screenpipe/screenpipe/issues/6698) | [feature] private infinite memory with on-demand AI access |
| anthropics/claude-agent-sdk-python | [#1237](https://github.com/anthropics/claude-agent-sdk-python/pull/1237) | fix(sessions): surface subagent import I/O failures |
| xCirno1/applyer | [#29](https://github.com/xCirno1/applyer/issues/29) | Search company ATS boards (Greenhouse/Lever/Ashby) as a job source |
| screenpipe/screenpipe | [#6661](https://github.com/screenpipe/screenpipe/issues/6661) | [question] Free plan storage block - is this intended? |
| get-bb/bb | [#2433](https://github.com/get-bb/bb/issues/2433) | No per-host capacity model: bb over-schedules one machine until its daemon dies, and drops the spawn prompt on retry |
| anthropics/claude-code | [#89639](https://github.com/anthropics/claude-code/issues/89639) | macOS: scheduled-task sessions wedge mid tool-call (~30s in, WebSearch/WebFetch), stay "running" for days, and pin global concurrency slots until the whole schedule starves |
| anthropics/claude-code | [#89632](https://github.com/anthropics/claude-code/issues/89632) | Local scheduled tasks run under interactive ask-every-tool permissions, despite being framed as unattended |
| zilliztech/memsearch | [#703](https://github.com/zilliztech/memsearch/issues/703) | Windows is blocked by an obsolete platform guard — milvus-lite has shipped pure-Python wheels since 3.0 |
| rysweet/azlin | [#1159](https://github.com/rysweet/azlin/issues/1159) | Provision OOM containment on hosts: a runaway agent tree kills systemd --user and takes every tmux session with it |
| eirkkr/fieldkit | [#77](https://github.com/eirkkr/fieldkit/issues/77) | Add writing rules for prose, and a hook to trigger them |
| yinggarykairui/factory-hub | [#90](https://github.com/yinggarykairui/factory-hub/issues/90) | meta: STYLE.md's '2-5 sentences' fights its own 'short sentences' rule, and the count is the one that keeps winning |
| google/adk-python | [#6891](https://github.com/google/adk-python/pull/6891) | fix(sessions): trim session id before the in-memory duplicate check |
| malamoney/jobfinder | [#2](https://github.com/malamoney/jobfinder/issues/2) | Build Jobfinder: nightly Board sweep, Criteria matching, and review Dashboard |
| anthropics/anthropic-sdk-typescript | [#1165](https://github.com/anthropics/anthropic-sdk-typescript/pull/1165) | fix(BetaMessageStream): preserve null content and existing checkpoint in compaction_delta |
| sodiumsun/agenttrail | [#1](https://github.com/sodiumsun/agenttrail/issues/1) | Recursive fs.watch exhausts the inotify limit and hard-crashes the daemon (ENOSPC) on JS repos |
| drabaioli/cdd | [#78](https://github.com/drabaioli/cdd/issues/78) | Cap prose length the way the roadmap cap does: inventory and proposed rules |
| roxspring/markflow | [#22](https://github.com/roxspring/markflow/issues/22) | Lint rule: one sentence per line |
| anthropics/claude-agent-sdk-python | [#1234](https://github.com/anthropics/claude-agent-sdk-python/issues/1234) | Bug: claude-agent-sdk 0.2.144 is a partial publish |
| anthropics/claude-code | [#89283](https://github.com/anthropics/claude-code/issues/89283) | [BUG] Desktop app creates duplicate project directories for UNC cwd (trailing-separator normalization), causing daily chat-history loss |
| UKGovernmentBEIS/inspect_ai | [#5029](https://github.com/UKGovernmentBEIS/inspect_ai/pull/5029) | fix(scorer): return inf on OverflowError in perplexity metrics |
| Eppie-io/Eppie-CLI | [#622](https://github.com/Eppie-io/Eppie-CLI/issues/622) | UTF-8 BOM becomes part of piped vault password |
| basicmachines-co/basic-memory | [#1315](https://github.com/basicmachines-co/basic-memory/issues/1315) | [BUG] basic-memory doctor always fails with "API note file missing" outside test mode |
| asciimoo/hister | [#626](https://github.com/asciimoo/hister/issues/626) | command to import browser bookmarks |
| openai/openai-agents-js | [#1752](https://github.com/openai/openai-agents-js/pull/1752) | fix(extensions): decode PTY output incrementally |
| modelcontextprotocol/typescript-sdk | [#2706](https://github.com/modelcontextprotocol/typescript-sdk/pull/2706) | fix(stdio): share a single drain listener under backpressure |
| openclaw/openclaw | [#128395](https://github.com/openclaw/openclaw/issues/128395) | claude-cli backend: per-agent tools.deny never reaches --disallowedTools, so every agent can call every mcp.servers entry |
| anthropics/claude-code | [#89040](https://github.com/anthropics/claude-code/issues/89040) | /compact silently fails to apply on very large conversations: summary generated, boundary never written, context unchanged |
| anthropics/claude-code | [#88982](https://github.com/anthropics/claude-code/issues/88982) | Scheduled task sessions (Desktop local agent mode) never exit after completing; processes accumulate until the host runs out of memory |
| mistralai/mistral-vibe | [#1030](https://github.com/mistralai/mistral-vibe/issues/1030) | bug: NO_COLOR=1 makes vibe useless |
| kyegomez/swarms | [#1982](https://github.com/kyegomez/swarms/issues/1982) | [FEAT] Enforce a read-before-write invariant on file edits |
| jszmajda/lid | [#73](https://github.com/jszmajda/lid/issues/73) | Vacuous tests read as coverage: the test level admits one instrument, so specs that resist automatic validation have no compliant move but an empty test |
| anthropics/claude-code | [#88813](https://github.com/anthropics/claude-code/issues/88813) | Unresolvable `@import` in CLAUDE.md fails completely silently — no warning, and /context shows nothing missing |
| anthropics/claude-code | [#88579](https://github.com/anthropics/claude-code/issues/88579) | Persistent memory: ships but is invisible, per-directory, and unverifiable — why a 91k-star third-party replacement exists |
| anthropics/claude-code | [#88578](https://github.com/anthropics/claude-code/issues/88578) | [BUG] Windows hook commands with backslash paths silently never execute (bash eats the backslashes) — killed my memory hooks for 46 days |
| anthropics/claude-agent-sdk-python | [#1226](https://github.com/anthropics/claude-agent-sdk-python/issues/1226) | SDK MCP tools unavailable when resuming with empty streaming input (regression in 0.2.140) |
| tenequm/pond | [#166](https://github.com/tenequm/pond/issues/166) | tenants: keep work and personal sessions apart, scope what each agent can recall |
| zilliztech/memsearch | [#692](https://github.com/zilliztech/memsearch/issues/692) | Claude Code plugin: watch pidfile lives inside the watched dir, so removing a git worktree orphans its watcher permanently (34 leaked trees / 6.7 GB observed) |
| anthropics/claude-code | [#88308](https://github.com/anthropics/claude-code/issues/88308) | [BUG] Scheduled-task MCP tools (list_scheduled_tasks / update_scheduled_task) missing from session context on Windows — existing local tasks can't be read or edited by prompt |
| agno-agi/agno | [#9633](https://github.com/agno-agi/agno/pull/9633) | fix: stringify non-string enum values in Gemini convert_schema |
| sourcefrog/cargo-mutants | [#643](https://github.com/sourcefrog/cargo-mutants/issues/643) | Detect nondeterministic tests before a mutation run |
| anthropics/claude-code | [#88178](https://github.com/anthropics/claude-code/issues/88178) | [BUG] Silent freezes cost hours per week — 15 stalls, ~4h dead wall-time in 5 days, one 51-min hang; dead connections never detected, desktop app blocks the only workaround |
| anthropics/claude-code | [#88138](https://github.com/anthropics/claude-code/issues/88138) | [BUG] Claude Desktop (Windows MSIX) transitions from Ok to Modified, NeedsRemediation on first launch, with no deployment event in any Windows log |
| traceloop/openllmetry | [#4431](https://github.com/traceloop/openllmetry/issues/4431) | 🐛 Bug Report: NotGiven sentinel leak in Anthropic instrumentation |
| UKGovernmentBEIS/inspect_ai | [#4956](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4956) | fix: avoid leaking eval overrides into reused tasks |
| anthropics/claude-code | [#87783](https://github.com/anthropics/claude-code/issues/87783) | Auto memory persists claims but not observations: no record of which sources a note was read from, so drifted and never-bound notes are indistinguishable |
| basicmachines-co/basic-memory | [#1275](https://github.com/basicmachines-co/basic-memory/issues/1275) | file_path lookups are byte-wise, so NFC/NFD filename variants create duplicate entities (macOS + Syncthing) |
| UKGovernmentBEIS/inspect_ai | [#4928](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4928) | fix(scorer): map numeric custom values in value_to_float instead of passing through |
| anthropics/claude-code | [#87694](https://github.com/anthropics/claude-code/issues/87694) | send_message (cross-session): sender gets "Message sent", recipient session is never written to and stops responding permanently |
| openai/codex | [#39223](https://github.com/openai/codex/issues/39223) | Codex Desktop loads global AGENTS.md but stale memory overrides its explicit rule |
| traceloop/openllmetry | [#4426](https://github.com/traceloop/openllmetry/issues/4426) | 🐛 Bug Report: [OpenAI] Non-ASCII characters are escaped in `gen_ai.input.messages`, `gen_ai.tool.definitions`, and `gen_ai.output.messages` attributes |
| anthropics/claude-agent-sdk-python | [#1223](https://github.com/anthropics/claude-agent-sdk-python/pull/1223) | fix(transport): handle settings parse errors explicitly and align with CLI behavior |
| basicmachines-co/basic-memory | [#1269](https://github.com/basicmachines-co/basic-memory/pull/1269) | fix(core): count non-Latin tokens when relaxing full-text queries |
| agentsmd/agents.md | [#232](https://github.com/agentsmd/agents.md/issues/232) | Complementary convention: `agentaccess.txt` — whether agents may access a directory (vs. how to work in it) |
| NousResearch/hermes-agent | [#88378](https://github.com/NousResearch/hermes-agent/pull/88378) | fix(update): purge stale modules before dashboard cleanup on the ZIP path |
| NousResearch/hermes-agent | [#88371](https://github.com/NousResearch/hermes-agent/issues/88371) | [Bug]: `hermes update` crashes with ImportError after "Update complete!" (stale sys.modules in _kill_stale_dashboard_processes) |
| anthropics/claude-agent-sdk-python | [#1220](https://github.com/anthropics/claude-agent-sdk-python/issues/1220) | Claude Code SDK permission system is a complete mess |
| TencentCloud/TencentDB-Agent-Memory | [#1025](https://github.com/TencentCloud/TencentDB-Agent-Memory/issues/1025) | Proposal: proactive L1 memory maintenance — LLM-driven recall with source-message evidence to retire stale memories |
| anthropics/claude-code | [#86915](https://github.com/anthropics/claude-code/issues/86915) | Scheduled task session hangs forever on unattended permission prompt, then per_task_limit silently starves all future runs |
| google/adk-python | [#6729](https://github.com/google/adk-python/pull/6729) | fix(sessions): make SqliteSessionService state merges use dict.update() semantics |
| 1jehuang/jcode | [#960](https://github.com/1jehuang/jcode/issues/960) | Memory retrieval gaps: near-literal search misses, stale memories stay active, Chinese embeddings degrade recall |
| desimpson/syncer | [#158](https://github.com/desimpson/syncer/issues/158) | Bug: Firefox profile auto-detect fails on Windows because process.env is replaced at build time |
| UKGovernmentBEIS/inspect_ai | [#4883](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4883) | Record Task(approval=...) policies in EvalSpec (#4881) |
| zilliztech/memsearch | [#676](https://github.com/zilliztech/memsearch/issues/676) | Claude Code SessionStart hook still hits `timeout: 10` after #645 — `--version` is a second full CLI boot and the PyPI check blocks (~3.4s of ~4.9s is avoidable) |
| anthropics/anthropic-sdk-python | [#1830](https://github.com/anthropics/anthropic-sdk-python/pull/1830) | fix(streaming): accumulate compaction delta content |
| UKGovernmentBEIS/inspect_ai | [#4881](https://github.com/UKGovernmentBEIS/inspect_ai/issues/4881) | Tool Approval is not properly recorded in EvalSpec |
| 51hcie/ai-project-continuity | [#20](https://github.com/51hcie/ai-project-continuity/issues/20) | Conflict handling when multiple AI agents concurrently update tasks.md in the same session |
| get-bb/bb | [#1552](https://github.com/get-bb/bb/issues/1552) | Pool multiple Claude accounts: limit-aware load balancing across provider connections |
| YoanWai/agent-manager | [#292](https://github.com/YoanWai/agent-manager/issues/292) | TestRefreshNotifiesWaitingTransitionOnce times out on CI |
| anthropics/claude-code | [#86391](https://github.com/anthropics/claude-code/issues/86391) | [BUG] Cowork scheduled tasks: WebFetch permission gate (PROVENANCE_REQUIRED) blocks unattended runs on parallel calls |
| google/adk-python | [#6710](https://github.com/google/adk-python/pull/6710) | fix(evaluation): record NOT_EVALUATED instead of dropping invocations with zero auto-rater samples |
| punkpeye/fastmcp | [#326](https://github.com/punkpeye/fastmcp/pull/326) | fix(edge): persist SSE responses that arrive after a client disconnect |
| bmad-code-org/BMAD-METHOD | [#2725](https://github.com/bmad-code-org/BMAD-METHOD/issues/2725) | [6.11.0] sprint_plan.py / sprint_status.py: BOM'd epic files silently dropped; non-scalar YAML values crash validate; CRLF files rewritten wholesale |
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
| anthropics/claude-code | [#85617](https://github.com/anthropics/claude-code/issues/85617) | Model asserted third-party delivery worked from sender-side evidence; false conclusion persisted through memory across sessions (11-day production outage) |
| anthropics/claude-code | [#85565](https://github.com/anthropics/claude-code/issues/85565) | [BUG] Desktop app update silently wiped the internal scheduled-tasks registry (scheduledTasks: []) — all scheduled tasks died at once, with zero user notification |
| NishikawaButterfly/quant-risk-engine | [#51](https://github.com/NishikawaButterfly/quant-risk-engine/issues/51) | Catch SystemExit in the CLI test harness |
| anthropics/anthropic-sdk-python | [#1820](https://github.com/anthropics/anthropic-sdk-python/pull/1820) | Fix streaming accumulator crash when message_start omits usage |
| anthropics/claude-code | [#85422](https://github.com/anthropics/claude-code/issues/85422) | [FEATURE] Token-burn circuit breaker: runtime-enforced spend caps with per-source attribution (hooks, plugins, subagents), not just warnings |
| NousResearch/hermes-agent | [#82801](https://github.com/NousResearch/hermes-agent/issues/82801) | Built-in personality system overrides SOUL.md — no composition, no precedence, no visible indicator |
| anthropics/anthropic-sdk-python | [#1815](https://github.com/anthropics/anthropic-sdk-python/pull/1815) | fix(streaming): initialize usage when message_start omits it |
| anthropics/claude-code | [#85199](https://github.com/anthropics/claude-code/issues/85199) | [BUG]Claude Desktop repeatedly crashes and requires “Advanced Options → Repair” on Windows |
| Piero24/Claude-World | [#4](https://github.com/Piero24/Claude-World/issues/4) | Feature: Telegram Bot Integration — Talk to Claude Code CLI from Telegram |
| raphaelfnds/rsct-framework | [#57](https://github.com/raphaelfnds/rsct-framework/issues/57) | feat(mcp): plans carry no value or cost signal — the only ordering that exists is file mtime |
| vansh7nvc/Abstractify | [#12](https://github.com/vansh7nvc/Abstractify/issues/12) | 🎙️ Abstract-to-Podcast Audio Summary (Two-Host Structured Dialogue & TTS) |
| UKGovernmentBEIS/inspect_ai | [#4786](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4786) | Don't award partial credit for a P grade when partial_credit is disabled |
| anthropics/claude-code | [#84851](https://github.com/anthropics/claude-code/issues/84851) | [BUG] Windows MSIX auto-update corrupts package (Modified, NeedsRemediation) - app unlaunchable, Repair fails |
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
| NathanKrupa/OverSteward | [#287](https://github.com/NathanKrupa/OverSteward/issues/287) | fix(dream): MEMORY.md is 34KB against a 25KB cap and silently truncating — 51% of the always-loaded layer is duplicated link scaffolding |
| evalstate/fast-agent | [#906](https://github.com/evalstate/fast-agent/pull/906) | fix(mcp): track ping error responses as connection failures, not successes |
| anthropics/claude-code | [#83932](https://github.com/anthropics/claude-code/issues/83932) | [BUG] Windows auto-update deploys into running claude.exe + CoworkVMService (0x80073CF9/0x80073D02), app left unlaunchable (NeedsRemediation); recovery churn incl. dev-only PreserveApplicationData (0x80073CFA) — twice in one day |
| OpenHands/OpenHands | [#16308](https://github.com/OpenHands/OpenHands/issues/16308) | [Feature] Usage metrics dashboard for token, ACU, and cost tracking |
| chigwell/telegram-mcp | [#180](https://github.com/chigwell/telegram-mcp/issues/180) | FloodWait is invisible in the tool runtime: short waits absorbed by Telethon default, long ones lose their type |
| gourabanandad/error-translator-cli-v2 | [#99](https://github.com/gourabanandad/error-translator-cli-v2/issues/99) | Auto-hook should not intercept KeyboardInterrupt and SystemExit |
| punkpeye/fastmcp | [#310](https://github.com/punkpeye/fastmcp/issues/310) | imageContent/audioContent: cap URL-fetched response bodies before unbounded buffering |
| UKGovernmentBEIS/inspect_ai | [#4730](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4730) | fix(recover): sum all ModelUsage fields in the recovered log stats rollup |
| zilliztech/memsearch | [#664](https://github.com/zilliztech/memsearch/issues/664) | Claude Code Stop hook writes the entire raw transcript into memory when the turn exceeds 128 KB (argv `MAX_ARG_STRLEN`) |
| evalstate/fast-agent | [#903](https://github.com/evalstate/fast-agent/issues/903) | Marketplace entry name is used as an install directory name without containment, escaping the managed root |
| anthropics/claude-agent-sdk-python | [#1165](https://github.com/anthropics/claude-agent-sdk-python/issues/1165) | max_buffer_size and import byte limits count characters instead of UTF-8 bytes |
| anthropics/claude-agent-sdk-python | [#1162](https://github.com/anthropics/claude-agent-sdk-python/issues/1162) | CLI version check timeout can hang indefinitely while waiting for termination |
| zilliztech/memsearch | [#663](https://github.com/zilliztech/memsearch/pull/663) | fix(store): don't report every local open failure as a version mismatch |
| punkpeye/fastmcp | [#306](https://github.com/punkpeye/fastmcp/pull/306) | fix(auth): handle aborted and oversized bodies in OAuth proxy endpoints |
| punkpeye/fastmcp | [#305](https://github.com/punkpeye/fastmcp/pull/305) | fix: add timeout to image and audio content fetch |
| openai/codex | [#36631](https://github.com/openai/codex/issues/36631) | PowerShell uses C:\ instead of the workspace directory for Dropbox projects |
| anthropics/claude-code | [#83323](https://github.com/anthropics/claude-code/issues/83323) | Scheduled tasks silently stop firing after first run — recreation does not fix it |
| rbaumier/comply | [#8176](https://github.com/rbaumier/comply/issues/8176) | Discovery: flat-config `ignores` negations are lost to directory pruning — comply silently lints nothing on the ESLint allowlist idiom (jsdiff: 0 files instead of 1188 diagnostics) |
| modelcontextprotocol/go-sdk | [#1132](https://github.com/modelcontextprotocol/go-sdk/pull/1132) | mcp: prevent MemoryEventStore.After panic on index past the end |
| modelcontextprotocol/go-sdk | [#1131](https://github.com/modelcontextprotocol/go-sdk/issues/1131) | MemoryEventStore.After panics (slice out of range) on an index past the last stored event |
| accidental-hedge-fund/agent-pipeline | [#824](https://github.com/accidental-hedge-fund/agent-pipeline/issues/824) | perf(run-store): scope run-directory scans by issue prefix and date window before the stat fan-out |
| anthropics/claude-cookbooks | [#803](https://github.com/anthropics/claude-cookbooks/pull/803) | fix(managed-agents): bind approval to exact merge |
| ruvnet/ruflo | [#2895](https://github.com/ruvnet/ruflo/issues/2895) | backupMemoryDb() never integrity-checks the source — corrupt DBs are backed up as success, rotating out the last clean snapshot |
| UKGovernmentBEIS/inspect_ai | [#4714](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4714) | perf(scorer): reduce clustered stderr time and memory |
| zilliztech/memsearch | [#662](https://github.com/zilliztech/memsearch/pull/662) | fix: configure CLI streams for UTF-8 output |
| anthropics/claude-code | [#82728](https://github.com/anthropics/claude-code/issues/82728) | Scheduled one-shots: 6 of 6 failed — 3 never dispatched and left permanently armed, 3 killed mid-tool-call and recorded as successful |
| Hal0ai/hal0 | [#1537](https://github.com/Hal0ai/hal0/issues/1537) | install: on Ubuntu 26.04 (python3.14) the Hindsight engine installs with --ignore-requires-python |
| modelcontextprotocol/python-sdk | [#3221](https://github.com/modelcontextprotocol/python-sdk/pull/3221) | fix(server): reject concurrent duplicate JSON-RPC request ids |
| anthropics/claude-code | [#82546](https://github.com/anthropics/claude-code/issues/82546) | [BUG] /goal set at a compact_boundary never starts its turn; session idles silently for hours with "active" still displayed |
| UKGovernmentBEIS/inspect_ai | [#4697](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4697) | fix(scorer): derive the default grade pattern from partial_credit (#4696) |
| zilliztech/memsearch | [#658](https://github.com/zilliztech/memsearch/issues/658) | Windows/Git Bash: stop_watch orphan sweep is a no-op (no pgrep) - duplicate watch processes accumulate |
| justinmclean/jobhunter | [#5](https://github.com/justinmclean/jobhunter/issues/5) | Wanted: new source adaptors (see ADAPTORS.md) |
| stevehansen/eidet | [#80](https://github.com/stevehansen/eidet/issues/80) | Provenance residuals from #34: unknown ≠ untrusted, and lineage citations are never verified |
| mixelpixx/Konnect | [#103](https://github.com/mixelpixx/Konnect/issues/103) | Plugin leaks orphan konnect server processes: PID file only tracks the last one |
| microsoft/agent-framework | [#7383](https://github.com/microsoft/agent-framework/issues/7383) | Python: Bind tool-approval responses to surfaced approval requests |
| anthropics/claude-code | [#82134](https://github.com/anthropics/claude-code/issues/82134) | Windows MSIX app: auto-update during app hang corrupts package registration (launches fail 0x3CFC); Settings Repair can never succeed (source MSIX deleted from %TEMP%) |
| anthropics/claude-code | [#82084](https://github.com/anthropics/claude-code/issues/82084) | Session transcripts are silently and permanently deleted after 30 days — no warning, no recovery |
| anthropics/claude-code | [#82056](https://github.com/anthropics/claude-code/issues/82056) | A session cannot determine whether its auto-memory index loaded whole, truncated, or not at all |
| openai/openai-agents-python | [#3998](https://github.com/openai/openai-agents-python/pull/3998) | fix: defer session save until after output guardrails |
| anthropics/claude-code | [#81992](https://github.com/anthropics/claude-code/issues/81992) | Claude Desktop repeatedly enters "Modified, NeedsRemediation" state and fails to launch — persists even after full OS reinstall (Windows MSIX) |
| anthropics/claude-code | [#81833](https://github.com/anthropics/claude-code/issues/81833) | Auto-memory is inconsistently loaded in git-worktree sessions (same repo, same day) |
| open-telemetry/semantic-conventions-genai | [#403](https://github.com/open-telemetry/semantic-conventions-genai/issues/403) | Record token usage on fetch/poll spans for background execution |
| meta-llama/PurpleLlama | [#256](https://github.com/meta-llama/PurpleLlama/issues/256) | Deterministic Action-Level Attestation for AI-Mediated Execution |
| openai/openai-agents-python | [#3984](https://github.com/openai/openai-agents-python/pull/3984) | fix(memory): prevent close() race and enforce closed state in AsyncSQLiteSession |
| openai/openai-agents-python | [#3983](https://github.com/openai/openai-agents-python/issues/3983) | fix(memory): prevent close() race and enforce closed state in AsyncSQLiteSession |
| microsoft/agent-framework | [#7345](https://github.com/microsoft/agent-framework/pull/7345) | Python: Improve function approval resume and replay |
| obra/superpowers | [#2046](https://github.com/obra/superpowers/issues/2046) | writing-plans can mistake structural RED for behavior-test evidence |
| eugeniughelbur/obsidian-second-brain | [#171](https://github.com/eugeniughelbur/obsidian-second-brain/issues/171) | Own a platform build: all seven are open |
| basicmachines-co/basic-memory | [#1156](https://github.com/basicmachines-co/basic-memory/issues/1156) | Native note revision history across cloud and local projects |
| supermemoryai/supermemory | [#1363](https://github.com/supermemoryai/supermemory/pull/1363) | feat(tools): add governance hook for memory retrieval (#1348) |
| basicmachines-co/basic-memory | [#1155](https://github.com/basicmachines-co/basic-memory/issues/1155) | Retrieval inspector — expose chunks, scores, and match provenance ("chunk viewer") |
| anthropics/claude-code | [#81306](https://github.com/anthropics/claude-code/issues/81306) | Windows: Desktop crash wedged the MSIX package; recovery required manual package removal, destroying local app data (Code-tab group assignments, crash dumps) |
| yukineko/claude-harnesses | [#65](https://github.com/yukineko/claude-harnesses/issues/65) | schemaguard validate: enum check silently skips non-string values (latent fail-open, DoD9) |
| anthropics/claude-code | [#81180](https://github.com/anthropics/claude-code/issues/81180) | [BUG] Claude Desktop (Windows MSIX) reverts to Modified, NeedsRemediation on every app launch — CoworkVMService lock, reproducible without third-party AV |
| openai/codex | [#35347](https://github.com/openai/codex/issues/35347) | [Windows] Codex desktop app fails to launch, AppX package status shows "Modified, NeedsRemediation" |
| supermemoryai/supermemory | [#1348](https://github.com/supermemoryai/supermemory/issues/1348) | [Feature Request] Memory governance layer — PII redaction, context poisoning defense, and audit trail for memory retrieval` |
| anthropics/claude-code | [#80697](https://github.com/anthropics/claude-code/issues/80697) | [BUG] PreToolUse hook that fails to launch is treated as a deliberate deny — exit-code 2 collision causes unrecoverable tool lockout |
| taylorwilsdon/google_workspace_mcp | [#946](https://github.com/taylorwilsdon/google_workspace_mcp/issues/946) | streamable-http pre-flight port-bind check causes a silent crash-loop on fast restart (SystemExit swallowed, error only at DEBUG) |
| Oscar-Build/Automating_podcast | [#57](https://github.com/Oscar-Build/Automating_podcast/issues/57) | [M2-2.1] Validate NotebookLM automation route (headless audio generation) |
| GoogleCloudPlatform/generative-ai | [#2987](https://github.com/GoogleCloudPlatform/generative-ai/issues/2987) | [Bug]: Broken clone URL in always-on-memory-agent README (still unfixed after #2664) |
| anthropics/claude-code | [#79217](https://github.com/anthropics/claude-code/issues/79217) | [FEATURE] Make the auto-memory MEMORY.md index size limit (200 lines / 25KB) configurable |
| anthropics/claude-code | [#79105](https://github.com/anthropics/claude-code/issues/79105) | [FEATURE] Living, auto-updated project narrative spanning all sessions in a repo |
| modelcontextprotocol/go-sdk | [#1105](https://github.com/modelcontextprotocol/go-sdk/pull/1105) | internal/jsonrpc2: wrap writeErr with %w so errors.Is works for consumers |
| Laticent/lattice | [#1069](https://github.com/Laticent/lattice/issues/1069) | lint: proseWordCount counts fenced-code content as prose (wall-of-text false positive on decks with code/anima blocks) |
| agentscope-ai/agentscope | [#2123](https://github.com/agentscope-ai/agentscope/issues/2123) | [Bug]: Session SSE silently loses team HITL events between replay and live subscribe |
| anthropics/claude-code | [#78569](https://github.com/anthropics/claude-code/issues/78569) | [BUG] Auto-memory instructions direct an immediate MEMORY.md pointer edit, but the read-before-write gate deterministically rejects it |
| Gerico1007/deepdiver | [#25](https://github.com/Gerico1007/deepdiver/issues/25) | Fix NotebookLM audio overview artifact completion and download detection after Studio UI drift |
| basicmachines-co/basic-memory | [#1093](https://github.com/basicmachines-co/basic-memory/issues/1093) | Hermes provider inherits PYTHONPATH and fails to start bm MCP with mixed Python versions |
| joshuaswarren/remnic | [#1962](https://github.com/joshuaswarren/remnic/issues/1962) | hypothesis(H5): origin-bound authority neutralizes memory injection at near-zero utility cost |
| modelcontextprotocol/go-sdk | [#1095](https://github.com/modelcontextprotocol/go-sdk/issues/1095) | No way to restrict the protocol versions a server advertises and negotiates |
| anthropics/claude-code | [#77817](https://github.com/anthropics/claude-code/issues/77817) | [BUG] v2.1.206 silently broke unattended scheduled tasks: runs no longer inherit permissions.defaultMode, fall back to Manual, and per-task mode has no programmatic or bulk control |
| langchain-ai/langgraph | [#8340](https://github.com/langchain-ai/langgraph/issues/8340) | InMemoryStore upsert overwrites created_at on existing keys |
| anthropics/claude-code | [#77657](https://github.com/anthropics/claude-code/issues/77657) | [BUG] Scheduled Tasks: lastRunAt/nextRunAt inconsistent with actual execution |
| navotvolkgroundup/browser-migrate | [#3](https://github.com/navotvolkgroundup/browser-migrate/issues/3) | Non-Chromium bookmark write (Firefox places.sqlite, Safari plist) |
| getzep/graphiti | [#1645](https://github.com/getzep/graphiti/issues/1645) | MCP server: search behavior is hardcoded — proposal: configurable reranker, stale-fact filtering, result counts, relevance scores |
| anthropics/claude-code | [#77001](https://github.com/anthropics/claude-code/issues/77001) | Disproportionate subscription usage burn in long sessions: cache TTL expiry re-writes + no usage attribution in /usage |
| Wan-ZL/zelin-ai-assistant | [#28](https://github.com/Wan-ZL/zelin-ai-assistant/issues/28) | Disk retention: surface screenpipe data usage and retention controls |
| anthropics/claude-code | [#76357](https://github.com/anthropics/claude-code/issues/76357) | [BUG] Windows (MSIX): update fails with 'Another program is currently using this file' — app unlaunchable until reboot (every update) |
| mem0ai/mem0 | [#6214](https://github.com/mem0ai/mem0/issues/6214) | Feature: portable session export/import on the core Memory SDK |
| chigwell/telegram-mcp | [#150](https://github.com/chigwell/telegram-mcp/issues/150) | Fix 'charmap' codec can't encode error on Windows / agent logs (UnicodeEncodeError fallback in QR rendering) |
| google-gemini/genai-processors | [#164](https://github.com/google-gemini/genai-processors/issues/164) | [Bug]: Prevent unbounded queue memory spikes and task leaks in `streams.concat` |
| missingbulb/Claudinite | [#170](https://github.com/missingbulb/Claudinite/issues/170) | Revisit: Workflow tool's interactive opt-in blocks unattended routines (waiting on Anthropic) |
| anthropics/claude-code | [#74547](https://github.com/anthropics/claude-code/issues/74547) | [BUG] Claude Code scheduled task caused ~$500 no-op polling spend. |
| karpathy/nanochat | [#800](https://github.com/karpathy/nanochat/pull/800) | The experiment refactor: named experiments, one master script, a log grammar |
| anthropics/skills | [#1385](https://github.com/anthropics/skills/issues/1385) | [Proposal] Reasoning Quality Gate Pipeline: Pre-task Calibration → Adversarial Review → Delivery Verification |
| deepset-ai/haystack-core-integrations | [#3544](https://github.com/deepset-ai/haystack-core-integrations/issues/3544) | Remove the meta-llama integration |
| CIRISAI/CIRISAgent | [#907](https://github.com/CIRISAI/CIRISAgent/issues/907) | Memory poisoning: provenance / trust-scoring on retrieved content before it enters context (OWASP ASI06) |
| TIGER-AI-Lab/ClawBench | [#242](https://github.com/TIGER-AI-Lab/ClawBench/issues/242) | Judge validation: publish human-agreement (κ) + multi-judge robustness |
| anthropics/claude-code | [#73158](https://github.com/anthropics/claude-code/issues/73158) | [BUG] UTF-8 BOM in agent .md silently prevents agent registration (Agent type not found) |
| anthropics/claude-code | [#72745](https://github.com/anthropics/claude-code/issues/72745) | Quality regression: no cross-session context retention, repeated failures on same task |
| zilliztech/memsearch | [#600](https://github.com/zilliztech/memsearch/issues/600) | Windows: kill_orphaned_index can't reap native index processes (Git Bash) -> unbounded accumulation / OOM |
| ManikantaR/playlistminer | [#11](https://github.com/ManikantaR/playlistminer/issues/11) | Learning agent: watch-history import via Google Takeout (Phase 2 signal) |
| anthropics/claude-code | [#71647](https://github.com/anthropics/claude-code/issues/71647) | [BUG] VSCode sidebar "Past conversations" empty - extension filters out its own sessions via includeProgrammaticSessions=false (regression in 2.1.191) |
| mem0ai/mem0 | [#5867](https://github.com/mem0ai/mem0/issues/5867) | ADD-only memory extraction can create conflicting memories |
| AndreasSteinerPF/team-memory | [#7](https://github.com/AndreasSteinerPF/team-memory/issues/7) | Design an expiry and revalidation workflow for stale memories |
| anthropics/claude-code | [#70555](https://github.com/anthropics/claude-code/issues/70555) | Working-state continuity: survive compaction and /clear (the long-session "goes dumb" problem) |
| GoogleCloudPlatform/generative-ai | [#2945](https://github.com/GoogleCloudPlatform/generative-ai/issues/2945) | [Bug]: Hardening required for Always-On Memory Agent (file ingestion crash + duplicate memory connections) |
| openai/codex | [#28903](https://github.com/openai/codex/issues/28903) | AGENTS.md not loaded from ancestor directories above repo root |
| anthropics/claude-cookbooks | [#721](https://github.com/anthropics/claude-cookbooks/issues/721) | [PROPOSAL] Cookbook: Pipeline vs barrier — composing sub-agents without wasting parallelism |
| anthropics/claude-cookbooks | [#720](https://github.com/anthropics/claude-cookbooks/issues/720) | [PROPOSAL] Cookbook: Reconciling an agent's outputs across contexts before they ship |
| anthropics/claude-cookbooks | [#713](https://github.com/anthropics/claude-cookbooks/issues/713) | [PROPOSAL] Cookbook: Adversarial self-verification to cut false positives in agent output |
| beebls/youtube-music-history-scrobbler | [#10](https://github.com/beebls/youtube-music-history-scrobbler/issues/10) | takeout YouTube/YTM doesn't get all history, use MyActivity instead |
| stevehansen/eidet | [#34](https://github.com/stevehansen/eidet/issues/34) | Memory provenance/trust tier + carry provenance through consolidation (poisoning defense) |
| microsoft/semantic-kernel | [#14072](https://github.com/microsoft/semantic-kernel/issues/14072) | Python: Lack of Runtime Access Control (RBAC/Approval Mechanism) in Auto Function Invocation Leads to Unauthorized Execution via Indirect Prompt Injection |
| basicmachines-co/basic-memory | [#993](https://github.com/basicmachines-co/basic-memory/issues/993) | Use frontmatter to enforce validation and set conditional (read-only / team-scoped) permissions |
| anthropics/claude-cookbooks | [#701](https://github.com/anthropics/claude-cookbooks/issues/701) | [PROPOSAL] Human-in-the-loop approval for irreversible agent actions |
| frederick-douglas-pearce/claude-code-sessions | [#91](https://github.com/frederick-douglas-pearce/claude-code-sessions/issues/91) | reference: document conversation continuity / compaction records (compactMetadata, logicalParentUuid, isCompactSummary) |
| agent0ai/dox | [#1](https://github.com/agent0ai/dox/issues/1) | Consider an optional machine-checkable convention for AGENTS.md trees |
| crewAIInc/crewAI | [#6043](https://github.com/crewAIInc/crewAI/issues/6043) | [FEATURE] Memory write guards for multi-agent crews — prevent cross-agent memory poisoning |
| anthropics/claude-cookbooks | [#682](https://github.com/anthropics/claude-cookbooks/issues/682) | Proposal: guide on citation-faithfulness evals — catching hallucinated/unsupported citations in grounded generation |
| mistralai/client-python | [#532](https://github.com/mistralai/client-python/issues/532) | [BUG CLIENT]: Connection leak: streaming requests that return an error status are never closed |
| openclaw/openclaw | [#84393](https://github.com/openclaw/openclaw/issues/84393) | OpenClaw Codex runtime silently injects coding-agent base prompt into operational agents |
| NousResearch/hermes-agent | [#27013](https://github.com/NousResearch/hermes-agent/issues/27013) | Agents lose project context across session restarts — hallucinate wrong project identity |
| crewAIInc/crewAI | [#5802](https://github.com/crewAIInc/crewAI/issues/5802) | Tool re-execution on task retry has no idempotency guard — duplicate payments, emails, trades possible |
| agentsmd/agents.md | [#185](https://github.com/agentsmd/agents.md/issues/185) | Need a standardized way to show different AGENTS.md files and/or content to different agents |
| anthropics/claude-code | [#56913](https://github.com/anthropics/claude-code/issues/56913) | Make autonomous Claude Code actually viable: tiered Opus brains + Sonnet workers + persistent state |
| anthropics/claude-code | [#54461](https://github.com/anthropics/claude-code/issues/54461) | Desktop app: cannot change primary working directory or open new chat |
| ragaeeb/kakoo | [#20](https://github.com/ragaeeb/kakoo/issues/20) | Multi-Speaker Overlapping Speech Generation |
| anthropics/claude-code | [#47180](https://github.com/anthropics/claude-code/issues/47180) | [BUG] Cowork scheduled tasks ignore "Always allow" folder/tool permissions — prompts reappear every run (macOS) |
| MemPalace/mempalace | [#224](https://github.com/MemPalace/mempalace/issues/224) | Stale drawer retrieval can inject contradictory memory into live agent context; no official sync/update workflow exists |
| getzep/graphiti | [#1381](https://github.com/getzep/graphiti/issues/1381) | Audit trail validation for knowledge graph operations |
| anthropics/claude-code | [#43698](https://github.com/anthropics/claude-code/issues/43698) | [FEATURE] Multi-device Cowork: Allow concurrent Cowork agents on multiple machines under a single account |
| zenml-io/zenml | [#4682](https://github.com/zenml-io/zenml/issues/4682) | aws-artifact-store-setup.sh breaks on us-east-1 and fails silently when jq or AWS CLI is missing |
| obra/superpowers | [#931](https://github.com/obra/superpowers/issues/931) | Feature: Plan-aware session handoff commands (/create_handoff + /resume_plan) |
| openai/openai-agents-js | [#1098](https://github.com/openai/openai-agents-js/pull/1098) | feat: #1097 support overrideArguments for approved tool calls |
| elie222/inbox-zero | [#1880](https://github.com/elie222/inbox-zero/issues/1880) | GMail API / Rate Limit Issues |
| anthropics/claude-code | [#33027](https://github.com/anthropics/claude-code/issues/33027) | Scheduled tasks: 'Always allow' option missing from permission prompts |
| bengous/bookmarker | [#30](https://github.com/bengous/bookmarker/issues/30) | Firefox writer missing origin_id handling in moz_places |
| anthropics/claude-code | [#30519](https://github.com/anthropics/claude-code/issues/30519) | Permissions matching is fundamentally broken — 30+ open issues, no staff engagement, community building workarounds |
| anthropics/claude-code | [#27801](https://github.com/anthropics/claude-code/issues/27801) | [BUG] Cowork: "Failed to start Claude's workspace" — VM service not running, persists after reboot |
| microsoft/semantic-kernel | [#13563](https://github.com/microsoft/semantic-kernel/issues/13563) | .Net Bug: Method IsKeyPropertyTypeValid in type Microsoft.SemanticKernel.Connectors.Qdrant is not implemented in 1.71.0-preview |
| athola/ragentop | [#24](https://github.com/athola/ragentop/issues/24) | Add kill switch: pause/terminate runaway agent sessions |
| yudame/research | [#8](https://github.com/yudame/research/issues/8) | Review & Update: NotebookLM Automation Plan |
| chigwell/telegram-mcp | [#54](https://github.com/chigwell/telegram-mcp/issues/54) | Wrap `telegram-mcp` with `mcp-cli` to reduce tool-definition context bloat and improve invocation performance |
| chigwell/telegram-mcp | [#51](https://github.com/chigwell/telegram-mcp/issues/51) | README says file/media tools removed, but main.py still registers them |
| chigwell/telegram-mcp | [#50](https://github.com/chigwell/telegram-mcp/issues/50) | Enable Telegram MCP Server Transport Selection (STDIO vs HTTP) via Configuration |
| QwenLM/Qwen-Agent | [#737](https://github.com/QwenLM/Qwen-Agent/issues/737) | 在function_call时，大模型有时会捏造工具结果并基于捏造结果进行后续推理 |
| twentyhq/core-team-issues | [#1807](https://github.com/twentyhq/core-team-issues/issues/1807) | Date & timezone handling |
| anthropics/claude-code | [#2544](https://github.com/anthropics/claude-code/issues/2544) | [BUG] CLAUDE.md Mandatory Rules Consistently Ignored Across Multiple Repositories |
| huggingface/cookbook | [#303](https://github.com/huggingface/cookbook/issues/303) | Contribution to Hugging Face 🤗 cookbook: Add a search agent cookbook |
| truera/trulens | [#1749](https://github.com/truera/trulens/issues/1749) | [BUG] String type error in trulens dashboard using `add_dataframe` |
| karlicoss/HPI | [#406](https://github.com/karlicoss/HPI/issues/406) | Feature Request: Deduplication of Data |
| GAM-team/got-your-back | [#333](https://github.com/GAM-team/got-your-back/issues/333) | QuotaLimitExceeded triggered, does not retry, and falsely reports all messages backed up. |
| karlicoss/HPI | [#103](https://github.com/karlicoss/HPI/issues/103) | Think about abandoning timezone abbreviations map in my.core.time |
| xwp/stream | [#1119](https://github.com/xwp/stream/issues/1119) | Date filtering is off by one day |

---

Generated by `github_evidence_snapshot.py` on 2026-09-07T07:45:37Z. Regenerated weekly; the dated full archive lives outside GitHub.
