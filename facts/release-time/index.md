# Fact: The fixes were scheduled for 14:00 UTC on 21 October and were published between 

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

The fixes were scheduled for 14:00 UTC on 21 October and were published between 13:31 and 13:35 UTC Who says it, its status (confirmed), its sources, and its timeline from publication to this site.

Fact · timing · confirmed

# The fixes were scheduled for 14:00 UTC on 21 October and were published between 13:31 and 13:35 UTC

**Who says it:** PHP 8.5's release manager, Daniel Scherzer, from the repositories' history; the GitHub tags and advisories (13:34 to 13:35 UTC); php.net pre-announcement (scheduled 14:00 UTC); CERT-EU (13:30 UTC) · **Sources:** [oss-security](../../sources/openwall-oss-security-2026-10-20-34/index.html) [Daubois](../../sources/daubois-blog-php2shell-rumors/index.html) [CERT-FR](../../sources/certfr-2026-ale-014/index.html) [CERT-EU](../../sources/certeu-sa-2026-018/index.html) [php-src](../../sources/github-php-src-tags/index.html) [PHP](../../sources/github-ghsa-w8hw-w9fx-j79w/index.html) [php-src](../../sources/github-php-src-tag-php-8.5.12/index.html) [php.net](../../sources/php-net-advisory/index.html) [scherzer.dev](../../sources/scherzer-dev-wikipedia-ref-15-blog-20261022-php2shell/index.html)

CERT-EU says 13:30 UTC; the tags and advisories are stamped 13:34 to 13:35 UTC; the GitHub release 14:06 UTC; the php.net feed entries carry 00:05 to 00:35 UTC, which are authoring times, not publication times. Revised by the correspondent on 26 October 2026: the release manager's own timeline (22 October) gives 13:31 (tarballs), 13:33 (announcements), 13:34 (GitHub advisories) and 13:35 (php-src), matching the tags' stamps; 14:00 UTC was the scheduled time, which BleepingComputer and others repeat. Status from disputed to confirmed, the claim reworded to say both.

## Fact-check

**A5** Confirmed●●●●●○ measures differently · Event · verdict: **holds**

The correspondent reworded the claim on 26 October to what the records show: scheduled for 14:00 UTC on 21 October (php.net pre-announcement, the oss-security relay, the PHP Foundation), published between 13:31 and 13:35 UTC. The release manager's own timeline, from the repositories' history, gives 13:31 (tarballs), 13:33 (announcements), 13:34 (GitHub advisories) and 13:35 (php-src); the GitHub advisory is stamped 13:34:25Z and the tags 13:35:38 UTC, and CERT-EU says 13:30 UTC: independent primary records inside five minutes. Different artifacts carry other times (the GitHub release 14:06:46Z, the CVE records 13:48Z and 13:54Z, php.net feed authoring times), which is why the tension is 'measures-differently', not 'disputed'. K-010 stays open on the original embargo time, not on this claim.

| Capture checked | Result | What it says | sha256 of the text read |
|---|---|---|---|
| [openwall-oss-security-2026-10-20-34](../../sources/openwall-oss-security-2026-10-20-34/index.html) | partial | *> It is scheduled for Wednesday, 21 October 2026 at 14:00 UTC.* | 57b273733e7d5fe6 |
| [daubois-blog-php2shell-rumors](../../sources/daubois-blog-php2shell-rumors/index.html) | carries | *Published: 2026-10-21, 14:00 UTC* | 5ef17f9886aa93f7 |
| [certfr-2026-ale-014](../../sources/certfr-2026-ale-014/index.html) | partial | *L'éditeur annonce la disponibilité des correctifs de sécurité pour le 21 octobre 2026 à 16h00 heure de Paris (14h00 UTC).* | f9e9557ab49ddb95 |
| [certeu-sa-2026-018](../../sources/certeu-sa-2026-018/index.html) | partial | *The PHP team released the fixes today, 21 October 2026 at 13:30 UTC, in PHP versions 8.5.12, 8.4.27, 8.3.36 and 8.2.35* | c65c95cf165d9ed7 |
| [github-php-src-tags](../../sources/github-php-src-tags/index.html) | partial | *datetime="2026-10-21 13:35:38 UTC"* | ca0a96e8466a3479 |
| [github-ghsa-w8hw-w9fx-j79w](../../sources/github-ghsa-w8hw-w9fx-j79w/index.html) | partial | *datetime="2026-10-21T13:34:25Z"* | 79647ef8c491692c |
| [github-php-src-tag-php-8.5.12](../../sources/github-php-src-tag-php-8.5.12/index.html) | partial | *datetime="2026-10-21T14:06:46Z"* | 330630ed887249f6 |
| [php-net-advisory](../../sources/php-net-advisory/index.html) | partial | *It is scheduled for Wednesday, 21 October 2026 at 14:00 UTC.* | df0b1bba3deae282 |
| [php-foundation-blog-security-release](../../sources/php-foundation-blog-security-release/index.html) | partial | *It also moved the release from October 22nd, 14:00 UTC, to October 21st, 14:00 UTC.* | a1be057adc1c5bfa |
| [scherzer-dev-wikipedia-ref-15-blog-20261022-php2shell](../../sources/scherzer-dev-wikipedia-ref-15-blog-20261022-php2shell/index.html) | carries | *13:31: the php/web-php-distributions repository* | ddee9f1e0bb29259 |

Open tickets: [Contradiction-10](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Contradiction-10), [Finding-39](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-39), [Finding-99](https://php.oct.2026.newsroom.sgit.ai/factcheck/#Finding-99).

Graded in Run-9, resting on captures up to 2026-10-26 09:40 UTC. The scale is on [the fact-check page](https://php.oct.2026.newsroom.sgit.ai/factcheck/#ladder).

## This fact over time
- 2026-10-20 20:22 UTCoss-security publishes [Upcoming Critical PHP Security Release](../../sources/openwall-oss-security-2026-10-20-34/index.html)
- 2026-10-21Daubois publishes [What the PHP2Shell rumors got wrong, from inside the PHP security team](../../sources/daubois-blog-php2shell-rumors/index.html)
- 2026-10-21CERT-FR publishes [[Màj] Multiples vulnérabilités dans PHP (CERTFR-2026-ALE-014)](../../sources/certfr-2026-ale-014/index.html)
- 2026-10-21php.net publishes [Security advisory: Critical remote code execution vulnerabilities, update now](../../sources/php-net-advisory/index.html)
- 2026-10-21 13:34 UTCPHP publishes [RCE via OOM corruption (CVE-2026-109618)](../../sources/github-ghsa-w8hw-w9fx-j79w/index.html)
- 2026-10-21 14:06 UTCphp-src publishes [Release PHP 8.5.12](../../sources/github-php-src-tag-php-8.5.12/index.html)
- 2026-10-21 15:20 UTCCERT-EU publishes [Security Advisory 2026-018: Critical Vulnerabilities in PHP](../../sources/certeu-sa-2026-018/index.html)
- 2026-10-22scherzer.dev publishes [Blog: PHP2Shell: a Timeline](../../sources/scherzer-dev-wikipedia-ref-15-blog-20261022-php2shell/index.html)
- 2026-10-22 08:09 UTCSaved into the evidence vault: PHP
- 2026-10-22 08:09 UTCSaved into the evidence vault: php.net
- 2026-10-22 08:12 UTCSaved into the evidence vault: Daubois, then 1 more capture
- 2026-10-22 08:13 UTCSaved into the evidence vault: CERT-FR
- 2026-10-22 08:13 UTCSaved into the evidence vault: CERT-EU
- 2026-10-22 08:14 UTCSaved into the evidence vault: oss-security
- 2026-10-22 08:15 UTCSaved into the evidence vault: php-src
- 2026-10-22 08:15 UTCSaved into the evidence vault: php-src
- 2026-10-22Enters this site as disputed in v0.1.0 (reconstructed from git)
- 2026-10-25 11:45 UTCSaved into the evidence vault: scherzer.dev
- 2026-10-26Status changes from disputed to confirmed in v0.22.29

Published: when the source says it was published. Saved: the first capture into the evidence vault. The rest are this site: the release in which the fact first appeared and every release that changed its wording, sources or status.

## What it rests on

## Where this fact appears

In the briefings for:
TTaylorProject or programme managerRRowanJournalistBBlakeAnalyst or policy advisorAAveryCTO
And on [every claim](https://php.oct.2026.newsroom.sgit.ai/claims/#release-time).

## Every version of this fact
v1 · site v0.1.0 · 22 October 2026 · disputed
```
The fixes were released at 14:00 UTC on 21 October
Who says it: php.net pre-announcement; Daubois; CERT-FR (16:00 Paris)
Status: disputed
Topic: timing
Sources: openwall-oss-security-2026-10-20-34, daubois-blog-php2shell-rumors, certfr-2026-ale-014, certeu-sa-2026-018, github-php-src-tags, github-ghsa-w8hw-w9fx-j79w, github-php-src-tag-php-8.5.12, php-net-advisory
```
v2 · site v0.22.29 · 26 October 2026 · confirmedThe fixes were releasedscheduled atfor 14:00 UTC on 21 October and were published between 13:31 and 13:35 UTCWho says it: PHP 8.5's release manager, Daniel Scherzer, from the repositories' history; the GitHub tags and advisories (13:34 to 13:35 UTC); php.net pre-announcement;pre-announcement Daubois;(scheduled CERT-FR14:00 (16:00UTC); Paris)CERT-EU (13:30 UTC)Status: disputedconfirmedTopic: timingSources: openwall-oss-security-2026-10-20-34, daubois-blog-php2shell-rumors, certfr-2026-ale-014, certeu-sa-2026-018, github-php-src-tags, github-ghsa-w8hw-w9fx-j79w, github-php-src-tag-php-8.5.12, php-net-advisoryphp-net-advisory, scherzer-dev-wikipedia-ref-15-blog-20261022-php2shell


---
site v0.22.43 · data as of 2026-10-27T00:45Z · vault commit 24f0b0e22666 · https://refs.php.oct.2026.newsroom.sgit.ai/facts/release-time/index.html
