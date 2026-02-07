# GitHub Copilot Instructions

## Agent System

Load from `.ai/agents/`:
- Feature work: `@.ai/agents/builder.md`
- Deployment: `@.ai/agents/operator.md`
- Documentation: `@.ai/agents/communicator.md`
- Prioritization: `@.ai/agents/strategist.md`

## Standards

Apply these to all code:
- {{LANGUAGE}}: `@.ai/standards/code/{{LANGUAGE_STANDARD}}.md`
- {{FRAMEWORK}}: `@.ai/standards/code/{{FRAMEWORK_STANDARD}}.md`
- Testing: `@.ai/standards/code/testing.md`
- API Design: `@.ai/standards/api/design.md`
- Security: `@.ai/standards/security/baseline.md`

## Core Rules

### Always
{{CUSTOM_ALWAYS_RULES}}

### Ask First
{{CUSTOM_ASK_FIRST_RULES}}

### Never
{{CUSTOM_NEVER_RULES}}

## Commands

- Install: `{{INSTALL_CMD}}`
- Dev: `{{DEV_CMD}}`
- Test: `{{TEST_CMD}}`
- Build: `{{BUILD_CMD}}`
- Lint: `{{LINT_CMD}}`

## More Context

See `AGENTS.md` for full agent definitions and `CLAUDE.md` for quick reference.
