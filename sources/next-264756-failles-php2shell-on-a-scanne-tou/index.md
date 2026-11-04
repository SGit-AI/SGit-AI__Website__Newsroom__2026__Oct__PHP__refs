# Source: Failles PHP2Shell : on a scanné tout le .fr, 250 000 sites affichent un PHP vulnérable - Next

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

Next: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# Failles PHP2Shell : on a scanné tout le .fr, 250 000 sites affichent un PHP vulnérable - Next

**Next** · [https://next.ink/264756/failles-php2shell-on-a-scanne-tout-le-fr-250-000-sites-affichent-un-php-vulnerable/](https://next.ink/264756/failles-php2shell-on-a-scanne-tout-le-fr-250-000-sites-affichent-un-php-vulnerable/) · published 2026-11-02 · added by `curator@php.newsroom` · slug `next-264756-failles-php2shell-on-a-scanne-tou`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261103T071521Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). A French tech-news report (Next, 2 November) in which the outlet scanned the .fr domain space after the disclosure. Working from the AFNIC open-data l...

## What it says, as the collector read it

#### Failles PHP2Shell : on a scanné tout le .fr, 250 000 sites affichent un PHP vulnérable - Next

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `fr/news/next/264756-failles-php2shell-on-a-scanne-tout-le-fr-250-000-site`, snapshot `20261103T071521Z`. Copied byte for byte; every file's sha256 is in `captures/20261103T071521Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

A French tech-news report (Next, 2 November) in which the outlet scanned the .fr domain space after the disclosure. Working from the AFNIC open-data list of the 4.6 million .fr domains that still existed in September 2026, it found about 1.2 million with no HTTP status, about 2.6 million answering without a PHP version (PHP may still be installed), and about 500,000 responses carrying a PHP version, of which at least 250,000 domains announce a vulnerable version. It recalls CISA's KEV listing a week after disclosure, CERT-FR's note of exploitation attempts against specific PHP deployments, the third flaw CVE-2026-115560 (which CERT-FR says needs an unlikely combination of options and will be fixed in the next cycle), Palo Alto Unit 42's statement on PAN-OS management interfaces and Dream Research's report of a campaign that rooted 25 servers including US government-affiliated systems. It stresses that exploitation is complex and the risk to ordinary users is limited.

> Nous avons identifié au moins 250 000 domaines en .fr qui annoncent une version de PHP vulnérable.

_Curator's translation:_ "We have identified at least 250,000 .fr domains that announce a vulnerable PHP version."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "Failles PHP2Shell : on a scanné tout le .fr, 250 000 sites affichent un PHP vulnérable - Next". Selected mechanically, not read by a person.

#### Capture notes

Language `fr-FR`. The scan is the outlet's own, by version banner, with the usual caveat that distributions backport fixes without changing the version number. The page is followed by reader comments, which are not recorded (they include unverified claims about backports). Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261103T071521Z · HTTP 200 · https://next.ink/264756/failles-php2shell-on-a-scanne-tout-le-fr-250-000-sites-affichent-un-php-vulnerable/- `headers.json` ef99fbfccdbf06a612de67465bc634a823f9efb58782b088af5c5c4856a82cd7 1,046 bytes
- `page.html` c82eb3f2a7134b4405897dee84bc49a091705201caa36b2eb68851f17da7eb04 463,720 bytes
- `provenance.json` 6239bc059e23c3b6956487cd968a18d7f04fcde920ba8a14e081543b97b48a28 1,811 bytes
- `rendered.html` 31193e405ffc77be03dd6b0d9cb9956ffbc4b955f4676b5d54854f0e385c7860 538,428 bytes
- `screenshot.jpg` d85cc84b002068f37c0728c9c10437bb8e04c525f782c23696d64f855afdd40b 705,554 bytes
- `text.txt` 692fed5a497e57e27fc5b3b9a8f750c5f2a4ac08b175d8cb7966314930311c2e 10,702 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.58 · data as of 2026-11-03T12:16Z · vault commit a8e4e3dc5490 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/next-264756-failles-php2shell-on-a-scanne-tou/index.html
