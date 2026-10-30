# Fact: The UK's NCSC, the NSA and their counterparts in the EU and Australia advise tak

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

The UK's NCSC, the NSA and their counterparts in the EU and Australia advise taking systems offline where patching is not feasible Who says it, its status (disputed), its sources, and its timeline from publication to this site.

Fact · advice · disputed

# The UK's NCSC, the NSA and their counterparts in the EU and Australia advise taking systems offline where patching is not feasible

**Who says it:** Not the BBC. This site's synthesis of the agencies' own pages. The BBC wrote only that the NCSC 'as well as its counterparts in the EU and Australia, earlier urged those who use PHP to apply the fixes', quoted the NCSC's offline sentence, and reported the NSA's call to go offline. · **Sources:** [ACSC](../../sources/acsc-alert-php/index.html) [CERT-EU](../../sources/certeu-sa-2026-018/index.html) [NCSC-NL](../../sources/ncsc-nl-php2shell/index.html) [ACN / CSIRT Italia](../../sources/acn-it-php2shell/index.html) [JPCERT/CC](../../sources/jpcert-at260033/index.html) [NSA](../../sources/nsa-press-php-4630238/index.html) [NCSC UK](../../sources/ncsc-news-php/index.html) [CERT-FR](../../sources/certfr-2026-ale-014/index.html)

Australia's ACSC gives no offline advice (as captured). CERT-EU says isolate internet-facing applications, CERT-FR isolate affected equipment. Italy's ACN does say to consider taking sites offline (acn-it-php2shell, capture 20261022T081354Z, line 70). The Netherlands and Japan give no offline advice; New Zealand's page gives none. Corrected 27 October 2026, PROJECT-001: this claim was attributed to the BBC ('by': 'BBC') and marked 'contradicted'; the BBC did not write it, so it cannot be contradicted against the BBC; the status now follows the agencies' own pages (holds in part: Australia not shown). Superseded note: 'Australia's ACSC gives no offline advice. CERT-EU says isolate. The Netherlands, Italy, Japan and New Zealand give no offline advice.' (its statement that Italy gives no offline advice was wrong).

## Fact-check

**A1** Weak signal●○○○○○ · Advice · verdict: **holds in part**

The captured BBC page does not say this: it says the NCSC 'as well as its counterparts in the EU and Australia' urged users 'to apply the fixes', and attributes the offline quote to the NCSC alone. On the substance, NCSC (after mitigations) and NSA advise offline, CERT-EU and CERT-FR advise isolation, and Italy's ACN advises taking sites offline; only Australia is not shown (ACSC's page as captured has no offline advice). 'Contradicted' overstates an absence for one of four parties and mislabels the BBC's statement. Corrected 27 October 2026, PROJECT-001: the claim is no longer attributed to the BBC and its status is now 'disputed', so status_fit is ok.

| Capture checked | Result | What it says | sha256 of the text read |
|---|---|---|---|
| [bbc-live-ckgel5xp2xv9t](../../sources/bbc-live-ckgel5xp2xv9t/index.html) | partial | *its counterparts in the EU and Australia, earlier urged those who use PHP to apply the fixes.* | c88b8c5f4c6bc07d |
| [acsc-alert-php](../../sources/acsc-alert-php/index.html) | absent | *Apply available security updates and other appropriate mitigations* | 9370af142ded6de9 |
| [certeu-sa-2026-018](../../sources/certeu-sa-2026-018/index.html) | carries | *Where that is not feasible, organisations should consider isolating internet-facing applications from public networks until a fix is applied and verified.* | c65c95cf165d9ed7 |
| [ncsc-nl-php2shell](../../sources/ncsc-nl-php2shell/index.html) | absent | *If immediate patching is not possible, follow PHP's temporary mitigations, including disabling session.upload_progress, restarting workers,* | f3eec24a226910fb |
| [acn-it-php2shell](../../sources/acn-it-php2shell/index.html) | carries | *si raccomanda di valutare di porre offline i siti e i servizi web che utilizzano versioni vulnerabili di PHP* | 19fac2edc25161cd |
| [jpcert-at260033](../../sources/jpcert-at260033/index.html) | absent | *十分なテストを実施の上、速やかに修正済みバージョンを適用してください。* | 1fea87241b307f92 |
| [ncsc-news-php](../../sources/ncsc-news-php/index.html) | carries | *or applying them would take too long, you should consider taking the system offline until it can be fully mitigated.* | a18ceeb011a3fe6f |
| [nsa-press-php-4630238](../../sources/nsa-press-php-4630238/index.html) | carries | *If an immediate update is not feasible, it is recommended that organizations take the system offline until it can be fully mitigated.* | 8a8553ea1ffcd794 |
| [certfr-2026-ale-014](../../sources/certfr-2026-ale-014/index.html) | carries | *Le CERT-FR recommande d'isoler les équipements affectés puis de procéder à la migration vers une version maintenue* | f9e9557ab49ddb95 |

Open tickets: [Finding-43](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-43), [Finding-44](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-44), [Finding-45](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-45), [Finding-87](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-87), [Finding-129](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-129), [Finding-131](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-131).

Graded in Run-1, resting on captures up to 2026-10-22 08:48 UTC. The scale is on [the fact-check page](https://php.oct.2026.newsroom.sgit.ai/factcheck/#ladder).

## This fact over time
- 2026-10-21ACSC publishes [Critical vulnerabilities in PHP](../../sources/acsc-alert-php/index.html)
- 2026-10-21ACN / CSIRT Italia publishes [PHP2Shell: sanate vulnerabilità critiche in PHP (AL07/261021/CSIRT-ITA)](../../sources/acn-it-php2shell/index.html)
- 2026-10-21NSA publishes [NSA Advisory: Critical Patches Recommended for PHP Vulnerabilities](../../sources/nsa-press-php-4630238/index.html)
- 2026-10-21NCSC UK publishes [Critical security issue affecting PHP](../../sources/ncsc-news-php/index.html)
- 2026-10-21CERT-FR publishes [[Màj] Multiples vulnérabilités dans PHP (CERTFR-2026-ALE-014)](../../sources/certfr-2026-ale-014/index.html)
- 2026-10-21 15:20 UTCCERT-EU publishes [Security Advisory 2026-018: Critical Vulnerabilities in PHP](../../sources/certeu-sa-2026-018/index.html)
- 2026-10-21 15:25 UTCNCSC-NL publishes [NCSC-NL/php2shell: Operational information regarding the 2026 php2shell vulnerabilities](../../sources/ncsc-nl-php2shell/index.html)
- 2026-10-22JPCERT/CC publishes [PHPにおける複数の脆弱性（CVE-2026-109618、CVE-2026-109619）に関する注意喚起 (JPCERT-AT-2026-0033)](../../sources/jpcert-at260033/index.html)
- 2026-10-22 08:09 UTCSaved into the evidence vault: NCSC-NL, then 1 more capture
- 2026-10-22 08:09 UTCSaved into the evidence vault: NSA
- 2026-10-22 08:09 UTCSaved into the evidence vault: NCSC UK
- 2026-10-22 08:13 UTCSaved into the evidence vault: CERT-EU
- 2026-10-22 08:13 UTCSaved into the evidence vault: ACN / CSIRT Italia
- 2026-10-22 08:13 UTCSaved into the evidence vault: CERT-FR
- 2026-10-22 08:16 UTCSaved into the evidence vault: ACSC
- 2026-10-22 08:17 UTCSaved into the evidence vault: JPCERT/CC
- 2026-10-22Enters this site as contradicted in v0.1.0 (reconstructed from git)
- 2026-10-27Status changes from contradicted to disputed in v0.22.46

Published: when the source says it was published. Saved: the first capture into the evidence vault. The rest are this site: the release in which the fact first appeared and every release that changed its wording, sources or status.

## What it rests on

## Where this fact appears

In the briefings for:
CCaseyWebsite ownerTTaylorProject or programme managerJJordanBoard member or executiveSSamSecurity leadRRowanJournalistRRobinCISOAAveryCTOMMorganData protection officerJJamieHead of AppSecRRileyCommunications team
And on [every claim](https://php.oct.2026.newsroom.sgit.ai/claims/#offline-allies).

## Every version of this fact
v1 · site v0.1.0 · 22 October 2026 · contradicted
```
The UK's NCSC, the NSA and their counterparts in the EU and Australia advise taking systems offline where patching is not feasible
Who says it: BBC
Status: contradicted
Topic: advice
Sources: bbc-live-ckgel5xp2xv9t, acsc-alert-php, certeu-sa-2026-018, ncsc-nl-php2shell, acn-it-php2shell, jpcert-at260033
```
v2 · site v0.22.46 · 27 October 2026 · disputedThe UK's NCSC, the NSA and their counterparts in the EU and Australia advise taking systems offline where patching is not feasibleWho says it: Not the BBC. This site's synthesis of the agencies' own pages. The BBC wrote only that the NCSC 'as well as its counterparts in the EU and Australia, earlier urged those who use PHP to apply the fixes', quoted the NCSC's offline sentence, and reported the NSA's call to go offline.Status: contradicteddisputedTopic: adviceSources: bbc-live-ckgel5xp2xv9t, acsc-alert-php, certeu-sa-2026-018, ncsc-nl-php2shell, acn-it-php2shell, jpcert-at260033jpcert-at260033, nsa-press-php-4630238, ncsc-news-php, certfr-2026-ale-014


---
site v0.22.54 · data as of 2026-10-29T17:13Z · vault commit cd9375f1aefd · https://refs.php.oct.2026.newsroom.sgit.ai/facts/offline-allies/index.html
