# Minimal Alignment Starter Pack

## Purpose

Use this file for copy-ready templates when applying approved minimal COG alignment changes to an existing project after inspect-only assessment is complete.

## When To Use

Use this only after:

- the existing project has been inspected
- the Codex inspect-only report has been reviewed
- a narrow scope of changes has been approved

## Required Inputs

- `[Project Name]`
- `[Repository URL]`
- `[Inspect-Only Issue URL]`
- `[Inspect-Only Report Summary]`
- `[Approved Changes]`
- `[Files Allowed To Change]`
- `[Files Not Allowed To Change]`
- `[Existing Rules To Preserve]`
- `[Safety Constraints]`
- `[Rollback Plan]`

## Minimal Alignment GitHub Issue Template

Title:

```text
Apply approved minimal COG alignment changes
```

Body:

```text
## Objective

Apply only the approved minimal COG alignment changes to the existing project.

## Context

- Project Name: [Project Name]
- Repository URL: [Repository URL]
- Inspect-Only Issue URL: [Inspect-Only Issue URL]
- Inspect-Only Report Summary: [Inspect-Only Report Summary]
- Existing Rules To Preserve: [Existing Rules To Preserve]
- Safety Constraints: [Safety Constraints]
- Rollback Plan: [Rollback Plan]

## Approved scope

- [Approved Changes]

## Files allowed to change

- [Files Allowed To Change]

## Files not allowed to change

- [Files Not Allowed To Change]

## Existing rules to preserve

- [Existing Rules To Preserve]

## Safety rules

- preserve project-specific rules
- do not overwrite `AGENTS.md` blindly
- do not expand scope beyond the approved changes
- do not delete files unless explicitly approved
- do not move private operational data into public-safe template areas
- keep changes Markdown-first and reviewable

## Out of scope

- unapproved workflow changes
- unrelated cleanup
- application code refactoring
- broad folder renames
- destructive rewrites of existing project rules

## Acceptance criteria

- only approved files were changed
- existing rules were preserved
- COG routing or navigation is clearer
- safety boundaries remain visible
- no unrelated code or application changes were made
- rollback path is clear

## Report back format

Follow `07_SKILLS_PROTOCOLS/TASK_COMPLETION_AND_HANDOFF_PROTOCOL.md` for closeout state and next-action payload.

1. Files created
2. Files modified
3. Files intentionally not touched
4. Existing rules preserved
5. Safety review result
6. Assumptions used
7. Risks / rollback notes
8. Recommended next step
9. Next Action Type
10. Next Action Payload
```

## Codex Minimal Alignment Handoff Template

```text
Repository:
[Project Name]

Repository URL:
[Repository URL]

Source of truth:
Use the minimal-alignment GitHub Issue as the source of truth.

Objective:
Apply only the approved minimal COG alignment changes to this existing project.

Context:
- Inspect-Only Issue URL: [Inspect-Only Issue URL]
- Inspect-Only Report Summary: [Inspect-Only Report Summary]
- Approved Changes: [Approved Changes]
- Files Allowed To Change: [Files Allowed To Change]
- Files Not Allowed To Change: [Files Not Allowed To Change]
- Existing Rules To Preserve: [Existing Rules To Preserve]
- Safety Constraints: [Safety Constraints]
- Rollback Plan: [Rollback Plan]

Required rules:
- apply only approved changes
- do not expand scope
- do not overwrite AGENTS.md blindly
- preserve project-specific rules
- do not refactor unrelated code
- do not delete files unless explicitly listed
- update navigation files only if approved
- keep changes Markdown-first and reviewable

Report back format:
1. Files created
2. Files modified
3. Files intentionally not touched
4. Existing rules preserved
5. Safety review result
6. Assumptions used
7. Risks / rollback notes
8. Recommended next step
9. Next Action Type
10. Next Action Payload
```

## Allowed Change Examples

- add or update `BRAIN_INDEX.md`
- add a COG workflow section to `README.md`
- add a COG process section to `AGENTS.md` without removing existing rules
- add notes, logs, decisions, or tasks folders or documentation
- add or update issue or handoff templates
- add navigation links to existing workflow documents

## Forbidden Change Examples

- rewrite `AGENTS.md` completely without approval
- delete existing workflow or protocol files without approval
- refactor application code
- move private operational data into public-safe template areas
- rename folders broadly
- combine unrelated cleanup with COG alignment
- infer missing scope

## Report Back Format

Use this exact structure:

1. Files created
2. Files modified
3. Files intentionally not touched
4. Existing rules preserved
5. Safety review result
6. Assumptions used
7. Risks / rollback notes
8. Recommended next step
9. Next Action Type
10. Next Action Payload

## Done Criteria

The minimal alignment pass is complete when:

- only approved files were changed
- existing project-specific rules were preserved
- COG workflow routing is clearer
- navigation is improved
- the safety boundary is visible
- no unrelated code or application changes were made
- the rollback path is clear
