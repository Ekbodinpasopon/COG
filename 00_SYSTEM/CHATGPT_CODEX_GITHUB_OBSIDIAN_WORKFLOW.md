# ChatGPT Codex GitHub Obsidian Workflow

## Purpose

Define how the four parts of the COG workflow work together.

## Core Principle

Use the right tool for the right kind of work.

- `ChatGPT` for thinking
- `Codex` for repository execution
- `GitHub` for tracked executable work and review
- `Obsidian` for Markdown knowledge organization

## Workflow Sequence

1. Define the problem in ChatGPT.
2. Clarify scope, constraints, and acceptance criteria in ChatGPT.
3. Convert executable repository work into a GitHub Issue.
4. Prepare a Codex handoff for the issue if files need to change.
5. Let Codex create, edit, review, or organize repository files.
6. Review changes through GitHub pull request workflow when branch-based work is used.
7. Record stable decisions, logs, and task state in Obsidian-compatible Markdown.

## Repository Source Of Truth

- Do not treat chat output as source of truth until it is written into the repository.
- Keep review discussion tied to files, decisions, and tracked repository work.
- Use `EXAMPLES/` only as sanitized formatting references, not as operational content.

## Tool Responsibilities

### ChatGPT

- reasoning
- planning
- instruction drafting
- review support
- ambiguity reduction

### Codex

- repository edits
- file generation
- repository reviews
- issue execution
- structured report back

### GitHub

- issue tracking
- branch history
- pull request review
- change visibility
- approval flow

### Obsidian

- notes
- decisions
- tasks
- logs
- index pages

## Handoff Logic

- If the work is still conceptual, keep it in ChatGPT.
- If the work is executable and repository-scoped, create a GitHub Issue.
- If the issue requires file changes, prepare a Codex handoff.
- If the result needs review, route it through GitHub review.
- If the result should be retained as knowledge, store it in Markdown files compatible with Obsidian.

## Repository Discipline

- Keep workflow documents separate from project content.
- Keep public-safe template files generic.
- Make file ownership and responsibilities explicit.
- Prefer stable Markdown artifacts over chat-only decisions.
- Use pull requests for review-sensitive template changes.
- Keep commit scope narrow and descriptive.
