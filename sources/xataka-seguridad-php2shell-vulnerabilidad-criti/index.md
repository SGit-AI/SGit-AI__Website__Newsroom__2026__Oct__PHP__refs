# Source: PHP2Shell es una vulnerabilidad crítica para tu web: cómo comprobar que tu sitio es seguro

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

Xataka: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell es una vulnerabilidad crítica para tu web: cómo comprobar que tu sitio es seguro

**Xataka** · [https://www.xataka.com/seguridad/php2shell-vulnerabilidad-critica-para-tu-web-como-comprobar-que-tu-sitio-seguro](https://www.xataka.com/seguridad/php2shell-vulnerabilidad-critica-para-tu-web-como-comprobar-que-tu-sitio-seguro) · published 2026-10-22T14:00:10Z · added by `curator@php.newsroom` · slug `xataka-seguridad-php2shell-vulnerabilidad-criti`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261023T160435Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). Xataka (Spain, Spanish), 22 October: how to check that your site is safe from PHP2Shell. It repeats the emergency patch of 21 October for CVE-2026-109...

## What it says, as the collector read it

#### PHP2Shell es una vulnerabilidad crítica para tu web: cómo comprobar que tu sitio es seguro

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `ar/news/xataka/seguridad-php2shell-vulnerabilidad-critica-para-tu-web-como`, snapshot `20261023T160435Z`. Copied byte for byte; every file's sha256 is in `captures/20261023T160435Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

Xataka (Spain, Spanish), 22 October: how to check that your site is safe from PHP2Shell. It repeats the emergency patch of 21 October for CVE-2026-109618 and CVE-2026-109619, says Qualys states they can be exploited without logging in and Cloudflare reported attacks hours before the patch was published, and gives practical steps: find the PHP version in the hosting panel (cPanel, Plesk), run php -v on your own server, remember distributions patch without changing the version number so check the changelog for the two CVE numbers, ask the host whether the 21 October fix is applied, back up before changes, and watch for unknown files, new admin users and unexplained traffic. It says PHP 8.1 and earlier get no project updates, that Sansec said servers installing PHP from the Remi repository did not have the fix on 21 October, and that major hosts have patched all versions. It mentions a tool OpenAI published to check whether a site is affected. A header line credits Cloudflare with shielding the other 40% of the internet. Advice only; no new facts.

> Las distribuciones de Linux suelen parchear los agujeros de seguridad sin cambiar el número de versión.

_Curator's translation:_ "Linux distributions often patch security holes without changing the version number."

_The watch reader's summary (researcher@php.newsroom, of its snapshot 20261022T181608Z, not necessarily this one):_ Xataka gives a how-to for checking whether a site's PHP is patched (version numbers, php -v, hosting panels, distro backports). It cites Qualys, Cloudflare's report of pre-patch attacks, and Sansec's note that the Remi repository lagged on 21 October.

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell es una vulnerabilidad crítica para tu web: cómo comprobar que tu sitio es seguro". Selected mechanically, not read by a person.

#### Capture notes

Language `es`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261023T160435Z · HTTP 200 · https://www.xataka.com/seguridad/php2shell-vulnerabilidad-critica-para-tu-web-como-comprobar-que-tu-sitio-seguro- `headers.json` d341bd2340366c98fbf954b9c9a5840a2fbce2c9e716de92552f1ce83579c59b 760 bytes
- `page.html` 817282a6f75762cb35dc896b7392c1aa5ae614619049a12a2a1cc4a194ff3d13 122,425 bytes
- `provenance.json` 03571582a6fec22b59322202a648e7a5a8a88fe02c726a22a7a84cd7ab2319f4 1,824 bytes
- `rendered.html` b28b02be46429cf9b42197be2a289e947b5987efd04394e524b61a435fd7be3c 277,032 bytes
- `screenshot.jpg` 5bfd6260845ccf8c1cbca26458f73e416ea853ae1ca730d119122acc954d68ee 938,731 bytes
- `text.txt` a7105a728435cd8937c24fd816b0290561f228a38b6c016cbc0545f6f3160820 11,281 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.45 · data as of 2026-10-27T09:43Z · vault commit 55b47c4d6af1 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/xataka-seguridad-php2shell-vulnerabilidad-criti/index.html
