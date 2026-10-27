# Source: PHP2Shell : les correctifs arrivent, mais pas au même rythme

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

Silicon.fr: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell : les correctifs arrivent, mais pas au même rythme

**Silicon.fr** · [https://www.silicon.fr/cybersecurite-1371/php2shell-vulnerabilites-php-229863](https://www.silicon.fr/cybersecurite-1371/php2shell-vulnerabilites-php-229863) · published 2026-10-22T16:19:07+00:00 · added by `curator@php.newsroom` · slug `silicon-cybersecurite-1371-php2shell-vulnerabili`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261024T133450Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). Silicon.fr (French), 22 October, by Clément Bohic: 'the fixes are arriving, but not at the same pace'. It says two critical flaws touch almost every P...

## What it says, as the collector read it

#### PHP2Shell : les correctifs arrivent, mais pas au même rythme

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `fr/news/silicon/cybersecurite-1371-php2shell-vulnerabilites-php-229863`, snapshot `20261024T133450Z`. Copied byte for byte; every file's sha256 is in `captures/20261024T133450Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

Silicon.fr (French), 22 October, by Clément Bohic: 'the fixes are arriving, but not at the same pace'. It says two critical flaws touch almost every PHP version released since March 2012; that Wiz did not find the flaw family alone but took the lead on the narrative, creating the site php2shell.com and praising the 'invaluable' contribution of Gemini 4 Argon; that the PHP project's bulletin is more neutral but says every installation serving web requests is exposed to unauthenticated arbitrary code execution; that Wiz speaks of 70% of websites and Palo Alto Networks' Unit 42 of 22.6 million potentially vulnerable instances; that PHP patched 8.5, 8.4, 8.3 and 8.2 and gave minimal source backports for 8.1, 8.0 and 7.4. It explains the two flaws at a high level (memory exhaustion during request start-up, and stale global state across requests), that mod_php and FrankenPHP are the most exposed, and lists the interim measures the PHP project gave, which are not repeated here.

> Deux vulnérabilités critiques touchent presque toutes les versions de PHP sorties depuis mars 2012.

_Curator's translation:_ "Two critical vulnerabilities affect almost every PHP version released since March 2012."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell : les correctifs arrivent, mais pas au même rythme". Selected mechanically, not read by a person.

#### Capture notes

Language `fr-FR`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261024T133450Z · HTTP 200 · https://www.silicon.fr/cybersecurite-1371/php2shell-vulnerabilites-php-229863- `headers.json` 28dd2d023285ec9edc477d5912e0159e64e1344db0d27f0dfd3fcba12df9706a 962 bytes
- `page.html` ae676d16d159aef9248db135caf534a7bb15b203b181eb977b64e688997d5d2f 146,915 bytes
- `provenance.json` a71fccd9edddd3fb093c7d34f4df2811e2d77ff5dbbbb833331f5a69e626c49b 1,714 bytes
- `rendered.html` 4897908c5ecc8be2c9d7467e4ad71de5549b6a2657b5a86d7caca36cc2197804 344,170 bytes
- `screenshot.jpg` 0e580291392fbb418e9ad2b4d70eebc0deddfaa0f930e3ef13d3fb9274c29a02 673,877 bytes
- `text.txt` 6b1c6af220b318579d0b31210decae2c0137b2b9b12d63ce3a41e1d8637282c3 15,381 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.36 · data as of 2026-10-26T17:09Z · vault commit 1dceaa1dfa7f · https://refs.php.oct.2026.newsroom.sgit.ai/sources/silicon-cybersecurite-1371-php2shell-vulnerabili/index.html
