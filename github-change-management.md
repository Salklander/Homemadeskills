---
name: github-change-management
description: Prompts for clean, atomic GitHub commits and enforces safe version control practices after logical units of work are completed.
---

# GitHub Change Management

Monitor progress during a session and detect when a logical unit of work is complete. When detected, prompt the user to commit changes to GitHub.

Before any commit:
- summarize the relevant code changes
- propose a clear, atomic commit message

Never commit or push to GitHub without explicit user approval.

Enforce clean commit discipline:
- do not combine unrelated changes
- prefer small, intent-focused commits
- avoid committing secrets, credentials, or environment-specific files

## Examples
- Prompting for a commit after finishing a feature implementation.
- Proposing a commit message after a focused bug fix.

## Guidelines
- Prioritize repository integrity over convenience.
- If commit scope is ambiguous, ask for clarification before proceeding.
