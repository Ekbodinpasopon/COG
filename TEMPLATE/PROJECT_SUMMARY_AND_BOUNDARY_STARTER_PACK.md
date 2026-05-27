# Project Summary And Boundary Starter Pack

## Purpose

Use this file for a copy-ready first ChatGPT prompt that turns a raw project idea into a clear project summary and boundary.

## When To Use

Use this before:

- creating the ChatGPT Project Instruction
- creating GitHub Issue #1
- creating Codex Handoff #1

## Required Inputs

- `[Project Name]`
- `[Repository Name]`
- `[Project Objective]`
- `[Current Starting Point]`
- `[Known Scope]`
- `[Known Out Of Scope]`
- `[Visibility Intent]`
- `[Primary Notes Location]`
- `[Initial Constraints]`
- `[Existing Materials Or References]`
- `[Preferred Working Style]`

## First ChatGPT Prompt Template

Copy this into the first ChatGPT chat and fill in the placeholders:

```text
I want to turn a raw project idea into a clear project summary and project boundary using the COG workflow.

Use these inputs:
- Project Name: [Project Name]
- Repository Name: [Repository Name]
- Project Objective: [Project Objective]
- Current Starting Point: [Current Starting Point]
- Known Scope: [Known Scope]
- Known Out Of Scope: [Known Out Of Scope]
- Visibility Intent: [Visibility Intent]
- Primary Notes Location: [Primary Notes Location]
- Initial Constraints: [Initial Constraints]
- Existing Materials Or References: [Existing Materials Or References]
- Preferred Working Style: [Preferred Working Style]

Produce:
- Project Summary
- Project Objective
- Problem Statement
- Intended Users
- Scope
- Out Of Scope
- Constraints
- Privacy Boundary
- Tool Roles
- Initial Repository Map
- Initial Obsidian Map, if used
- First Risks
- Open Questions
- Recommended GitHub Issue #1
- Recommended Codex Handoff #1 outline
- Recommendation for whether to create the repository from the COG template or start from an empty repository

Respond using exactly these sections:
- Project Summary
- Project Objective
- Problem Statement
- Intended Users
- Boundary
- Scope
- Out Of Scope
- Constraints
- Privacy Boundary
- Tool Routing
- Initial Repository Plan
- Initial Obsidian Plan
- First GitHub Issue Recommendation
- First Codex Handoff Recommendation
- Risks
- Questions To Confirm
- Recommended Next Step

Use this operating model:
- ChatGPT = planning, review, clarification, instruction drafting
- Codex = repository execution
- GitHub = source of truth, issues, pull requests, review
- Obsidian = Markdown notes, decisions, tasks, logs
```

## Required ChatGPT Output Format

Ask ChatGPT to respond with these sections:

- `Project Summary`
- `Project Objective`
- `Problem Statement`
- `Intended Users`
- `Boundary`
- `Scope`
- `Out Of Scope`
- `Constraints`
- `Privacy Boundary`
- `Tool Routing`
- `Initial Repository Plan`
- `Initial Obsidian Plan`
- `First GitHub Issue Recommendation`
- `First Codex Handoff Recommendation`
- `Risks`
- `Questions To Confirm`
- `Recommended Next Step`

## Safety Notes

- do not add private data unless intentionally working in a private repository
- use placeholders where details are sensitive
- keep public-safe summaries generic
- separate workflow rules from project-specific operational data
- do not include credentials, secrets, real contacts, private pricing, local machine paths, or incident details in public-safe templates

## Done Criteria

This starter pack is complete when:

- a raw project idea can be converted into a clear project summary
- scope and out-of-scope are defined
- privacy boundary is defined
- tool roles are defined
- first Issue and first Codex handoff recommendations are produced
- the result can feed into `TEMPLATE/CHATGPT_PROJECT_INSTRUCTION_STARTER_PACK.md`
