# Review Protocol

## Purpose

Provide a repeatable repository review gate for Markdown-first AI-assisted workflow repositories.

## Review Scope

Review for:

- scope control
- structure completeness
- placeholder discipline
- public safety
- Markdown and Obsidian compatibility

## Required Checks

### Scope Check

- Does the change stay within the requested repository scope?
- Were unrelated files, features, or systems added?
- Does the repository still behave like a master template rather than a live project?

### Structure Check

- Are all required folders and files present?
- Do root files explain purpose, roles, and navigation clearly?
- Does `BRAIN_INDEX.md` map the repository correctly?

### Safety Check

- Are placeholders used instead of real project data?
- Is private or identifying information absent?
- Are examples generic and sanitized?
- Are local paths replaced with placeholders?

### Markdown Check

- Are all files plain Markdown?
- Are headings and sections readable and reusable?
- Are the files compatible with Obsidian vault use?

### Workflow Check

- Are ChatGPT, Codex, GitHub, and Obsidian roles clearly separated?
- Does the routing logic between prompt, issue, and handoff remain clear?
- Are review and sanitization rules discoverable?

## Review Result Format

Use this output format:

- `Status:` Pass or Needs Changes
- `Findings:` list each issue with file and reason
- `Decision:` approve, revise, or block for sanitization

## Blocking Conditions

Block the repository if:

- private data is present
- executable work has no issue or handoff structure
- the template is no longer generic
- required workflow files are missing
