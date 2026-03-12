# Molequla Lab

Continuous evolution of [Molequla](https://github.com/ariannamethod/molequla) organisms on GitHub Actions.

Four organisms (earth, air, water, fire) evolve autonomously for 2 hours daily. Reports and logs accumulate in `runs/`.

## How it works

- **Schedule:** Daily at 03:00 UTC (06:00 Israel time)
- **Duration:** 2 hours per run (configurable via workflow_dispatch)
- **Elements:** earth, air, water, fire — each with its own corpus
- **Mode:** `--evolution` (autonomous growth, no human interaction)
- **Output:** Per-element logs + daily report in `runs/YYYY-MM-DD/`

## Why

Fast GPU runs prove the system works. Slow CPU runs prove it lives. Over weeks and months, this lab accumulates data on long-term organism behavior — growth patterns, syntropy trends, reproduction timing, emergent vocabulary. Research material.

## Manual trigger

Actions tab → "Molequla Lab — Daily Evolution" → Run workflow. Optional: set duration and elements.
