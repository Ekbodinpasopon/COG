# AGENTS.md

## Project Name
COG Workflow Template

## Project Purpose
This repository is a master reference template for building AI-assisted project systems with ChatGPT, Codex, Obsidian, and GitHub.

## Core Rule
Do not redesign beyond the requested structure.
Do not copy live project data from any private repository.
Do not include real names, contacts, incidents, policy details, or machine-specific paths.
Use placeholders where project-specific information is missing.
Keep everything Markdown-first and Obsidian-compatible.
Do not install packages unless explicitly requested.
Do not create an app or database unless explicitly requested.

## Tool Roles
ChatGPT is the:
- project instruction writer
- workflow advisor
- review checklist advisor
- publication safety advisor

Codex is the:
- file creator
- Markdown editor
- repository worker
- template organizer

Obsidian is the Markdown knowledge vault.
GitHub is the version control and review layer.

## Folder Rules
`00_SYSTEM` = master workflow, review, and publication control.
`07_SKILLS_PROTOCOLS` = reusable operating methods.
`TEMPLATE` = reusable project templates and checklists.
`99_CODEX_HANDOFF` = Codex prompts and handoff material.
`EXAMPLES` = sanitized examples only.

## Sanitization Rules
Use placeholders only for project-specific references.
Do not include real client, property, owner, guest, or contact data.
Do not include real email addresses, phone numbers, policy numbers, or incident records.
Do not include local machine paths; use `[Local Vault Path]` or other placeholders instead.
Do not include `.obsidian/workspace.json`, `.obsidian/plugins/`, or `.obsidian/themes/`.

## Review Rules
Check every new file for private data leakage before commit or publication.
Treat publication safety review as required before making a repository public.
Keep public-safe examples generic and non-identifying.

## Codex Output Rules
After completing any task, report only:
1. Files created
2. Files modified
3. Assumptions used
4. Risks / rollback notes
5. Next recommended step

## Safety Rules
Do not delete files unless explicitly requested.
Do not overwrite approved project-specific material without permission.
Do not create unrelated folders or features.
