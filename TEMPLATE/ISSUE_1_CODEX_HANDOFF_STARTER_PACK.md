# Issue #1 And Codex Handoff Starter Pack

## Purpose

Use this file for copy-ready text when starting a new project from zero with COG.

It provides:

- GitHub Issue #1
- Codex Handoff #1
- Codex report back format

## When To Use

Use this when starting a brand-new project from zero using COG.

## Required Inputs

- `[Project Name]`
- `[Repository Name]`
- `[Repository URL]`
- `[Project Objective]`
- `[Project Scope]`
- `[Visibility Intent]`
- `[Primary Notes Location]`
- `[Initial Constraints]`

## GitHub Issue #1 Template

Title:

```text
Bootstrap project repository from COG workflow
```

Body:

```text
## Objective

Bootstrap the repository from the COG workflow so the project can start with a clean Markdown-first operating structure.

## Context

- Project Name: [Project Name]
- Repository Name: [Repository Name]
- Repository URL: [Repository URL]
- Project Objective: [Project Objective]
- Project Scope: [Project Scope]
- Visibility Intent: [Visibility Intent]
- Primary Notes Location: [Primary Notes Location]

## Scope

- create or update the initial workflow files needed to start the repository
- create the initial folder structure for system, notes, logs, decisions, tasks, protocols, and handoffs
- keep the repository Markdown-first and Obsidian-compatible

## Files to create/update

- README.md
- AGENTS.md
- BRAIN_INDEX.md
- 00_SYSTEM/
- 03_MEMOS/
- 04_LOGS/
- 05_DECISIONS/
- 06_TASKS/
- 07_SKILLS_PROTOCOLS/
- 99_CODEX_HANDOFF/

## Constraints

- keep everything Markdown-first
- do not add code, packages, dependencies, or automation
- do not expand scope beyond bootstrap
- follow [Initial Constraints]

## Safety rules

- do not add private project data
- do not add credentials or secrets
- do not add client private data
- do not add local machine paths
- do not add pricing, contacts, incidents, or operational private data unless explicitly approved and repository visibility is private

## Acceptance criteria

- initial repository workflow files exist
- initial folder structure exists
- README.md, AGENTS.md, and BRAIN_INDEX.md are usable
- repository is ready for the next issue and Codex handoff

## Report back format

Follow `07_SKILLS_PROTOCOLS/TASK_COMPLETION_AND_HANDOFF_PROTOCOL.md` for closeout state and next-action payload.

1. Files created
2. Files modified
3. Files intentionally not touched, when scope control matters
4. Safety review result
5. Assumptions used
6. Risks / rollback notes
7. Recommended next step
8. Next Action Type
9. Next Action Payload
```

## Codex Handoff #1 Template

```text
Repository:
[Repository Name]

Repository URL:
[Repository URL]

Objective:
Bootstrap this repository from the COG workflow for a brand-new project from zero.

Source of truth:
Use GitHub Issue #1 as the source of truth for scope and acceptance criteria.

Project context:
- Project Name: [Project Name]
- Project Objective: [Project Objective]
- Project Scope: [Project Scope]
- Visibility Intent: [Visibility Intent]
- Primary Notes Location: [Primary Notes Location]
- Initial Constraints: [Initial Constraints]

Required work:
- create the initial repository structure
- create or update README.md
- create or update AGENTS.md
- create or update BRAIN_INDEX.md
- create basic folders for system, notes, logs, decisions, tasks, protocols, and handoffs
- keep everything Markdown-first and Obsidian-compatible

Constraints:
- do not infer missing scope beyond Issue #1
- do not add code, packages, dependencies, or automation
- do not add private data
- do not add local machine paths
- do not redesign unrelated files

Safety rules:
- use placeholders when project-specific values are not yet approved
- avoid credentials, secrets, client private data, pricing, contacts, incidents, and operational private data
- keep the repository public-safe unless the project is explicitly private and approved for private content

Report back format:
1. Files created
2. Files modified
3. Files intentionally not touched, when scope control matters
4. Safety review result
5. Assumptions used
6. Risks / rollback notes
7. Recommended next step
8. Next Action Type
9. Next Action Payload
```

## Report Back Format

Use this exact structure:

1. Files created
2. Files modified
3. Files intentionally not touched, when scope control matters
4. Safety review result
5. Assumptions used
6. Risks / rollback notes
7. Recommended next step
8. Next Action Type
9. Next Action Payload

## Safety Notes

- start private first for real projects
- do not add credentials or secrets
- do not add client private data
- do not add local machine paths
- do not add pricing, contacts, incidents, or operational private data unless explicitly approved and repository visibility is private
