---
title: Activity stream
description: A central event bus for all user and agent activity, powering context graph traces, process mining, and procedure iteration.
date: 2026-06-20
tag: Context Graph
releaseType: roadmap
contentPage: true
---

A central event bus that captures all activity across the platform in one structured pipeline. Every event follows a consistent schema:

- **Subject** — who initiated the activity
- **Activity type** — what happened
- **Object** — what the activity acted on
- **Data** — the structured payload and context

### What this powers

The stream feeds downstream consumers including the Context Graph. You can pull complete traces of user and agent activity within a case, across related cases, or across broader process segments. This supports:

- Process mining
- Procedure iteration
- Quality analytics
- Governance reporting

### Connected through the context graph

Activities reference other objects through the Context Graph, so you can aggregate them in two ways:

- **By object** — for example, all messages an agent posted across the workspace
- **By scope** — for example, all activities in a space or case

### Two pillars

The Context Graph is built on two foundations:

- The **object graph** captures business structure (object-to-object relationships)
- The **activity stream** captures execution behavior (how work actually happens)

Together, they let us reinforce successful patterns and continuously improve procedure design.
