# Source: PHP2Shell deja a millones de servidores con versiones de PHP sin un parche oficial - NotebookCheck.org News

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

Notebookcheck: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell deja a millones de servidores con versiones de PHP sin un parche oficial - NotebookCheck.org News

**Notebookcheck** · [https://www.notebookcheck.org/PHP2Shell-deja-a-millones-de-servidores-con-versiones-de-PHP-sin-un-parche-oficial.1433709.0.html](https://www.notebookcheck.org/PHP2Shell-deja-a-millones-de-servidores-con-versiones-de-PHP-sin-un-parche-oficial.1433709.0.html) · published 2026-10-26 · added by `curator@php.newsroom` · slug `notebookcheck-php2shell-deja-a-millones-de-servidores`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261027T121358Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). Notebookcheck (Spanish edition, a translation of the English article by Darryl Linington), 26 October: the fixes cover only PHP 8.2 to 8.5, leaving ma...

## What it says, as the collector read it

#### PHP2Shell deja a millones de servidores con versiones de PHP sin un parche oficial - NotebookCheck.org News

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `cl/news/notebookcheck/php2shell-deja-a-millones-de-servidores-con-versiones-de-php`, snapshot `20261027T121358Z`. Copied byte for byte; every file's sha256 is in `captures/20261027T121358Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

Notebookcheck (Spanish edition, a translation of the English article by Darryl Linington), 26 October: the fixes cover only PHP 8.2 to 8.5, leaving many exposed hosts on versions with no official fixed release. It cites a Shodan count published by Mallory on 20 October of about 884,000 internet-exposed hosts indicating an unsupported PHP version, 59% of the roughly 1.5 million that reveal a version (about 740,000 more hide it), and CybelAngel's breakdown: PHP 5.x about 369,000, 7.x 329,000, 8.0 and 8.1 186,000, against 612,000 on 8.2 to 8.5 which had no fix when counted. It says these are banner counts, not confirmed vulnerable sites, that PHP published minimal source backports for 7.4, 8.0 and 8.1 but nothing for 5.6 or 7.3 and earlier, that distributions such as Ubuntu may patch while keeping the old version string, and that CISA advised disconnecting PHP-based systems that cannot be updated or run unsupported PHP 8.1 or older.

> Las correcciones de PHP2Shell solo abarcan PHP 8.2 a 8.5, lo que deja a una gran proporción de los hosts PHP expuestos a internet en versiones para las que nunca se publicó una versión oficial con correcciones.

_Curator's translation:_ "The PHP2Shell fixes cover only PHP 8.2 to 8.5, leaving a large proportion of internet-exposed PHP hosts on versions for which no official fixed release was ever published."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell deja a millones de servidores con versiones de PHP sin un parche oficial - NotebookCheck.org News". Selected mechanically, not read by a person.

#### Capture notes

Language `es`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261027T121358Z · HTTP 200 · https://www.notebookcheck.org/PHP2Shell-deja-a-millones-de-servidores-con-versiones-de-PHP-sin-un-parche-oficial.1433709.0.html- `headers.json` f9b14070af854c491569b9575fbc5a4b4e24b1e15d8c6c11124e582787d3bf08 982 bytes
- `page.html` 703f5ef70042e9a2acf585cd70d869b6a2d1592f1356da731a4705cf927428b3 112,867 bytes
- `provenance.json` 6dcc147f84681cfbbf55914f5193d4061969c9f70154b3bc3eac58de7ebf0266 1,889 bytes
- `rendered.html` e90d2c4951e365cfcfaa63298490bb6ae6723197dafa66a2d739f8544a044c10 115,857 bytes
- `screenshot.jpg` e05047693c87645478eb6d38655c0b2e817d167725e2dce2ab52d7186f49c799 415,882 bytes
- `text.txt` 4ac9fa1c36c1807c546f15cf967d7796c274e882bc79387a0ed7d53cdbf494f9 6,767 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.49 · data as of 2026-10-27T19:13Z · vault commit 6f0d5c50bf12 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/notebookcheck-php2shell-deja-a-millones-de-servidores/index.html
