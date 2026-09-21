# Multi-Agent Model

[中文说明](README.zh-CN.md) | [Installation](INSTALL.md)

A Codex skill for stable module ownership with minimal coordination overhead.
Use it to initialize or simplify collaboration, not for every implementation.

## Default Workflow

- A simple feature, page, or fix: implement in the existing stack, run relevant
  checks, deliver, and stop. No automatic architecture or audit workflow.
- One task: short `AGENTS.md` rules and the current product todo are enough.
- Simple bounded work prefers Luna + xhigh where supported; model selection is not
  a reason to create another agent.
- Stable modules: keep a responsibility map. Small work needs no mandatory hop
  absent active conflict or explicit exclusive ownership; genuinely separate work
  goes directly to its owner.
- Cross-module work: one lead, non-overlapping slices, and only the shared
  interface decisions needed for the requested outcome.
- Independent subagents: useful bounded work within the lead's scope, not
  replacements for registered module owners.
- Execution state: native tasks and existing trackers, not duplicate file logs.
- Durable facts: update their existing documentation only when they change.

Native search, messaging, waits, result inspection, fork, and handoff are the
preferred coordination tools when available. Creating a separate visible task
still requires explicit user authorization.

## What Is No Longer Default

Do not automatically create PRDs, architecture documents, status/handoff/runbook
sets, formal dispatch forms, hash ledgers, locks, independent verification tasks,
or return packets. Existing project requirements and concrete high-impact risks
still apply. Optional controls remain available in `references/`.

The [capability notes](references/codex-native-notes.md) explain the relevant
March-September 2026 Codex updates and GPT-6 Astra prompting implications.
Version 2026.09.14 adds a lightweight Luna preference, not provider routing.
Dispatch preserves existing authority and one current-request return ID. Executors
actually send results; senders wait and finish authorized delivery. Terminal empty
results are recovered narrowly without rerunning the business task.

## Project Skeleton

The skeleton is a menu, not a copy-all bundle:

```text
AGENTS.md                       project entrypoint
docs/current_todolist.html      current product/module state; maintained per commit
docs/thread-registry.md         only for stable visible module tasks
docs/current-work.md            continuity when needed; reuse an existing equivalent
```

Reuse existing project docs and work trackers. Extended operating notes,
product/design templates, and recovery controls are optional references.
Upgrading the skill does not silently migrate every existing project.

## Personal Preferences

The [Chinese global preference example](references/personal-instructions.zh-CN.md)
unifies execution, collaboration, continuity, Git, and delivery rules with this
skill. It also supplies Chinese-language and factual model/usage output preferences.
One compact snapshot supports single-task continuation, even without a repository;
stable responsibility does not require a permanently growing conversation.

Installing the skill does not change personal settings. Apply that example to
the supported global `AGENTS.md` only when the user requests it; merge existing
preferences instead of overwriting them. Do not duplicate old and new preference
blocks in multiple settings surfaces.

## License

[MIT](LICENSE).

## Current Product Todo

Maintain `docs/current_todolist.html` as the compact feature/module snapshot.
Every agent commit checks affected modules and includes factual updates in the same
commit; unchanged facts need no empty edit. Done is capped at 3 outcomes per module
and 10 total. This is an agent workflow, not a Git hook or scheduled updater.
Migrate existing todos and repair links; technical handoff remains optional.
