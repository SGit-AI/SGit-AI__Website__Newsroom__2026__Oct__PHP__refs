# Source: PHP2Shell Response | SecOps Remediation Playbook | Zscaler

> Research: collected from outside sources and what this site derives from them; every fact links to a saved copy of its source.

Zscaler: what it says, the claims and events that cite it, and the hashes of every captured file.

Source · news · secondary · captured

# PHP2Shell Response | SecOps Remediation Playbook | Zscaler

**Zscaler** · [https://www.zscaler.com/fr/blogs/cybersecurity-best-practices/php2shell-and-limits-patching-secops-playbook-layered-response](https://www.zscaler.com/fr/blogs/cybersecurity-best-practices/php2shell-and-limits-patching-secops-playbook-layered-response) · published not stated in the capture · added by `curator@php.newsroom` · slug `zscaler-fr-blogs-cybersecurity-best-practices-ph`

Promoted from the source watch (pack copy 7r83qic5), snapshot 20261102T072810Z, queue priority 2 (mechanical selection by researcher@php.newsroom, read by the curator). A vendor blog post (Zscaler, a layered-response playbook) on PHP2Shell. It reports the speed of exploitation seen on the vendor's internet-facing deco...

## What it says, as the collector read it

#### PHP2Shell Response | SecOps Remediation Playbook | Zscaler

Promoted by curator@php.newsroom from the source watch (vault `oq9gflln`, read from its pack copy `7r83qic5`), page `be/news/zscaler/fr-blogs-cybersecurity-best-practices-php2shell-and-limits-p`, snapshot `20261102T072810Z`. Copied byte for byte; every file's sha256 is in `captures/20261102T072810Z/provenance.json` and was re-checked against the watch's own hashes.

#### What the page says

_Curator's reading of the capture._

A vendor blog post (Zscaler, a layered-response playbook) on PHP2Shell. It reports the speed of exploitation seen on the vendor's internet-facing decoys (in the first 48 hours 187 events across 23 high-priority IPs, and by the 96-hour mark 3,038 scanning and exploit attempts from 248 unique IPs, with some activity predating the public announcement), relays Qualys's finding that only 199,000 of about 156 million PHP installations were patched within 12 hours and OX Security's that 99.3% were unpatched after 24 hours and nearly 94% after five days (noting the figures omit how many were internet-exposed), and says about a third of PHP sites run PHP 7 or older with no official fix, that about 2.24 million internet-facing hosts advertise PHP of which 59% of those reporting a version run a branch with no official security release, and that PHP 8.2 loses security support on 31 December 2026. It then argues patching alone is not enough and lists layered controls, ending in the vendor's own products.

> Qualys analysis found that only 199,000 of approximately 156 million PHP installations were patched within the first 12 hours after disclosure, a fraction of 1%.

#### Why it is here

From the promotion queue (`index/promote.json`, priority 2): Mentions CVE-2026-109618/109619 or php2shell: "PHP2Shell Response | SecOps Remediation Playbook | Zscaler". Selected mechanically, not read by a person. Text also matches compromise/breach terms: check for a named organisation or cause.

#### Capture notes

Language `fr-FR`. A vendor's marketing-adjacent blog: its recommended controls and product descriptions are not recorded, and the exploit-path remark is not copied. The capture shows no publication date; the text refers to the previous week's disclosure. Nothing in the page addresses an AI or hides text from a reader.

## Claims that cite it

No claim cites this source yet.

## Events that cite it

No timeline event cites this source yet.

## The bytes
capture 20261102T072810Z · HTTP 200 · https://www.zscaler.com/fr/blogs/cybersecurity-best-practices/php2shell-and-limits-patching-secops-playbook-layered-response- `headers.json` 44870fc3e002bcf2d4b868e3e3c7352cdb6543ef18bb3254d4f018357d8ef8cd 7,541 bytes
- `page.html` 636afa9c757f76c9bc8a3e0b837f6568a18a95be4cf4003e76053ffef4ced608 324,672 bytes
- `provenance.json` 14fc14be1c64b9d3244bd22fe73c31eecefd9f3d1fe5a5ba019a70b5c20cd731 1,817 bytes
- `rendered.html` b5b1257ee44a0aa42c6fc60cd6846c4dcfdde559e4bbfe8228b8cd356cd5180f 552,315 bytes
- `screenshot.jpg` 4d4d964c9a32dac185ef2a4733a5e793d8d4552d9e2991af72cc42ad5511f78f 975,698 bytes
- `text.txt` 7cabdeaedd5c18012a5465fd9ec8a5cb18fa6c0d230a9953dfa83195fbe4714f 20,547 bytes

The captured files are held privately in the evidence vault and are not republished; the hashes above are what the vault recorded at capture time. [Every source →](../index.html)


---
site v0.22.58 · data as of 2026-11-03T12:16Z · vault commit a8e4e3dc5490 · https://refs.php.oct.2026.newsroom.sgit.ai/sources/zscaler-fr-blogs-cybersecurity-best-practices-ph/index.html
