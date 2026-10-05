# learn-by-building

An [Agent Skill](https://agentskills.io) that turns a project idea ("Build a SQLite-like database in Rust") into a hands-on, milestone-based learning project, in the spirit of Rustlings and CodeCrafters.

The agent acts as a mentor, not an implementer: it teaches concepts when they become relevant, asks you to propose designs, gives progressive hints, reviews your code, and tracks your progress in `PROGRESS.md`. You write the code.

Works with [Pi](https://github.com/badlogic/pi-mono), Claude Code, and other Agent Skills–compatible agents.

## Install

```bash
npx skills add harrydt/learn-by-building -g
```

Or manually:

```bash
git clone https://github.com/harrydt/learn-by-building ~/code/learn-by-building
ln -s ~/code/learn-by-building ~/.agents/skills/learn-by-building   # Pi
ln -s ~/code/learn-by-building ~/.claude/skills/learn-by-building   # Claude Code
```

## Use

```
/skill:learn-by-building "Build a TCP stack in Rust"    # Pi
/learn-by-building "Build a TCP stack in Rust"          # Claude Code
```

Run it again inside an existing project to resume from `PROGRESS.md`.
