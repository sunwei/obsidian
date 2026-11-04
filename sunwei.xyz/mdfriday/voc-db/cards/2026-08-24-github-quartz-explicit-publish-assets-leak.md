---
type: voc
id: "github-quartz-2531"
date: 2026-08-24
platform: github
url: "https://github.com/jackyzha0/quartz/issues/2531"
author: "archifont"
title: "Quartz explicit-publish still emits assets from unpublished notes"
quote: "`explicit-publish` keeps unpublished notes off the site, but attachments belonging to those notes are still copied into `public/` and served. A vault used with `explicit-publish` therefore publishes every image, PDF and video it contains, including those only ever referenced from notes marked `publish: false`.\n\nThis is independent of `encrypted-pages` — the asset is emitted with that plugin disabled entirely, so the cause is `explicit-publish` alone. But the two together make the gap wider: pages are encrypted, attachments are not, so the files are readable without the password that gates everything else.\n\nI do not think this is a misconfiguration — the [Assets plugin docs](https://quartz.jzhao.xyz/plugins/assets) say it emits \"all non-Markdown static assets in your content folder\" and has no configuration options. But when a filter plugin is enabled, \"all\" is probably not what the user is asking for."
need: "Selective publish that keeps unpublished notes AND their attachments off the public site."
pain: "With explicit-publish, unpublished notes stay off the site but their images/PDFs/videos are still copied into public/ and served — privacy leak for vaults mixing publish:false media."
topic: "[[selective-publish-and-privacy]]"
persona: developer
competitor:
  - "Quartz"
fit: supported
intensity: need
decision: opportunity
reply: not-replied
engagement: none
reply_url:
last_touch:
seo_brief: "[[B03-publish-obsidian-folder]]"
source:
tags:
  - voc
---

# Quartz explicit-publish still emits assets from unpublished notes

> `explicit-publish` keeps unpublished notes off the site, but attachments belonging to those notes are still copied into `public/` and served. A vault used with `explicit-publish` therefore publishes every image, PDF and video it contains, including those only ever referenced from notes marked `publish: false`.

This is independent of `encrypted-pages` — the asset is emitted with that plugin disabled entirely, so the cause is `explicit-publish` alone. But the two together make the gap wider: pages are encrypted, attachments are not, so the files are readable without the password that gates everything else.

I do not think this is a misconfiguration — the [Assets plugin docs](https://quartz.jzhao.xyz/plugins/assets) say it emits "all non-Markdown static assets in your content folder" and has no configuration options. But when a filter plugin is enabled, "all" is probably not what the user is asking for.

## Context

GitHub issue jackyzha0/quartz#2531 by @archifont opened 2026-08-24. Reports that Quartz `explicit-publish` hides unpublished notes but still emits their attachments into `public/`. Independent of encrypted-pages. Classic selective-publish / privacy voice. English.

## Our assessment

- Fit: supported · Intensity: need · Decision: opportunity
- MDFriday folder/selective publish is meant to publish only what you choose; password protection also available on all plans. Confirms market pain around vault media leaking when only some notes are public. Supports [[B03-publish-obsidian-folder|B03]] (and selective-publish topic).
- Staged 2026-10-27-08 GitHub scan (URL was missing from url-index).

## Follow-up log

- (none yet)
