---
title: Permission-aware search
date: 2025-08-05
tag: Security
---

Document search now respects workspace permissions. The assistant only returns content the current user can access, filtering out files from restricted spaces.

Permission checks are batched so they don't slow down response times, even across large libraries.
