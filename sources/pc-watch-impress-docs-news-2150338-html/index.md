# Source: 深刻度9.2のPHP脆弱性「PHP2Shell」、OpenAIが影響確認ツール公開 - PC Watch

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

PC Watch: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# 深刻度9.2のPHP脆弱性「PHP2Shell」、OpenAIが影響確認ツール公開 - PC Watch

**PC Watch** · [https://pc.watch.impress.co.jp/docs/news/2150338.html](https://pc.watch.impress.co.jp/docs/news/2150338.html) · published 2026-10-22T13:59:59+09:00 · added by `curator@php.newsroom` · slug `pc-watch-impress-docs-news-2150338-html`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261023T160435Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). PC Watch (Impress, Japanese), 22 October. It reports that the PHP project brought forward its fixed releases and that OpenAI published, on 21 October...

## What it says, as the collector read it

#### 深刻度9.2のPHP脆弱性「PHP2Shell」、OpenAIが影響確認ツール公開 - PC Watch

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `jp/news/pc-watch-impress/docs-news-2150338-html`, snapshot `20261023T160435Z`. Copied byte for byte; every file's sha256 is in `captures/20261023T160435Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

PC Watch (Impress, Japanese), 22 October. It reports that the PHP project brought forward its fixed releases and that OpenAI published, on 21 October on GitHub under Apache-2.0, a tool called 'PHP Version Checker' that reads the PHP version from a site's HTTP response headers and says whether it is older than the fixed versions; it can also check a local PHP and is offered as a Codex skill. The tool only compares version numbers, does not verify that a fix is applied, and cannot judge sites that do not expose the version. It dates PHP2Shell (CVE-2026-109618 and CVE-2026-109619) to 21 October, says PHP 5.4 and later before the fixed versions are affected, and says Wiz Research found it using Gemini 4 Argon, GPT-5.6 Sol and others. Noted here as material only: the vault does not run such tools against live sites.

> ただし、同ツールはバージョン番号を比較するだけで、修正の適用そのものは検証しない。

_Curator's translation:_ "However, the tool only compares version numbers and does not verify that a fix has actually been applied."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "深刻度9.2のPHP脆弱性「PHP2Shell」、OpenAIが影響確認ツール公開 - PC Watch". Selected mechanically, not read by a person.

#### Capture notes

Language `ja`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261023T160435Z · HTTP 200 · https://pc.watch.impress.co.jp/docs/news/2150338.html- `headers.json` ef54ff09cd8670eeff7106b801f8d7e88dcb74271e0e22dc0e04742d63cae362 286 bytes
- `page.html` 152e866797f57bc33b75dfa2640aaa23aa0e3ef33bb1486d748ce510d8b39320 173,434 bytes
- `provenance.json` 4340e78c6a6c783f7723ccdfcfa17b456e769c9f832e7f3b267ded7ffcd1999f 1,554 bytes
- `rendered.html` f8f05ac6ecf711538279044827bb65054e3fbbb56e5312dc610473814fd8920a 408,465 bytes
- `text.txt` 491e54d11503658d0610f93a9b9588a998e97a327640805aa02e6d12265e164e 10,089 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.33 · data as of 2026-10-26T14:42Z · vault commit 2fc7e432584b · https://refs.php.oct.2026.newsroom.sgit.ai/sources/pc-watch-impress-docs-news-2150338-html/index.html
