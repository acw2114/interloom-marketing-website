---
title: Permission-Aware Search
date: 2025-08-05
tag: Security
---

Document search now respects workspace permissions. The assistant only returns results the current user has access to, filtering out files from other spaces or restricted contexts.

Permission checks are batched so they don't slow down results, even across large libraries.
