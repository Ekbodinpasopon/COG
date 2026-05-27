# COG Workflow Template

COG means `Codex + Obsidian + GitHub`.

This repository is a public-safe master template for starting new AI-assisted projects from zero with `ChatGPT + Codex + Obsidian + GitHub`.

## Stable Release

- Current stable release: `v1.0.0-canonical`
- Release URL: [https://github.com/Ekbodinpasopon/COG/releases/tag/v1.0.0-canonical](https://github.com/Ekbodinpasopon/COG/releases/tag/v1.0.0-canonical)
- Use this release as the public entry point for starting new projects from the canonical COG workflow surface.

## Purpose

Use this repository to:

1. Start a new repository and Obsidian vault from a clean template.
2. Define how ChatGPT and Codex should divide planning, review, and execution work.
3. Keep project operations Markdown-first and Obsidian-compatible.
4. Standardize GitHub issue, pull request, and review workflows.
5. Prepare derivative repositories for safe public sharing.

## Operating Model

- `ChatGPT` is used for thinking, planning, reviewing, clarification, and instruction drafting.
- `Codex` is used for repository execution: creating, editing, reviewing, and pushing files.
- `Obsidian` is the Markdown knowledge layer.
- `GitHub` is the issue, versioning, and review layer.

## Who This Template Is For

Use COG when you want to create a project repository from zero with:

- a reusable operating structure
- clear AI role boundaries
- sanitized public-safe templates
- a predictable repository review process

## Repository Map

- `README.md` explains the template and how to use it.
- `AGENTS.md` defines execution rules and AI role boundaries.
- `BRAIN_INDEX.md` is the root map of the workflow system.
- `00_SYSTEM/` holds bootstrap, safety, workflow, review, and publication protocols.
- `07_SKILLS_PROTOCOLS/` holds role-specific operating protocols.
- `TEMPLATE/` holds reusable project starter files.
- `99_CODEX_HANDOFF/` holds ready-to-use Codex handoff prompts.
- `EXAMPLES/` holds sanitized examples only.

Use the files listed in `BRAIN_INDEX.md` as the canonical COG surface.

## Core Rules

- Keep everything Markdown-first and Obsidian-compatible.
- Use placeholders until project-specific data is approved.
- Do not add application code, dependencies, packages, or automation scripts unless explicitly requested.
- Do not place private operational data in this template repository.
- Treat this repository as a master workflow template, not as a live project workspace.

## How To Use COG

1. Copy or template this repository into a new repository.
2. Read [00_SYSTEM/PROJECT_BOOTSTRAP_PLAYBOOK.md](00_SYSTEM/PROJECT_BOOTSTRAP_PLAYBOOK.md).
3. Starting a new project from zero? Read [00_SYSTEM/START_FROM_ZERO_WORKFLOW.md](00_SYSTEM/START_FROM_ZERO_WORKFLOW.md) first.
4. Working with an existing project? Read [00_SYSTEM/RUN_EXISTING_PROJECT_WORKFLOW.md](00_SYSTEM/RUN_EXISTING_PROJECT_WORKFLOW.md) before changing repository files.
5. Use [BRAIN_INDEX.md](BRAIN_INDEX.md) as the authoritative navigation map.
6. Fill in the files under `TEMPLATE/` with project-specific placeholders first.
7. Start planning in ChatGPT.
8. Open executable repository work as GitHub Issues.
9. Use a Codex handoff from `99_CODEX_HANDOFF/` when files need to be created, edited, reviewed, or pushed.

## Safety

Before publishing any derivative repository, run:

1. [00_SYSTEM/REPO_SAFETY_AND_SANITIZATION_PROTOCOL.md](00_SYSTEM/REPO_SAFETY_AND_SANITIZATION_PROTOCOL.md)
2. [00_SYSTEM/REVIEW_PROTOCOL.md](00_SYSTEM/REVIEW_PROTOCOL.md)
3. [99_CODEX_HANDOFF/SANITIZE_PROJECT_FOR_PUBLIC_TEMPLATE.md](99_CODEX_HANDOFF/SANITIZE_PROJECT_FOR_PUBLIC_TEMPLATE.md)
