# AGENTS.md - {{PROJECT_NAME}} Project Constitution

## Project Overview

{{PROJECT_NAME}} is **{{PROJECT_TAGLINE}}**.

**Vision:** {{PROJECT_VISION}}

## Build Phases

| Phase | Timeline | Focus |
|-------|----------|-------|
| **MVP** | {{MVP_TIMELINE}} | {{MVP_FOCUS}} |
| **V1.5** | {{V15_TIMELINE}} | {{V15_FOCUS}} |
| **V2** | {{V2_TIMELINE}} | {{V2_FOCUS}} |

## Quick Commands

| Command | Purpose |
|---------|---------|
| `{{INSTALL_CMD}}` | Install dependencies |
| `{{DEV_CMD}}` | Start dev server |
| `{{BUILD_CMD}}` | Production build |
| `{{TEST_CMD}}` | Run tests |
| `{{LINT_CMD}}` | Lint and auto-fix |

## Tech Stack

- **Framework:** {{FRAMEWORK}}
- **Language:** {{LANGUAGE}}
- **Database:** {{DATABASE}}
- **{{TECH_STACK_CUSTOM}}**

## Project Structure

```
{{PROJECT_ROOT}}/
├── {{SOURCE_DIR}}/           # Source code
├── {{COMPONENTS_DIR}}/       # Reusable components
├── {{LIB_DIR}}/              # Utilities and libraries
├── {{SERVER_DIR}}/           # API routes and server logic
└── {{TESTS_DIR}}/            # Test files
```

## Two Parallel Systems

| System | Location | Purpose |
|--------|----------|---------|
| **Playbooks** | `docs/playbooks/` | Human-facing prompts for driving AI sessions |
| **.ai** | `.ai/` | AI-facing context and standards for autonomous operation |

Use **playbooks** when you want to guide an AI through a specific workflow step-by-step.
Use **.ai** when you want AI to operate autonomously with full context.

## Agent System

| Task Type | Agent | File |
|-----------|-------|------|
| Build anything technical | Builder | `.ai/agents/builder.md` |
| Keep it running | Operator | `.ai/agents/operator.md` |
| Talk to humans | Communicator | `.ai/agents/communicator.md` |
| Decide what to build | Strategist | `.ai/agents/strategist.md` |

## Standards

- {{LANGUAGE}}: `.ai/standards/code/{{LANGUAGE_STANDARD}}.md`
- {{FRAMEWORK}}: `.ai/standards/code/{{FRAMEWORK_STANDARD}}.md`
- Testing: `.ai/standards/code/testing.md`
- API: `.ai/standards/api/design.md`
- Security: `.ai/standards/security/baseline.md`
- Voice: `.ai/standards/comms/voice.md`

## Workflows

- Ship Feature: `.ai/workflows/ship-feature.md`
- Investigate Bug: `.ai/workflows/investigate-bug.md`
- Customer Feedback: `.ai/workflows/customer-feedback.md`
- Weekly Ops: `.ai/workflows/weekly-ops.md`

## Contexts

- Product: `.ai/contexts/product-context.md`
- Priorities: `.ai/contexts/current-priorities.md`
- Optional project-specific context: `.ai/contexts/{{PROJECT_SLUG}}.md`

## Templates

- PR Description: `.ai/templates/pr-description.md`
- Changelog Entry: `.ai/templates/changelog-entry.md`
- Customer Response: `.ai/templates/customer-response.md`
- Weekly Update: `.ai/templates/weekly-update.md`

## Core Rules

### Always

- Use {{LANGUAGE}} strict mode
- Write tests for business logic
- Run `{{LINT_CMD}}` before committing
- Add documentation to exported functions
{{CUSTOM_ALWAYS_RULES}}

### Ask First

- Adding new dependencies
- Modifying database schema
- Changing authentication flow
- Major architectural changes
{{CUSTOM_ASK_FIRST_RULES}}

### Never

- Commit API keys or secrets
- Disable type checking
- Skip error handling
{{CUSTOM_NEVER_RULES}}

## Escalation (All Agents)

- Work estimate > 1 day
- Breaking change to API or database
- Security severity > Medium
- Confidence is low

See `.ai/decision-boundaries.md` for full authority matrix.

## Domain Concepts

{{DOMAIN_CONCEPTS}}

## Specs

- **MVP:** `specs/{{MVP_SPEC_FILE}}.md`
