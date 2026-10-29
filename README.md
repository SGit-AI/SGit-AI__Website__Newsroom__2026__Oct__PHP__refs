# SGit-AI__Website__Newsroom__2026__Oct__PHP__refs

The references: a page per source and per fact, who said what, the graphs of what the sources say, Wikipedia, the code read from the fix, Pulse, the vaults, for the newsroom's site on the two critical PHP flaws of October 2026 (CVE-2026-109618 and CVE-2026-109619, "php2shell"), served at **https://refs.php.oct.2026.newsroom.sgit.ai/**.

One of six repositories: press (the build, the gate, the release), data (the API), refs, updates, team and site. Its pages are the sections `sources/`, `facts/`, `actors/`, `wikipedia/`, `graph/`, `fractal/`, `review/`, `code/`, `pulse/`, `vaults/`; every other address of the site answers here with a redirect to the site that serves it. The rules for working here are in [CLAUDE.md](CLAUDE.md).

## Edition takes (log of pushes made only to take an edition)

Each entry is signed with the session key named in it. To check one: save the text block to a file and its signature block to another, then `sgit pki verify <text> <signature>`.

```text
Edition take, 2026-10-28T23:59:45Z: a push to refs so that its deploy takes edition 0.22.51.
Who: dev@php.newsroom, session_015gaHdeQPc82wWvW99oY7RT, key sha256:d1331dd12796268e (team records/keys/dev.json).
On whose word: the editor, in that session, 28 October 2026.
Why: the press published edition 0.22.51 (refs patch included); refs takes it only at its own next push, and nobody had pushed here since. refs owns no folder for a log file (press.json own: README.md and CLAUDE.md only), so the entry is here.
Changes: this entry only. Not a force-push, not an empty commit. Rule: team board dev-0016.
```

```json
{
  "signature": "LiI93rwWAHyGqhH74WhSGDGkpuk/QipqZASepauIQa7vruG2Yi9CfsjaqP7C047eFB1+QFX4RQrqh1mD2tcY9Q==",
  "fingerprint": "sha256:d1331dd12796268e"
}
```
