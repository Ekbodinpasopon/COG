# Task Completion And Handoff Protocol

## Purpose

Define a standard compact completion and handoff format for ChatGPT and Codex when a task is completed, needs review, needs an issue, needs another prompt, or has no next action.

## When To Use

Use this at the end of:

- execution tasks
- inspect-only tasks
- review tasks
- advisory tasks
- Codex handoff tasks
- repository alignment tasks

## Core Rule

Every task closeout must clearly state:

- what was done
- what changed
- what evidence or result exists
- what the next action type is
- whether the process is complete or requires another handoff

The user should not need to infer what happens next.

## Compact Completion Format

Use this format:

```text
Status:
Summary:
Evidence:
Next Action Type:
Next Action Payload:
```

## Allowed Next Action Types

Use only these next action types:

- `No further action`
- `Codex prompt`
- `GitHub Issue`
- `ChatGPT review`
- `Process complete`

## Next Action Type Rules

- Use `No further action` when the requested work is done and no follow-up is needed.
- Use `Codex prompt` when repository work must continue and a direct Codex handoff is the next useful artifact.
- Use `GitHub Issue` when new executable repository work should be tracked before execution.
- Use `ChatGPT review` when reasoning, validation, decision support, or PR or report review is needed.
- Use `Process complete` when the workflow or issue cycle is fully closed.

## Codex Report Block

Use this compact report block for Codex closeout:

```text
Files created:
Files modified:
Files intentionally not touched:
Safety review result:
Assumptions used:
Risks / rollback notes:
Recommended next step:
Next Action Type:
Next Action Payload:
```

Notes:

- `Files intentionally not touched` is optional but recommended when scope control matters.
- `Safety review result` is required when the work touches public-safe templates, sanitization, repository visibility, private-data handling, or workflow rules.
- `Recommended next step` must not be vague. It should align with the `Next Action Type`.

## Payload Rules

If `Next Action Type` is `GitHub Issue`, include:

- issue title
- objective
- scope
- constraints
- acceptance criteria
- report back format

If `Next Action Type` is `Codex prompt`, include:

- repository
- objective
- scope
- files to inspect, create, or update
- constraints
- safety rules
- acceptance criteria
- report back format

If `Next Action Type` is `ChatGPT review`, include:

- what needs review
- source material to review
- decision needed
- risks or open questions

If `Next Action Type` is `No further action` or `Process complete`, keep the payload short and explicitly state that no follow-up is required.

## Boundary With Other Protocols

- `PROMPT_VS_ISSUE_ROUTING_PROTOCOL.md` controls where work goes before execution.
- `TASK_COMPLETION_AND_HANDOFF_PROTOCOL.md` controls how completed work is closed out and routed after execution or review.
- `CODEX_EXECUTION_PROTOCOL.md` controls how Codex performs repository execution.
- This protocol does not replace issue templates, Codex handoff templates, or review protocols.

## Anti-Patterns

- vague `next step` with no routing label
- saying `done` without stating whether follow-up is needed
- outputting a Codex prompt when a GitHub Issue is required first
- asking Codex to infer missing scope
- declaring process complete when review or safety checks are still pending
- changing report fields differently across templates without reason
