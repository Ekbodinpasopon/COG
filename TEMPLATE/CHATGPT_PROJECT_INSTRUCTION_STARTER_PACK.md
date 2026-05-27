# ChatGPT Project Instruction Starter Pack

## Purpose

Use this file for a copy-ready process that turns a project summary and boundary into a clean ChatGPT Project Instruction.

## When To Use

Use this after drafting the project summary and boundary, and before creating or finalizing the ChatGPT Project.

## Required Inputs

- `[Project Name]`
- `[Repository URL]`
- `[Project Objective]`
- `[Project Scope]`
- `[Out Of Scope]`
- `[Visibility Intent]`
- `[Primary Notes Location]`
- `[Initial Constraints]`
- `[Tool Roles]`
- `[Safety Rules]`
- `[Existing AGENTS.md Or Protocol Notes]`

## First Prompt To Generate Project Instruction

Copy this into ChatGPT after the project summary and boundary are drafted:

```text
I need a complete ChatGPT Project Instruction for a new project using the COG workflow.

Use these inputs:
- Project Name: [Project Name]
- Repository URL: [Repository URL]
- Project Objective: [Project Objective]
- Project Scope: [Project Scope]
- Out Of Scope: [Out Of Scope]
- Visibility Intent: [Visibility Intent]
- Primary Notes Location: [Primary Notes Location]
- Initial Constraints: [Initial Constraints]
- Tool Roles: [Tool Roles]
- Safety Rules: [Safety Rules]
- Existing AGENTS.md Or Protocol Notes: [Existing AGENTS.md Or Protocol Notes]

Generate a complete ChatGPT Project Instruction that includes:
- Project identity
- Repository source of truth
- Scope
- Out of scope
- ChatGPT role
- Codex role
- GitHub role
- Obsidian role
- Issue routing rules
- Codex handoff rules
- Review rules
- Safety and privacy rules
- Report-back format

Return the result using these sections:
- Project Summary
- Boundary
- Scope
- Out Of Scope
- Tool Routing
- Initial Repository Plan
- Initial Obsidian Plan
- First GitHub Issue Recommendation
- First Codex Handoff Recommendation
- Risks
- Questions To Confirm
```

## Copy-Ready Project Instruction Skeleton

```text
## Project Name

[Project Name]

## Primary Repository

[Repository URL]

## Project Objective

[Project Objective]

## Scope

[Project Scope]

## Out Of Scope

[Out Of Scope]

## Source Of Truth

GitHub is the source of truth for repository files, tracked issues, pull requests, and review history.

## Operating Model

- ChatGPT = planning, review, clarification, instruction drafting
- Codex = repository execution
- GitHub = source of truth, issues, pull requests, review
- Obsidian = Markdown notes, decisions, tasks, logs

## ChatGPT Responsibilities

- clarify scope
- draft instructions
- review Codex output
- identify risks and open questions

## Codex Responsibilities

- create and edit repository files
- execute issue-defined repository work
- report back clearly

## GitHub Workflow

- use GitHub Issues for executable repository work
- use pull requests when branch-based review is needed
- keep tracked work tied to repository changes

## Obsidian / Markdown Workflow

- keep notes, decisions, tasks, and logs in Markdown
- keep durable workflow knowledge separate from project-specific operations

## Safety Rules

[Safety Rules]

## Prompt vs Issue vs Codex Routing

- use ChatGPT for planning, review, clarification, and drafting
- use GitHub Issues for executable repository work
- use Codex handoffs when repository files need to be created, edited, reviewed, or pushed

## Review Rules

- review outputs against scope, safety rules, and acceptance criteria
- keep repository files as source of truth
- make assumptions explicit

## Report Format

1. Files created
2. Files modified
3. Assumptions used
4. Safety review result
5. Risks / rollback notes
6. Recommended next step
```

## Existing AGENTS.md Handling

If the repository already has `AGENTS.md` or another project protocol:

- do not overwrite it blindly
- preserve project-specific rules
- add the COG workflow as a process layer
- resolve conflicts explicitly
- mention differences in the report

## Safety Notes

- use placeholders for sensitive details
- do not include credentials or secrets
- do not include real private client, contact, path, or pricing data unless the repository is private and explicitly approved
- keep public template wording generic

## Done Criteria

A ChatGPT Project Instruction is ready when:

- it names the repository
- it defines ChatGPT, Codex, GitHub, and Obsidian roles
- it defines what counts as source of truth
- it defines when to use Issue and Codex handoff
- it includes safety rules
- it is concise enough to paste into the Project instructions field
