# Portable Thread Run: <task-id>

Use this file only for long, risky, resumable, audited, cross-tool, or
native-state-limited work. Do not mirror every native task event.

Last updated: YYYY-MM-DD HH:MM

## Routing

- Task ID:
- Source task/module:
- Target task/module:
- Current-request return task ID (not a historical Main/lead):
- Native task ID/link:
- State: pending | running | checkpointed | blocked | returned | closed
- Portable-control reason:

## Brief

- Desired outcome:
- Acceptance criteria:
  - [ ] Criterion 1
  - [ ] Criterion 2
- Relevant files/docs:
- Existing authorization and actual constraints:
- Key decisions and why:

## Latest Checkpoint

- Completed:
- Verification completed:
- Remaining:
- Blocker / input needed:
- Files with active edits:
- Safe to resume: yes | no
- Do not repeat:
- Next action:

## Resume Prompt

You are resuming `<task-id>` for `<module>`.

Read `AGENTS.md`, this run record or the equivalent existing snapshot, and only the
relevant current project docs. Inspect the current workspace before continuing.
Confirm whether acceptance criteria are already satisfied. Continue from the
latest checkpoint and do not repeat completed destructive steps.

Send the result once to this request's return task ID using native messaging.
A final in the executor alone is not delivery. A Return Packet is only a fallback
when native delivery is unavailable or explicitly inadequate.

中文恢复提示词：

你正在恢复 `<module>` 的 `<task-id>`。先读取 `AGENTS.md`、本运行记录、
与任务直接相关的当前项目文档；已有等价快照时不另读 status/handoff。继续前先
检查当前工作区，并确认验收条件是否已经满足。从最新检查点继续，不要重复
已经完成的破坏性步骤。通过原生消息向本次唯一回传任务 ID 实际发送一次结果，
自己的 final 不算回传；原生交付不可用或明确不足时才使用 Return Packet。

## Result

- Result state: pending | completed | partial | blocked | failed
- Summary:
- Verification:
- Risks / decisions needed:
- Durable docs updated:

## Closure

- Current request's responsible lead reviewed: yes | no
- Follow-up:
- Archive/delete policy:
