# After: Initialization Framework

This folder contains the reusable framework you copy into new projects.

## Use It

Copy the template to your new project:

```bash
cp -r after/template/. /path/to/new-project/
cd /path/to/new-project/
```

Then customize `AGENTS.md` and `CLAUDE.md` with your project details.

## What Is Here

- `template/` complete reusable framework

## Template Highlights

- `.ai/` single source of truth for all AI rules
- `AGENTS.md` universal entry point (works with 60+ AI tools)
- `CLAUDE.md` quick context for Claude Code
- `docs/playbooks/` guided delivery phases (1-6 + hotfix)
- Tool adapters: `.claude`, `.github`, `.agent`, `.codex`
- Multi-tool compatibility via reference system
