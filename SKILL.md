---
name: multi-agent-model
description: >
  Initialize, simplify, audit, or upgrade goal-focused project collaboration.
  Use for explicit operating-model work, not routine implementation. Supports
  项目智能体协作, 长期模块任务, 会话统筹初始化, and collaboration-doc cleanup.
---

# Multi-Agent Model

Version 2026.09.21. Keep stable responsibility, not mandatory routing or an
ever-growing execution conversation. Native tasks hold history; one existing
work surface holds the current facts needed to continue.

## Small And Direct First

Simple, clearly scoped work with a known path prefers `gpt-5.6-luna` + `xhigh`.
This is an execution preference, not a provider router. Honor explicit user
model choices and the host's tool contract. Use a supported selector; never claim
a prompt changed the running model. Do not create an extra agent merely to
switch models. If selection is unavailable, continue on the current model and
disclose the limitation when relevant. Escalate only for demonstrated ambiguity,
coupled reasoning, consequential uncertainty, or capability failure after checking
the immediate cause, not directory size or task prestige.

Use the existing stack. Implement the requested outcome, check relevant behavior,
and deliver. A one-off account/data operation is not permission to build a reusable
product feature. Do not invent architecture, audit systems, locks, gates, recovery
frameworks, or independent reviewers. Preserve existing requirements and safeguards
for concrete risks. New evidence, changes, failures, or unresolved doubts justify
more investigation or tests; a passed check alone does not.

## Install Or Upgrade

1. Read existing instructions and enough context to identify the real need.
   Reuse current owners, trackers, and project conventions.
2. Merge the concise [runtime rules](references/agents.template.md), preserving
   project-specific requirements. Global preferences and project collaboration
   follow one behavior, not competing rule sets. The complete
   [Chinese global version](references/personal-instructions.zh-CN.md) includes
   language and output preferences; merge it only when globally authorized.
3. Add [the registry](references/thread-registry.template.md) only for real stable
   module responsibilities. It is not a blanket write ban or dispatch queue.
   Small work may stay with the current responsible task across modules when no
   active conflict or explicit exclusive boundary exists.
4. Maintain `docs/current_todolist.html` using the
   [product todo template](references/current-todolist.template.html). Migrate an
   existing todo and repair links, rather than add a duplicate. Apply the runtime
   rules' per-commit reconciliation and bounded Done section. For technical
   continuity not covered there, reuse an existing surface or the optional
   [current-work snapshot](references/current-work.template.md), including outside
   a repository. Do not copy product status into a second tracker.
5. Discover and reuse visible tasks when delegation is worthwhile. Create or
   replace a visible task only on explicit user request and with runtime support.
   Use [the startup prompt](references/module-startup-prompt.template.md).
   Initialization alone does not authorize product work.
6. Remove conflicting generic rules, preserving unique local requirements,
   active ownership, explicit stops, and useful facts. Check affected metadata,
   mirrors, links, and behavior scenarios; do not build a separate audit system.

For authorized maintenance, validate and publish source first, then sync the
installed skill, then adopted local project rules including development worktrees,
excluding frozen snapshots. Follow [Contributing](CONTRIBUTING.md). Standalone
installation does not authorize publishing, global edits, or unrelated migration.
Do not interrupt active tasks or claim updated files hot-reload their context.

## Coordination Essentials

- One lead integrates results. Delegate only independent work with clear benefit;
  keep shared state and sequential decisions local. Preserve actual exclusive
  owners and coordinate only contending writes or external operations.
- Send goal, scope, existing authorization, inputs, acceptance, and **one
  current-request return task ID**. Do not inherit an old Main/lead ID or invent
  prohibitions such as no schema changes or no restart. Forwarding cannot expand
  authority; genuinely new scope or irreversible effects still require a decision.
  Explicit STOP remains binding.
- For work sent via `send_message_to_thread`, the executor actually sends one
  result/blocker to that ID on completion, failure, or required user decision.
  Its own final is not delivery. No receipt acknowledgments or multi-party CC.
- The sender owns the user's outcome through delivery or a real stop/blocker.
  Sending, executor startup, and wait timeout are not completion. Continue the
  authorized next step after results; never imply background work after pausing.
- Prefer native waits with cursors, batched targets, and bounded output. Inspect
  detailed history only for a concrete missing fact; do not narrate unchanged
  state. Where supported, let the outer tool yield cover the inner wait instead
  of repeated wrapper polling. No free asynchronous wakeup is guaranteed.
- Empty terminal results are not success or continued execution. Read that task;
  if still empty, read only its relevant local turn's final/error when available.
  Ask the executor once for the missing result, never redispatch the business work.
  Report known quota/tool failure if recovery is impossible. Normally delivered
  results need no repeated retrieval or confirmation.
- Status questions and new messages do not cancel pending authorized work.
  Reconcile the latest goal and unfinished actions; apply corrections and stops
  to their actual scope. No message ledger or custom scheduler is needed.

## Context And Optional Detail

Stable responsibility does not require permanently reusing a heavy conversation.
At meaningful milestones or before handoff, refresh the existing snapshot with
goal, constraints/authorization, decisions and why, actual state, evidence limits,
useful paths/commands, and next step. On continuation, read it and verify the
minimum live state. Supported compaction or an explicitly authorized replacement
task may use it. Do not auto-create tasks, promise crash-proof recall, copy all
history, or update a file after every message.

Load only relevant detail: [dispatch](references/main-thread-dispatch-task.template.md),
[cross-module dispatch](references/cross-thread-task.template.md),
[extended notes](references/thread-operating-model.template.md), or
[handoff](references/handoff.template.md). Independent
[verification](references/verification-operating-model.template.md) and portable
locks/packets remain opt-in for concrete needs. Other PRD, design, ADR, and runbook
templates are not startup requirements.
[Capability notes](references/codex-native-notes.md) are maintainer context.
