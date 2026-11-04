---
type: voc
id: "github-oleeskild-obsidian-digital-garden-854"
date: 2026-11-03
platform: github
url: "https://github.com/oleeskild/obsidian-digital-garden/issues/854"
author: "switchupcb"
title: "Digital Garden / forestry.md: custom component with frontmatter for note icon indicators"
quote: |
  I want to add note icon indicators (as defined by https://guide.switchupcb.com/blog#indicators ) to my digital garden notes where the timestamp data is placed ( see picture below ).
  You cannot use `dg-pass-frontmatter` with custom CSS to implement this feature because `dg-pass-frontmatter` passes the frontmatter to the website template and not the website HTML ( https://github.com/oleeskild/obsidian-digital-garden/issues/354 ).
  You cannot use forestry.md dashboard to implement this feature because forestry.md does not let you add custom components or manage the site template without a custom theme or community plugin.
  So, what other solutions are there to implement a custom component with frontmatter in forestry.md?
need: "Render custom note icon indicators from frontmatter in a Digital Garden / forestry.md published site."
pain: "dg-pass-frontmatter only reaches the template, not HTML; forestry.md blocks custom components without a custom theme/plugin."
topic: "[[themes-and-customization]]"
persona: knowledge-worker
competitor:
  - "Digital Garden (oleeskild)"
  - "forestry.md"
fit: not-supported
intensity: need
decision: watch
reply: not-replied
engagement: none
reply_url:
last_touch:
seo_brief: "[[B25-obsidian-publish-themes]]"
source: "voc-loop/staged/2026-11-04-08/github-854"
tags:
  - voc
---

# Digital Garden / forestry.md: custom component with frontmatter for note icon indicators

> I want to add note icon indicators (as defined by https://guide.switchupcb.com/blog#indicators ) to my digital garden notes where the timestamp data is placed ( see picture below ).
>
> You cannot use `dg-pass-frontmatter` with custom CSS to implement this feature because `dg-pass-frontmatter` passes the frontmatter to the website template and not the website HTML ( https://github.com/oleeskild/obsidian-digital-garden/issues/354 ).
>
> You cannot use forestry.md dashboard to implement this feature because forestry.md does not let you add custom components or manage the site template without a custom theme or community plugin.
>
> So, what other solutions are there to implement a custom component with frontmatter in forestry.md?

## Context

GitHub issue [#854](https://github.com/oleeskild/obsidian-digital-garden/issues/854) by switchupcb (same author as #853) opened 2026-11-03. Asks how to implement a custom component driven by frontmatter for note icon indicators on a Digital Garden site hosted via forestry.md.

## Our assessment

- Fit: not-supported · Intensity: need · Decision: watch
- Custom HTML components / template slots beyond stock themes are outside confirmed MDFriday Publish facts (to verify whether theme CSS + frontmatter props cover icon indicators). Competitor-repo signal; no reply draft this slot.
- Closest brief B25 (themes); may not fully cover component APIs.

## Follow-up log

- (none yet)
