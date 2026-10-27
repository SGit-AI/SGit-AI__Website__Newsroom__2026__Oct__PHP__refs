# Source: Jetzt wird es ernst: Erste richtige PHP2Shell-Angriffe beobachtet

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

WinFuture.de: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# Jetzt wird es ernst: Erste richtige PHP2Shell-Angriffe beobachtet

**WinFuture.de** · [https://winfuture.de/news,162222.html](https://winfuture.de/news,162222.html) · published 2026-10-27T07:46:00+01:00 · added by `curator@php.newsroom` · slug `winfuture-news-162222-html`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261027T094306Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). WinFuture (Germany, German), 27 October: 'Now it gets serious: first real PHP2Shell attacks observed'. It reports that a Perplexity researcher, Adel K...

## What it says, as the collector read it

#### Jetzt wird es ernst: Erste richtige PHP2Shell-Angriffe beobachtet

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `de/news/winfuture/news-162222-html`, snapshot `20261027T094306Z`. Copied byte for byte; every file's sha256 is in `captures/20261027T094306Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

WinFuture (Germany, German), 27 October: 'Now it gets serious: first real PHP2Shell attacks observed'. It reports that a Perplexity researcher, Adel Karimi, recorded 35 shell processes started on three honeypot systems over the weekend, regarded as the most telling evidence so far that the flaws are used in successful attacks: an earlier analysis of just over 26 hours had found 30 memory errors and eleven worker crashes but no command execution; on 24 October one address caused three shell processes on one system and another was behind 32 spread across all three, and the traffic closely resembled a public proof of concept. No follow-on malware was seen, and Karimi stressed that the setup (PHP 8.4.26, Apache mod_php, one worker) was especially favourable and not transferable to other configurations. The article notes millions of attempts had been logged before without a confirmed code execution.

> Ein nachgeladener Schadcode wurde bei den beobachteten Angriffen aber auch noch nicht festgestellt.

_Curator's translation:_ "No follow-on malware was, however, detected in the observed attacks."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "Jetzt wird es ernst: Erste richtige PHP2Shell-Angriffe beobachtet". Selected mechanically, not read by a person.

#### Capture notes

Language `de`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261027T094306Z · HTTP 200 · https://winfuture.de/news,162222.html- `headers.json` 713b90cec55cbafd19f13aaf4c7f7a04060e0ef2876b7e25247a76615d027487 1,364 bytes
- `page.html` 42ab8fbf195723774983dea9cd88dfce68ff572b8c93f962aed65f1d331ce126 101,343 bytes
- `provenance.json` 79c95c085cf60b42efd76e915589e10626442a8e6261fec7bbe95cba5ddc6f99 1,544 bytes
- `rendered.html` 0c838f8a32c6c3ec433b28a9b6f007b1ae07ee8a4d771a106b73ef2c192e7cca 111,096 bytes
- `screenshot.jpg` 915a3027029abf35d52ae301a9c26a6f5650dce5a4b242308acee1ed416a4908 453,200 bytes
- `text.txt` 56f365f88538329422e02e53580f615a4f99bec61fd729b4da414b4d2ffcafa3 7,138 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.46 · data as of 2026-10-27T19:13Z · vault commit 6f0d5c50bf12 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/winfuture-news-162222-html/index.html
