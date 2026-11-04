---
title: Access keys
weight: 37
tags: [security, access]
date: 2026-10-20
lastmod: 2026-10-20
description: Protect pages with access keys and scopes. Bodies are encrypted before upload; readers unlock in the browser. Works on every plan.
---

# Access keys

## Goal

Protect notes so visitors need an **access key** before they can read the page body. Useful for a brief, a paid section, or an internal folder that still needs a shareable link.

This is content encryption, not a login. Bodies are encrypted on your computer (AES-256-GCM) and decrypted in the visitor's browser after the key is checked with MDFriday.

## What stays public

- The page title
- The URL
- Image and attachment files (only the HTML body is encrypted)
- **Site search index and graph data**, when those features are enabled — protected bodies are omitted from those indexes in the access-aware build

Do not publish an attachment that cannot be public.

## How it differs from a single password

| | Access keys (current) | Old site password |
| --- | --- | --- |
| Who can read | Anyone with a key you issued | Anyone with the shared password |
| Revoke one reader | Yes (Dashboard → revoke / pause) | No — change password and republish |
| Multiple readers | Separate personal keys, or one shared key | One password for everyone |
| Folder / section | Scopes (`access_scope`) + grants | One password for the whole site |

## Prerequisites

- Any plan: Guest, Free, and Personal. A Guest site still clears at the next UTC 00:00. Claim Free to keep the same URL
- Keys are created in the **Dashboard → Access** page (or shown once after the first protected publish for the root shared key). They are not stored in your vault frontmatter

## Steps

1. On the note or folder `index.md`, set frontmatter:

```yaml
access: protected
# optional independent section:
# access_scope: skill
teaser: A short public preview…
```

2. Right panel → **Advanced → Access** → confirm **Protected**, scope, and teaser
3. [[local-preview|Preview]], then **Publish**
4. Copy the **shared access key** from the publish notice (root scope) or open **Manage keys in Dashboard**
5. Send the link and the key on separate channels (or use the share link that embeds `#mdf-key=…`)

To grant a reader only one folder inside a scope, create a personal key in the Dashboard and narrow the grant to that folder prefix.

## Confirm success

- An incognito visitor sees the unlock card before the body
- View source: the body is ciphertext, not the note text
- After you revoke a key in the Dashboard, that key stops unlocking within about a minute
- To make content public again: remove `access: protected` and publish

## Related

- [[unpublish|Unpublish]]
- <https://mdfriday.com/dashboard/access/>
- <https://mdfriday.com/security/>

## Common failures

| Symptom | What to do |
| --- | --- |
| Set protected but the page is still public | **Publish again.** Frontmatter changes do nothing until publish |
| Key works on the home page but not a folder | That folder may use an independent `access_scope`. Grant that scope (or `*`) in the Dashboard |
| Images are visible without a key | Expected. Attachments are not encrypted |
| “Try another key” | The key is valid but does not include this page’s scope — issue a wider grant or use a different key |
