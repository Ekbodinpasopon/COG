# Start From Zero Workflow

## Purpose

Use this document when you are starting a new project from zero with the COG workflow.

It explains what to open, what to create, what to configure, and how ChatGPT, GitHub, Codex, and Obsidian fit together from the first project idea to the first working execution loop.

## Who This Is For

This document is for users who only have:

- a project idea
- ChatGPT
- GitHub
- Codex
- optionally Obsidian

## Required Tools

### ChatGPT

Use ChatGPT for:

- planning
- review
- instruction drafting
- issue drafting
- Codex handoff drafting

### GitHub

Use GitHub as the:

- repository
- source of truth
- issues layer
- pull request layer
- review history

### Codex

Use Codex for:

- repository execution
- file creation
- file edits
- structured report back

### Obsidian

Use Obsidian for:

- Markdown notes
- decisions
- tasks
- logs

## Account And Permission Setup

Before starting, confirm:

- you have a GitHub account
- you can create or access the target GitHub repository
- ChatGPT has GitHub connector access if that option is available to you
- Codex is authorized to access the target repository
- an Obsidian vault or notes folder is ready if you plan to use Obsidian

## Start From Zero Sequence

Follow this order:

1. Open a new ChatGPT chat.
2. Describe the project idea, objective, scope, constraints, and visibility intent.
3. Ask ChatGPT to create:
   - Project Summary
   - Project Boundary
   - Agent Protocol
   - ChatGPT Project Instruction
   - Project Map
   - GitHub Issue #1
   - Codex Handoff #1
4. Create a GitHub repository.
   - Prefer private first for real projects.
5. Create a ChatGPT Project after the Project Instruction is drafted.
6. Paste the Project Instruction into the ChatGPT Project instructions field.
7. Add the GitHub repository URL to the Project Instruction.
8. Open Issue #1 in GitHub.
   - Use `TEMPLATE/ISSUE_1_CODEX_HANDOFF_STARTER_PACK.md` for copy-ready Issue #1 text.
9. Run Codex using Codex Handoff #1.
   - Use `TEMPLATE/ISSUE_1_CODEX_HANDOFF_STARTER_PACK.md` for copy-ready Codex Handoff #1 text.
10. Bring the Codex report back to ChatGPT for review.
11. Create or align the Obsidian vault structure.
12. Continue normal work using:
   - Issue
   - Codex
   - Review
   - Log

## First ChatGPT Prompt

Use `TEMPLATE/PROJECT_SUMMARY_AND_BOUNDARY_STARTER_PACK.md` before drafting the ChatGPT Project Instruction, GitHub Issue #1, and Codex Handoff #1 if you want a copy-ready first-session prompt.

Copy this into the first ChatGPT chat and fill in the placeholders:

```text
BEGIN FIRST CHATGPT PROMPT

I want to start a new project from zero using the COG workflow.

Project Name:
Repository Name:
Project Objective:
Project Scope:
Visibility Intent:
Primary Notes Location:
Initial Constraints:

Help me create:
1. Project Summary
2. Project Boundary
3. Agent Protocol
4. ChatGPT Project Instruction
5. Initial Repository Map
6. Initial Obsidian Structure
7. GitHub Issue #1
8. Codex Handoff Prompt #1

Use this operating model:
ChatGPT = planning, review, clarification, instruction drafting
Codex = repository execution
GitHub = source of truth, issues, pull requests, review
Obsidian = Markdown notes, decisions, tasks, logs

END FIRST CHATGPT PROMPT
```

## GitHub Repo Setup

When creating the GitHub repository:

- create a new repository
- use private first for real projects
- enable Issues
- keep the initial README minimal if you are not using the COG template directly at creation time
- do not add sensitive data

## ChatGPT Project Setup

Set up the ChatGPT Project only after the Project Instruction is drafted.

Use `TEMPLATE/CHATGPT_PROJECT_INSTRUCTION_STARTER_PACK.md` after project summary and boundary drafting, and before finalizing the ChatGPT Project.

Then:

1. Create the ChatGPT Project.
2. Paste the Project Instruction into the Project instructions field.
3. Include the repository URL.
4. Use this Project for future project conversations.

## Codex Setup And Timing

Use Codex only after the repository, issue, and handoff are ready.

Rules:

- do not ask Codex to infer missing scope
- paste the Codex handoff into Codex
- use `TEMPLATE/ISSUE_1_CODEX_HANDOFF_STARTER_PACK.md` if you want a faster bootstrap draft
- expect Codex to report:
  - files created
  - files modified
  - assumptions
  - risks
  - next step

## Existing Agent Protocol Handling

If the target project already has `AGENTS.md` or another agent protocol:

- do not overwrite it blindly
- inspect it first
- keep project-specific rules
- add the COG workflow as a process layer
- resolve conflicts explicitly

## Normal Operating Loop

Use this loop after the first setup:

Idea or problem -> ChatGPT analysis -> GitHub Issue -> Codex Handoff -> Codex execution -> ChatGPT review -> Markdown log, decision, or task

## Common Mistakes

Avoid these:

- starting in Codex before scope is clear
- creating the ChatGPT Project before the instructions are drafted
- skipping the GitHub Issue
- using chat as source of truth without writing to the repository
- adding private data to public-safe templates
- mixing project content and workflow protocol files

## Done Criteria

A start-from-zero setup is complete when:

- a GitHub repository exists
- a ChatGPT Project exists
- a Project Instruction exists
- `AGENTS.md` exists
- `BRAIN_INDEX.md` exists
- Issue #1 exists
- a Codex handoff exists
- the Obsidian structure exists or is defined
- the first review, log, and decision path is clear
