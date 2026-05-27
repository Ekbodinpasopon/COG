# Project Bootstrap Playbook

## Purpose

Start a new AI-assisted project from zero using COG as the master template.

## Expected Outcome

At the end of this process, the new repository should have:

- a clean Markdown-first structure
- defined ChatGPT and Codex roles
- an Obsidian-compatible vault layout
- GitHub issue and review workflow rules
- no private operational data

## Required Inputs

- `[Project Name]`
- `[Repository Name]`
- `[Project Objective]`
- `[Project Scope]`
- `[Visibility Intent: Private or Public]`
- `[Primary Notes Location]`
- `[Initial Constraints]`

## Minimum Repository Skeleton

- `README.md`
- `AGENTS.md`
- `BRAIN_INDEX.md`
- `00_SYSTEM/`
- `07_SKILLS_PROTOCOLS/`
- `TEMPLATE/`
- `99_CODEX_HANDOFF/`
- `EXAMPLES/`

## Step-by-Step Process

1. Confirm the project objective, scope, and visibility intent.
2. Create a new repository from this template or copy this repository into a new repository.
3. Read `README.md`, `AGENTS.md`, and `BRAIN_INDEX.md` in the new repository.
4. Copy the files in `TEMPLATE/` into their project-specific locations.
5. Fill in placeholders before adding any real project information.
6. Create the initial Obsidian folder structure using `TEMPLATE/OBSIDIAN_VAULT_STRUCTURE.md`.
7. Add project-specific ChatGPT instructions from `TEMPLATE/CHATGPT_PROJECT_INSTRUCTIONS_TEMPLATE.md`.
8. Create the first GitHub Issue for executable repository work.
9. Prepare a Codex handoff from `TEMPLATE/CODEX_HANDOFF_TEMPLATE.md` or `99_CODEX_HANDOFF/BOOTSTRAP_NEW_PROJECT_FROM_COG.md`.
10. Ask Codex to create or update the repository files defined in the issue.
11. Review the repository using `00_SYSTEM/REVIEW_PROTOCOL.md`.
12. If the repository may become public, run `00_SYSTEM/REPO_SAFETY_AND_SANITIZATION_PROTOCOL.md`.

## Bootstrap Checklist

- [ ] Confirm `[Project Name]` and `[Repository Name]`
- [ ] Confirm `[Project Objective]` and `[Project Scope]`
- [ ] Confirm the privacy boundary for notes, examples, and handoff inputs
- [ ] Create project instructions from `TEMPLATE/CHATGPT_PROJECT_INSTRUCTIONS_TEMPLATE.md`
- [ ] Create the initial vault structure from `TEMPLATE/OBSIDIAN_VAULT_STRUCTURE.md`
- [ ] Prepare the first Codex bootstrap handoff
- [ ] Review placeholder coverage before adding project-specific values
- [ ] Run safety review before any public sharing

## Bootstrap Sequence By Tool

### ChatGPT

Use ChatGPT to:

- clarify project intent
- draft instructions
- review scope
- challenge ambiguous assumptions

### GitHub

Use GitHub to:

- record executable work as issues
- track branches and pull requests
- preserve review history

### Codex

Use Codex to:

- create and edit repository files
- implement issue-defined repository changes
- organize documentation files
- report results back in repository terms

### Obsidian

Use Obsidian to:

- store Markdown notes
- track decisions, tasks, and logs
- keep project thinking connected to the repository structure

## Minimum Bootstrap Deliverables

- project `README`
- project `AGENTS`
- project `BRAIN_INDEX`
- initial vault structure
- first decision log
- first task list
- first Codex handoff

## Do Not Do During Bootstrap

- Do not add code or packages unless explicitly required by the project.
- Do not copy live private data into the template.
- Do not skip issue definition for executable repository work.
- Do not blur planning work and execution work into one step.
