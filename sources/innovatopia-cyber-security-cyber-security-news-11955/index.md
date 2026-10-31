# Source: PHP2Shell、PAN-OS機器など25台がroot化 Fragnesiaと連鎖し米政府関連のADへ

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

innovatopia: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell、PAN-OS機器など25台がroot化 Fragnesiaと連鎖し米政府関連のADへ

**innovatopia** · [https://innovatopia.jp/cyber-security/cyber-security-news/119552/](https://innovatopia.jp/cyber-security/cyber-security-news/119552/) · published 2026-10-30 · added by `curator@php.newsroom` · slug `innovatopia-cyber-security-cyber-security-news-11955`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261030T121407Z, queue priority 4 (mechanical selection by researcher@php.newsroom, read by the curator). A Japanese security-trade analysis (Innovatopia, 30 October) of research by the security firm Dream Research, which on 26 October published traces of...

## What it says, as the collector read it

#### PHP2Shell、PAN-OS機器など25台がroot化 Fragnesiaと連鎖し米政府関連のADへ

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `jp/news/innovatopia/cyber-security-cyber-security-news-119552`, snapshot `20261030T121407Z`. Copied byte for byte; every file's sha256 is in `captures/20261030T121407Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

A Japanese security-trade analysis (Innovatopia, 30 October) of research by the security firm Dream Research, which on 26 October published traces of an attack that chained PHP2Shell with a Linux kernel flaw to gain root on 25 Palo Alto Networks PAN-OS firewalls and management servers. According to the article the attacker found about 19,000 exposed management interfaces with a scanning search engine and automatically attacked 240 devices in the United States, Japan, Taiwan and Korea; at a US government-linked organisation a first firewall was rooted on 23 October (UTC), a second and then the central management server were reached the next day, and the attacker began attacks on Active Directory, where Dream confirmed only the decryption of a service-account password and the listing of all users and groups. Unit 42 independently verified the attacker's tools and results; Palo Alto says management interfaces are not exposed by default, that about 0.02% of deployed devices exposed it and were affected and each was contacted, and published PAN-OS fixes by series from 25 to 29 October. Dream found an attack-support tool configured for AI models but says it has no direct evidence AI wrote the exploits or scripts, and the article notes Unit 42's 25 October withdrawal of its earlier AI-agent description from a European government case.

> Dreamは、侵害したファイアウォール24台のうち22台について、Webシェルの設置以外の活動は見つからなかったと報告しています。

_Curator's translation:_ "Dream reports that on 22 of the 24 compromised firewalls it found no activity other than the planting of a web shell."

#### Why it is here

From the promotion queue (`index/promote.json`, priority 4): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell、PAN-OS機器など25台がroot化 Fragnesiaと連鎖し米政府関連のADへ". Selected mechanically, not read by a person.

#### Capture notes

Language `ja`. Secondhand on Dream Research's own report, which is the primary. The article describes the exploit chain and the privilege-escalation technique in detail; none of that is copied here. The breaking desk's coverage of the same report is in the vault (breaking-0005). Nothing in the page addresses an AI or hides text from a reader; it names AI tools found in the attacker's environment as part of the report.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261030T121407Z · HTTP 200 · https://innovatopia.jp/cyber-security/cyber-security-news/119552/- `headers.json` 9dfab8e07c0345897172966269fba52b478d7f3d10ffa32a755095c3a142410c 1,680 bytes
- `page.html` c13830e13c294cd77e06d7cf1ea8a54b99216cc473d24bd62b1b37abcc10035b 241,562 bytes
- `provenance.json` db5772799a03c3ff1517a78468868ff3f4623ba68651c87d8d3360edb812804d 1,705 bytes
- `rendered.html` df68faf5f9c068cf49e9f7f8e12709090e850678c5f3f694ac1efd1874598d59 268,235 bytes
- `screenshot.jpg` ab8539980172e90137556a4ca78d9696774fdb9728ba0de0dc0c9e27a2b06b6e 886,744 bytes
- `text.txt` 89a4e59a60158451a405127245a33bd9d7593e8349e641d03e162c1c54201e6f 16,797 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.55 · data as of 2026-10-30T17:13Z · vault commit 2f80607e87ad · https://refs.php.oct.2026.newsroom.sgit.ai/sources/innovatopia-cyber-security-cyber-security-news-11955/index.html
