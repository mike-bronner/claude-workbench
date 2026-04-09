# claude-workbench

Mike Bronner's personal Claude Code plugin marketplace.

## What this is

A catalog of Claude Code plugins I use across my workflows — persistent agent identity, operational memory, and workflow automation. Each plugin lives in its own repo; this repo is just the marketplace manifest that points at them.

## Installation

```
/plugin marketplace add mike-bronner/claude-workbench
/plugin install <plugin-name>@claude-workbench
```

## Plugins

_(Plugins will be listed here as they are added to the marketplace.)_

## Plan of record

The architectural plan behind this marketplace lives in a private planning document. The short version: everything that was once a collection of flat files in `~/.claude/` becomes a versioned, installable plugin, so any Claude Code install can be bootstrapped to Mike's preferred setup with a single `/plugin install`.
