---
type: voc
id: "blog-daktre-obsidian-publish-to-quartz"
date: 2026-10-31
platform: blog
url: "https://notes.daktre.com/6.-Index/Obsidian-Publish-to-Quartz"
author: "daktre"
title: "Migrated two Obsidian Publish gardens to Quartz for crawlable HTML"
quote: "I had two Obsidian-based digital gardens which I was pushing via Obsidian Publish. Wanted to move to Quartz, a free, open-source static site generator."
need: "Leave Obsidian Publish for a static generator so search engines and AI crawlers get full HTML, not JS-injected shells."
pain: "Publish delivered near-empty HTML shells; sitemap pages stayed unindexed and site: searches returned almost nothing months after launch."
topic: "[[seo-discoverability-and-ai-crawlers]]"
persona: developer
competitor:
  - Obsidian Publish
  - Quartz
  - Cloudflare Pages
  - GitHub
fit: supported
intensity: pain
decision: opportunity
reply: not-appropriate
engagement: none
reply_url:
last_touch:
seo_brief: "[[B15-move-from-obsidian-publish]]"
source:
tags:
  - voc
---

# Migrated two Obsidian Publish gardens to Quartz for crawlable HTML

> I had two Obsidian-based digital gardens which I was pushing via Obsidian Publish. Wanted to move to Quartz, a free, open-source static site generator.

## Context

Blog write-up on notes.daktre.com dated Oct 31, 2026. Author documents migrating two Obsidian Publish gardens to Quartz + GitHub + Cloudflare Pages because Publish’s JS-rendered HTML hurt Google/AI crawling and indexing. Also covers rsync sync, custom domain, numbered-folder display stripping, and a `publish-notes` shell workflow. Same daktre domain family as an earlier Publish iframe/custom-domain forum card. Found by Grok Bot periodic VOC pass 2026-11-01 18:51 Asia/Shanghai.

## Our assessment

- Fit: supported · Intensity: pain · Decision: opportunity
- Confirmed MDFriday facts that match: local build/preview (static HTML before publish), wiki-style themes, custom domains on Personal, selective folder/note publish, no account/token for first publish. SEO/crawlability of built pages is a real Publish-exit motive for [[B15-move-from-obsidian-publish|B15]] and [[seo-discoverability-and-ai-crawlers]].
- Blog article → `reply: not-appropriate` (no public reply thread to join).
- Do not claim MDFriday indexing metrics we have not measured; use as quote-backed SEO proof only.

## Follow-up log

- 2026-11-01: Card created on box staged + macx mirror. Mac vault push still needed when e26998c5 is online.
