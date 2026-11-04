# Source: PHP2Shell: LA FALLA QUE DEJÓ 22 MILLONES DE SERVIDORES EXPUESTOS - RedUSERS

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

RedUSERS: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell: LA FALLA QUE DEJÓ 22 MILLONES DE SERVIDORES EXPUESTOS - RedUSERS

**RedUSERS** · [https://www.redusers.com/noticias/publicaciones/pllhp2she/](https://www.redusers.com/noticias/publicaciones/pllhp2she/) · published not stated in the capture · added by `curator@php.newsroom` · slug `redusers-noticias-publicaciones-pllhp2she`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261102T122013Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). An Argentine IT-magazine summary (RedUSERS) of a longer paid guide on PHP2Shell, which it says left 22 million servers exposed. It says the two CVE id...

## What it says, as the collector read it

#### PHP2Shell: LA FALLA QUE DEJÓ 22 MILLONES DE SERVIDORES EXPUESTOS - RedUSERS

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `ar/news/redusers/noticias-publicaciones-pllhp2she`, snapshot `20261102T122013Z`. Copied byte for byte; every file's sha256 is in `captures/20261102T122013Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

An Argentine IT-magazine summary (RedUSERS) of a longer paid guide on PHP2Shell, which it says left 22 million servers exposed. It says the two CVE ids group four core PHP errors with a common cause, that three teams reached the same flaw separately in August with the help of AI agents, that there were leaks before the 21 October patch and more than a hundred Dutch organisations took sites down, among them DigiD, and that the closing was messy. Practical points: many distributions fix without changing the version number so the full package string must be compared; the console's PHP can differ from the web server's; updating a package does not help until services restart; the corrected versions have known problems, among them an error with SimpleXML objects, so logs should be watched in the first hours; and updating does not clean a previous intrusion, so logs and upload folders should be checked for signs of one.

> Por último, actualizar no limpia una intrusión previa.

_Curator's translation:_ "Lastly, updating does not clean up a previous intrusion."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell: LA FALLA QUE DEJÓ 22 MILLONES DE SERVIDORES EXPUESTOS - RedUSERS". Selected mechanically, not read by a person.

#### Capture notes

Language `es`. The capture shows no publication date. A summary of a paid guide, with the full technical detail behind a subscription; the description of how the errors work, one variant's behaviour and the temporary configuration measures are not copied. The page ends with unrelated promotions. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261102T122013Z · HTTP 200 · https://www.redusers.com/noticias/publicaciones/pllhp2she/- `headers.json` 7f790398fc52fa015d4e800f1560d50a2da81734e6d6671a891bc65aa53179ad 1,122 bytes
- `page.html` 0ea848aee6be53b0a787b18e15727025c2d2f1bc3ac1f5c929a4ee63fd1d5867 68,024 bytes
- `provenance.json` f108e929aa4fd2739bb711764239748c4c13839018a4a12c8ca746b69b707606 1,642 bytes
- `rendered.html` 618046e06bcc2247bcc5dda15803d48d19c8189fd7012bcb1025b61caff8c5e7 131,141 bytes
- `screenshot.jpg` 3b7ae3524488293efa75942133d20b741dd2c6d7b694a01b333bed1a96e9a2c5 592,784 bytes
- `text.txt` b0ffb1e130195a9f7846c4cb7fa96ba230c1294ab292bc83ac2f45d50240b002 5,805 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.58 · data as of 2026-11-03T12:16Z · vault commit a8e4e3dc5490 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/redusers-noticias-publicaciones-pllhp2she/index.html
