# Extended Collaboration Notes

Optional detail for actual cross-module coordination. The installed AGENTS.md
is the runtime contract; do not create another file merely to repeat it.

## Distribution

A registry identifies responsibility and useful context, not mandatory hops.
Keep simple work local where no active conflict or explicit exclusive boundary
exists. Delegate only genuinely separate work; one lead handles integration and
shared decisions. Inspect active state only when overlap is plausible.
Production and shared external resources retain their actual responsible owner.

Use the [dispatch prompt](main-thread-dispatch-task.template.md): carry existing
authority and one current-request return ID. Do not invent prohibitions, expand
authorization, or fall back to a historical Main ID. The executor actually sends
its result; the sender waits and continues authorized delivery. Forwarded results
do not need another acknowledgment chain.

## Native Coordination

Use native search/messages and cursor-based, grouped, bounded waits. A wait timeout
or executor startup is not a stopping condition. Fetch detailed history for a
specific missing fact, not every cycle. If terminal state has no result, inspect
that task and only the relevant local turn if needed; ask once for the result,
not another business run. Report an unrecoverable tool/quota failure.

Subagents and visible tasks are distinct. Do not create a task just to use Luna
or renew context. Supported compaction may keep the current task; a replacement
visible task requires explicit user authorization. Do not build a scheduler or
promise post-turn asynchronous delivery without a supported authorized mechanism.

## Verification And Continuity

Keep local checks with the implementer and proportional to changed behavior.
A database/permission change needs evidence for the actual application role and
affected path where feasible, not an unrelated full suite. Mark unverified
boundaries. Independent review requires an explicit request, project rule, or
concrete high-impact need; portable review templates are optional.

For continuation, use [one snapshot](current-work.template.md) or an equivalent
existing surface. It works outside multi-agent projects too. Preserve decisions
and their rationale, current evidence, authorization, and the next useful step.
Do not require a second handoff or raw history copy. Update at meaningful progress
or handoff, not every message; verify minimum current state before resuming.

Doc cleanup preserves unique current facts, explicit stops, ownership, and project
requirements. Ordinary edits do not need locks; coordinate only actual concurrent
writes. Do not use cleanup to change product decisions or resume stopped work.
