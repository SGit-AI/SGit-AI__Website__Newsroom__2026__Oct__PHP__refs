# Source: PHP2Shell laisse des millions de serveurs sous des versions de PHP sans correctif officiel - NotebookCheck.biz News

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

Notebookcheck: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell laisse des millions de serveurs sous des versions de PHP sans correctif officiel - NotebookCheck.biz News

**Notebookcheck** · [https://www.notebookcheck.biz/PHP2Shell-laisse-des-millions-de-serveurs-sous-des-versions-de-PHP-sans-correctif-officiel.1433758.0.html](https://www.notebookcheck.biz/PHP2Shell-laisse-des-millions-de-serveurs-sous-des-versions-de-PHP-sans-correctif-officiel.1433758.0.html) · published 2026-10-26 · added by `curator@php.newsroom` · slug `notebookcheck-php2shell-laisse-des-millions-de-serveur`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261026T071149Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). Notebookcheck (French edition, DeepL translation of Darryl Linington's article), 26 October: the fixes cover only PHP 8.2 to 8.5, leaving many interne...

## What it says, as the collector read it

#### PHP2Shell laisse des millions de serveurs sous des versions de PHP sans correctif officiel - NotebookCheck.biz News

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `fr/news/notebookcheck/php2shell-laisse-des-millions-de-serveurs-sous-des-versions`, snapshot `20261026T071149Z`. Copied byte for byte; every file's sha256 is in `captures/20261026T071149Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

Notebookcheck (French edition, DeepL translation of Darryl Linington's article), 26 October: the fixes cover only PHP 8.2 to 8.5, leaving many internet-exposed hosts on versions that never got an official fix. A Shodan count published by Mallory on 20 October found about 884,000 exposed hosts declaring an unsupported PHP version, 59% of the roughly 1.5 million hosts that reveal a version, with about 740,000 more hiding it; CybelAngel's split is about 369,000 on PHP 5.x, 329,000 on 7.x and 186,000 on 8.0 and 8.1, against 612,000 on 8.2 to 8.5; Palo Alto Networks separately counted over 22.6 million potentially vulnerable instances. The article stresses these are banner counts, not confirmed vulnerable sites. It says PHP issued no numbered releases for end-of-life branches but minimal source backports for 7.4, 8.0 and 8.1, nothing for 5.6 or 7.3 and earlier; that distributions can ship the fix under an old version string; and that CISA advised taking PHP-based systems offline if they cannot be updated.

> Les correctifs de PHP2Shell ne couvrent que PHP 8.2 à 8.5, ce qui laisse une grande partie des hôtes PHP exposés à Internet sur des versions qui n’ont jamais bénéficié d’une publication officielle de correctifs.

_Curator's translation:_ "The PHP2Shell fixes cover only PHP 8.2 to 8.5, which leaves a large share of internet-exposed PHP hosts on versions that never received an official fix release."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell laisse des millions de serveurs sous des versions de PHP sans correctif officiel - NotebookCheck.biz News". Selected mechanically, not read by a person.

#### Capture notes

Language `fr`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261026T071149Z · HTTP 200 · https://www.notebookcheck.biz/PHP2Shell-laisse-des-millions-de-serveurs-sous-des-versions-de-PHP-sans-correctif-officiel.1433758.0.html- `headers.json` 360cbc07f59a0abfddd99295dd0de0456e00bf1229f3f9a789bf68d433a14760 1,033 bytes
- `page.html` bafda66bb412634f1b935c3c82d65da88fa9533c48c7ca394761b12c3a1caeec 112,413 bytes
- `provenance.json` 013003cf372cd2b53c1863d9255c878acfc758c8706d26fbc4bf9bd769f92a10 1,912 bytes
- `rendered.html` a7ff6ef1a63125ddea5b59c6faf48dcfff063173d604d72efde1fa36da930d4f 125,599 bytes
- `screenshot.jpg` 5ae019437d3dd0f74695bd288680ea0b9fe7b7c8d2179f4d0c43e34fd8a22558 429,828 bytes
- `text.txt` 0002440a5cd32c18d09e484692ce35f531b131f80afcd8c80188db66a1505d3b 6,824 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.34 · data as of 2026-10-26T17:09Z · vault commit 1dceaa1dfa7f · https://refs.php.oct.2026.newsroom.sgit.ai/sources/notebookcheck-php2shell-laisse-des-millions-de-serveur/index.html
