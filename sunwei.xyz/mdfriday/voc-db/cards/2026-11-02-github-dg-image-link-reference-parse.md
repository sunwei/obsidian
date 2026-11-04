---
type: voc
id: "github-oleeskild-obsidian-digital-garden-853"
date: 2026-11-02
platform: github
url: "https://github.com/oleeskild/obsidian-digital-garden/issues/853"
author: "switchupcb"
title: "Digital Garden: image parse failure for link-reference image→note markdown"
quote: |
  The expected behavior is using a format like `[  ![text](img.jpg)  ](name.md)` is displayed on the website
  The current behavior is the website fails to load the image.
  - Line in Obsidianis `[  ![Bongcloud Chess Board](2738312886676881408.png)  ](🖼-2738312886676881408.md)`
  - 🖼-2738312886676881408.md has `dg-publish: true`
need: "Clickable images that link to another published note render correctly on the Digital Garden site."
pain: "Nested `[ ![img](file) ](note.md)` fails to load the image on the published Digital Garden site."
topic: "[[rendering-fidelity]]"
persona: knowledge-worker
competitor:
  - "Digital Garden (oleeskild)"
fit: not-supported
intensity: pain
decision: watch
reply: not-replied
engagement: none
reply_url:
last_touch:
seo_brief: "[[B54-obsidian-notes-broken-after-publishing]]"
source: "voc-loop/staged/2026-11-03-08/github-853"
tags:
  - voc
---

# Digital Garden: image parse failure for link-reference image→note markdown

> The expected behavior is using a format like `[  ![text](img.jpg)  ](name.md)` is displayed on the website
>
> The current behavior is the website fails to load the image.
>
> - Line in Obsidianis `[  ![Bongcloud Chess Board](2738312886676881408.png)  ](🖼-2738312886676881408.md)`
> - 🖼-2738312886676881408.md has `dg-publish: true`

## Context

GitHub issue [oleeskild/obsidian-digital-garden#853](https://github.com/oleeskild/obsidian-digital-garden/issues/853) by @switchupcb, created 2026-11-02 (Asia/Shanghai 2026-11-03 morning). End-user publish fidelity bug. Quote lines taken verbatim from Expected Behavior / Current Behavior / Example sections (screenshot figures omitted). English.

## Our assessment

- Fit: not-supported · Intensity: pain · Decision: watch
- Whether MDFriday correctly renders this nested image→note markdown construct is **to verify** (README: unsure → not-supported). Real competitor pain on Digital Garden publishing. Supports [[B54-obsidian-notes-broken-after-publishing|B54]]. Not a reply-today lead (issue on competitor repo).

## Follow-up log

- 2026-11-03: Staged from 08:00 GitHub scan.
