---
title: Performance
date: 2025-06-02
tag: Tools
---

We rewrote the execution engine for parallel processing. Step latency is now sub-second, and outputs stream as they complete.

The result is roughly 3x throughput — more work runs in parallel, and downstream actions start sooner.
