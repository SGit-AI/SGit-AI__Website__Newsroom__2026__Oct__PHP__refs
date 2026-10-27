# Source: Internet sotto attacco: PHP2Shell mette a rischio milioni di siti

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

TechGaming.it: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# Internet sotto attacco: PHP2Shell mette a rischio milioni di siti

**TechGaming.it** · [https://www.techgaming.it/internet-sotto-attacco-php2shell-vulnerabilita-pokemon-plex-gitlab/](https://www.techgaming.it/internet-sotto-attacco-php2shell-vulnerabilita-pokemon-plex-gitlab/) · published 2026-10-22T18:55:29+02:00 · added by `curator@php.newsroom` · slug `techgaming-internet-sotto-attacco-php2shell-vulnera`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261023T160435Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). TechGaming.it (Italian), 22 October: a roundup, via Kotaku, of the week's security problems in PHP, GitLab and Plex and their effect on gaming. On PHP...

## What it says, as the collector read it

#### Internet sotto attacco: PHP2Shell mette a rischio milioni di siti

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `it/news/techgaming/internet-sotto-attacco-php2shell-vulnerabilita-pokemon-plex`, snapshot `20261023T160435Z`. Copied byte for byte; every file's sha256 is in `captures/20261023T160435Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

TechGaming.it (Italian), 22 October: a roundup, via Kotaku, of the week's security problems in PHP, GitLab and Plex and their effect on gaming. On PHP2Shell it gives Cloudflare's figures (thousands of attempts in the ten hours before disclosure, tens of thousands in the first 45 minutes after), says several Pokémon-related apps were temporarily suspended for emergency maintenance, that Square Enix confirmed unauthorised access to its systems, and that the PHP vulnerability reportedly contributed to the decision to end two long-running Japanese mobile games for good. It then covers separate issues: a GitLab flaw (CVE-2026-110264, CVSS 10, very old versions) and four Plex vulnerabilities that can be combined, some already used by attackers to mine cryptocurrency and route traffic. The link between Square Enix's unauthorised access and PHP2Shell is not established.

> Diverse applicazioni legate al franchise Pokémon sono state temporaneamente sospese per consentire interventi di manutenzione straordinaria, mentre Square Enix ha confermato episodi di accesso non autorizzato ai propri sistemi.

_Curator's translation:_ "Several applications linked to the Pokémon franchise were temporarily suspended for extraordinary maintenance, while Square Enix confirmed episodes of unauthorised access to its systems."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "Internet sotto attacco: PHP2Shell mette a rischio milioni di siti". Selected mechanically, not read by a person.

#### Capture notes

Language `it-IT`. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

| Claim | Who says it | Status | [Fact-check](https://php.oct.2026.newsroom.sgit.ai/factcheck/) | Primary | Sources |
|---|---|---|---|---|---|
| As of 14:42 UTC on 26 October, no named organisation has said it was compromised through php2shell. Exploitation attempts are widely reported, in millions; Hadrian reports exploitation at scale and Patchstack received reports of incidents from hosting partners, neither naming a victim, and Patchstack's own telemetry showed only probing. Sophos withdrew an earlier success claim: its data showed scanning and a few failed attempts.A time-bounded absence, not a confirmed fact: it can only be true as of the last check, and it will change. Changed from "confirmed" on 22 October at the editor's request. Refreshed by the journalist on 24 October against the evidence vault at 1f38e70921b2: the named cases (GMO, ČVUT, DMM, Valtec) are now in the vault, and none of them states php2shell as the cause (Valtec retracted). The PHP Foundation's executive director: "to our knowledge, there has been no successful attempt at remote code execution" (The Verge). Luxembourg: no institution has announced an intrusion (Paperjam). Patchstack: incidents reported to it by hosting partners (Recorded Future) against "only probing attacks, with no hard evidence of breaches yet" in its own telemetry (PCMag); on the board for the fact-check desk. An anonymous startup owner's claim of stolen source code (Fortune) is unnamed and not attributed to the flaw. Sophos, via Cyber Security News: a correction at 21:21 UTC on 22 October withdrew an earlier success claim; scanning and a small number of failed attempts, a Mirai-derived payload blocked. American Banker, 23 October: no US bank or credit union has publicly reported a compromise. Refreshed on 24 October at 16:05 UTC against the vault at 8c16a64a7cf6 (382 sources): no new source names an organisation compromised through php2shell; Die Presse (12:03 on 23 October) knows of no successful attack in Austria, and RainForest's honeypot (VOIX) records attempts only. Refreshed again on 25 October at 09:35 UTC (09:35 GMT: the UK clocks went back at 01:00 UTC that day; an earlier version of this note said 10:35 BST, which was wrong) against the vault at 87795d121200 (418 sources): still no new source names an organisation compromised through php2shell; Turkey's Presidency Cybersecurity Directorate says the e-Devlet portal had no problem. Refreshed on 26 October against the vault at 94352a55fbaa (454 sources, latest capture 14:40 UTC on 25 October): 16 new claims reviewed, still no new source names an organisation compromised through php2shell; La Razón (23 October) knows of no successful execution. Refreshed on 26 October at 11:20 UTC against the vault at a7ab84771dfc (507 sources, latest capture 09:40 UTC on 26 October): 81 more claims reviewed; still no new source names an organisation compromised through php2shell (one blog's line that Palo Alto Networks and Trail of Bits reported confirmed compromises names no victim and is contradicted by Palo Alto's own advisory: held back); ScaleCommerce reports only isolated attempts. Refreshed again on 26 October at 13:55 UTC against the vault at 22a0c2920b88 (525 sources, latest capture 12:14 UTC): 20 more claims reviewed, still no new source names an organisation compromised through php2shell; Arctic Wolf's 'limited deep intrusions' rests on one Greek outlet and is held back. Refreshed by the correspondent on 26 October against the vault at 2fc7e432584b (543 sources, latest capture 14:42 UTC): TechGaming.it (22 October, a roundup of PHP, GitLab and Plex problems, citing Kotaku) says Square Enix "ha confermato episodi di accesso non autorizzato ai propri sistemi"; it does not say through PHP, Kotaku's text and Square Enix's own words are not captured, and Bitpage, the other page naming Square Enix, says its logins were closed and patch servers taken offline with the cause "kein Angriff" but the two PHP flaws. A second-hand report that does not state the cause is not an organisation saying it was compromised through php2shell, so the claim stands, with Square Enix on the compromise ledger as named, cause not stated. [fact timeline →](../../facts/no-confirmed-compromise/index.html) | this site, from every captured source in the evidence vault (543 sources, head 2fc7e432584b), as of its latest capture at 14:42 UTC on 26 October | reported | **A4** Corroborated●●●●○○ | 6/26 | [CISA](../../sources/cisa-kev-json/index.html) [CISA](../../sources/cisa-alert-php-20261021/index.html) [Huntress](../../sources/huntress-php2shell-rapid-response/index.html) [Amazon](../../sources/aws-security-blog-madpot/index.html) [SecurityWeek](../../sources/securityweek-first-attempts-sensors/index.html) [SecurityWeek](../../sources/securityweek-exploitation-days-before/index.html) [Recorded Future](../../sources/recordedfuture-php2shell/index.html) [Imperva Threat Research](../../sources/imperva-blog-php2shell/index.html) [Weird Gloop](../../sources/weirdgloop-blog-php2shell/index.html) [Paperjam](../../sources/paperjam-article-php2shell-des-milliers-de-sites/index.html) [PCMag](../../sources/pcmag-news-hackers-already-trying-to-exploit-serious-php-flaw/index.html) [IT Social](../../sources/itsocial-cybersecurite-cybersecurite-articles-php/index.html) [Lupa.cz](../../sources/lupa-cvut-cyber-attack/index.html) [Yahoo! News Japan](../../sources/yahoo-jp-gmo-fx-login-leak/index.html) [産経ニュース](../../sources/sankei-dmm-service-halt/index.html) [INTERNET Watch](../../sources/impress-watch-valtec/index.html) [The Verge](../../sources/the-verge-php2shell-websites-down/index.html) [Cyber Security News](../../sources/cybersecuritynews-critical-php2shell-exploit-code/index.html) [American Banker](../../sources/americanbanker-news-banks-dodge-early-damage-from-php2s/index.html) [The Next Web](../../sources/the-next-web-php2shell-no-confirmed-breaches/index.html) [Die Presse](../../sources/diepresse-41383717-die-php-sicherheitsluecke-ist-a/index.html) [voix](../../sources/voix-business-cards-rainforest-ip-activity-an/index.html) [Haber.com](../../sources/haber-teknoloji-siber-guvenlik-baskanligi-ndan/index.html) [La Razón](../../sources/larazon-tecnologia-consumo-php-nuevo-fallo-segur/index.html) [TechGaming.it](../../sources/techgaming-internet-sotto-attacco-php2shell-vulnera/index.html) [Bitpage.de](../../sources/bitpage-php2shell-php-sicherheitsluecke-webseite/index.html) |

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261023T160435Z · HTTP 200 · https://www.techgaming.it/internet-sotto-attacco-php2shell-vulnerabilita-pokemon-plex-gitlab/- `headers.json` b242a353ac37e8bed264060f690e11c624f05ae16b10f6b794367f5d08bc7e88 491 bytes
- `page.html` 3ba4259ae28924925d19db0652b3ddcc789c1219319a4d44a0e7ac57f0970770 87,655 bytes
- `provenance.json` a8c9c07742a1a8b67fdc48db05292cdb10a42bb4ff427eef328395a0f2a755a3 1,769 bytes
- `rendered.html` de0edb377cc84cfc56d0c5971e619ef7c46285ba302cc38310e1c93e647a0ffd 124,947 bytes
- `screenshot.jpg` 4daf321cd631fc535ff36cad1cd3790c703ba35c268d0dd754a89991b41a816b 396,480 bytes
- `text.txt` 75acc700630c3f2a197a81ac80c4017d2e05115f04c092bf7dd476b200baa00b 6,440 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.41 · data as of 2026-10-26T17:09Z · vault commit 1dceaa1dfa7f · https://refs.php.oct.2026.newsroom.sgit.ai/sources/techgaming-internet-sotto-attacco-php2shell-vulnera/index.html
