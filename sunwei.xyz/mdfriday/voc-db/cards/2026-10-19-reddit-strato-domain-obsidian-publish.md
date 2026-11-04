---
type: voc
id: "reddit-1xa0a8x"
date: 2026-10-19
platform: reddit
url: "https://www.reddit.com/r/ObsidianMD/comments/1xa0a8x/has_anyone_managed_to_use_their_strato_domain/"
author: "hysterese1337"
title: "Trying to connect a Strato custom domain to Obsidian Publish; worked briefly then broke"
quote: "I’m trying to set up a custom domain from Strato for my Obsidian Publish site. It actually worked briefly yesterday, but now it’s no longer working and I can’t figure out why.\n\nHas anyone here successfully connected a Strato domain to Obsidian Publish? If so, I’d love to know:\n\n* How did you configure the DNS records (CNAME/A record) in the Strato customer area?\n* Did you run into issues with the SSL certificate or propagation time?\n* Is there anything specific about Strato (e.g. DNS settings, “Domain umziehen” vs. “Domain verwalten”) that I should watch out for?"
need: "Get a registrar-bought Strato domain stably connected to an Obsidian Publish site (DNS + SSL)."
pain: "Custom domain worked briefly then timed out; DNS/SSL at Strato unclear; OP later bought another domain at Cloudflare after ~2 hours of brokenness."
topic: "[[custom-domains]]"
persona: knowledge-worker
competitor:
  - "Obsidian Publish"
  - "Strato"
  - "Cloudflare"
fit: supported
intensity: pain
decision: opportunity
reply: not-replied
engagement: none
reply_url:
last_touch: 2026-10-21
seo_brief: "[[B11-obsidian-publish-custom-domain]]"
source:
tags:
  - voc
---

# Trying to connect a Strato custom domain to Obsidian Publish; worked briefly then broke

> I’m trying to set up a custom domain from Strato for my Obsidian Publish site. It actually worked briefly yesterday, but now it’s no longer working and I can’t figure out why.
>
> Has anyone here successfully connected a Strato domain to Obsidian Publish? If so, I’d love to know:
>
> * How did you configure the DNS records (CNAME/A record) in the Strato customer area?
> * Did you run into issues with the SSL certificate or propagation time?
> * Is there anything specific about Strato (e.g. DNS settings, “Domain umziehen” vs. “Domain verwalten”) that I should watch out for?

## Context

r/ObsidianMD post by u/hysterese1337 on 2026-10-19, titled "Has anyone managed to use their Strato domain with Obsidian Publish?". Verbatim quote from Arctic selftext (fuller of the two duplicate cards). Paying Obsidian Publish user; reported CNAME `blog` → `publish-main.obsidian.md`; DNS resolved (e.g. to 146.190.3.220) but HTTPS/HTTP timed out from multiple networks after a brief working window. One earlier commenter had suggested Cloudflare proxy per Obsidian docs.

**Dedup note (2026-10-21-08):** Merged duplicate Mac card `2026-10-19-reddit-strato-custom-domain-obsidian-publish.md` (same URL `1xa0a8x`) into this file; duplicate deleted.

## Our assessment

- Fit: supported · Intensity: pain · Decision: opportunity
- Confirmed product facts: custom domains with automatic HTTPS are on the Personal plan. MDFriday can cover “own domain on published notes” without inventing registrar-specific Strato DNS steps. Do not claim free custom domains, unshipped SEO controls, or Personal 5GB. Name Obsidian Publish neutrally as the tool they already use.
- Reply: not-replied. Fresh help request; drafts exist under `/workspace/voc-loop/staging/2026-10-20/reply-drafts.md` and prior digest drafts (**not posted**). Soft MDFriday mention only after DNS help.

## Follow-up log

- 2026-10-20: Duplicate card created in an earlier run; merged into this canonical file on 2026-10-21-08. Reply draft staged (not posted).
- 2026-10-21 00:29 Asia/Shanghai (window 2026-10-21-08): OP u/hysterese1337 commented: "It did work for like 2 hours and randomly stopped. I bought another domain at Cloudflare." — still stuck on Publish custom domain; now moving registrar toward Cloudflare. No MDFriday reply yet.
