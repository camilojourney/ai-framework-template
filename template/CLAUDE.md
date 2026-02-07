# {{PROJECT_NAME}}

{{PROJECT_TAGLINE}}

## The Vision

{{PROJECT_VISION}}

## Commands

- Dev: `{{DEV_CMD}}`
- Test: `{{TEST_CMD}}`
- Lint: `{{LINT_CMD}}`
- Build: `{{BUILD_CMD}}`

## Structure

- Pages: `{{PAGES_DIR}}/`
- Components: `{{COMPONENTS_DIR}}/`
- Lib: `{{LIB_DIR}}/`
- Server: `{{SERVER_DIR}}/`
- Tests: `{{TESTS_DIR}}/`

## Agents

Load from `.ai/agents/`:

- builder.md (features, bugs, tests, review)
- operator.md (deploy, security, infrastructure)
- communicator.md (docs, UI, support)
- strategist.md (prioritization, feedback, growth)

## Standards

- `.ai/standards/code/` ({{LANGUAGE}}, {{FRAMEWORK}}, testing)
- `.ai/standards/api/design.md`
- `.ai/standards/security/baseline.md`
- `.ai/standards/comms/voice.md`

## Critical Rules

{{CRITICAL_RULES}}

## Key Files

{{KEY_FILES}}

## Database Tables

{{DATABASE_TABLES}}

## External Services

{{EXTERNAL_SERVICES}}

## Current Focus

See `.ai/contexts/current-priorities.md`

## Two Parallel Systems

| System | Location | Purpose |
|--------|----------|---------|
| **Playbooks** | `docs/playbooks/` | Human-facing prompts for driving AI sessions |
| **.ai** | `.ai/` | AI-facing context and standards for autonomous operation |

Use **playbooks** when you want to guide an AI through a specific workflow step-by-step.
Use **.ai** when you want AI to operate autonomously with full context.

## Development Workflow

Phase-based playbook in `docs/playbooks/`:

1. `1-spec-create.md` - Write detailed specs from ideas
2. `2-spec-review.md` - QA specs before implementation
3. `3-implement.md` - Build from specs
4. `4-audit-logic.md` - Hostile bug hunting (be adversarial)
5. `5-audit-intent.md` - UX and intent verification
6. `6-fix-iterate.md` - Apply fixes with minimal changes

Usage: "Read docs/playbooks/4-audit-logic.md and audit the feature I just built"

## MCP Servers

Configured in `.mcp.json` - filesystem, memory, GitHub access.
