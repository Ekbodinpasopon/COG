# COG Workflow Template

COG Workflow Template is a master reference template for building AI-assisted project systems using ChatGPT, Codex, Obsidian, and GitHub.

COG means Codex + Obsidian + GitHub.

## Purpose

This repo is used to:
1. Start new projects from zero
2. Standardize existing unfinished projects
3. Create project-specific ChatGPT instructions
4. Create Codex handoff prompts
5. Build Obsidian-compatible Markdown vault structures
6. Control GitHub review workflow
7. Prepare public-safe template publishing

## Core Rules

- Use placeholders only until project-specific data is approved.
- Keep all content Obsidian-compatible and Markdown-first.
- Do not add application code, databases, or package dependencies unless explicitly requested.
- Do not store private names, contacts, incidents, policies, or machine-specific paths in this template.

## Repository Layout

- `00_SYSTEM/` = bootstrap, workflow, review, and publication control
- `07_SKILLS_PROTOCOLS/` = reusable operating protocols
- `TEMPLATE/` = copy-and-adapt template files
- `99_CODEX_HANDOFF/` = ready-to-use Codex prompts
- `EXAMPLES/` = sanitized examples

## Recommended Use

1. Copy or template this repository into a new project repository.
2. Replace placeholders after confirming project scope and privacy rules.
3. Keep private operational data outside the public-safe template layer.
4. Run the sanitization and review checklists before publishing any derivative repository.
