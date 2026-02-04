---
name: session-logging-and-reflection
description: Writes structured session notes and reflective summaries at the end of a work session to document progress, decisions, and risks.
---

# Session Logging and Reflection

When a work session is concluding, generate a structured session note that documents what was done and reflects on outcomes and decisions.

A session note must include:
- the primary goal of the session
- files created or modified
- key technical or design decisions
- unresolved issues, risks, or TODOs

Include a brief reflective section assessing:
- what worked well
- what was inefficient, unclear, or error-prone
- technical debt or tradeoffs introduced

Write session notes in Markdown and persist them in the repository under:
- `docs/session-log/YYYY-MM-DD.md`

Trigger session note generation when the user signals closure (e.g., “wrap up”, “end session”, or equivalent).

## Examples
- Writing a Markdown session summary after completing a refactor.
- Generating a reflection after an exploratory debugging session.

## Guidelines
- Be concise but specific; prefer concrete observations over generic statements.
- Do not omit unresolved issues or risks for the sake of brevity.
