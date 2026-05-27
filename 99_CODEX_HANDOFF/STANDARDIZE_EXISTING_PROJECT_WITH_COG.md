# Standardize Existing Project With COG

Use this prompt when an existing repository should be aligned to the COG workflow model.

## Repository

`[owner/repository]`

## Objective

Standardize the repository so its workflow files align with the COG operating model.

## Scope

- inspect current workflow and documentation files
- create missing Markdown workflow files
- update inconsistent workflow files
- avoid unrelated application changes

## Files to inspect

- `README.md`
- `AGENTS.md`
- `BRAIN_INDEX.md`
- existing workflow folders
- existing note and template structure

## Files to create/update

- `[List the exact files to create or update]`

## Constraints

- preserve project-specific content where approved
- avoid refactoring unrelated files
- keep Markdown-first and Obsidian-compatible

## Safety rules

- do not publish or expose private project data
- replace sensitive examples with placeholders where needed
- do not add code, packages, or automation unless requested

## Acceptance criteria

- workflow roles are clear
- routing between ChatGPT, GitHub, and Codex is explicit
- repository structure is documented
- public-safety boundaries are visible

## Report back format

1. Files created
2. Files modified
3. Assumptions used
4. Risks / rollback notes
5. Recommended next step
