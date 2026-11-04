---
type: voc
id: "devto-astro-visual-editing"
date: 2026-09-07
platform: blog
url: "https://dev.to/maninderpreet_singh/visual-editing-for-astro-with-no-second-source-of-truth-1lb7"
author: "maninderpreet_singh"
title: "Visual editing for Astro, with no second source of truth"
quote: |
  Most visual editors for static sites ask for the same trade. Content moves into a CMS, layout moves into an editor-specific format, and your `.astro` files become a rendering target instead of the thing you edit.
  
  I built [`@sudodevstudio/astro-ai`](https://github.com/SudoDevStudio/astro-ai) to avoid that trade. It is a development-only Astro integration. You select an element on the rendered page, and the edit is written to the source file that produced it.
  
  ## Why source ownership was the point
  
  A separate authoring system is a reasonable choice for some projects. Editorial workflows and non-technical authors need an architecture built for them.
need: "Edit Astro sites visually without moving content into a separate CMS."
pain: "Most visual editors force a second source of truth (CMS + editor format)."
topic: "[[choosing-a-publishing-tool]]"
persona: developer
competitor:
  - "Astro"
fit: not-supported
intensity: preference
decision: fyi
reply: not-appropriate
engagement: none
reply_url:
last_touch:
seo_brief:
source: "voc-loop/hand-review/2026-11-04-08"
tags:
  - voc
---

# Visual editing for Astro, with no second source of truth

> Most visual editors for static sites ask for the same trade. Content moves into a CMS, layout moves into an editor-specific format, and your `.astro` files become a rendering target instead of the thing you edit.
>
> I built [`@sudodevstudio/astro-ai`](https://github.com/SudoDevStudio/astro-ai) to avoid that trade. It is a development-only Astro integration. You select an element on the rendered page, and the edit is written to the source file that produced it.
>
> ## Why source ownership was the point
>
> A separate authoring system is a reasonable choice for some projects. Editorial workflows and non-technical authors need an architecture built for them.

## Context

Dev.to article by maninderpreet_singh on 2026-09-07 promoting `@sudodevstudio/astro-ai` visual editing for Astro. Not an Obsidian vault publish request. Quote restored from Dev.to API.

## Our assessment

- Fit: not-supported · Intensity: preference · Decision: fyi
- Astro visual-editor product post — outside MDFriday Obsidian-publish scope. Cleared B01. Hand-reviewed 2026-11-04-08; removed Auto-triaged marker.

## Follow-up log

- 2026-11-04-08: hand-review — full quote; opportunity→fyi; seo_brief cleared.
