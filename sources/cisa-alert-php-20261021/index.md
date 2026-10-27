# Source: Critical Vulnerabilities in PHP Require Immediate Patching

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

US Cybersecurity and Infrastructure Security Agency (CISA): what it says, the claims and events that cite it, and the hashes of every captured file.

Source · advisory · primary · captured

# Critical Vulnerabilities in PHP Require Immediate Patching

**US Cybersecurity and Infrastructure Security Agency (CISA)** · [https://www.cisa.gov/news-events/alerts/2026/10/21/critical-vulnerabilities-php-require-immediate-patching](https://www.cisa.gov/news-events/alerts/2026/10/21/critical-vulnerabilities-php-require-immediate-patching) · published 2026-10-21 · added by `collector-gov` · slug `cisa-alert-php-20261021`

CISA Alert, Release Date October 21, 2026. Names CVE-2026-109618/109619 'php2shell'. 'Organizations that cannot update immediately, or that continue to use PHP 8.1 or earlier unsupported versions, should take PHP-based systems offline until they can be patched or updated.' CISA 'has not observed exploitation ... as of the time of publication'. Not in KEV as of catalog 2026.10.21.

## What it says, as the collector read it

#### CISA Alert: Critical Vulnerabilities in PHP Require Immediate Patching

- URL: https://www.cisa.gov/news-events/alerts/2026/10/21/critical-vulnerabilities-php-require-immediate-patching. "Release Date October 21, 2026" (no time given).

- Captured 2026-10-22T08:13:53Z with Playwright. Plain curl to www.cisa.gov returns 403 (Akamai), but the headless browser gets 200. The CISA home page (`cisa-home`) lists it at the top as "OCT 21, 2026 ALERT".

- Exact advice, verbatim:

- "CISA strongly urges organizations to immediately patch the recently disclosed critical vulnerabilities in PHP, CVE-2026-109618 and CVE-2026-109619."

- "Organizations should immediately update to PHP 8.5.12, 8.4.27, 8.3.36, or 8.2.35"

- "Identify and inventory systems running any version of PHP across your organization."

- "Apply the patch immediately, prioritizing internet-facing systems."

- "Organizations that cannot update immediately, or that continue to use PHP 8.1 or earlier unsupported versions, should take PHP-based systems offline until they can be patched or updated."

- "A web application firewall may provide some protection until systems are updated or patched."

- "Monitor for suspicious activity, including PHP worker processes launching shells or downloading tools."

- Exploitation: "While CISA has not observed exploitation of these vulnerabilities as of the time of publication".

- The CISA offline advice is the most absolute ("should take ... offline"), and it explicitly covers EOL 8.1 and older. No emergency directive found (see `cisa-kev-json`).

## Claims that cite it

| Claim | Who says it | Status | [Fact-check](https://php.oct.2026.newsroom.sgit.ai/factcheck/) | Primary | Sources |
|---|---|---|---|---|---|
| A web application firewall may provide some protection until systems are patchedSwiss BACS: 'Even a web application firewall alone is not sufficient.' Cloudflare says its rules blocked the traffic it saw and that attackers mutated payloads to get past them. [fact timeline →](../../facts/waf/index.html) | CISA | disputed | **A6** Established●●●●●● | 3/3 | [CISA](../../sources/cisa-alert-php-20261021/index.html) [BACS](../../sources/ch-bacs-warnung-php/index.html) [Cloudflare](../../sources/cloudflare-blog-php2shell-waf/index.html) |
| As of its alert of 21 October and KEV catalog version 2026.10.21 (fetched 2026-10-22T08:15Z), CISA had not observed exploitation and neither CVE was in the Known Exploited Vulnerabilities catalog. Superseded on 26 October: CISA added both CVEs to KEV (catalog version 2026.10.26, released 22:24 UTC; brk1-kev-listed-20261026)Catalog version 2026.10.21 fetched 2026-10-22T08:15Z, 1,754 entries. A point-in-time negative finding. Revised by the correspondent on 27 October (breaking desk, correspondent's role): the claim said in the present tense that neither CVE is in KEV; since catalog version 2026.10.26 (released 22:24:24 UTC on 26 October, captured at 00:45 UTC on 27 October) both are, dateAdded 2026-10-26. Kept as a dated point-in-time claim, true for its time, and marked superseded; the current state is the vault claim brk1-kev-listed-20261026. [fact timeline →](../../facts/cisa-none/index.html) | CISA | confirmed | **A6** Established●●●●●● | 5/5 | [CISA](../../sources/cisa-alert-php-20261021/index.html) [CISA](../../sources/cisa-kev-json/index.html) [CVE record](../../sources/cve-cve-2026-109618/index.html) [CISA](../../sources/cisa-alert-kev-20261026/index.html) [CISA](../../sources/cisa-kev-catalog/index.html) |
| Organisations that cannot update immediately, or that run PHP 8.1 or older, should take PHP-based systems offline [fact timeline →](../../facts/offline-cisa/index.html) | CISA | confirmed | **A6** Established●●●●●● | 1/1 | [CISA](../../sources/cisa-alert-php-20261021/index.html) |
| As of 00:45 UTC on 27 October, no named organisation has said it was compromised through php2shell. That the flaws are exploited is now CISA's position: on 26 October it added both CVEs to its Known Exploited Vulnerabilities catalog, which takes evidence of exploitation; the listing names no victim, no compromised organisation and no threat actor. Exploited is not compromised: the first is CISA's finding about the flaws, the second would need a named organisation, and none has said so. Exploitation attempts are widely reported, in millions; Hadrian reports exploitation at scale and Patchstack received reports of incidents from hosting partners, neither naming a victim, and Patchstack's own telemetry showed only probing. Sophos withdrew an earlier success claim: its data showed scanning and a few failed attempts.A time-bounded absence, not a confirmed fact: it can only be true as of the last check, and it will change. Changed from "confirmed" on 22 October at the editor's request. Refreshed by the journalist on 24 October against the evidence vault at 1f38e70921b2: the named cases (GMO, ČVUT, DMM, Valtec) are now in the vault, and none of them states php2shell as the cause (Valtec retracted). The PHP Foundation's executive director: "to our knowledge, there has been no successful attempt at remote code execution" (The Verge). Luxembourg: no institution has announced an intrusion (Paperjam). Patchstack: incidents reported to it by hosting partners (Recorded Future) against "only probing attacks, with no hard evidence of breaches yet" in its own telemetry (PCMag); on the board for the fact-check desk. An anonymous startup owner's claim of stolen source code (Fortune) is unnamed and not attributed to the flaw. Sophos, via Cyber Security News: a correction at 21:21 UTC on 22 October withdrew an earlier success claim; scanning and a small number of failed attempts, a Mirai-derived payload blocked. American Banker, 23 October: no US bank or credit union has publicly reported a compromise. Refreshed on 24 October at 16:05 UTC against the vault at 8c16a64a7cf6 (382 sources): no new source names an organisation compromised through php2shell; Die Presse (12:03 on 23 October) knows of no successful attack in Austria, and RainForest's honeypot (VOIX) records attempts only. Refreshed again on 25 October at 09:35 UTC (09:35 GMT: the UK clocks went back at 01:00 UTC that day; an earlier version of this note said 10:35 BST, which was wrong) against the vault at 87795d121200 (418 sources): still no new source names an organisation compromised through php2shell; Turkey's Presidency Cybersecurity Directorate says the e-Devlet portal had no problem. Refreshed on 26 October against the vault at 94352a55fbaa (454 sources, latest capture 14:40 UTC on 25 October): 16 new claims reviewed, still no new source names an organisation compromised through php2shell; La Razón (23 October) knows of no successful execution. Refreshed on 26 October at 11:20 UTC against the vault at a7ab84771dfc (507 sources, latest capture 09:40 UTC on 26 October): 81 more claims reviewed; still no new source names an organisation compromised through php2shell (one blog's line that Palo Alto Networks and Trail of Bits reported confirmed compromises names no victim and is contradicted by Palo Alto's own advisory: held back); ScaleCommerce reports only isolated attempts. Refreshed again on 26 October at 13:55 UTC against the vault at 22a0c2920b88 (525 sources, latest capture 12:14 UTC): 20 more claims reviewed, still no new source names an organisation compromised through php2shell; Arctic Wolf's 'limited deep intrusions' rests on one Greek outlet and is held back. Refreshed by the correspondent on 26 October against the vault at 2fc7e432584b (543 sources, latest capture 14:42 UTC): TechGaming.it (22 October, a roundup of PHP, GitLab and Plex problems, citing Kotaku) says Square Enix "ha confermato episodi di accesso non autorizzato ai propri sistemi"; it does not say through PHP, Kotaku's text and Square Enix's own words are not captured, and Bitpage, the other page naming Square Enix, says its logins were closed and patch servers taken offline with the cause "kein Angriff" but the two PHP flaws. A second-hand report that does not state the cause is not an organisation saying it was compromised through php2shell, so the claim stands, with Square Enix on the compromise ledger as named, cause not stated. Refreshed by breaking@php.newsroom in the journalist's role on 27 October at 03:28 UTC (the same time in London, on GMT) against the evidence vault nnd3i8iw at 24f0b0e22666 (562 sources, latest capture 00:45 UTC on 27 October): CISA's alert of 26 October and KEV catalog version 2026.10.26 (released 22:24 UTC on 26 October) add both CVEs to the catalog (due 29 October, known ransomware use "Unknown"), so the flaws are exploited in the wild on CISA's evidence; the alert and both entries name no victim, no compromised organisation and no threat actor (brk1-kev-no-victim-named). The claim stands, and now says exploited and compromised apart. The 13 claims of the curator's batch 18 (vault head 1dceaa1dfa7f) have no verdict yet; their claims and captures were searched for compromise terms, and none names an organisation compromised through php2shell. [fact timeline →](../../facts/no-confirmed-compromise/index.html) | this site, from every captured source in the evidence vault (562 sources, vault nnd3i8iw at head 24f0b0e22666), as of its latest capture at 00:45 UTC on 27 October | reported | **A4** Corroborated●●●●○○ | 8/28 | [CISA](../../sources/cisa-kev-json/index.html) [CISA](../../sources/cisa-alert-php-20261021/index.html) [Huntress](../../sources/huntress-php2shell-rapid-response/index.html) [Amazon](../../sources/aws-security-blog-madpot/index.html) [SecurityWeek](../../sources/securityweek-first-attempts-sensors/index.html) [SecurityWeek](../../sources/securityweek-exploitation-days-before/index.html) [Recorded Future](../../sources/recordedfuture-php2shell/index.html) [Imperva Threat Research](../../sources/imperva-blog-php2shell/index.html) [Weird Gloop](../../sources/weirdgloop-blog-php2shell/index.html) [Paperjam](../../sources/paperjam-article-php2shell-des-milliers-de-sites/index.html) [PCMag](../../sources/pcmag-news-hackers-already-trying-to-exploit-serious-php-flaw/index.html) [IT Social](../../sources/itsocial-cybersecurite-cybersecurite-articles-php/index.html) [Lupa.cz](../../sources/lupa-cvut-cyber-attack/index.html) [Yahoo! News Japan](../../sources/yahoo-jp-gmo-fx-login-leak/index.html) [産経ニュース](../../sources/sankei-dmm-service-halt/index.html) [INTERNET Watch](../../sources/impress-watch-valtec/index.html) [The Verge](../../sources/the-verge-php2shell-websites-down/index.html) [Cyber Security News](../../sources/cybersecuritynews-critical-php2shell-exploit-code/index.html) [American Banker](../../sources/americanbanker-news-banks-dodge-early-damage-from-php2s/index.html) [The Next Web](../../sources/the-next-web-php2shell-no-confirmed-breaches/index.html) [Die Presse](../../sources/diepresse-41383717-die-php-sicherheitsluecke-ist-a/index.html) [voix](../../sources/voix-business-cards-rainforest-ip-activity-an/index.html) [Haber.com](../../sources/haber-teknoloji-siber-guvenlik-baskanligi-ndan/index.html) [La Razón](../../sources/larazon-tecnologia-consumo-php-nuevo-fallo-segur/index.html) [TechGaming.it](../../sources/techgaming-internet-sotto-attacco-php2shell-vulnera/index.html) [Bitpage.de](../../sources/bitpage-php2shell-php-sicherheitsluecke-webseite/index.html) [CISA](../../sources/cisa-alert-kev-20261026/index.html) [CISA](../../sources/cisa-kev-catalog/index.html) |

## Events that cite it

| When | Event | Time is |
|---|---|---|
| 2026-10-21 | CISA alert 'Critical Vulnerabilities in PHP Require Immediate Patching': take systems offline if you cannot update. NSA press release 'PHP2Shell'. UK NCSC alert. CCCS AL26-026. CERT-FR ALE-014. ACN AL07/261021. Cloudflare, Wiz, Calif, the PHP Foundation and Daubois publish their accounts. | stated |

### Agency rows from this source
- [CISA](https://php.oct.2026.newsroom.sgit.ai/agencies/): offline yes

### Exploitation signals from this source
- [2026-10-21](https://php.oct.2026.newsroom.sgit.ai/exploitation/): 'CISA has not observed exploitation of these vulnerabilities as of the time of publication.' Neither CVE was then in the Known Exploited Vulnerabilities catalog

## The bytes
capture 20261022T081353Z · HTTP 200 · https://www.cisa.gov/news-events/alerts/2026/10/21/critical-vulnerabilities-php-require-immediate-patching- `headers.json` 30fb6764c792111ac226e0fb1ca4f574f5e2faadfc10d2150ae9dfa35ea0858d 2,825 bytes
- `page.html` be6b410fc0da16de2c1b96dc3132a195632d636467ab7c859c343494fa7accfa 53,868 bytes
- `provenance.json` ea18f4dbc502d3c87b5d9a6c83d49ff128544ad074140c502f37abff350d9f8a 1,110 bytes
- `rendered.html` 0e3e08492a52d48e8ccb18f836df984af4f15f251f6089697676b540458b3371 78,116 bytes
- `screenshot.png` 2724e9107ccae45a888b3531fdc43373b154be3eeadb78841791dcb6a60a34c1 384,239 bytes
- `text.txt` 7bf853872a073bde9c2d71a41fbf9bfd3cda8147c278ab15426ebc9c8e627a9f 3,223 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.44 · data as of 2026-10-27T00:45Z · vault commit 24f0b0e22666 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/cisa-alert-php-20261021/index.html
