---
type: voc
id: "reddit-obsidianmd-1w5ldsd"
date: 2026-09-02
platform: reddit
url: "https://www.reddit.com/r/ObsidianMD/comments/1w5ldsd/i_turned_my_3900note_vault_into_a_3d_brain_one/"
author: "d1smiss3d"
title: "I turned my 3,900-note vault into a 3D brain. One HTML file, no plugins."
quote: |
  ![Second Brain 3D demo](https://raw.githubusercontent.com/paultaki/second-brain-3d/master/assets/demo.gif)

  I've been living in one vault for over a year and I wanted to actually see it. So I built this: a Python script (standard library only, nothing to install) that scans the vault and writes a single brain.html. Every note is a glowing node, every [[wikilink]] is a conduit, and a containment force squeezes the layout into a brain silhouette.

  The part I keep replaying is Genesis. It pulls creation dates from git history and replays the vault assembling note by note with the date ticking up. Watching a year of thinking pour in over five seconds is worth the build on its own.

  Numbers from my vault: 3,907 notes, 8,294 links, 3.4M words. Rebuild takes about a second. The file opens instantly and makes zero network requests, fonts embedded, nothing phones home. Double-click a node and it opens the note in Obsidian. Shift-click two notes and it traces the shortest thought path between them.

  Privacy got the most engineering time because my vault has my whole life in it. Folders named Private, 90-Private, or _private are never walked, never counted, never emitted, and a fail-closed check re-verifies after every scan. I ran adversarial AI reviews against it and they still caught a symlink trick and a case-sensitivity hole. Both fixed. The output does contain your note titles and link structure, so share the file like you'd share a screenshot of your graph view.

  Repo: https://github.com/paultaki/second-brain-3d (MIT, built on three.js + 3d-force-graph, built with Claude Code over a weekend). Drop the folder in your vault or point `--vault` at it.

  Honest edge: the biggest vault I've tested is mine at about 4k notes, running 47fps on my Mac. If you throw a 20k-note vault at it I genuinely don't know what happens, and I'd love to find out.
need: "Visualize a large Obsidian vault as a single offline HTML graph."
pain: "Stock graph view does not give a portable brain-shaped showcase."
topic: "[[choosing-a-publishing-tool]]"
persona: developer
competitor:
  - "Obsidian Graph"
fit: not-supported
intensity: preference
decision: fyi
reply: not-appropriate
engagement: none
reply_url:
last_touch: 2026-11-03
seo_brief:
source: "marketing/voice-of-customer/competitor-signals/2026-09-02-reddit-obsidianmd-1w5ldsd.md"
tags:
  - voc
---

# I turned my 3,900-note vault into a 3D brain. One HTML file, no plugins.

> ![Second Brain 3D demo](https://raw.githubusercontent.com/paultaki/second-brain-3d/master/assets/demo.gif)
>
> I've been living in one vault for over a year and I wanted to actually see it. So I built this: a Python script (standard library only, nothing to install) that scans the vault and writes a single brain.html. Every note is a glowing node, every [[wikilink]] is a conduit, and a containment force squeezes the layout into a brain silhouette.
>
> The part I keep replaying is Genesis. It pulls creation dates from git history and replays the vault assembling note by note with the date ticking up. Watching a year of thinking pour in over five seconds is worth the build on its own.
>
> Numbers from my vault: 3,907 notes, 8,294 links, 3.4M words. Rebuild takes about a second. The file opens instantly and makes zero network requests, fonts embedded, nothing phones home. Double-click a node and it opens the note in Obsidian. Shift-click two notes and it traces the shortest thought path between them.
>
> Privacy got the most engineering time because my vault has my whole life in it. Folders named Private, 90-Private, or _private are never walked, never counted, never emitted, and a fail-closed check re-verifies after every scan. I ran adversarial AI reviews against it and they still caught a symlink trick and a case-sensitivity hole. Both fixed. The output does contain your note titles and link structure, so share the file like you'd share a screenshot of your graph view.
>
> Repo: https://github.com/paultaki/second-brain-3d (MIT, built on three.js + 3d-force-graph, built with Claude Code over a weekend). Drop the folder in your vault or point `--vault` at it.
>
> Honest edge: the biggest vault I've tested is mine at about 4k notes, running 47fps on my Mac. If you throw a 20k-note vault at it I genuinely don't know what happens, and I'd love to find out.

## Context

r/ObsidianMD by u/d1smiss3d on 2026-09-02. Author showcase of a DIY Python→single `brain.html` 3D vault visualizer. Quote restored verbatim from Arctic on 2026-11-03-08. English.

## Our assessment

- Fit: not-supported · Intensity: preference · Decision: fyi
- Showcase / "I built" — not a user asking how to publish. 3D brain HTML viewer is outside confirmed MDFriday product facts. Was wrongly opportunity/supported + B31. Cleared seo_brief; reply not-appropriate. Cleared Auto-triaged.

## Follow-up log

- 2026-11-03: Hand-review 08:00 — full quote; reclassified fyi; seo_brief cleared.
