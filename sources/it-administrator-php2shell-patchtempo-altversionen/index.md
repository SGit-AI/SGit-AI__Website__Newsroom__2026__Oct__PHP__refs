# Source: PHP2Shell: Altlasten bremsen Patches | IT-Administrator

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

IT-Administrator: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell: Altlasten bremsen Patches | IT-Administrator

**IT-Administrator** · [https://www.it-administrator.de/php2shell-patchtempo-altversionen](https://www.it-administrator.de/php2shell-patchtempo-altversionen) · published 2026-10-26 · added by `curator@php.newsroom` · slug `it-administrator-php2shell-patchtempo-altversionen`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261031T094210Z, queue priority 2 (mechanical selection by researcher@php.newsroom, read by the curator). A German IT-administrator trade piece (IT-Administrator, 26 October) on the pace of patching, built on the public PHP2Shell dashboard of the security...

## What it says, as the collector read it

#### PHP2Shell: Altlasten bremsen Patches | IT-Administrator

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `de/news/it-administrator/php2shell-patchtempo-altversionen`, snapshot `20261031T094210Z`. Copied byte for byte; every file's sha256 is in `captures/20261031T094210Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

A German IT-administrator trade piece (IT-Administrator, 26 October) on the pace of patching, built on the public PHP2Shell dashboard of the security firm Censys as of Monday morning, 26 October, 07:15. It says nearly ten million PHP services have been updated since the patch release, but about 32.4 million still run a vulnerable version and patching is slowing (only about 346,000 newly patched in 24 hours); about 9.9 million services have switched from a vulnerable to a secured version since 21 October and about 42.3 million vulnerable services have been seen since tracking began. By branch, PHP 8.5 is about 75% secured, 8.4 about 64% and 8.2 and 8.3 each just under half. Of about 43 million services that reveal a version, about 24 million run PHP 8.1 or older, where only source backports exist for 7.4, 8.0 and 8.1 although some distributions and long-term-support vendors ship their own fixes without changing the version number; only about 8.8 million vulnerable services could simply move to a ready release and another 11 million are already secured. PHP 7.4.33 is the commonest version (over 6.7 million), PHP 5.6.40 still appears about 1.6 million times, the United States has the most vulnerable services (over 10.3 million) and Germany about 4.2 million. It lists German hosters among the networks with the most vulnerable addresses, notes that about 57% of PHP services hide their version and are missing from the statistics, that Censys scores only the reported version number, that it dropped about 850,000 services with never-released version numbers as likely honeypots, and that patched systems only show as safe after the next scan. It adds that Palo Alto firewalls are also affected, attackers have PAN-OS management interfaces in their sights, and the vendor is distributing hotfixes and interim measures.

> Knapp zehn Millionen PHP-Dienste haben seit dem Patch-Release ein Update bekommen.

_Curator's translation:_ "Nearly ten million PHP services have received an update since the patch release."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 2): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell: Altlasten bremsen Patches | IT-Administrator". Selected mechanically, not read by a person. Text also matches compromise/breach terms: check for a named organisation or cause.

#### Capture notes

Language `de`. Secondhand on Censys's dashboard, which is the primary; the figures are a version-based count with the method caveats the article states. The page also carries unrelated older news items and an advertisement. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261031T094210Z · HTTP 200 · https://www.it-administrator.de/php2shell-patchtempo-altversionen- `headers.json` 3955de5873153e86eca2374a80ce5cf69690e7cfd2a05e8988ab4659b776d16c 681 bytes
- `page.html` 88687151553392690b6abff15cfd8668be3b27203a162d2e3258d9c39ba97691 86,795 bytes
- `provenance.json` 392affe056363d86e88eed17ee463b035f24b937987445d194cfc857a1e16402 1,662 bytes
- `rendered.html` 66db137e7651492d1385bd679ce93637c7aeb2eca57bf78595dd4aa5143c0f3b 106,001 bytes
- `screenshot.jpg` 1cd70ffccd8a6f73c82d65b88d2da703b0430b15422799b0223b88500970e91d 551,666 bytes
- `text.txt` 3c3a81e0f2454a5dc0ce53496d5737d809e3cf0f7878d477d65cfcb8db054770 7,082 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.57 · data as of 2026-11-02T15:57Z · vault commit e4bbd16da443 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/it-administrator-php2shell-patchtempo-altversionen/index.html
