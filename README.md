# OhMyOpenAgent: Professional Workflow Examples

> Structured, reproducible autonomous research workflows using OhMyOpenAgent.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Powered by: ohmyopenagent](https://img.shields.io/badge/Powered%20by-ohmyopenagent-orange.svg)](https://github.com/ohmyopenagent/ohmyopenagent)
[![Status: Experimental](https://img.shields.io/badge/Status-Experimental-success.svg)]()

This repository provides a set of structured, multi-phase research pipelines for `ohmyopenagent`. Each pipeline is a reusable command that runs inside the opencode TUI — the agent discovers sources, downloads content, extracts findings, and writes structured reports.

## Available Commands

| Command | Topic | Target sources |
|---|---|---|
| `/agent-frameworks` | AI agent harnesses, deep agent frameworks, coding assistants | 25+ |
| `/swiss-housing-market` | Swiss housing market, rental platforms, property management | 15+ |
| `/swiss-retail-market` | Swiss retail landscape (Migros, Coop, Lidl, Aldi) | 40+ |

## How to Run

Install [opencode](https://opencode.ai/docs/) and the [ohmyopenagent](https://github.com/code-yeongyu/oh-my-openagent) plugin, then `cd` into this repo and run `opencode` to launch the TUI.

Inside the TUI, type `/` followed by the command name:

```
/agent-frameworks
```

The command files live in `.opencode/commands/` and are auto-discovered by the TUI — no setup needed.

Each command is self-contained — open the file in `.opencode/commands/` to see its specific workflow and outputs.
