# iStack

The skills that make a coding agent work the way a careful senior engineer does: plan before code,
prove every change on the real thing, keep a decision log, and never block on you for reversible work.
iStack is a folder of plain [Agent Skills](https://agentskills.io), so it works in any harness:
Claude Code, Codex, Pi, OpenCode, Cursor and others.

## Install

The issance installer sets it up for the harness you choose. By hand:

```bash
npx skills add issance/istack -g -a claude-code -s '*' -y
```

Change `claude-code` to your harness (`codex`, `pi`, `opencode`, `cursor`). Then run `/setup-istack` once
to choose the models it uses.

## Use

Start a task with `/poteto-mode`, or say "poteto mode". The full guide is in [GUIDE.md](GUIDE.md)
and [docs/guide/](docs/guide/README.md).

iStack is a rebranded distribution of an MIT-licensed project; see NOTICE-ISSANCE.md and LICENSE.
