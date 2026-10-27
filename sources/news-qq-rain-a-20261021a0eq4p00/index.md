# Source: PHP2Shell 高危漏洞补丁紧急发布，我在流量设备里发现了什么？_腾讯新闻

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

腾讯网: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell 高危漏洞补丁紧急发布，我在流量设备里发现了什么？_腾讯新闻

**腾讯网** · [https://news.qq.com/rain/a/20261021A0EQ4P00](https://news.qq.com/rain/a/20261021A0EQ4P00) · published 2026-10-21 23:00 (Beijing) · added by `curator@php.newsroom` · slug `news-qq-rain-a-20261021a0eq4p00`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261023T160435Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). Tencent News (Chinese), 21 October, by the creator account 荣姐聊AI (the page's disclaimer says creator content does not represent Tencent). A security p...

## What it says, as the collector read it

#### PHP2Shell 高危漏洞补丁紧急发布，我在流量设备里发现了什么？_腾讯新闻

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `hk/news/news-qq/rain-a-20261021a0eq4p00`, snapshot `20261023T160435Z`. Copied byte for byte; every file's sha256 is in `captures/20261023T160435Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

Tencent News (Chinese), 21 October, by the creator account 荣姐聊AI (the page's disclaimer says creator content does not represent Tencent). A security practitioner describes what a traffic threat-detection appliance caught on the day the patch came out: several suspicious requests, one of which carried the User-Agent 'php2shell-scan/1.0'. The author is careful: the first requests looked like older, unrelated session-forgery attempts, a User-Agent can be set by anyone, there was no command-execution payload and no host-side evidence, so successful remote code execution cannot be inferred. The rest recaps the PHP advisory (versions 8.2.35, 8.3.36, 8.4.27, 8.5.12; Apache mod_php the most exposed) and the stopgap measures PHP published, which are not repeated here.

> 最后，流量中没有出现明显的命令执行载荷，也没有后端主机行为证据，因此无法据此判断攻击者已经实现远程代码执行。

_Curator's translation:_ "Finally, no obvious command-execution payload appeared in the traffic and there is no back-end host evidence, so it cannot be concluded that the attacker achieved remote code execution."

_The watch reader's summary (researcher@php.newsroom, of its snapshot 20261022T181608Z, not necessarily this one):_ Tencent News first-person write-up by a SOC analyst. On 22 Oct they used ThreatBook (Weibu) TDP traffic sensors to catch suspicious requests that abuse PHP's session upload-progress feature, including a scanner whose User-Agent was 'php2shell-scan/1.0'. They give a careful analysis of what is a scan versus a real exploit. A sidebar headline says MIIT issued a risk alert and Tencent Cloud and Alibaba Cloud published advisories.

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell 高危漏洞补丁紧急发布，我在流量设备里发现了什么？_腾讯新闻". Selected mechanically, not read by a person.

#### Capture notes

Language `zh-CN`. The page has an 'Ask AI' button and ads/recommendation links (site chrome). Nothing in the article text addresses an AI or hides text from a reader. The request details the author shows are left out of the notes.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261023T160435Z · HTTP 200 · https://news.qq.com/rain/a/20261021A0EQ4P00- `headers.json` aea7e3b72758e817dd7ec1dfc1f18bb6a491138d6d9f31143df458dd1229c106 490 bytes
- `page.html` 3924aece8436a9564869859985b05ac51d74e685daf781492eb27e750caee9d2 323,379 bytes
- `provenance.json` 1ebe765a6beef1e1cba4146e4ef0117ffbcf11c81ec9aab45914fb4829e85f39 1,603 bytes
- `rendered.html` 3fc819bce68ccd1b21de17fa52229f5e66ba2ea8f41592240c2b2459b0bae2fe 415,882 bytes
- `screenshot.jpg` c79dbc57516d1b8e35417109984d1f2a98036d6597a40a4b37831436073aef29 112,150 bytes
- `text.txt` a95c73b30f448263e41a4385719b08cc015a889b427b7dc33381cce5fa05f974 12,164 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.41 · data as of 2026-10-26T17:09Z · vault commit 1dceaa1dfa7f · https://refs.php.oct.2026.newsroom.sgit.ai/sources/news-qq-rain-a-20261021a0eq4p00/index.html
