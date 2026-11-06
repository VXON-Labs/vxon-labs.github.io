## What is this PR?

<!-- Tick ONE and delete the rest -->
- [ ] Writeup (HTB machine, CTF challenge, lab)
- [ ] Research / article / blog post
- [ ] CVE / vulnerability report
- [ ] Site change (layout, CSS, JS, config)
- [ ] Small fix (typo, broken link, metadata)

## Summary

<!-- 1-3 sentences. Post: what is it about and who wrote it? Site change: what changed and why? -->

---

## If this adds or edits a post (writeup, research, CVE)

**Format**
- [ ] File is in `content/posts/`, named in lowercase with hyphens and no spaces (e.g. `cobblestone-htb-linux-insane.md`)
- [ ] Front matter has `title`, `description` (1-2 sentences), `author`, `date` (`YYYY-MM-DD`) and `tags`
- [ ] Title is specific (platform + name, or vulnerability + product), not generic
- [ ] Either the full post is here, or `redirect:` points to a **public** link that opens while logged out (checked in a private window)
- [ ] Images are in `static/images/` and are reasonably small

**Safety and ethics**
- [ ] Writeup: the machine or challenge is **retired**, or the CTF has **ended** (no active HTB machines or running events)
- [ ] No live flags, passwords, API keys, tokens, session cookies or personal data
- [ ] Everything was tested only on systems I own or am explicitly authorised to test
- [ ] CVE / vulnerability: disclosure status is stated (vendor notified / CVE assigned / patch available) and there is no working exploit for an unpatched issue
- [ ] Original work: sources, tools and prior research are credited, and no copied or copyrighted text

---

## If this changes the site itself

- [ ] `hugo --minify` builds with no errors (Hugo 0.123.7, same as CI)
- [ ] Checked at phone width and in at least two themes
- [ ] No new third-party scripts, trackers or external fonts
- [ ] Naming is **VXON Labs** / `VXON-Labs` (no `VX0N`, no "Vxon Team")
- [ ] Screenshot or screen recording attached for visual changes

---

## Before you submit

- [ ] I am on a branch, not `main`
- [ ] I read my own diff and it only contains what I meant to change
