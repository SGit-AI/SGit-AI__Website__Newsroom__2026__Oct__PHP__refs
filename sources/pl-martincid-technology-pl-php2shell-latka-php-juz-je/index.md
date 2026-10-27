# Source: PHP2Shell: łatka PHP już jest, ale strony na WordPressie muszą czekać na hostingodawcę – Martin Cid Magazine PL

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

pl.martincid: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell: łatka PHP już jest, ale strony na WordPressie muszą czekać na hostingodawcę – Martin Cid Magazine PL

**pl.martincid** · [https://pl.martincid.com/technology-pl/php2shell-latka-php-juz-jest-ale-strony-na-wordpressie-musza-czekac-na-hostingodawce/](https://pl.martincid.com/technology-pl/php2shell-latka-php-juz-jest-ale-strony-na-wordpressie-musza-czekac-na-hostingodawce/) · published 2026-10-21T16:29:41-04:00 · added by `curator@php.newsroom` · slug `pl-martincid-technology-pl-php2shell-latka-php-juz-je`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261024T083755Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). Martin Cid Magazine Polska (Polish), 21 October: why WordPress sites must wait for their host rather than update themselves. It says the flaws are in...

## What it says, as the collector read it

#### PHP2Shell: łatka PHP już jest, ale strony na WordPressie muszą czekać na hostingodawcę – Martin Cid Magazine PL

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `pl/news/pl-martincid/technology-pl-php2shell-latka-php-juz-jest-ale-strony-na-wor`, snapshot `20261024T083755Z`. Copied byte for byte; every file's sha256 is in `captures/20261024T083755Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

Martin Cid Magazine Polska (Polish), 21 October: why WordPress sites must wait for their host rather than update themselves. It says the flaws are in PHP itself, below the CMS, so a WordPress update changes nothing; PHP covers every web-request set-up (FPM, mod_php, php-cgi, FrankenPHP, LiteSpeed), citing The Hacker News that an attack works even against a default 'Hello World' page, and that the worst case is mod_php. Wordfence says the patch cannot arrive through automatic updates, and Laravel Forge says Ubuntu's unattended upgrades do not cover PHP installed from outside packages. On package-source timing, mySites.guru reported that cPanel EasyApache 4 had fixed builds within minutes while Ondřej Surý's PPA and Remi's repository did not yet; only 0.08% of the active sites it monitors showed a fixed PHP at 13:52 UTC. It warns that backports by Ubuntu, Debian and Red Hat keep the old version number, so version checks mislead, and that long-running processes must be restarted. The fixed versions are 8.5.12, 8.4.27, 8.3.36 and 8.2.35; PHP 8.1 and older get no fix from the project beyond minimal source patches.

> Wśród aktywnych witryn monitorowanych przez mySites.guru o 13:52 UTC poprawioną wersję PHP zgłaszało 0,08%.

_Curator's translation:_ "Among the active sites monitored by mySites.guru at 13:52 UTC, 0.08% reported a patched PHP version."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell: łatka PHP już jest, ale strony na WordPressie muszą czekać na hostingodawcę – Martin Cid Magazine PL". Selected mechanically, not read by a person.

#### Capture notes

Language `pl-PL`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261024T083755Z · HTTP 200 · https://pl.martincid.com/technology-pl/php2shell-latka-php-juz-jest-ale-strony-na-wordpressie-musza-czekac-na-hostingodawce/- `headers.json` 498941cb4310e3e054ad5443fd649dcee6adddac7cb8de1d1ac4069dce62ef31 1,259 bytes
- `page.html` 76deb19b68cd29dcdbbdd8ff5d618b743f26abd404c013fcae33f0d1890c0670 168,184 bytes
- `provenance.json` fafa4d1a4a70afa79638a4f8857442b5b1b3089aa8d82706436b08d051a588bc 1,892 bytes
- `rendered.html` c2b9538085393058f4f442fe0d8d15e67cc6810f85b7a6044093a5c0b9b7dde4 169,733 bytes
- `screenshot.jpg` 81938541bcbf15dcb4d9eae6b2fa7399aa1e3d269599998cc398f622b34cee9a 783,200 bytes
- `text.txt` bc7469e5682b9d31e924a9825ede18c4994f530fca3b735840c69fc92b5fbc0b 10,457 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.45 · data as of 2026-10-27T09:43Z · vault commit 55b47c4d6af1 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/pl-martincid-technology-pl-php2shell-latka-php-juz-je/index.html
