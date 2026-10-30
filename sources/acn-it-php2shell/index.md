# Source: PHP2Shell: sanate vulnerabilità critiche in PHP (AL07/261021/CSIRT-ITA)

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

ACN / CSIRT Italia: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · advisory · secondary · captured

# PHP2Shell: sanate vulnerabilità critiche in PHP (AL07/261021/CSIRT-ITA)

**ACN / CSIRT Italia** · [https://www.acn.gov.it/portale/w/php2shell-sanate-vulnerabilita-critiche-in-php](https://www.acn.gov.it/portale/w/php2shell-sanate-vulnerabilita-critiche-in-php) · published 2026-10-21 · added by `collector-gov` · slug `acn-it-php2shell`

Alert AL07/261021/CSIRT-ITA, published 21-10-2026. CVSS v4.0 9.2 each (Use After Free). Mitigation: only 'aggiornare i prodotti vulnerabili' (update); it gives no offline advice.

## What it says, as the collector read it

#### ACN / CSIRT Italia alert AL07/261021/CSIRT-ITA

- "Pubblicato il 21-10-2026". Captured 2026-10-22T08:13:54Z.

- It calls both CVEs "Use After Free" with CVSS v4.0 9.2. Affected: 8.5

## Claims that cite it

| Claim | Who says it | Status | [Fact-check](https://php.oct.2026.newsroom.sgit.ai/factcheck/) | Primary | Sources |
|---|---|---|---|---|---|
| The UK's NCSC, the NSA and their counterparts in the EU and Australia advise taking systems offline where patching is not feasibleAustralia's ACSC gives no offline advice (as captured). CERT-EU says isolate internet-facing applications, CERT-FR isolate affected equipment. Italy's ACN does say to consider taking sites offline (acn-it-php2shell, capture 20261022T081354Z, line 70). The Netherlands and Japan give no offline advice; New Zealand's page gives none. Corrected 27 October 2026, PROJECT-001: this claim was attributed to the BBC ('by': 'BBC') and marked 'contradicted'; the BBC did not write it, so it cannot be contradicted against the BBC; the status now follows the agencies' own pages (holds in part: Australia not shown). Superseded note: 'Australia's ACSC gives no offline advice. CERT-EU says isolate. The Netherlands, Italy, Japan and New Zealand give no offline advice.' (its statement that Italy gives no offline advice was wrong). [fact timeline →](../../facts/offline-allies/index.html) | Not the BBC. This site's synthesis of the agencies' own pages. The BBC wrote only that the NCSC 'as well as its counterparts in the EU and Australia, earlier urged those who use PHP to apply the fixes', quoted the NCSC's offline sentence, and reported the NSA's call to go offline. | disputed | **A1** Weak signal●○○○○○ | 7/8 | [ACSC](../../sources/acsc-alert-php/index.html) [CERT-EU](../../sources/certeu-sa-2026-018/index.html) [NCSC-NL](../../sources/ncsc-nl-php2shell/index.html) [ACN / CSIRT Italia](../../sources/acn-it-php2shell/index.html) [JPCERT/CC](../../sources/jpcert-at260033/index.html) [NSA](../../sources/nsa-press-php-4630238/index.html) [NCSC UK](../../sources/ncsc-news-php/index.html) [CERT-FR](../../sources/certfr-2026-ale-014/index.html) |

## Events that cite it

| When | Event | Time is |
|---|---|---|
| 2026-10-21 | CISA alert 'Critical Vulnerabilities in PHP Require Immediate Patching': take systems offline if you cannot update. NSA press release 'PHP2Shell'. UK NCSC alert. CCCS AL26-026. CERT-FR ALE-014. ACN AL07/261021. Cloudflare, Wiz, Calif, the PHP Foundation and Daubois publish their accounts. | stated |

### Numbers from this source

| Figure | Of | Status |
|---|---|---|
| 9.2 | CVSS v4.0, each CVE | confirmed |

### Agency rows from this source
- [ACN / CSIRT Italia](https://php.oct.2026.newsroom.sgit.ai/agencies/): offline consider

## The bytes
capture 20261022T081354Z · HTTP 200 · https://www.acn.gov.it/portale/w/php2shell-sanate-vulnerabilita-critiche-in-php- `headers.json` c44211ff9b8440ef6922919056abed0873179324fdf7db7ddf969c8d1dd6bd15 732 bytes
- `page.html` 6ab511ebb1dd7a3d6235d88dc71a02c8ecefec27283538cec68a134d33d67440 118,598 bytes
- `provenance.json` b832861c53d09b3d98083bc23e3c4578748f1f8173e2ea7c23bd8c9dfa6f1c8b 1,038 bytes
- `rendered.html` 91c9550654c551eeacb33e829fe2246a7307efbcf7cd00d4cf10f5a44413cf07 131,205 bytes
- `screenshot.png` 94246ab38f323d629edf5c1820908d804f7f45f61bc276e7c77e756aa549fc65 687,162 bytes
- `text.txt` 19fac2edc25161cd867bda0ea1c8bf8b6ce7625fbdd1e9a9a7cd41bdd8d1bef6 6,137 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.54 · data as of 2026-10-29T17:13Z · vault commit cd9375f1aefd · https://refs.php.oct.2026.newsroom.sgit.ai/sources/acn-it-php2shell/index.html
