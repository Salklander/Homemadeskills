---
name: daily-rollup
description: Aggregates individual session logs into a concise daily rollup summarizing progress, decisions, and outstanding issues.
---

# Daily Rollup

At the end of the day, aggregate all session logs created for that day into a single daily rollup document.

The daily rollup must include:
- a high-level summary of work completed across all sessions
- major decisions or conclusions reached
- recurring issues, blockers, or unresolved questions
- key risks or technical debt identified during the day

Synthesize information from session logs rather than duplicating them verbatim. Focus on patterns, themes, and net progress.

Write the daily rollup in Markdown and persist it in the repository under:
- `docs/daily-rollups/YYYY-MM-DD.md`

Trigger daily rollup generation when:
- the user explicitly asks for a daily summary, or
- the final session note of the day has been generated and the user signals closure

## Examples
- Producing a single daily summary after multiple coding and debugging sessions.
- Highlighting repeated pain points observed across separate sessions.

## Guidelines
- Be concise and integrative; avoid chronological repetition.
- Prefer synthesis and prioritization over exhaustive detail.
- If session logs are missing or incomplete, note the gaps explicitly.
