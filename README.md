# browser-crashtest-lab

Standalone home for the OpenCode `browser-crashtest-lab` skill.

## What this repository contains
- `SKILL.md` — canonical skill definition
- `scripts/` — audit, judge, and probe tooling
- `references/` — standards and stack notes
- `quick_validate.py` — fast sanity helper
- `agents/` — model config for browser audit runs

## Current use
- Crawl and stress-test web surfaces
- Collect console, network, and page failures
- Run accessibility and Lighthouse quality checks
- Produce PASS / WARN / FAIL readiness reports

## Install
```bash
mkdir -p ~/.config/opencode/skills
rm -rf ~/.config/opencode/skills/browser-crashtest-lab
git clone https://github.com/SIN-Skills/browser-crashtest-lab ~/.config/opencode/skills/browser-crashtest-lab
```

## Goal
Crash-test the surface before users do.
