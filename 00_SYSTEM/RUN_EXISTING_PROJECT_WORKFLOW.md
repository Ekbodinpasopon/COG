# Run Existing Project Workflow

## Purpose

Use this document when you want to apply COG to an existing project or repository without replacing the current project-specific system.

## Who This Is For

Use this workflow if you already have one or more of these:

- an existing GitHub repository
- an existing `README.md`
- an existing `AGENTS.md`
- existing workflow or protocol files
- an existing Obsidian vault or note structure
- existing issues, tasks, or project documents

## Core Principle

Inspect before changing.

Preserve project-specific rules.

Add COG as a workflow and process layer, not as a destructive replacement.

## Required Tools

- `ChatGPT` = assessment, planning, conflict analysis, instruction drafting, review
- `GitHub` = source of truth, issue tracking, pull requests, review history
- `Codex` = inspect the repository, report structure, and create or update files only after scope is approved
- `Obsidian` = notes, logs, decisions, tasks

## Existing Project Intake

Gather these inputs first:

- `[Project Name]`
- `[Repository URL]`
- `[Current Purpose]`
- `[Current Pain Points]`
- `[Existing AGENTS.md? yes/no]`
- `[Existing Protocol Files?]`
- `[Existing Obsidian Vault?]`
- `[Visibility: Private/Public]`
- `[Sensitive Data Risk]`
- `[What Must Not Be Changed]`

## Recommended Sequence

Use this order:

1. Open ChatGPT in a new chat, or use the existing ChatGPT Project if one already exists.
2. Provide the repository URL and current project purpose.
3. Ask ChatGPT to create an assessment plan first.
4. Read or inspect `README.md`, `AGENTS.md`, `BRAIN_INDEX.md`, workflow folders, templates, and notes.
5. Create an existing project map.
6. Identify conflicts, gaps, duplicates, and unsafe areas.
7. Open a GitHub Issue for an inspect-only pass.
8. Use Codex for inspect-only review first.
9. Bring the Codex report back to ChatGPT.
10. Approve a narrow update scope.
11. Open or update a GitHub Issue for minimal alignment work.
12. Use Codex to apply only the approved changes.
13. Review the results.
14. Record decisions, logs, and tasks.

Use `99_CODEX_HANDOFF/STANDARDIZE_EXISTING_PROJECT_WITH_COG.md` when you need a standard Codex handoff for existing-project alignment work.

## First ChatGPT Prompt For Existing Project

Use `TEMPLATE/EXISTING_PROJECT_ASSESSMENT_STARTER_PACK.md` before opening the first inspect-only GitHub Issue and Codex inspect-only handoff if you want a copy-ready assessment pack.

Copy this into the first ChatGPT chat and fill in the placeholders:

```text
BEGIN EXISTING PROJECT CHATGPT PROMPT

I want to apply the COG workflow to an existing project without overwriting the current system.

Project Name:
Repository URL:
Current Purpose:
Current Pain Points:
Existing AGENTS.md or Protocols:
Existing Obsidian / Notes:
Visibility:
Sensitive Data Risk:
What Must Not Be Changed:

Help me create:
1. Existing Project Assessment Plan
2. Current Repository / Knowledge Map
3. Existing AGENTS.md or Protocol Handling Plan
4. COG Alignment Strategy
5. Risks And Conflict Points
6. Inspect-Only GitHub Issue
7. Codex Inspect-Only Handoff
8. Recommended Next Step

Rules:
- Inspect before changing
- Preserve project-specific rules
- Add COG as a process layer
- Do not overwrite AGENTS.md blindly
- Do not refactor unrelated files
- Do not expose private data

END EXISTING PROJECT CHATGPT PROMPT
```

## Existing AGENTS.md Handling

If the repository already has `AGENTS.md` or other protocol files:

- inspect them first
- summarize the current rules
- identify project-specific rules
- identify reusable workflow rules
- preserve project-specific rules
- add COG process only where it does not conflict
- if a conflict exists, report it instead of resolving it silently

## Inspect-Only Codex Pass

The first Codex pass should usually be inspect-only.

Codex should report:

- current structure
- key workflow files
- existing `AGENTS.md` or protocol rules
- missing COG-compatible pieces
- duplicate or conflicting files
- sensitive data risk
- recommended minimal changes

No files should be changed during inspect-only review unless that is explicitly requested.

## Minimal Alignment Pass

After the inspect-only review, Codex may create or update only approved files.

Use `TEMPLATE/MINIMAL_ALIGNMENT_STARTER_PACK.md` only after the inspect-only assessment has been reviewed and the minimal alignment scope has been explicitly approved.

Examples:

- add or update `BRAIN_INDEX.md`
- add a workflow map
- add a missing issue or handoff protocol
- add note, log, or decision structure
- update `README.md` navigation
- add a COG process section to `AGENTS.md` without deleting existing rules

## What Not To Do

- do not overwrite `AGENTS.md` blindly
- do not delete existing workflow files without review
- do not refactor code while aligning workflow documents
- do not move private operational data into public-safe templates
- do not merge unrelated cleanup with COG alignment
- do not treat ChatGPT output as source of truth until it is written to the repository

## Normal Operating Loop For Existing Projects

Use this loop:

Existing task or problem -> ChatGPT assessment -> GitHub Issue -> Codex inspect or apply handoff -> Review -> Decision, task, or log update

## Done Criteria

An existing project is COG-aligned when:

- the current system is mapped
- existing rules are preserved or explicitly revised
- ChatGPT, Codex, GitHub, and Obsidian roles are clear
- GitHub Issue routing is clear
- Codex handoff rules are clear
- `BRAIN_INDEX.md` or an equivalent navigation map exists
- the safety boundary is visible
- no unrelated code or application changes were made
