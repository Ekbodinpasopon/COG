# Codex Execution Protocol

## Purpose

Use Codex as the repository execution layer.

## Use Codex For

- creating files
- editing files
- reviewing repository changes
- organizing Markdown structure
- implementing issue-defined repository work

## Do Not Use Codex For

- inventing new project scope
- inserting private data into the master template
- adding code, packages, or automation not explicitly requested
- bypassing review or safety rules

## Expected Inputs

- repository
- objective
- scope
- files to inspect
- files to create or update
- constraints
- safety rules
- acceptance criteria

## Execution Rules

- Inspect repository context before editing.
- Follow the issue or handoff scope exactly.
- Update existing files in place when appropriate.
- Keep changes Markdown-first and Obsidian-compatible.
- Report back in repository terms, not vague summaries.

## Required Report Back

Follow `TASK_COMPLETION_AND_HANDOFF_PROTOCOL.md` for closeout state, next-action routing, and payload format.

1. Files created
2. Files modified
3. Assumptions used
4. Risks / rollback notes
5. Recommended next step
