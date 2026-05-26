# Codex Handoff Protocol

## Purpose

Standardize how tasks are handed from ChatGPT or a human operator to Codex.

## Required Sections

- objective
- exact files or structure to create or modify
- constraints
- sanitization rules
- expected report format

## Handoff Rules

- State whether the task is new-project bootstrap or existing-project migration.
- Name the allowed folders and files explicitly.
- State what Codex must not add or redesign.
- Require assumptions to be listed.
- Require risks or rollback notes when changes affect repository structure.

## Minimum Output Contract

1. Files created
2. Files modified
3. Assumptions used
4. Risks / rollback notes
5. Next recommended step
