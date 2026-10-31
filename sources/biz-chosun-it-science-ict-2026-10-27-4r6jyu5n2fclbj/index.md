# Source: 포티넷, PHP 취약점 ‘PHP2Shell’ 대응 가이드 공개 - 조선비즈

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

조선비즈: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# 포티넷, PHP 취약점 ‘PHP2Shell’ 대응 가이드 공개 - 조선비즈

**조선비즈** · [https://biz.chosun.com/it-science/ict/2026/10/27/4R6JYU5N2FCLBJR3CSMLZ4FTNQ/](https://biz.chosun.com/it-science/ict/2026/10/27/4R6JYU5N2FCLBJR3CSMLZ4FTNQ/) · published 2026-10-27 · added by `curator@php.newsroom` · slug `biz-chosun-it-science-ict-2026-10-27-4r6jyu5n2fclbj`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261028T032724Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). A Korean business-press piece (Chosun Biz, 27 October) reporting that Fortinet published a response guide for PHP2Shell. It describes the two flaws (C...

## What it says, as the collector read it

#### 포티넷, PHP 취약점 ‘PHP2Shell’ 대응 가이드 공개 - 조선비즈

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `kr/news/biz-chosun/it-science-ict-2026-10-27-4r6jyu5n2fclbjr3csmlz4ftnq`, snapshot `20261028T032724Z`. Copied byte for byte; every file's sha256 is in `captures/20261028T032724Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

A Korean business-press piece (Chosun Biz, 27 October) reporting that Fortinet published a response guide for PHP2Shell. It describes the two flaws (CVE-2026-109618 and CVE-2026-109619, both CVSS 4.0 9.2, remote code execution without authentication), notes that updating a CMS or plugin alone does not fix an engine-level flaw, and lists Fortinet's four steps: identify affected systems (using external attack surface management, including containers, hosting and third-party apps), test and deploy updates and verify they reached production, interim protection by IPS, WAF or virtual patching and by restricting or isolating systems that need not be exposed, and investigation for compromise. Fortinet says its FortiGuard Labs released a virtual patch and IPS signature, that these cannot replace the update, and that FortiGate, FortiManager, FortiAnalyzer and FortiWeb are not affected.

> 보안 업데이트를 적용하더라도 공격자가 이미 확보한 접근 권한까지 제거되는 것은 아니기 때문이다.

_Curator's translation:_ "Applying the security update does not remove access the attacker has already obtained."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "포티넷, PHP 취약점 ‘PHP2Shell’ 대응 가이드 공개 - 조선비즈". Selected mechanically, not read by a person.

#### Capture notes

Language `ko`. A vendor announcement relayed by the press; the vendor statements about its own products are the vendor's own. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261028T032724Z · HTTP 200 · https://biz.chosun.com/it-science/ict/2026/10/27/4R6JYU5N2FCLBJR3CSMLZ4FTNQ/- `headers.json` 3c60d7034a11774c228ff02fedc15c072e3bea16d38e11861bf47dae42c6586a 1,509 bytes
- `page.html` d0d4cb3274229b4f5c32fee91e198ed3d6dc3b9a3c75baac23a740ec070a3d05 460,501 bytes
- `provenance.json` 5242a72c761d3b3e732b54184fe59506978b9b24e99b5776e81a8a45a3664d04 1,735 bytes
- `rendered.html` aa006ca68ce8362bcd3770eaff46e5524ff6eaf1b106d5267f5cb87768c173d7 753,685 bytes
- `screenshot.jpg` 8726c10bba05cfd41dafe7c81db8465720794c489a6838142f9cd84fab8dc386 450,901 bytes
- `text.txt` fda91cfe796239d8a8146bd18a448fa8edb9cb6eaa4ed8db77f0886979bddef1 9,909 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.55 · data as of 2026-10-30T17:13Z · vault commit 2f80607e87ad · https://refs.php.oct.2026.newsroom.sgit.ai/sources/biz-chosun-it-science-ict-2026-10-27-4r6jyu5n2fclbj/index.html
