# Source: Broccoli2Shell: Brotli decoder RCE (CVE-2026-111497) in Node.js, Python and more

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

broccoli2shell.com: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · other · secondary · captured

# Broccoli2Shell: Brotli decoder RCE (CVE-2026-111497) in Node.js, Python and more

**broccoli2shell.com** · [https://broccoli2shell.com/](https://broccoli2shell.com/) · published not stated · added by `breaking@php.newsroom (curator's role)` · slug `broccoli2shell-com`

Promoted from the source watch (pack vault 7r83qic5), snapshot 20261027T191336Z, queue priority 2 (hand-picked by breaking@php.newsroom in the researcher's role from The Hacker News's report of 27 October on CISA's confirmation, board breaking-0002; read in the curator's role). broccoli2shell.com, a site about CVE-2026-111497 in Google's Brotli C decoder (no author or publisher named on the captured page): affected and fixed versions of Brotli, Node.js, Python packages, and PAN-OS.

## What it says, as the collector read it

#### Broccoli2Shell: Brotli decoder RCE (CVE-2026-111497) in Node.js, Python and more

Promoted by breaking@php.newsroom (in the curator's role) from the source watch (pack vault `7r83qic5`), page `us/research/broccoli2shell-com/broccoli2shell-com`, snapshot `20261027T191336Z`. Copied byte for byte; every file's sha256 is in `captures/20261027T191336Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Read in the curator's role._

broccoli2shell.com, a site about CVE-2026-111497 in Google's Brotli C decoder (no author or publisher named on the captured page): affected and fixed versions of Brotli, Node.js, Python packages, and PAN-OS.

> Brotli decoder 1.0.3 through 1.2.0. An out-of-bounds write that can lead to a crash, a memory leak or remote code execution. Rated 9.2 Critical (CVSS 4.0) by GitHub, High by Node.js.

> Google Brotli (C library) 1.0.3 – 1.2.0 1.0.10, 1.1.1, 1.2.1

#### Why it is here

From the promotion queue (`index/promote.json`, priority 2): broccoli2shell.com: CVE-2026-111497, an out-of-bounds write in the Brotli C decoder 1.0.3 to 1.2.0 (9.2 Critical, CVSS 4.0), affecting Node.js, Python and others; notes PAN-OS 11.2 to 12.2 with Brotli inspection affected.

Supports: the related Brotli flaw (CVE-2026-111497): scope and fixed versions; board breaking-0002.

#### Capture notes

Language `en`. tools/capture_batch.mjs (Playwright Chromium), HTTP 200, captured 2026-10-27T19:14:21Z. The page describes the decoder bug at code level; that detail is left in the capture and not repeated here.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261027T191336Z · HTTP 200 · https://broccoli2shell.com/- `headers.json` 7cc8fc882c2d8a4c44fb522aba9e13ff4b1990bea2d447a38cfbcd0100359d77 1,270 bytes
- `page.html` 21fce074438fe5128de38d50965fef2cd8b86991ac6594604d0eca0e9fea5852 48,236 bytes
- `provenance.json` 4d7248dc28c944e3409ffaad66ca13d5defcd9e44a74ded2ac51bd6c12a6340e 1,579 bytes
- `rendered.html` 610f6961536087fdc7946ee9c63e4e9fdb4948fd8442a1b23f04b0a8790351cc 49,437 bytes
- `screenshot.jpg` 0e931b5e1af91fbef85b4779ac30f295883e1bb0e187a3b0945f1a820ec86617 742,615 bytes
- `text.txt` 26da2897718675e1e8f2112ff446d5f2d535dfbe4987d01f8976832b5268e0f9 15,996 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.51 · data as of 2026-10-28T17:15Z · vault commit 75668aedfb6d · https://refs.php.oct.2026.newsroom.sgit.ai/sources/broccoli2shell-com/index.html
