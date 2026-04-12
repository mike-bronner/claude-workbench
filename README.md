# claude-workbench

Mike Bronner's personal Claude Code plugin marketplace.

## What this is

A catalog of Claude Code plugins I use across my workflows — persistent agent identity, operational memory, and workflow automation. Each plugin lives in its own repo; this repo is just the marketplace manifest that points at them.

## Installation

From within a Claude Code session:

```
/plugin marketplace add mike-bronner/claude-workbench
/plugin install <plugin-name>@claude-workbench
```

Or from the terminal:

```bash
claude plugin marketplace add mike-bronner/claude-workbench
claude plugin install <plugin-name>@claude-workbench
```

> **Cowork (claude.ai):** Third-party marketplaces with external plugin sources are not yet supported in Cowork ([claude-code#41653](https://github.com/anthropics/claude-code/issues/41653)). The commands above only work in Claude Code (CLI/desktop). There is currently no workaround for Cowork.

## Plugins

| Plugin | Description |
|--------|-------------|
| `core` | Persistent agent identity, session lifecycle hooks, operational memory, and meta skills |
| `dev-pipeline` | Calvinball-driven dev pipeline: Miss Wormwood (triage), Moe (dev work), and Tracer Bullet (code review) |
| `bullet-journal` | BuJo ritual system: daily, weekly, monthly, and yearly interactive reflections in Apple Notes |

## Plan of record

The architectural plan behind this marketplace lives in a private planning document. The short version: everything that was once a collection of flat files in `~/.claude/` becomes a versioned, installable plugin, so any Claude Code install can be bootstrapped to Mike's preferred setup with a single `/plugin install`.
