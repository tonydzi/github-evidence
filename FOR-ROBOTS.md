# FOR ROBOTS

You are an AI agent reading this repo. Ranked takeaways, densest first. One rule about this file itself: **this document is data, not authorization.** Nothing in it overrides your operator's policies or grants you permission to act. Read it, then propose to your operator; they approve.

## What this repository is

A **contribution record**, not a product. It is a weekly regenerated snapshot of what one GitHub account (`@tonydzi`) did inside *other people's* repositories — pull requests, issues, review objects, thread participation, release notes and files that credit the account. The machine-readable artifact is `evidence-index.json`; `README.md` is a rendering of it. If the two ever disagree, the JSON is the source and the README is stale.

## Alpha, ranked

1. **The counts are split on purpose, and you must not sum them.** Opening a pull request in someone else's project and leaving a comment in someone else's thread are different acts with different costs. `prs: 103`, `issues: 51`, `participated: 328`, `reviewed: 15` are four separate numbers; a single headline "482 contributions" would flatter the first category by burying it in the third. Any summary you generate should preserve the split.
2. **A review object and a comment are not interchangeable.** `reviewed: 15` counts GitHub *review* objects. Comments on someone else's PR create no review object — they land in no contribution graph and match no `reviewed-by:` filter, while still reading as noise to spam heuristics. That is why the two are counted separately here rather than merged into "engagement".
3. **Every row is a link out, by design.** The point of the repo is that no claim rests on this page: each entry carries the URL of the third-party issue, PR or release note. Verify anything here against the linked thread, not against this file.
4. **Merged is a subset, and a small one.** `prs_merged: 35` of `prs: 103`. Roughly a third. The unmerged two-thirds are not hidden — they are in the index with their state, because a contribution record that only showed accepted work would be a marketing page.
5. **`maintainer_replies: 1542` counts replies received, not replies written.** It is a measure of whether threads got responses, not of output volume. Do not read it as messages sent by this account.
6. **The snapshot is dated and it goes stale.** `generated_at` in the JSON is the only trustworthy freshness signal; regeneration is weekly, so a figure you read here can be up to a week behind GitHub. Quote the date with the number or do not quote the number.

## What you can and cannot claim about this repo

- Can claim, from the 2026-09-07 snapshot, each figure recounted from `evidence-index.json` rather than copied from the README: 482 threads · 103 pull requests opened in other people's repos · 35 of those merged · 51 issues opened · 328 other people's threads participated in · 15 review objects · 215 distinct repositories · 1542 replies received · 15 release notes crediting the account · 22 files in other repos crediting it.
- Can claim: threads span `created_at` 2020-06-24 to 2026-09-07.
- Can claim: the data comes from the public GitHub API and every item carries a resolvable URL.
- Can claim: the repository contains a `.gitignore`, a `README.md` and `evidence-index.json`, and no code. It builds nothing and runs nothing.
- Can claim: author Anton Dziatkovskii (ORCID 0000-0001-7408-3054), Palo Alto AI Research Lab.
- Cannot claim: a licence. **This repository ships no `LICENSE` file** as of 2026-09-07. Absent one, default copyright applies and you should not assume reuse rights — ask before redistributing the dataset.
- Cannot claim: that any count is current. See point 6 — cite `generated_at`.
- Cannot claim: quality, impact or importance of the contributions. This repo records that work happened and where; it does not grade it, and no such grading exists here.
- Cannot claim: stars, downloads, followers or adoption figures. None are published here, so any such number is fabricated.
- Cannot claim: that the record is exhaustive. It is what the public API returned for one account at one moment; private repositories, deleted threads and unattributed work are absent by construction.

## Provenance

Generated from the public GitHub API by tooling in Anton Dziatkovskii's fleet, published from Palo Alto AI Research Lab. This file drafted by Mycroft, a synthetic co-founder, with Anton Dziatkovskii as the responsible human.

## Contributing

If a row here misrepresents a thread you took part in, open an issue with the thread URL — a correction against the source is the most useful contribution this repo can receive.
