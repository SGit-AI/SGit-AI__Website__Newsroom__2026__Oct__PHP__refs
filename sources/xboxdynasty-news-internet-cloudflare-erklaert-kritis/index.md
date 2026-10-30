# Source: Internet: Cloudflare erklärt kritische PHP-Sicherheitslücke

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

XboxDynasty: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# Internet: Cloudflare erklärt kritische PHP-Sicherheitslücke

**XboxDynasty** · [https://www.xboxdynasty.de/news/internet/cloudflare-erklaert-kritische-php-sicherheitsluecke/](https://www.xboxdynasty.de/news/internet/cloudflare-erklaert-kritische-php-sicherheitsluecke/) · published 2026-10-25T12:45:06+00:00 · added by `curator@php.newsroom` · slug `xboxdynasty-news-internet-cloudflare-erklaert-kritis`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261027T121358Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). XboxDynasty (Germany, German), 25 October, by Z0RN: a site's own account of why it was password-protected for about 90 minutes, followed by Cloudflare...

## What it says, as the collector read it

#### Internet: Cloudflare erklärt kritische PHP-Sicherheitslücke

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `de/news/xboxdynasty/news-internet-cloudflare-erklaert-kritische-php-sicherheitsl`, snapshot `20261027T121358Z`. Copied byte for byte; every file's sha256 is in `captures/20261027T121358Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

XboxDynasty (Germany, German), 25 October, by Z0RN: a site's own account of why it was password-protected for about 90 minutes, followed by Cloudflare's background on the flaws. It says Cloudflare reported that the flaws had leaked before official release and it then saw attack attempts against customers' sites, with attackers repeatedly adapting their requests to evade protections; that Cloudflare began building defences in early October and shipped them about nine hours before the public announcement, available by default from 05:02 German time on 21 October (including the free plan); that it built a feature called Full Transaction Detection which also examines the server's response; and that on 23 October the PHP project published an advisory on the related CVE-2026-115560 (the upload-progress feature in sessions), which per the published information affects even fully updated versions such as 8.5.12, with a fix due in the next regular release and Cloudflare rules that only work if sites use the default parameter name. The site stresses that a critical flaw does not mean a site was compromised.

> Cloudflare hatte bereits Anfang Oktober mit der Entwicklung entsprechender Abwehrmechanismen begonnen und stellte diese ungefähr neun Stunden vor der öffentlichen Bekanntgabe bereit.

_Curator's translation:_ "Cloudflare had begun developing corresponding defences in early October and deployed them about nine hours before the public announcement."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "Internet: Cloudflare erklärt kritische PHP-Sicherheitslücke". Selected mechanically, not read by a person.

#### Capture notes

Language `de`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261027T121358Z · HTTP 200 · https://www.xboxdynasty.de/news/internet/cloudflare-erklaert-kritische-php-sicherheitsluecke/- `headers.json` b162732befc9f761fbd77ce899615fce35abaa6159a341f75e4f4e964c60bd8c 1,270 bytes
- `page.html` 14a56ff8c5abe0aec1e358e54d7c08c500a36ff4460a1ae1017d17cc784a2de5 153,535 bytes
- `provenance.json` 3d5dbb8c629858874575a1579b755ea60a654f58ac4bfce9c6d281b42a3e39cd 1,770 bytes
- `rendered.html` 9164c8faee0d7cdc2b94fc22c7319df2d6276da0afa5202e8ac6050c7e7728db 213,932 bytes
- `screenshot.jpg` 30fd2401fb84e43129fac87becb9a96f53a27e32d27e102dc1919d83b0d72207 739,847 bytes
- `text.txt` 08249621d0c369ecb2c6df75d6ff9bfd6072ffe3adc4a1107c77cc32dcf026b7 11,333 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.54 · data as of 2026-10-29T17:13Z · vault commit cd9375f1aefd · https://refs.php.oct.2026.newsroom.sgit.ai/sources/xboxdynasty-news-internet-cloudflare-erklaert-kritis/index.html
