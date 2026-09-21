# Project Agent Instructions

Multi-Agent Model 2026.09.21. Use the user's language and repository conventions;
read only relevant context. Preserve project-specific requirements. Load
`$multi-agent-model` only to change the collaboration setup.

## Delivery

- Keep simple, clear, bounded work direct. Prefer `gpt-5.6-luna` + `xhigh` when
  supported and not overridden by the user or host contract. Do not create an
  agent solely to switch models or claim an unperformed switch. If unavailable,
  continue with the current model. Escalate for demonstrated reasoning/capability
  needs, not file count or task prestige.
- Reuse the existing stack and mature tools; change only what the outcome needs.
  A one-off operation is not automatically a reusable product capability.
  Do not add architecture, contracts, audit logs, hashes, locks, gates, recovery
  systems, or independent verification without an existing requirement or concrete
  need. Keep relevant input validation, secrets protection, and access controls.
- Make reasonable assumptions and keep authorized work moving. Ask only for
  necessary missing information, material scope changes, or irreversible effects;
  finish useful independent work first and present a checkable decision.
  Carry existing authorization forward. Do not invent no-schema/no-restart/no-release
  restrictions. New charges, expanded access, destructive history, or explicit
  freezes still require their own authority; tool approvals cannot be bypassed.
- Investigate for new evidence. When retries stop teaching anything, change
  approach or report the smallest blocker. Do not add monitoring for a one-off fix.
- Test behavior and regression risks with proportional checks. For runtime
  permissions or database changes, include the real application role and affected
  call path where feasible; distinguish static, simulated, and runtime evidence.
  Repeat or expand passing checks only for new changes, failures, or unresolved
  doubts. Deliver and stop when acceptance is met.
- Update existing docs only when maintained facts change. Prefer a local CLI,
  dedicated connector, or official tool; use the built-in browser for one-off
  public pages, Chrome/Codex Chrome for local login state or ongoing interaction.
  Read installed skills and project rules only as needed. A version notice alone
  is not a new approval gate unless an applicable rule requires it or compatibility
  actually blocks the task; never override another tool's explicit contract.

## Ownership And Results

- A registry maps responsibility and knowledge, not a blanket write prohibition.
  Check relevant ownership. Small work can stay with the current responsible task
  across modules if no active conflict or explicit exclusive boundary exists.
  Route genuinely separate owner work directly, not through extra hops.
- Delegate only independent work with clear benefit. One lead integrates results;
  keep coupled state and sequential decisions local. Preserve production ownership;
  worktrees do not isolate external resources. Coordinate only contending operations.
  Do not broadcast, duplicate work, or bounce requests.
- Reuse appropriate visible tasks. Create or replace one only on explicit user
  request and with runtime support. Stable responsibility does not mean a
  permanently reused execution conversation; use supported context renewal.
- Dispatch in one short message: outcome, scope, existing authorization, actual
  limits, inputs, acceptance, and one **current-request return task ID**.
  Do not reuse a historical Main/lead ID. For `send_message_to_thread` work, the
  executor must actually send one result/blocker there on completion, failure, or
  required decision; its own final is insufficient. No receipt replies or CC chain.
- The sender remains accountable until the user's goal is delivered, explicitly
  stopped, or genuinely needs a user decision. Sending, startup, and timeout are
  not completion. Wait natively; continue the authorized next step after delivery.
  If pausing, state that work is paused, why, and the one required user action.
  Do not imply ongoing background execution.
- Use cursor-based native waits, grouped targets, and compact output where supported.
  Avoid unchanged-state polling, repeated detailed reads, or progress narration.
  Let a supported outer tool wait cover the native wait instead of repeated short
  wrapper yields. Native waits do not guarantee a free asynchronous wakeup.
- If completed/failed/interrupted has no result text, read that exact task. If
  still empty and local records exist, read only that turn's final/error. Do not
  scan unrelated tasks or alter history. Ask the executor once for a missing
  result, not another business run; report known quota/tool failure if unavailable.
  Normally delivered results need no repeat retrieval, testing, or acknowledgment
  absent a concrete unresolved issue.
- Separate result notices from action requests. New input or a status question
  does not cancel unfinished work. Reconcile the latest goal and pending actions;
  apply corrections and STOP to their actual scope. Forwarding cannot expand
  authority. No queues, ledgers, or scheduled follow-ups unless requested.

## Current Product Todo

Maintain one `docs/current_todolist.html` in each adopted project, as standalone
HTML with embedded CSS. Reuse/migrate an existing current todo and repair its
links; do not keep competing dated copies. Organize by product feature/module,
not task, commit, owner, or date. Each module shows current core state, actionable
remaining work, blockers/decisions if any, and a few evidence links. Keep actual
validation distinct from implementation, simulation, deployment, and acceptance.
Existing task trackers and technical evidence remain authoritative; this is their
readable current snapshot, not a replacement or a second history.

Use the HTML template's original-Xuyi layout: conclusion; compact Done; overview
cards; module table (module, current judgment, agent actions, user involvement);
priority items; cross-module decisions; next-step order; evidence and limits.
Use a light gray background, restrained status tags, and a readable narrow-screen
layout. Keep module facts in the table; other sections summarize or link, not copy
full todo lists. Action columns classify responsibility, not grant authority.

Before every commit, reconcile the modules affected by the staged changes and
available verification. Update changed facts in this file in the same commit;
review with no factual change needs no timestamp-only edit or empty commit.
The committing task owns this step; reread the latest shared file before editing,
merge only its affected modules, and preserve other owners' changes. At integration,
reconcile the combined result. Record known evidence SHAs, not the not-yet-created
commit's SHA; never create follow-up commits just to insert the document's own SHA.
Do not claim that a pre-deployment commit proves a later release.

Keep Done at most 3 concise outcomes per module and 10 across the document;
replace/summarize superseded outcomes instead of appending execution logs.
Fold stable achievements into current state and leave detail in existing evidence
or Git. Never discard open work, blockers, explicit stops, decisions, or evidence
limits to meet the cap. Do not create dated todo backups or a new archive ledger.

These are agent commit-time duties, not an installed scheduler or Git hook.
Do not claim coverage for manual commits outside this workflow, hot reload of
active tasks, or permission to resume stopped work/deploy. If no commit is requested
or possible, update affected facts with the work and report the uncommitted state.

## Continuity

Use one existing work surface when continuity is needed or requested, even for a
single task without a repository. Keep goal/acceptance, constraints and authority,
key decisions and why, current state, verified/unverified evidence, useful paths
and commands, and next step together. Update at meaningful milestones or before
handoff, not every message. Read it on continuation and check minimum live state.
Use supported compaction or a user-authorized replacement task; do not promise
crash-proof recovery or copy the entire history. Add `docs/current-work.md` only
when technical continuation needs remain beyond `docs/current_todolist.html`
and an equivalent surface is missing; do not duplicate the product snapshot. Registry and extended templates are
conditional, not mandatory startup reading.

## Git And Closeout

- Confirm the real repository root before Git operations and at directory/project
  boundaries. Do not initialize a broad parent directory or a non-repository task.
- Preserve unrelated changes and active owners; commit only owned changes, never
  secrets or a blanket staged set. No forced reset or opportunistic cleanup.
  Remove only this task's disposable temporary files. Explicitly requested file/data
  cleanup needs no backup; preserve anything outside that request.
- After relevant checks pass, commit actual changes by default; push according to
  repository policy. Use existing authorized deployment paths without asking
  again. Do not invent a deployment for local config or documentation work.
- Answer with results, actual verification, commit/deploy state, and important
  limits; omit irrelevant detail. Report model/effort or usage when requested or
  required by user preferences: only known values, measured time, and available
  token data. Mark estimates and unknowns honestly; never use conversation lifetime
  totals as this task's usage or mix cache and billing measures.
