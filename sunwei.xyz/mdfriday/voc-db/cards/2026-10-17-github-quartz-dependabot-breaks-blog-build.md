---
type: voc
id: "github-quartz-2586"
date: 2026-10-17
platform: github
url: "https://github.com/jackyzha0/quartz/issues/2586"
author: "egphilippov"
title: "Quartz 5 blog on GitHub Pages stopped building after merging two Dependabot PRs"
quote: "dependabot's PR broke my blog: github action's build fails"
need: "Keep a Quartz blog deploying through GitHub Actions without dependency updates breaking the build."
pain: "Merging two automated dependency PRs made `npm ci` fail with a peer-dependency conflict (preact 11 vs @quartz-community/utils needing preact 10), so the blog no longer builds or deploys."
topic: "[[maintenance-burden]]"
persona: developer
competitor:
  - "Quartz"
  - "GitHub Pages"
fit: partial
intensity: pain
decision: opportunity
reply: not-appropriate
engagement: none
reply_url:
last_touch:
seo_brief: "[[B13-quartz-alternative]]"
source:
tags:
  - voc
---

# Quartz 5 blog on GitHub Pages stopped building after merging two Dependabot PRs

> dependabot's PR broke my blog: github action's build fails

> All CI should work smoothly.

## Context

GitHub issue #2586 on `jackyzha0/quartz`, opened by egphilippov on 2026-10-17 (07:15 Asia/Shanghai), labelled `bug`, 0 comments when fetched. Quartz 5.0.0, node v24.18.0, npm 11.16.0, Ubuntu 22.04. Repro: merge two Dependabot PRs on their `egphilippov.github.io` repo. The pasted log shows `npm ci` failing with `ERESOLVE`: `@quartz-community/utils@1.0.1` needs `preact@^10.0.0` while the root project now has `preact@11.0.0`. Found in the daily GitHub scan of the VOC growth loop run of 2026-10-17 08:00; no raw card.

## Our assessment

- Fit: partial · Intensity: pain · Decision: opportunity
- Classic self-hosted SSG upkeep cost: a routine dependency bump silently breaks the CI pipeline and the blog stops publishing. MDFriday Publish builds locally inside Obsidian and publishes without a GitHub repo, CI or token, so this whole failure mode doesn't exist there. Fit is partial, not supported, because this user is a developer who chose a Git-based Quartz setup and wants that pipeline fixed, not a different tool.
- Reply: not-appropriate. It's a bug report in Quartz's own issue tracker, and pitching another product there would be off-topic. Use it as evidence on the Quartz-alternative page (maintenance and dependency-breakage section) instead.

## Follow-up log

- (none yet)
