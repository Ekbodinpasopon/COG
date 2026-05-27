# BRAIN_INDEX

This file is the root map of the COG workflow system.

Use it to understand where each rule, template, and handoff file belongs before changing the repository.

## Root Files

- `README.md` explains what COG is and how to use the template.
- `AGENTS.md` defines repository rules and AI role boundaries.
- `BRAIN_INDEX.md` maps the workflow system.

## 00_SYSTEM

- `00_SYSTEM/PROJECT_BOOTSTRAP_PLAYBOOK.md`
  - Step-by-step process for starting a new project from zero.
- `00_SYSTEM/CHATGPT_CODEX_GITHUB_OBSIDIAN_WORKFLOW.md`
  - End-to-end operating model across ChatGPT, Codex, Obsidian, and GitHub.
- `00_SYSTEM/REPO_SAFETY_AND_SANITIZATION_PROTOCOL.md`
  - Public/private safety and sanitization rules.
- `00_SYSTEM/REVIEW_PROTOCOL.md`
  - Repository review gate before merge or publication.
- `00_SYSTEM/PUBLIC_TEMPLATE_RULES.md`
  - Rules that keep the repository reusable and public-safe.

## 07_SKILLS_PROTOCOLS

- `07_SKILLS_PROTOCOLS/CHATGPT_ADVISORY_PROTOCOL.md`
  - How ChatGPT should be used for planning and review.
- `07_SKILLS_PROTOCOLS/CODEX_EXECUTION_PROTOCOL.md`
  - How Codex should be used for repository execution work.
- `07_SKILLS_PROTOCOLS/GITHUB_ISSUE_PROTOCOL.md`
  - How to define executable repository work as GitHub Issues.
- `07_SKILLS_PROTOCOLS/GITHUB_PR_REVIEW_PROTOCOL.md`
  - How to review pull requests in a structured way.
- `07_SKILLS_PROTOCOLS/OBSIDIAN_NOTE_PROTOCOL.md`
  - How notes should be structured inside the vault.
- `07_SKILLS_PROTOCOLS/PROMPT_VS_ISSUE_ROUTING_PROTOCOL.md`
  - How to decide between ChatGPT prompts, GitHub Issues, and Codex handoffs.

## TEMPLATE

- `TEMPLATE/CHATGPT_PROJECT_INSTRUCTIONS_TEMPLATE.md`
  - Copy-ready project instruction template for ChatGPT.
- `TEMPLATE/CODEX_HANDOFF_TEMPLATE.md`
  - Copy-ready Codex handoff template.
- `TEMPLATE/PROJECT_README_TEMPLATE.md`
  - Starter README for a new derivative project.
- `TEMPLATE/AGENTS_TEMPLATE.md`
  - Starter AGENTS file for a derivative project.
- `TEMPLATE/BRAIN_INDEX_TEMPLATE.md`
  - Starter root map for a derivative project.
- `TEMPLATE/OBSIDIAN_VAULT_STRUCTURE.md`
  - Standard vault folder layout.
- `TEMPLATE/DECISIONS_TEMPLATE.md`
  - Decision log template.
- `TEMPLATE/TASKS_TEMPLATE.md`
  - Task tracking template.
- `TEMPLATE/LOG_TEMPLATE.md`
  - Operating log template.

## 99_CODEX_HANDOFF

- `99_CODEX_HANDOFF/BOOTSTRAP_NEW_PROJECT_FROM_COG.md`
  - Codex prompt for starting a new project from this template.
- `99_CODEX_HANDOFF/STANDARDIZE_EXISTING_PROJECT_WITH_COG.md`
  - Codex prompt for applying COG to an existing repository.
- `99_CODEX_HANDOFF/SANITIZE_PROJECT_FOR_PUBLIC_TEMPLATE.md`
  - Codex prompt for publication safety and sanitization work.

## EXAMPLES

- `EXAMPLES/README.md`
  - Explains how to use the examples folder safely.
- `EXAMPLES/EXAMPLE_PROJECT_SCOPE_SANITIZED.md`
  - Sanitized project scope example.
- `EXAMPLES/EXAMPLE_CODEX_HANDOFF_SANITIZED.md`
  - Sanitized Codex handoff example.
- `EXAMPLES/EXAMPLE_CHATGPT_PROJECT_INSTRUCTION_SANITIZED.md`
  - Sanitized ChatGPT project instruction example.

## Retained Legacy Files

These files may remain in the repository from earlier template iterations and should be treated as retained foundation material until explicitly cleaned up:

- `00_SYSTEM/CHATGPT_CODEX_GITHUB_WORKFLOW_PROTOCOL.md`
- `00_SYSTEM/MASTER_REFERENCE_USAGE_GUIDE.md`
- `00_SYSTEM/PUBLICATION_SAFETY_PROTOCOL.md`
- `07_SKILLS_PROTOCOLS/codex-handoff-protocol.md`
- `07_SKILLS_PROTOCOLS/github-obsidian-sync-protocol.md`
- `07_SKILLS_PROTOCOLS/obsidian-lite-navigation-protocol.md`
- `99_CODEX_HANDOFF/existing-project-migration-prompt.md`
- `99_CODEX_HANDOFF/new-project-bootstrap-master-prompt.md`
- `99_CODEX_HANDOFF/public-repo-sanitization-review-prompt.md`
- `99_CODEX_HANDOFF/sample-codex-task-prompt.md`
- `EXAMPLES/example-codex-report.md`
- `EXAMPLES/example-project-map.md`
- `EXAMPLES/example-review-result.md`
- `TEMPLATE/EXISTING_PROJECT_MIGRATION_CHECKLIST.md`
- `TEMPLATE/NEW_PROJECT_CHECKLIST.md`
- `TEMPLATE/OBSIDIAN_LITE_HOME_TEMPLATE.md`
- `TEMPLATE/PROJECT_FOLDER_STRUCTURE_TEMPLATE.md`
- `TEMPLATE/SANITIZATION_CHECKLIST.md`

## Navigation Order

1. Read `README.md`.
2. Read `AGENTS.md`.
3. Use this index to find the relevant protocol or template.
4. Use `00_SYSTEM/` before changing workflow behavior.
5. Use `07_SKILLS_PROTOCOLS/` before drafting prompts, issues, or review requests.
6. Use `TEMPLATE/` when creating a new derivative repository.
7. Use `99_CODEX_HANDOFF/` when handing repository work to Codex.
