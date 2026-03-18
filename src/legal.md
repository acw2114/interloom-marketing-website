---
layout: base.njk
title: Legal Notice
description: Legal notice and company information for Interloom.
---

<section class="pt-24 pb-12 px-4 flex items-end min-h-[26vh]">
  <div class="mx-auto max-w-5xl w-full">
    <h1 class="mb-0">Legal Notice</h1>
    <p class="text-fg-3 mt-5 mb-0 max-w-2xl">Company, product, and release information for Interloom.</p>
  </div>
</section>

<section class="pb-20 px-4">
  <div class="mx-auto max-w-5xl grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12">
    <aside class="md:col-span-4">
      <div class="rounded-lg border border-line bg-surface-1 p-4">
        <p class="text-sm text-fg-3 mb-2">Last updated</p>
        <p class="text-sm text-fg-1 mb-0">Jun 2026</p>
      </div>
    </aside>

    <div class="md:col-span-8 prose max-w-none">
      <h2>Interloom Assistant (Odin)</h2>
      <p>
        <strong>Jun 2026</strong><br>
        Agent Experience
      </p>
      <p>
        Interloom Assistant (Odin) is a roadmap epic for a personal chief of staff experience across the
        platform. The long-term goal is to support all users. The initial focus is on forward deployed
        engineers and workflow architects who design, test, deploy, and iterate on procedures and execution
        flows for complex business operations.
      </p>
      <h3>Why this epic matters now</h3>
      <p>
        Most Q1 stories focused on giving agents stronger context and broader tool access. Odin builds on that
        foundation and turns it into an operational copilot layer that actively helps teams run and improve
        work, not just automate isolated tasks.
      </p>
      <h3>Scope of the epic</h3>
      <p>Odin is designed to orchestrate work across:</p>
      <ul>
        <li>domain experts operating in spaces</li>
        <li>agents and their delegated responsibilities</li>
        <li>reusable skills and tools</li>
        <li>procedure stages and execution paths</li>
        <li>cross-system and cross-department workflows</li>
      </ul>
      <p>
        The objective is faster and more reliable case resolution in back-office operations, even when many
        systems, teams, user groups, and agents are involved.
      </p>
      <h3>Agent choice and execution power</h3>
      <p>
        The epic includes agent choice with at least Claude Code and Codex, plus full command line interface
        and Model Context Protocol access to Interloom primitives. This allows teams to choose the right
        execution model for each task while keeping design and runtime actions grounded in one operating
        context.
      </p>
      <h3>Expert in the loop, chief of staff in the loop</h3>
      <p>
        Odin does not remove human ownership. It reinforces it. Experts remain in the loop while Odin acts as
        a chief of staff that continuously monitors execution, highlights risks, and alerts teams where
        intervention or iteration is needed across core business process management functions.
      </p>
      <h3>Expected impact</h3>
      <p>
        By combining context, tools, skills, and continuous oversight into one assistant layer, Odin can
        unlock a step-change in speed for workflow design and operation, while improving reliability and
        control in high-complexity business processes.
      </p>

      <h2>Interloom Activity Stream</h2>
      <p>
        <strong>Jun 2026</strong><br>
        Context Graph
      </p>
      <p>
        Interloom Activity Stream is a central event bus that captures all activities across the platform,
        and selected activities outside the platform, in one structured pipeline.
      </p>
      <p>Every event follows a consistent schema:</p>
      <ul>
        <li>subject: who initiated the activity</li>
        <li>activity type: what happened</li>
        <li>object: what the activity acted on</li>
        <li>data: the structured payload and context</li>
      </ul>
      <h3>Central pipeline for downstream consumers</h3>
      <p>
        The stream is designed as a core pipeline for downstream use cases and consumers, including the
        Context Graph. It enables retrieval of complete traces of user and agent activity within one case,
        across a related case set, or across broader process segments for analysis.
      </p>
      <p>This supports high-value scenarios such as:</p>
      <ul>
        <li>process mining</li>
        <li>procedure iteration loops</li>
        <li>operational quality analytics</li>
        <li>reliability and governance reporting</li>
      </ul>
      <h3>Activity references through the Context Graph</h3>
      <p>
        Like everything in Interloom, activities reference other objects through the Context Graph. This
        creates a durable relationship model between operational entities and the work performed on them.
      </p>
      <p>Activities can be aggregated in two primary ways:</p>
      <ul>
        <li>by object, for example all messages an agent posted across the workspace</li>
        <li>by primitive scope, for example all activities in a space or all activities in a case</li>
      </ul>
      <p>
        That aggregation model forms the trace layer needed for deep operational visibility.
      </p>
      <h3>Second pillar of the Context Graph</h3>
      <p>Interloom's Context Graph is built on two pillars:</p>
      <ul>
        <li>the object graph (business ontology, object-to-object relationships)</li>
        <li>the activity stream graph (activity-to-object relationships and observed patterns of work)</li>
      </ul>
      <p>
        The first pillar captures business structure. The second captures execution behavior. Together they
        let Interloom reinforce successful work patterns for case resolution and continuously improve
        procedure design over time.
      </p>

      <h2>Tool Forge Epic for Code in the Loop</h2>
      <p>
        <strong>Apr 2026</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Tool Forge is the Q2 epic that consolidates Interloom's code in the loop roadmap into one capability.
        It brings leading coding agents into a secure, governed environment so domain teams can build and run
        custom process tools without long handoffs to central engineering.
      </p>
      <h3>Why this changes time to value</h3>
      <p>
        Most business process automation programs lose momentum at the boundary between process design and code
        delivery. Tool Forge closes that gap by letting domain experts define requirements in context, generate
        a first version with an agent, test it against live process data, and deploy it into the same
        procedure loop.
      </p>
      <p>
        This shortens the path from idea to measurable production impact from weeks to days and, for many
        changes, from days to hours.
      </p>
      <h3>From Human in the Loop to Code in the Loop</h3>
      <p>
        Interloom already supports human checkpoints where judgment is required. Tool Forge adds a new
        pattern: Code in the Loop.
      </p>
      <p>In Code in the Loop, custom code modules become first-class procedure building blocks that can be:</p>
      <ul>
        <li>drafted by users with agent support</li>
        <li>refined through simulation and test runs</li>
        <li>executed as part of standard stage transitions</li>
        <li>monitored with full traceability in activity history</li>
      </ul>
      <p>
        The result is not replacing humans, but giving both humans and agents a higher-leverage execution
        layer inside the process itself.
      </p>
      <h3>Secure by design</h3>
      <p>
        Tool Forge includes the secure runtime foundation in the same epic. Execution is controlled through
        explicit policies for permissions, dependency boundaries, resource limits, and full auditability. This
        allows organizations to expose self-service build power while preserving governance requirements in
        regulated and high-risk workflows.
      </p>
      <h3>Process-native app building</h3>
      <p>
        The epic also includes process-native app building so teams can package reusable functions, internal
        mini-applications, and specialized automation modules directly from procedures. Build, test, and
        execution happen in one operational surface, which reduces coordination overhead and speeds up
        continuous improvement.
      </p>
      <h3>Potential impact</h3>
      <p>
        Over time, teams can build a reusable internal library of process-specific capabilities: validators,
        enrichment tools, pricing logic, compliance checks, routing strategies, and mini-applications tailored
        to their operating model. This creates compounding speed where each new process starts from proven
        components instead of rebuilding logic from scratch.
      </p>

      <h2>Context Graph for Interloom Primitives</h2>
      <p>
        <strong>Mar 2026</strong><br>
        Context Graph
      </p>
      <p>
        This roadmap item introduces a context graph for Interloom Primitives so teams can accumulate,
        assemble, and navigate operational context across the workspace with less friction. Interloom
        Primitives include Space, Task, Note, File, Agent, Procedure, Stage, and Subtask, connected through
        explicit ownership and reference relationships that reflect how work actually moves. This is the
        foundation for the Interloom Assistant, which will traverse the Interloom Context Graph along the
        relationships of work to surface relevant context, explain dependencies, and guide faster,
        higher-confidence decisions.
      </p>

      <h2>AI-First Design System LUI (Loom User Interface)</h2>
      <p>
        <strong>Mar 2026</strong><br>
        User Experience
      </p>
      <p>
        This roadmap item moves the product user interface to a unified design system called lui, creating a
        single source of truth for presentation logic across the application. The plan includes standardized
        standard and wide layouts with a universal top bar and sidebar, strict separation between user
        interface components and business logic, and a layered architecture of components, theme foundations,
        and data-model-aligned game object components. The customer value is a more predictable and cohesive
        product experience, plus faster and safer interface improvements over time.
      </p>

      <h2>Procedure Stages Execution Flows</h2>
      <p>
        <strong>Mar 2026</strong><br>
        Agent Experience
      </p>
      <p>
        This roadmap item introduces clearer stage boundaries and explicit orchestration so teams can follow
        case progression without needing to understand internal execution mechanics. Planned capabilities
        include optional sequential stages, parallel subtasks, improved agent invocation status tracking,
        manual stage controls, and automatic subtask summaries in the main case thread. The customer value is
        lower cognitive load, better visibility of objectives and progress, and faster day-to-day case
        handling.
      </p>

      <h2>Enhanced Activity Traces for Procedures</h2>
      <p>
        <strong>Feb 2026</strong><br>
        Security
      </p>
      <p>
        Every procedure action, including stage transitions, tool executions, and agent decisions, is now
        captured in a timestamped activity trail directly in the task view. This gives teams a clear audit
        record for compliance reviews, faster root-cause analysis, and more confident approvals in regulated
        workflows.
      </p>

      <h2>Structured File Processing</h2>
      <p>
        <strong>Feb 2026</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        The assistant can now parse and analyze uploaded files directly in conversation, including comma
        separated values, tab separated values, Excel, JavaScript Object Notation, JavaScript Object Notation
        Lines, and Portable Document Format files up to 100 megabytes, with structure-aware previews and
        sheet-level handling for spreadsheets. Customers can move from raw documents to actionable insights in
        one place, without external conversion steps.
      </p>

      <h2>Private Chat Conversations</h2>
      <p>
        <strong>Feb 2026</strong><br>
        Agent Experience
      </p>
      <p>
        Users can now run private artificial intelligence conversations outside case threads for ad-hoc
        research, drafting, and brainstorming, with separate history and dedicated navigation placement. This
        creates a safe workspace for exploration while keeping case timelines focused, structured, and easier
        to review.
      </p>

      <h2>Salesforce Integration</h2>
      <p>
        <strong>Feb 2026</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Agents can now query and update Salesforce records directly from Interloom, reducing context
        switching between customer relationship management and case operations while bringing account context
        into ongoing conversations. Customers can resolve requests faster and maintain cleaner customer
        relationship management data without duplicating updates across tools.
      </p>

      <h2>Self-Service Procedure Creation</h2>
      <p>
        <strong>Feb 2026</strong><br>
        Agent Experience
      </p>
      <p>
        Teams can now define, reorder, and manage explicit stages per procedure so cases move through a
        visible, structured sequence from intake to completion. This improves operational predictability,
        makes ownership clearer at each handoff, and helps leaders identify bottlenecks earlier.
      </p>

      <h2>Unified Space Files and Code Execution 1.5</h2>
      <p>
        <strong>Feb 2026</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Space files and task files are now unified into a single synchronized view, and code execution
        reliability for note and file manipulation workflows has been improved through a stronger markdown
        bridge. Customers get fewer handoff errors, less duplicate work across contexts, and more dependable
        automation outcomes.
      </p>

      <h2>Email Lifecycle in Tasks</h2>
      <p>
        <strong>Feb 2026</strong><br>
        Agent Experience
      </p>
      <p>
        Interloom now supports end-to-end email handling in case workflows, including inbound routing,
        context-aware draft replies, user review before send, and correct thread continuation across follow-up
        messages. Teams can keep communication quality high at scale while reducing manual triage and missed
        follow-ups.
      </p>

      <h2>Code Interpreter and External API Access</h2>
      <p>
        <strong>Jan 2026</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        The assistant can now execute Python in an isolated runtime for structured analysis and call external
        Hypertext Transfer Protocol or GraphQL endpoints to fetch and update operational data during task
        execution. Customers can automate richer end-to-end workflows without leaving Interloom or building
        custom glue code first.
      </p>

      <h2>Summaries, Integrations, and Agent Reliability</h2>
      <p>
        <strong>Dec 2025</strong><br>
        Agent Experience
      </p>
      <p>
        This release improves case handovers with automatic task summaries, expands retrieval via SharePoint
        and Model Context Protocol integrations, and increases multi-step agent reliability for longer
        execution chains. Teams get faster onboarding into active work, better connected context, and fewer
        dropped steps in complex automations.
      </p>

      <h2>Workspace Navigation and Files</h2>
      <p>
        <strong>Nov 2025</strong><br>
        User Experience
      </p>
      <p>
        Spaces are now directly accessible in the sidebar, and each space includes a dedicated Files view for
        faster document browsing, preview, and management in context. Customers spend less time navigating and
        more time executing work with the right documents immediately at hand.
      </p>

      <h2>Tags</h2>
      <p>
        <strong>Nov 2025</strong><br>
        User Experience
      </p>
      <p>
        Tags were released on November 5, 2025. Teams can apply custom tags, filter work by operational
        priorities, and use a faster tag picker with assistant-supported suggestions for more consistent
        classification.
      </p>

      <h2>Predictive Agent Execution</h2>
      <p>
        <strong>Sep 2025</strong><br>
        Agent Experience
      </p>
      <p>
        Agents now recommend high-value next steps, suggest the right specialist for each follow-up, and
        execute structured plans more reliably in a single workflow. This helps teams reduce planning overhead
        and convert intent into completed outcomes with fewer manual interventions.
      </p>

      <h2>Rich Text Editor Rebuild</h2>
      <p>
        <strong>Sep 2025</strong><br>
        User Experience
      </p>
      <p>
        Interloom moved to a modern Tiptap-based editor for faster performance and more reliable formatting
        across notes, mentions, links, and longer task descriptions. Customers get a smoother writing
        experience, cleaner structured content, and fewer formatting regressions in daily operations.
      </p>

      <h2>Permission-Aware Search</h2>
      <p>
        <strong>Aug 2025</strong><br>
        Security
      </p>
      <p>
        Document search now fully respects workspace permissions. When the artificial intelligence assistant
        searches your document library, it returns only content the current user can access, filtering out
        files and notes from restricted spaces and contexts.
      </p>
      <p>
        Search queries are batched for performance so permission checks do not slow response times, even
        across large libraries. This makes artificial intelligence-powered retrieval safe for multi-team
        environments handling sensitive or segmented information.
      </p>

      <h2>File Viewer</h2>
      <p>
        <strong>Jun 2025</strong><br>
        User Experience
      </p>
      <p>
        Teams can now open Portable Document Format files, images, email files, and note attachments directly
        inside Interloom, with consistent metadata and in-context side-panel review from threads, files, and
        search results. This reduces tool switching and helps reviewers make faster decisions with full
        context in one interface.
      </p>

      <h2>Three Times the Throughput with Sub-Second Latency</h2>
      <p>
        <strong>Jun 2025</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Interloom rewrote the execution engine for parallel branch processing, reduced deterministic step
        latency to sub-second performance, and introduced streaming outputs for faster downstream action.
        Customers can run more work in parallel, shorten cycle times, and react to intermediate results
        sooner.
      </p>

      <h2>Native Integrations for SAP, Salesforce, and ServiceNow</h2>
      <p>
        <strong>May 2025</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Interloom added direct SAP, Salesforce, and ServiceNow connectors with bi-directional synchronization
        and webhook triggers, so workflows can start and complete against core enterprise systems without
        middleware. Customers can launch automation faster, reduce integration maintenance, and keep business
        data consistent across platforms.
      </p>

      <h2>Citations and Document Transparency</h2>
      <p>
        <strong>Apr 2025</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Assistant responses now include inline citations to exact source passages, and files show clear
        indexing states so teams can verify evidence and know when content is ready for retrieval. Customers
        can trust and validate artificial intelligence output faster, which is especially valuable in
        high-accuracy and compliance-sensitive processes.
      </p>

      <h2>Audit Trail and Compliance Reports</h2>
      <p>
        <strong>Apr 2025</strong><br>
        Security
      </p>
      <p>
        Interloom added end-to-end execution logging, one-click compliance report generation, and role-scoped
        access controls for audit-ready operations in regulated environments. Customers can prepare audits
        faster, reduce compliance risk, and prove process integrity with less manual evidence gathering.
      </p>

      <h2>Global Search</h2>
      <p>
        <strong>Apr 2025</strong><br>
        User Experience
      </p>
      <p>
        Teams can now search task titles, descriptions, and task content from one global entry point in the
        navigation, then open results directly in context without losing workflow state. This cuts retrieval
        time and helps operators resume work immediately instead of re-navigating across spaces.
      </p>

      <h2>Document Search</h2>
      <p>
        <strong>Mar 2025</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Interloom now indexes workspace documents in the background and lets the assistant retrieve relevant
        passages across files, notes, and attachments so responses are grounded in searchable operational
        context. Customers get faster, evidence-backed answers and spend less time manually hunting for
        supporting information.
      </p>

      <h2>Visual Workflow Editor</h2>
      <p>
        <strong>Mar 2025</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Teams can now inspect execution graphs, step through workflows with live debugging context, and keep
        visual and natural-language workflow definitions synchronized. This makes troubleshooting faster,
        improves collaboration between technical and domain teams, and reduces drift between design and
        execution.
      </p>

      <h2>Context Layer v2 with Incremental Learning</h2>
      <p>
        <strong>Feb 2025</strong><br>
        Context Graph
      </p>
      <p>
        The context graph now updates from validated case outcomes and supports portable Markdown export, so
        organizational knowledge improves continuously without manual maintenance overhead. Customers keep
        institutional knowledge current over time and can reuse trusted context across teams more easily.
      </p>

      <h2>Improved Document Extraction and Email Parsing</h2>
      <p>
        <strong>Jan 2025</strong><br>
        Tools &amp; Integrations
      </p>
      <p>
        Interloom introduced a stronger two-pass extraction pipeline for scanned and annotated documents and
        added email thread reconstruction for clearer conversation context, with additional reliability gains
        for high-volume processing. Customers can process complex inbound content more accurately while
        reducing manual cleanup and rework.
      </p>
    </div>
  </div>
</section>
