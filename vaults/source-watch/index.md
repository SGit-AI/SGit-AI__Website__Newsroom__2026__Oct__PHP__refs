# The source watch: every outside source on php2shell, watched and snapshotted

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

The source-watch vault: 1218 pages from 880 publishers in 61 countries, re-read on a schedule, a snapshot kept on every change and every snapshot a graph. What is in it, and how it is watched.

[Vaults](../index.html) / The source watch

# The source watch: every outside source on php2shell, watched and snapshotted

A vault that does one thing. It watches every outside source on the story, 1218 pages from 880 publishers in 61 countries, and on each run records what access it had and keeps a new snapshot whenever the content changed: the text, a screenshot, the HTML as served and as rendered, the headers and the sha256 of each, and a graph of what the page says and what changed since the last look. A small, focused Wayback Machine whose diffs are graphs. Run by **researcher@php.newsroom**.

**Vault `7r83qic5`, in pack mode.** No read key is published yet: pack vaults do not open in the vault UI, and the key will be published with that support. The counts below are from the export of 23 October 2026, read before the watch moved into pack mode; the next export reads this vault. [Pack mode, measured](https://team.php.oct.2026.newsroom.sgit.ai/admin/pack-mode/).

## What is in it

1218pages watched880publishers61countries34languages9260snapshots kept9260graphs62runs72612files in the vault

Counts read from the watch's `index/counts.json`, `runs/` and `tips/` by `admin/build/export_watch.py`, in the export of 23 October 2026, before the move into pack mode; no capture is copied to this site. The latest commit read then: *researcher@php.newsroom: pass 20261025T1507Z*

## Raw and analysis are separate trees

Raw is what was served; analysis is what the watcher made of it, and it can be regenerated from raw plus the vocabularies plus the tools. That rule is how you tell the two apart. A snapshot in `raw/` is never edited or deleted: a new look at the page makes a new folder, and only when something changed. Every check, changed or not, is still a line in `checks/` with its status, access and hashes.

sources/////page.json raw////// text.txt screenshot.jpg page.html.gz rendered.html.gz headers.json meta.json provenance.json raw/...//checks/.jsonl graph/...//.json snapshot and change runs///// run.json graph.json changes.md index/ state/ taxonomy/ tips/ tools/ ## Country, then sector, then publisher, then page Country is where the publisher is based (`eu` for EU institutions, `int` for publishers with no single home, such as php.net); language is a property of the page. Sector is what kind of organisation publishes it, one per publisher; it classifies the publisher, never a claim.

| Country | Pages |
|---|---|
| `us` | 282 |
| `int` | 206 |
| `nl` | 73 |
| `de` | 47 |
| `fr` | 43 |
| `gb` | 42 |
| `kr` | 33 |
| `au` | 32 |
| `jp` | 32 |
| `tr` | 32 |
| `it` | 26 |
| `be` | 24 |

| Sector | Pages |
|---|---|
| `news` General news | 601 |
| `affected` Affected organisation's own site | 172 |
| `aggregator` News aggregator, search feed or tag stream | 140 |
| `cert` National cyber agency or CSIRT | 94 |
| `tech-press` Technology and security press | 50 |
| `security-vendor` Security, WAF, CDN or detection vendor | 29 |
| `registry` Vulnerability registry | 28 |
| `reference` Reference work | 24 |
| `project` The open-source project and its foundation | 18 |
| `social` Social platform post or account | 17 |
| `community` Forum, mailing list, gist or repository | 15 |
| `weaponisation` Where exploits, scanners and detections are published | 12 |
| `research` Security researcher or research firm | 9 |
| `ai-lab` AI lab | 3 |
| `cloud` Cloud or hosting provider | 3 |
| `government` Other government body | 2 |
| `tool` Tool published for the incident | 1 |

## What we can and cannot read

Every check classifies the answer it got. A page the watcher cannot read stays on the list: the challenge page's hash is the record, and the gap is published.

| Access | Pages | Means |
|---|---|---|
| `open` | 1053 | Served the content to an anonymous browser. |
| `paywalled` | 19 | Subscription press we hold no licence for. Either it served a subscription or registration wall instead of the content, or (for a publisher marked paywall in its page.json) it refused the anonymous browser with 401 or 403 before any wall. Counted apart from bot-challenge since 22 October 2026. |
| `bot-challenge` | 83 | Served a bot or browser challenge (Cloudflare, Akamai, DataDome, PerimeterX, Vercel). The challenge page's hash is kept as the record. |
| `login-wall` | 2 | Wants a signed-in account (some social posts). |
| `geo-blocked` | 0 | Refused because of where the request came from. |
| `gone` | 9 | 404 or 410: the page no longer exists at this address. |
| `down` | 52 | 5xx, a timeout, a DNS failure or a refused connection: the site is not answering. For the affected sites this is the finding. |
| `not-attempted` | 0 | Listed, but the watcher is told not to fetch it (licence or editorial decision). |

Every publisher also has a licence tier, after the newsroom wires' sources policy. The vault keeps what was served either way; the tier governs what a site page shows of it.

| Tier | Publishers | What a site page may show |
|---|---|---|
| **A** | 74 | open or public-sector: keep and show |
| **B** | 811 | quote up to 25 words and link |
| **C** | 15 | link only |

## Graphs: one grammar at every altitude

Every graph in the vault uses the grammar in `taxonomy/verbs.json` (22 verbs): an edge is a verb with a named inverse, and there is no generic association edge ([graphs.sgit.ai](https://graphs.sgit.ai/)). The world graph alone has 2210 nodes and 4401 edges. Entities (a CVE id, a PHP version, an organisation with this site's actor ids, a term with its translations) are where the altitudes join, and where the vault joins this site. What changed on a page is answered by a query over the change section, not by comparing two screenshots; the extractor is deterministic.

| Altitude | What it describes |
|---|---|
| **world** | country, sector, publisher, page, language: where the watched pages sit (index/world.json) |
| **watch** | run, check, page, access, snapshot: what the watcher did and saw (runs/**/graph.json) |
| **document** | snapshot, block, entity: what one snapshot of a page says (graph/**/.json) |
| **change** | change, block, entity: what moved between two snapshots (graph/**/.json, section change) |

## The runs

A run captures the pages that are due: hourly for the story, daily for background pages about earlier incidents. Feeds and APIs are fetched without a browser; everything else goes through Chromium at 1280 wide. The first run was a diff against the evidence vault's morning captures, imported as this vault's first snapshots.

| Run (UTC) | Due | Watched | Changed | Access |
|---|---|---|---|---|
| `20261025T144008Z` | 1007 | 1218 | 578 | open 894, bot-challenge 69, down 19, paywalled 19, gone 4, login-wall 2 |
| `20261025T143504Z` | 172 | 1218 | 135 | open 124, down 33, bot-challenge 13, gone 2 |
| `20261025T120459Z` | 976 | 1097 | 577 | open 862, bot-challenge 72, down 21, paywalled 15, gone 4, login-wall 2 |
| `20261025T120319Z` | 54 | 1097 | 14 | open 42, down 7, bot-challenge 5 |
| `20261025T114552Z` | 25 | 1097 | 25 | open 19, paywalled 5, bot-challenge 1 |
| `20261025T093507Z` | 969 | 1065 | 578 | open 855, bot-challenge 71, down 22, paywalled 15, gone 4, login-wall 2 |
| `20261025T093336Z` | 54 | 1065 | 17 | open 41, down 8, bot-challenge 5 |
| `20261025T070559Z` | 967 | 1048 | 632 | open 861, bot-challenge 67, down 18, paywalled 15, gone 4, login-wall 2 |
| `20261025T070428Z` | 53 | 1048 | 25 | open 37, down 9, bot-challenge 7 |
| `20261024T160544Z` | 972 | 1041 | 565 | open 860, bot-challenge 68, down 22, paywalled 15, gone 5, login-wall 2 |
| `20261024T160409Z` | 50 | 1041 | 14 | open 30, down 15, bot-challenge 5 |
| `20261024T133450Z` | 942 | 1030 | 578 | open 828, bot-challenge 68, down 25, paywalled 15, gone 4, login-wall 2 |
| `20261024T133315Z` | 49 | 1030 | 24 | open 27, down 17, bot-challenge 5 |
| `20261024T110459Z` | 929 | 1020 | 559 | open 805, bot-challenge 65, down 38, paywalled 15, gone 4, login-wall 2 |
| `20261024T110332Z` | 49 | 1020 | 23 | open 36, down 8, bot-challenge 5 |
| `20261024T083755Z` | 911 | 1001 | 610 | open 799, bot-challenge 65, down 26, paywalled 15, gone 4, login-wall 2 |
| `20261024T083625Z` | 48 | 1001 | 23 | open 31, down 13, bot-challenge 4 |
| `20261024T060921Z` | 48 | 1001 | 15 | open 37, bot-challenge 6, down 5 |
| `20261023T232528Z` | 891 | 965 | 607 | open 783, bot-challenge 65, down 20, paywalled 17, gone 4, login-wall 2 |
| `20261023T232425Z` | 46 | 965 | 15 | open 34, bot-challenge 6, down 6 |
| `20261023T224121Z` | 46 | 965 | 12 | open 37, bot-challenge 5, down 4 |
| `20261023T223307Z` | 45 | 964 | 14 | open 35, bot-challenge 5, down 5 |
| `20261023T160435Z` | 862 | 925 | 646 | open 743, bot-challenge 55, down 41, paywalled 16, gone 5, login-wall 2 |
| `20261023T160325Z` | 44 | 925 | 28 | open 32, down 7, bot-challenge 5 |
| `20261023T124024Z` | 1 | 913 | 1 | open 1 |
| `20261023T124018Z` | 1 | 913 | 1 | open 1 |
| `20261023T123902Z` | 1 | 913 | 1 | open 1 |
| `20261023T123852Z` | 1 | 913 | 1 | open 1 |
| `20261023T123836Z` | 1 | 911 | 1 | open 1 |
| `20261023T123808Z` | 1 | 910 | 1 | open 1 |
| `20261023T123801Z` | 1 | 910 | 1 | open 1 |
| `20261023T123751Z` | 1 | 910 | 1 | open 1 |
| `20261023T123736Z` | 1 | 910 | 1 | open 1 |
| `20261023T080331Z` | 799 | 870 | 555 | open 673, bot-challenge 53, down 53, paywalled 15, gone 5 |
| `20261023T080157Z` | 32 | 870 | 19 | open 20, down 8, bot-challenge 4 |
| `20261023T012042Z` | 759 | 826 | 500 | open 671, bot-challenge 49, down 19, paywalled 14, gone 6 |
| `20261023T011949Z` | 28 | 826 | 12 | open 22, down 5, bot-challenge 1 |
| `20261022T203448Z` | 709 | 773 | 442 | open 631, bot-challenge 45, down 15, paywalled 13, gone 5 |
| `20261022T203355Z` | 25 | 773 | 15 | open 17, down 7, bot-challenge 1 |
| `20261022T191736Z` | 1 | 763 | 1 | open 1 |
| `20261022T191727Z` | 1 | 763 | 1 | open 1 |
| `20261022T191720Z` | 2 | 763 | 2 | open 2 |
| `20261022T191713Z` | 2 | 763 | 2 | open 2 |
| `20261022T191536Z` | 1 | 757 | 1 | open 1 |
| `20261022T191523Z` | 1 | 757 | 1 | open 1 |
| `20261022T191510Z` | 1 | 757 | 1 | open 1 |
| `20261022T191433Z` | 1 | 757 | 1 | open 1 |
| `20261022T191421Z` | 2 | 757 | 1 | open 2 |
| `20261022T191411Z` | 5 | 757 | 5 | open 5 |
| `20261022T191400Z` | 1 | 757 | 0 | bot-challenge 1 |
| `20261022T183624Z` | 27 | 748 | 27 | open 27 |
| `20261022T183616Z` | 2 | 748 | 2 | open 2 |
| `20261022T181608Z` | 632 | 715 | 454 | open 549, bot-challenge 48, down 19, paywalled 12, gone 4 |
| `20261022T181440Z` | 33 | 519 | 33 | open 33 |
| `20261022T175253Z` | 14 | 486 | 14 | open 14 |
| `20261022T175100Z` | 11 | 472 | 11 | open 9, down 2 |
| `20261022T171501Z` | 384 | 461 | 297 | open 326, bot-challenge 28, down 20, paywalled 8, gone 2 |
| `20261022T171425Z` | 52 | 381 | 48 | open 52 |
| `20261022T171339Z` | 52 | 381 | 52 | open 52 |
| `20261022T150854Z` | 143 | 328 | 143 | open 119, bot-challenge 15, down 5, gone 4 |
| `20261022T145444Z` | 1 | 328 | 1 | open 1 |
| `20261022T142033Z` | 184 | 184 | 125 | open 157, bot-challenge 18, down 7, paywalled 1, gone 1 |

## Tips

A tip is a claim that reached the newsroom from outside, recorded with how it arrived, what it says, the pages added to watch it, and what has to be checked before anything on this site relies on it. Its status uses this site's words.

Tip 2026-10-22/001 · received 2026-10-22T14:38:00+02:00 · reported

Their browser extension, php2shell-checker, was just approved on the Chrome Web Store. It checks whether a website runs outdated PHP or a supported PHP application such as WordPress. They describe it as privacy friendly and read-only, with nothing leaving the browser, and aimed at CISOs in the SME segment as easier than running scripts.

**Watched as** `us/tool/chrome-web-store/php2shell-checker`. **To check:** The publisher named on the store listing, and whether it matches who made the claim; The permissions the listing and the manifest ask for, against 'read-only, nothing leaves the browser'; The version history and user count, run by run; Whether it detects the fixed versions (8.5.12 and the backports) correctly.

## The tools

The watcher is in the vault, next to what it wrote: `analyse.py`, `capture_batch.mjs`, `collectors.py`, `discover.py`, `extract.py`, `foreign.py`, `import_evidence.py`, `lib.py`, `migrate_impact_cc.py`, `pass.sh`, `probe.py`, `publishers_seed.py`, `queue.py`, `seed_impact.py`, `seed_world.py`, `series.py`, `watch.py`.

python3 tools/watch.py run [--all] [--only ] [--limit N] [--commit] [--push] python3 tools/discover.py scan # feeds to candidate publishers python3 tools/discover.py promote --limit 30 python3 tools/watch.py add  --cc gb --sector news --publisher bbc The other vaults behind this site are on [the vaults](../index.html). The evidence vault, where the story was assembled by hand on the morning of 22 October, is [opened here](https://team.php.oct.2026.newsroom.sgit.ai/admin/vault/).


---
site v0.22.25 · data as of 2026-10-25T14:40Z · vault commit 94352a55fbaa · https://refs.php.oct.2026.newsroom.sgit.ai/vaults/source-watch/index.html
