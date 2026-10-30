# Source: PHP2Shellの悪用によるRCE成功例を研究者が報告 | Codebook｜Security News

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

codebook.machinarecord: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shellの悪用によるRCE成功例を研究者が報告 | Codebook｜Security News

**codebook.machinarecord** · [https://codebook.machinarecord.com/threatreport/silobreaker-cyber-alert/48256/](https://codebook.machinarecord.com/threatreport/silobreaker-cyber-alert/48256/) · published 2026-10-27T02:28:24+00:00 · added by `curator@php.newsroom` · slug `codebook-machinarecord-threatreport-silobreaker-cyber-alert-482`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261027T094306Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). Codebook, Security News (Japan, Japanese), 27 October, a Silobreaker daily cyber alert summarising BleepingComputer of 26 October: Perplexity's Adel K...

## What it says, as the collector read it

#### PHP2Shellの悪用によるRCE成功例を研究者が報告 | Codebook｜Security News

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `cz/news/codebook-machinarecord/threatreport-silobreaker-cyber-alert-48256`, snapshot `20261027T094306Z`. Copied byte for byte; every file's sha256 is in `captures/20261027T094306Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

Codebook, Security News (Japan, Japanese), 27 October, a Silobreaker daily cyber alert summarising BleepingComputer of 26 October: Perplexity's Adel Karimi reported successful remote code execution on his honeypots against Apache mod_php with PHP 8.4.26, from two different source addresses and a total of 35 shell processes on three honeypots, with the two activities possibly by different actors; he cautioned it shows the attack works in a deliberately favourable single-worker setup, not reliability elsewhere; Expel's Marcus Hutchins called it by far the best-quality evidence of PHP2Shell exploitation in real attacks. It adds that on 23 October the PHP team shared mitigations for another remote-code-execution flaw, CVE-2026-115560, which has no patch yet and applies only to unusual configuration and application-code combinations, with session.upload_progress.enabled set to 0 recommended. Duplicates the BleepingComputer report held by other items.

> ただ、「今回の証拠は、攻撃が成立しやすいよう意図的に構成された、ワーカープロセスが1つのmod_php環境で一連の攻撃が成立したことを示している。

_Curator's translation:_ "'This evidence shows that the sequence of attacks succeeded in a mod_php environment deliberately set up to make an attack easy, with a single worker process.'"

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shellの悪用によるRCE成功例を研究者が報告 | Codebook｜Security News". Selected mechanically, not read by a person.

#### Capture notes

Language `ja`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261027T094306Z · HTTP 200 · https://codebook.machinarecord.com/threatreport/silobreaker-cyber-alert/48256/- `headers.json` 15728bfec405dc4f3eacd384b26b6e3ee96d6e0029707b0eaf536b7a30bb1f6b 1,879 bytes
- `page.html` a2640ecb6c9e8aea86b9250298d9452565351f9b8d6399e5363da269e3968307 97,264 bytes
- `provenance.json` 5e30a8c85acf20beefd89c3930a2aa465628e0136318598af81a7478234085df 1,763 bytes
- `rendered.html` 9832c46b07ac3600d0e78e8177d3fb757b95e1a6fce1087ef064057f2ceb28fb 109,495 bytes
- `screenshot.jpg` 1b275d93f998ec92ca8b69a3387eace21ce2bafa065d3cb20a4c36b0112e1296 570,593 bytes
- `text.txt` d9f8c30afa670000b0989a36a53fa46b1a902693d409b8b6e17d38d344172575 9,711 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.54 · data as of 2026-10-29T17:13Z · vault commit cd9375f1aefd · https://refs.php.oct.2026.newsroom.sgit.ai/sources/codebook-machinarecord-threatreport-silobreaker-cyber-alert-482/index.html
