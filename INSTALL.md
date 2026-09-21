# Installation

[中文完整提示词与说明](INSTALL.zh-CN.md)

## Install Or Upgrade

中文提示词：

```text
请从 https://github.com/sekiyaoshen-blip/multi-agent-project-playbook 安装或升级 $multi-agent-model。
使用本机实际 skill 目录；Codex 优先 $CODEX_HOME/skills，否则使用 ~/.codex/skills。
保留已有本地修改，检查 SKILL.md 和 agents/openai.yaml 的格式。
不要因此初始化当前项目、创建显性任务或修改全局个性化设置。
完成后报告安装位置和提交版本。
```

English equivalent:

```text
Install or upgrade $multi-agent-model from https://github.com/sekiyaoshen-blip/multi-agent-project-playbook in the actual local skill directory.
For Codex, prefer $CODEX_HOME/skills, otherwise ~/.codex/skills. Preserve local edits and check SKILL.md and agents/openai.yaml formatting.
Do not initialize a project, create visible tasks, or change personal settings as part of installation. Report the path and commit.
```

## Initialize Or Simplify A Project

中文提示词：

```text
使用 $multi-agent-model 初始化或精简当前项目协作。
保留项目专属规则、现有模块负责人和有用事实；复用已有文档与工作看板。
简单明确的任务优先 Luna+xhigh，在工具支持且符合用户选择时使用；直接实现、相关验证、交付，不自动添加架构、台账或验证旁路。
只有稳定多模块协作才维护归属表；小范围工作无活动冲突或明确独占边界时不强制转派，确需协作时只设一个牵头任务。
派单保留已有授权并写明本次唯一回传 ID，执行者实际回传，派单者等待并完成后续授权交付；复用原生能力，不擅自创建任务。
这次只调整协作配置，不开始产品实现。最后简短报告实际改动和保留的必要限制。
```

English equivalent:

```text
Use $multi-agent-model to initialize or simplify this project's collaboration.
Preserve project-specific requirements, existing owners, and useful facts. Reuse docs and work trackers.
Keep simple work direct: implement, run relevant checks, deliver. Do not automatically add architecture, contracts, hash ledgers, gates, or verification lanes.
Prefer Luna + xhigh for simple bounded work where supported; do not create an agent just to switch models.
Use a registry only for stable responsibilities; small work needs no forced hop absent conflict or exclusive ownership. Keep one lead.
Carry existing authority and a current-request return ID; the executor sends a result and the sender waits through authorized delivery.
Prefer native messages, waits, and result inspection. Reuse visible tasks; ask before creating missing ones.
Only adjust collaboration configuration, not product implementation. Briefly report changes and necessary constraints.
```

## Scope

The skeleton is a menu: AGENTS.md is the entrypoint; the current product todo is maintained per commit; the registry and technical
handoff snapshot are conditional. Do not copy all references. An upgrade must not
silently remove project-specific release requirements or migrate other projects.

The [Chinese personal preference example](references/personal-instructions.zh-CN.md)
is separate and opt-in. Merge it into `$CODEX_HOME/AGENTS.md` (normally
`~/.codex/AGENTS.md`) only on explicit request. Preserve unique preferences;
do not edit private app state. Replace a separately configured old instruction
block at its actual settings surface to avoid duplication. Existing running
tasks may need a new task to load the updated instructions.

For manual installation, place the repository under `multi-agent-model/` in
the skill root and retain SKILL.md, agents/, and references/. Validate YAML;
no additional acceptance framework is needed for a documentation-only install.
The existing explicit-only invocation policy remains unchanged.

## Maintainer Updates

After an authorized skill change, publish the validated source to GitHub, sync
the local skill, then update adopted local project rules within the established
scope. Follow [the update sequence](CONTRIBUTING.md#update-sequence), preserving
customizations and frozen snapshots. Standalone installation remains separate.

## Current Product Todo

Maintain `docs/current_todolist.html` as the compact feature/module snapshot.
Every agent commit checks affected modules and includes factual updates in the same
commit; unchanged facts need no empty edit. Done is capped at 3 outcomes per module
and 10 total. This is an agent workflow, not a Git hook or scheduled updater.
Migrate existing todos and repair links; technical handoff remains optional.
