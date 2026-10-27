# Source: NASに重大な脆弱性「PHP2Shell」、QNAPなど一部メーカーは修正パッチ未提供 | XenoSpectrum

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

xenospectrum: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# NASに重大な脆弱性「PHP2Shell」、QNAPなど一部メーカーは修正パッチ未提供 | XenoSpectrum

**xenospectrum** · [https://xenospectrum.com/php2shell-nas-qnap-synology-patch-gap/](https://xenospectrum.com/php2shell-nas-qnap-synology-patch-gap/) · published 2026-10-23T02:43:47.858Z · added by `curator@php.newsroom` · slug `xenospectrum-php2shell-nas-qnap-synology-patch-gap`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261023T160435Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). XenoSpectrum (Japan, Japanese), 23 October: a major PHP2Shell flaw in NAS devices, with some makers, QNAP among them, having no fixed release as of 23...

## What it says, as the collector read it

#### NASに重大な脆弱性「PHP2Shell」、QNAPなど一部メーカーは修正パッチ未提供 | XenoSpectrum

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `cz/news/xenospectrum/php2shell-nas-qnap-synology-patch-gap`, snapshot `20261023T160435Z`. Copied byte for byte; every file's sha256 is in `captures/20261023T160435Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

XenoSpectrum (Japan, Japanese), 23 October: a major PHP2Shell flaw in NAS devices, with some makers, QNAP among them, having no fixed release as of 23 October. It says PHP is embedded in NAS operating systems that owners cannot always update, and compares vendors: Synology's advisory lists PHP 7.3 to 8.4 packages and apps such as Mail Station and Calendar as affected, rates the OS-embedded PHP's risk as very low and published fixes for affected packages (none for the end-of-life 7.3); Asustor's advisory AS-2026-023 says products where PHP was added to ADM are affected and recommends stopping the web server until a fix; QNAP's advisory QSA-26-18 says PHP is used by the OS's web functions and several apps, lists the affected products' status as 'Fixing' with no fix date, warns that stopping the built-in web server does not protect the web admin interface, and says containers and third-party apps are outside its updates. It also relays AppleInsider that TerraMaster was investigating an owner's report of PHP 7.4.33 on a web admin interface, and that QNAP reports no exploitation targeting its products. Defensive advice for owners is summarised.

> 何が起きた: PHP開発チームが10月21日に重大な脆弱性「PHP2Shell」を修正したが、一部のNASメーカーでは10月23日時点でも修正版が公開されていない。

_Curator's translation:_ "What happened: the PHP team fixed the critical PHP2Shell vulnerabilities on 21 October, but some NAS makers still had no fixed version published as of 23 October."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "NASに重大な脆弱性「PHP2Shell」、QNAPなど一部メーカーは修正パッチ未提供 | XenoSpectrum". Selected mechanically, not read by a person.

#### Capture notes

Language `ja`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261023T160435Z · HTTP 200 · https://xenospectrum.com/php2shell-nas-qnap-synology-patch-gap/- `headers.json` dddabc662d919110564a46e072ec54892606272a8901f5ad9c168900847ac723 1,078 bytes
- `page.html` a4e9abde66eb575c17d17697aa5eed9f88daf6f6533ee5da1eadf6991d5ae252 282,605 bytes
- `provenance.json` 3f7ccea9b3575885c923379393dd402f025af47854230cc63ddae7e9b233a9e6 1,715 bytes
- `rendered.html` 22f3a1a04bc5ca3b66cf30c178e8426eac1c2fa723069c028087840a982a2dfb 1,802,860 bytes
- `screenshot.jpg` d071bfedad692c616fa30c435bdba63e3a77466c8bc4bae1a7cddb8db2446268 854,008 bytes
- `text.txt` c3cfcfbb0b2c8a5e600ceecd270853c28fa587c6977da5d84202d68af9967d14 24,442 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.49 · data as of 2026-10-27T19:13Z · vault commit 6f0d5c50bf12 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/xenospectrum-php2shell-nas-qnap-synology-patch-gap/index.html
