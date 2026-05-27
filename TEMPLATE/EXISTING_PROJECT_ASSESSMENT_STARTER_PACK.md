# Existing Project Assessment Starter Pack

## Purpose

Use this file for copy-ready prompts and templates when assessing an existing repository before applying COG workflow changes.

## When To Use

Use this when you already have:

- an existing repository
- an existing `README.md`
- an existing `AGENTS.md` or protocol files
- existing documentation
- existing Obsidian notes
- existing issues or tasks

## Required Inputs

- `[Project Name]`
- `[Repository URL]`
- `[Current Purpose]`
- `[Current Pain Points]`
- `[Existing AGENTS.md?]`
- `[Existing Protocol Files?]`
- `[Existing Obsidian Vault Or Notes?]`
- `[Visibility: Private/Public]`
- `[Sensitive Data Risk]`
- `[What Must Not Be Changed]`
- `[Desired COG Outcome]`

## First ChatGPT Assessment Prompt

Copy this into the first ChatGPT assessment chat and fill in the placeholders:

```text
I want to assess an existing project before applying any COG workflow changes.

Use these inputs:
- Project Name: [Project Name]
- Repository URL: [Repository URL]
- Current Purpose: [Current Purpose]
- Current Pain Points: [Current Pain Points]
- Existing AGENTS.md?: [Existing AGENTS.md?]
- Existing Protocol Files?: [Existing Protocol Files?]
- Existing Obsidian Vault Or Notes?: [Existing Obsidian Vault Or Notes?]
- Visibility: [Visibility: Private/Public]
- Sensitive Data Risk: [Sensitive Data Risk]
- What Must Not Be Changed: [What Must Not Be Changed]
- Desired COG Outcome: [Desired COG Outcome]

Produce:
- Existing Project Assessment Plan
- Current Repository / Knowledge Map
- Existing AGENTS.md Handling Plan
- Existing Protocol Handling Plan
- COG Alignment Strategy
- Conflict / Gap / Duplicate Analysis
- Sensitive Data Risk Review
- Inspect-Only GitHub Issue
- Codex Inspect-Only Handoff
- Recommended Next Step

Respond using exactly these sections:
- Existing Project Summary
- Current System Map
- Existing Rules To Preserve
- Missing Or Weak Workflow Areas
- Conflict / Duplicate Risk
- Sensitive Data Risk
- Proposed COG Process Layer
- Inspect-Only Issue Draft
- Codex Inspect-Only Handoff Draft
- Do Not Change List
- Recommended Next Step

Rules:
- inspect before changing
- preserve project-specific rules
- do not overwrite AGENTS.md
- do not refactor unrelated code
- do not expose private data
```

## Required ChatGPT Output Format

Ask ChatGPT to respond with these sections:

- `Existing Project Summary`
- `Current System Map`
- `Existing Rules To Preserve`
- `Missing Or Weak Workflow Areas`
- `Conflict / Duplicate Risk`
- `Sensitive Data Risk`
- `Proposed COG Process Layer`
- `Inspect-Only Issue Draft`
- `Codex Inspect-Only Handoff Draft`
- `Do Not Change List`
- `Recommended Next Step`

## Inspect-Only GitHub Issue Template

Title:

```text
Inspect existing project for COG alignment
```

Body:

```text
## Objective

Inspect the existing project and identify how COG can be layered onto it without overwriting project-specific rules.

## Context

- Project Name: [Project Name]
- Repository URL: [Repository URL]
- Current Purpose: [Current Purpose]
- Current Pain Points: [Current Pain Points]
- Existing AGENTS.md?: [Existing AGENTS.md?]
- Existing Protocol Files?: [Existing Protocol Files?]
- Existing Obsidian Vault Or Notes?: [Existing Obsidian Vault Or Notes?]
- Visibility: [Visibility: Private/Public]
- Sensitive Data Risk: [Sensitive Data Risk]
- What Must Not Be Changed: [What Must Not Be Changed]
- Desired COG Outcome: [Desired COG Outcome]

## Scope

- inspect the current workflow and documentation structure
- inspect existing rules, protocols, notes, and navigation files
- identify gaps, duplicates, conflicts, and sensitive-data risks
- recommend minimal alignment work only after assessment is complete

## Files/folders to inspect

- README.md
- AGENTS.md
- BRAIN_INDEX.md
- workflow folders
- template folders
- notes folders
- issue and handoff files
- documentation folders

## Out of scope

- creating new files
- editing existing files
- moving, renaming, deleting, or reformatting files
- refactoring unrelated code or documentation

## Safety rules

- preserve project-specific rules
- do not expose private data
- do not move sensitive operational data into public-safe templates
- make risks explicit

## No-change rule

This issue is inspect-only. No repository files should be created, edited, moved, deleted, renamed, or reformatted.

## Report back format

Follow `07_SKILLS_PROTOCOLS/TASK_COMPLETION_AND_HANDOFF_PROTOCOL.md` for closeout state and next-action payload.

1. Files inspected
2. Existing structure summary
3. Existing rules found
4. Gaps found
5. Conflicts or duplicates found
6. Sensitive data risk notes
7. Recommended minimal changes
8. Assumptions used
9. Risks / rollback notes
10. Recommended next step
11. Next Action Type
12. Next Action Payload

## Acceptance criteria

- current workflow structure is mapped
- existing rules are summarized
- gaps, duplicates, conflicts, and safety risks are visible
- recommended minimal alignment work is clear
- no files were changed
```

## Codex Inspect-Only Handoff Template

```text
Repository:
[Project Name]

Repository URL:
[Repository URL]

Objective:
Inspect this existing project for COG alignment without making any repository changes.

Mode:
Inspect-only

Required rules:
- do not create, edit, move, delete, rename, or reformat files
- do not infer approval for changes from the assessment alone
- do not make changes unless separately authorized

Files and areas to inspect:
- README.md
- AGENTS.md
- BRAIN_INDEX.md
- workflow folders
- template folders
- notes folders
- issue and handoff files
- documentation folders

Required report:
- existing structure
- current AGENTS.md or protocol rules
- missing COG-compatible pieces
- duplicate or conflicting files
- private-data risk indicators
- recommended minimal alignment work

Project context:
- Project Name: [Project Name]
- Current Purpose: [Current Purpose]
- Current Pain Points: [Current Pain Points]
- Existing AGENTS.md?: [Existing AGENTS.md?]
- Existing Protocol Files?: [Existing Protocol Files?]
- Existing Obsidian Vault Or Notes?: [Existing Obsidian Vault Or Notes?]
- Visibility: [Visibility: Private/Public]
- Sensitive Data Risk: [Sensitive Data Risk]
- What Must Not Be Changed: [What Must Not Be Changed]
- Desired COG Outcome: [Desired COG Outcome]

Report back format:
1. Files inspected
2. Existing structure summary
3. Existing rules found
4. Gaps found
5. Conflicts or duplicates found
6. Sensitive data risk notes
7. Recommended minimal changes
8. Assumptions used
9. Risks / rollback notes
10. Recommended next step
11. Next Action Type
12. Next Action Payload
```

## Report Back Format

Use this exact structure:

1. Files inspected
2. Existing structure summary
3. Existing rules found
4. Gaps found
5. Conflicts or duplicates found
6. Sensitive data risk notes
7. Recommended minimal changes
8. Assumptions used
9. Risks / rollback notes
10. Recommended next step
11. Next Action Type
12. Next Action Payload

## Safety Notes

- inspect before changing
- preserve project-specific rules
- do not overwrite `AGENTS.md`
- do not expose private data
- do not refactor unrelated code
- do not move sensitive operational data into public-safe templates

## Done Criteria

This assessment starter pack is complete when:

- users can run the first ChatGPT assessment
- users can create an inspect-only GitHub Issue
- users can send Codex an inspect-only handoff
- no file changes are requested before assessment is complete
- the result can feed into a later minimal-alignment issue
