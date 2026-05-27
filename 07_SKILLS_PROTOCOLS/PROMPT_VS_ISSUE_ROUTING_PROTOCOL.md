# Prompt Vs Issue Routing Protocol

## Purpose

Route work to the right place before execution begins.

## Use A ChatGPT Prompt For

Use a ChatGPT prompt for:

- thinking
- planning
- reviewing
- instruction drafting
- clarification

ChatGPT is the right place when the work is still conceptual, ambiguous, or needs refinement before repository execution.

## Use A GitHub Issue For

Use a GitHub Issue for:

- executable repository work
- tracked changes
- file creation requests
- file update requests
- reviewable implementation scope

If the work should be performed inside the repository, it should be written as an issue.

## Use A Codex Handoff For

Use a Codex handoff when repository files need to be:

- created
- edited
- reviewed
- organized
- pushed

The Codex handoff is the execution packet that translates issue scope into concrete repository work.

## Routing Decision

1. If the work needs thinking, clarification, planning, or review first, start in ChatGPT.
2. If the work is ready to execute in the repository, create a GitHub Issue.
3. If the GitHub Issue requires file work, prepare a Codex handoff.

## Anti-Patterns

- Do not use ChatGPT alone for untracked repository execution.
- Do not skip the issue when the work is clearly executable.
- Do not ask Codex to infer missing scope that should have been defined in the issue.
