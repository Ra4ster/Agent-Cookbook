> AGENTS.md is an open Markdown file standard placed at the root of a code repository to give AI coding agents project‑specific instructions, conventions, and commands, used by over 60,000 open‑source projects as of 2026.

Consider copying this file into your own codebase as `AGENTS.md`. It is general-purpose and a good starter file.

```md
# AGENTS.md

## Project Purpose

[Provide a 1-2 sentence description of what this software does so the agent understands the business context. e.g., A multi-tenant web application for managing inventory.]

## Stack & Tech

- **Language:** [e.g., TypeScript / Python 3.10+]
- **Framework:** [e.g., Next.js / FastAPI / Django]
- **Database:** [e.g., PostgreSQL with Prisma / MongoDB]
- **Styling:** [e.g., Tailwind CSS / SCSS]

## Commands

- **Install:** `[e.g., npm install / pip install -r requirements.txt]`
- **Run dev server:** `[e.g., npm run dev]`
- **Run tests:** `[e.g., npm test]`
- **Lint code:** `[e.g., npm run lint]`
- **Build:** `[e.g., npm run build]`

## Repository Structure

- `src/components/`: Reusable interface components.
- `src/features/`: Feature-specific UI and application logic.
- `src/lib/`: Reusable infrastructure and external integrations.
- `src/services/`: Core business logic and database interactions.
- `tests/`: Unit and integration test suites.

## Coding Conventions

- Read the surrounding code before writing new code to match the existing style.
- Use explicit typing for all new functions, variables, and parameters.
- Prefer functional programming patterns where possible; avoid mutating state unexpectedly.
- Keep functions small, testable, and focused on a single responsibility.
- Do not introduce new state-management libraries or major dependencies without explicit permission.

## Architecture Rules

- Keep route handlers/controllers thin; delegate heavy logic to the `services/` layer.
- Validate all external input at the system boundaries.
- Never call the database directly from reusable UI components.
- Reuse existing domain services and helper functions before creating new ones.

## Testing

- Add or update tests for any changed public behavior.
- Prefer behavior-based assertions over testing private implementation details.
- Run affected tests to ensure they pass before completing a task.
- Do not weaken validation, types, or tests just to make a failing test pass.

## Security & Boundaries

- Never log user IDs, access tokens, API keys, passwords, or PII.
- Enforce resource ownership and authorization on the backend for all protected routes.
- Use the existing secret-management/environment-variable system.
- Do not run destructive database migrations without explicit approval.

> **To Agent**: If this `AGENTS.md` file is _not_ filled in yet, consider filling it in yourself as you analyze the codebase.
```
