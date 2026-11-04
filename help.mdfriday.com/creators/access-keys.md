---
title: Manage access keys
weight: 20
tags: [security, access, dashboard]
date: 2026-10-20
lastmod: 2026-10-20
description: Issue, narrow, pause, extend, reissue, and revoke reader access keys from the MDFriday Dashboard.
---

# Manage access keys

## Goal

Control who can unlock protected pages after you publish with `access: protected`.

Open <https://mdfriday.com/dashboard/access/> (or **Manage keys in Dashboard** from the plugin Access panel).

## Keys tab

- **New key** — pick scopes (or `*` for everything). Optionally narrow to a folder prefix such as `skill/python/`
- **Copy key** — show the secret again (stored wrapped on the server)
- **Edit grants** — add/remove scopes or change the folder narrow; takes effect in about a minute
- **Pause / Resume** — temporary block without rotating epochs
- **Extend** — add 30 days (works even if the key already expired)
- **Reissue** — new secret, same grants; old secret stops immediately
- **Revoke** — permanent; related scopes’ epochs increase so the next publish re-encrypts those pages

## Scopes tab

- Lists scopes discovered on publish (`site`, `skill`, …) with page counts
- **Shared key** — root scope gets one on first publish; other scopes can enable/rotate a shared key here

## Related

- [[../publish/access|Protect pages with access keys]]
- <https://mdfriday.com/security/>
