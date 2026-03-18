---
title: Permission-Aware Search
date: 2025-08-05
tag: Security
---

Document search now fully respects workspace permissions. When the assistant searches your document library, it only returns results the current user has access to — filtering out files and notes that belong to other spaces or restricted contexts.

Search queries are batched for performance, so permission checks don't slow down results even across large libraries. The agent surfaces relevant knowledge without ever crossing permission boundaries.
