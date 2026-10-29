# Fact: The last PHP core RCE, CVE-2024-4577, was exploited in the wild one day after di

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

The last PHP core RCE, CVE-2024-4577, was exploited in the wild one day after disclosure and in KEV three days after; php2shell was not in KEV one day after disclosure (catalog version 2026.10.21) and both its CVEs were added on 26 October, five days after the fixes of 21 October (catalog version 2026.10.26) Who says it, its status (reported), its sources, and its timeline from publication to this site.

Fact · exploitation · reported

# The last PHP core RCE, CVE-2024-4577, was exploited in the wild one day after disclosure and in KEV three days after; php2shell was not in KEV one day after disclosure (catalog version 2026.10.21) and both its CVEs were added on 26 October, five days after the fixes of 21 October (catalog version 2026.10.26)

**Who says it:** CISA KEV catalog; Akamai (2024) · **Sources:** [CISA](../../sources/cisa-kev-json/index.html) [CVE record](../../sources/cve-cve-2024-4577/index.html) [Akamai Security Research](../../sources/akamai-blog-cve-2024-4577-one-day/index.html) [CISA](../../sources/cisa-kev-catalog/index.html) [CISA](../../sources/cisa-alert-kev-20261026/index.html)

The KEV dates are counted from the captured catalog; 'exploited in the wild one day after disclosure' rests on Akamai alone. Revised by the correspondent on 27 October (breaking desk, correspondent's role): the claim ended 'php2shell is not in KEV after one day', in the present tense; both CVEs are in catalog version 2026.10.26 with dateAdded 2026-10-26. The one-day check is kept, with its catalog version, and the listing added.

## Fact-check

**A2** Reported●●○○○○ · Record · verdict: **holds in part**

'Reported' now fits, and the note says the one-day exploitation rests on Akamai alone. The claim text still calls CVE-2024-4577 'the last PHP core RCE', which the CVE record does not carry (a PHP-CGI argument injection on Windows); and 'not in KEV after one day' should name the catalog version checked. Finding-20 partly fixed; Finding-21 open. Run 12: the claim now carries both halves from the catalogs: version 2026.10.21 (not listed one day after disclosure) and 2026.10.26 (both CVEs added 26 October, five days after the 21 October fixes; due date 29 October). The 2024 half, CVE-2024-4577 'exploited one day after disclosure', still rests on Akamai alone, which keeps the grade at A2 holds-in-part.

| Capture checked | Result | What it says | sha256 of the text read |
|---|---|---|---|
| [cisa-kev-json](../../sources/cisa-kev-json/index.html) | carries | *nothing that carries it* | ef8fffede5c47200 |
| [cve-cve-2024-4577](../../sources/cve-cve-2024-4577/index.html) | carries | *nothing that carries it* | e8cc1b1dcd1a3333 |
| [akamai-blog-cve-2024-4577-one-day](../../sources/akamai-blog-cve-2024-4577-one-day/index.html) | carries | *As early as one day after disclosure, the SIRT observed numerous exploit attempts to abuse this vulnerability* | f7a58be0ecaaa8db |
| [akamai-blog-cve-2024-4577-one-day](../../sources/akamai-blog-cve-2024-4577-one-day/index.html) | partial | *we observed exploit attempts targeting this PHP flaw on our honeypot network within 24 hours of its disclosure.* | f7a58be0ecaaa8db |
| [cisa-alert-kev-20261026](../../sources/cisa-alert-kev-20261026/index.html) | carries | *CVE-2026-109618 – PHP Memory Corruption Vulnerability* | 9c124af5dc9e5115 |
| [cisa-kev-catalog](../../sources/cisa-kev-catalog/index.html) | carries | *"dateReleased": "2026-10-26T22:24:24.6101Z"* | 653c72ea869cbca7 |

Open tickets: [Evidence-1](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Evidence-1), [Evidence-19](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Evidence-19), [Finding-20](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-20), [Finding-21](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-21), [Finding-76](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-76).

Graded in Run-12, resting on captures up to 2026-10-27 00:45 UTC. The scale is on [the fact-check page](https://php.oct.2026.newsroom.sgit.ai/factcheck/#ladder).

## This fact over time
- 2024Akamai Security Research publishes [CVE-2024-4577 Exploits in the Wild One Day After Disclosure](../../sources/akamai-blog-cve-2024-4577-one-day/index.html)
- 2024-06-09 19:42 UTCCVE record publishes [CVE-2024-4577 (PHP-CGI argument injection)](../../sources/cve-cve-2024-4577/index.html)
- 2026-10-21 14:04 UTCCISA publishes [CISA Known Exploited Vulnerabilities catalog (JSON feed)](../../sources/cisa-kev-json/index.html)
- 2026-10-21 14:04 UTCCISA publishes [Known Exploited Vulnerabilities Catalog (JSON feed)](../../sources/cisa-kev-catalog/index.html)
- 2026-10-22 11:25 UTCSaved into the evidence vault: Akamai Security Research
- 2026-10-22Enters this site as confirmed in v0.2.0 (reconstructed from git)
- 2026-10-24Status changes from confirmed to reported in v0.12.1
- 2026-10-26CISA publishes [CISA Adds Two Known Exploited Vulnerabilities to Catalog | CISA](../../sources/cisa-alert-kev-20261026/index.html)
- 2026-10-27 00:45 UTCSaved into the evidence vault: CISA
- 2026-10-27 00:45 UTCSaved into the evidence vault: CISA
- 2026-10-27 00:45 UTCSaved into the evidence vault: CISA
- 2026-10-27Reworded or re-sourced in v0.22.43

Published: when the source says it was published. Saved: the first capture into the evidence vault. The rest are this site: the release in which the fact first appeared and every release that changed its wording, sources or status.

## What it rests on

## Where this fact appears

In the briefings for:
AAlexCurious readerCCaseyWebsite ownerJJordanBoard member or executiveSSamSecurity leadBBlakeAnalyst or policy advisorRRobinCISOQQuinnCFOMMorganData protection officerJJamieHead of AppSec
And on [every claim](https://php.oct.2026.newsroom.sgit.ai/claims/#kev-precedent).

## Every version of this fact
v1 · site v0.2.0 · 22 October 2026 · confirmed
```
The last PHP core RCE, CVE-2024-4577, was exploited in the wild one day after disclosure and in KEV three days after; php2shell is not in KEV after one day
Who says it: CISA KEV catalog; Akamai (2024)
Status: confirmed
Topic: exploitation
Sources: cisa-kev-json, cve-cve-2024-4577, akamai-blog-cve-2024-4577-one-day
```
v2 · site v0.12.1 · 24 October 2026 · reportedThe last PHP core RCE, CVE-2024-4577, was exploited in the wild one day after disclosure and in KEV three days after; php2shell is not in KEV after one dayWho says it: CISA KEV catalog; Akamai (2024)Status: confirmedreportedTopic: exploitationSources: cisa-kev-json, cve-cve-2024-4577, akamai-blog-cve-2024-4577-one-dayv3 · site v0.22.43 · 27 October 2026 · reportedThe last PHP core RCE, CVE-2024-4577, was exploited in the wild one day after disclosure and in KEV three days after; php2shell iswas not in KEV after one day after disclosure (catalog version 2026.10.21) and both its CVEs were added on 26 October, five days after the fixes of 21 October (catalog version 2026.10.26)Who says it: CISA KEV catalog; Akamai (2024)Status: reportedTopic: exploitationSources: cisa-kev-json, cve-cve-2024-4577, akamai-blog-cve-2024-4577-one-dayakamai-blog-cve-2024-4577-one-day, cisa-kev-catalog, cisa-alert-kev-20261026


---
site v0.22.51 · data as of 2026-10-28T17:15Z · vault commit 75668aedfb6d · https://refs.php.oct.2026.newsroom.sgit.ai/facts/kev-precedent/index.html
