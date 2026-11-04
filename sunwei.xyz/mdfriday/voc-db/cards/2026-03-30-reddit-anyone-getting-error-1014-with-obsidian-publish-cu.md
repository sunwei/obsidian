---
type: voc
id: "reddit-obsidianmd-1s84urd"
date: 2026-03-30
platform: reddit
url: "https://www.reddit.com/r/ObsidianMD/comments/1s84urd/anyone_getting_error_1014_with_obsidian_publish"
author: "goneuphoric"
title: "Anyone getting Error 1014 with Obsidian Publish custom domain? DNS is correct, I think it's a backend issue?"
quote: |
  In bit of a strange situation with support and hoping someone here has been through this.
  
  I can't get my Obsidian Publish site to point to my custom domain. I set up my Cloudflare account specifically for Obsidian Publish and followed their docs exactly — this domain has never been connected to any other service or Cloudflare account.
  
  **What I've confirmed:**
  
  \- CNAME → `publish.obsidian.md`, tried both proxied and DNS only but neither works
  
  \- DNS resolves correctly, confirmed via dig:
  
    `... 300 IN CNAME publish.obsidian.md.`
  
  \- Removed and re-added the custom domain in Publish settings multiple times
  
  \- Been at this for 72+ hours
  
  **The error:** 
  
  Cloudflare 1014 -- CNAME cross-user banned. This is a backend binding issue, not a DNS or propagation issue, meaning the hostname isn't registered as a valid custom domain target in Obsidian's Cloudflare account.
  
  Support has suggested I might have a "second block" from another service, but I don't. I've hit a wall with the ticket and not getting further investigation.
  
  Has anyone dealt with this and actually resolved it?
need: "Custom domain for published Obsidian site without Cloudflare 1014 binding failures."
pain: "Obsidian Publish + Cloudflare Error 1014 CNAME cross-user banned for 72h+ despite correct DNS."
topic: "[[custom-domains]]"
persona: knowledge-worker
competitor:
  - "Obsidian Publish"
  - "Cloudflare"
fit: supported
intensity: pain
decision: opportunity
reply: not-replied
engagement: none
reply_url:
last_touch: 2026-10-29
seo_brief: "[[B11-obsidian-publish-custom-domain]]"
source: "marketing/voice-of-customer/publish-fidelity/2026-03-30-reddit-obsidianmd-1s84urd.md"
tags:
  - voc
---

# Anyone getting Error 1014 with Obsidian Publish custom domain? DNS is correct, I think it's a backend issue?

> In bit of a strange situation with support and hoping someone here has been through this.
>
> I can't get my Obsidian Publish site to point to my custom domain. I set up my Cloudflare account specifically for Obsidian Publish and followed their docs exactly — this domain has never been connected to any other service or Cloudflare account.
>
> **What I've confirmed:**
>
> \- CNAME → `publish.obsidian.md`, tried both proxied and DNS only but neither works
>
> \- DNS resolves correctly, confirmed via dig:
>
>   `... 300 IN CNAME publish.obsidian.md.`
>
> \- Removed and re-added the custom domain in Publish settings multiple times
>
> \- Been at this for 72+ hours
>
> **The error:** 
>
> Cloudflare 1014 -- CNAME cross-user banned. This is a backend binding issue, not a DNS or propagation issue, meaning the hostname isn't registered as a valid custom domain target in Obsidian's Cloudflare account.
>
> Support has suggested I might have a "second block" from another service, but I don't. I've hit a wall with the ticket and not getting further investigation.
>
> Has anyone dealt with this and actually resolved it?

## Context

r/ObsidianMD by u/goneuphoric on 2026-03-30. Quote re-fetched in full from Arctic `api/posts/ids` on 2026-10-29-08 (was truncated with …). English.

## Our assessment

- Fit: supported · Intensity: pain · Decision: opportunity
- MDFriday Personal custom domains with automatic HTTPS — supported alternative path. Keep as competitor-pain opportunity. Supports B11-obsidian-publish-custom-domain.
- Hand-reviewed 2026-10-29-08: quote restored verbatim; Auto-triaged marker removed. **Applied to Mac on 2026-10-29-16**.

## Follow-up log

- 2026-10-29: Hand-review prepared — full quote from Arctic; triage confirmed; waiting Mac CopyFromBox.
