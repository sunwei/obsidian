---
type: voc
id: "reddit-1xf4j26"
date: 2026-10-25
platform: reddit
url: "https://www.reddit.com/r/ObsidianMD/comments/1xf4j26/help_with_obsidian_quartz/"
author: "RadiatedMolecule"
title: "Quartz deploy: Bases embeds with this.hasLink filters work in Obsidian but not on the site"
quote: "I’m trying to convert my vault to a webpage with Quartz, and I noticed an issue with my files created from templates. Some of my templates have embedded bases using filters such as “this.hasLink(asFile)” to automatically show files that are linked to the created file.\n\nThis works in Obsidian, but when I try to deploy to Quartz, the bases aren’t able to pull data. I think it has something to do with the bases-page plugin.\n\nIs there a known workaround?"
need: "Publish an Obsidian vault as a website while keeping template-embedded Bases (filtered linked-file lists) working on the public pages."
pain: "Bases embeds with this.hasLink(asFile) render in Obsidian but pull no data after Quartz deploy; suspects bases-page plugin; asking for a workaround."
topic: "[[rendering-fidelity]]"
persona: unknown
competitor:
  - "Quartz"
fit: not-supported
intensity: need
decision: watch
reply: not-replied
engagement: none
reply_url:
last_touch:
seo_brief: "[[B13-quartz-alternative]]"
source:
tags:
  - voc
---

# Quartz deploy: Bases embeds with this.hasLink filters work in Obsidian but not on the site

> I’m trying to convert my vault to a webpage with Quartz, and I noticed an issue with my files created from templates. Some of my templates have embedded bases using filters such as “this.hasLink(asFile)” to automatically show files that are linked to the created file.
>
> This works in Obsidian, but when I try to deploy to Quartz, the bases aren’t able to pull data. I think it has something to do with the bases-page plugin.
>
> Is there a known workaround?

## Context

r/ObsidianMD help flair by u/RadiatedMolecule on 2026-10-25 (22:58 Asia/Shanghai), titled "Help with Obsidian Quartz". Score 1, 0 comments when scanned (window 2026-10-26-00). English. Gallery post; verbatim quote from Arctic selftext. Classic rendering-fidelity voice: vault→webpage with Quartz, Bases dynamic filters fine in-app, broken once published. Aligns with VOC topic ranking of Dataview/Bases as top publish casualties (Quartz / Publish / DG).

## Our assessment

- Fit: not-supported · Intensity: need · Decision: watch
- Confirmed product facts: MDFriday can publish from inside Obsidian (no account, no token for first publish) with local preview and themes, but **Bases / Dataview-like live queries on the published site are not supported** (README: Dataview inside folder publishing is not-supported; Bases and Canvas are backlog — do not claim shipped). So we cannot honestly fix this user's Bases-on-Quartz ask today; keep as watch for when/if Bases web rendering ships. Soft alternative framing only if reply: publish path without Git/Quartz setup, while being explicit that Bases embeds still won't run on the public site.
- Reply: not-replied. Draft peer answer optional (honest limits). Intensity=need, decision=watch → not wake-worthy alone.

## Follow-up log

- (none yet)
