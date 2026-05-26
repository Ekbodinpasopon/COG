# Review Protocol

## Purpose

Provide a repeatable review gate for Markdown-first AI-assisted repositories.

## Required Checks

### Scope Check

- Does the change stay within the requested files and structure?
- Were any extra folders, features, or systems added without approval?

### Privacy Check

- Are all project-specific values still placeholders where required?
- Is any real client, property, owner, guest, contact, incident, or policy data present?
- Are any machine-specific paths present instead of `[Local Vault Path]`?

### Obsidian Check

- Are all files plain Markdown?
- Is the structure Obsidian-compatible?
- Are excluded `.obsidian` files and folders absent?

### GitHub Review Check

- Is the change readable as a template or protocol?
- Are assumptions explicit?
- Is the result safe to keep private, and ready for later sanitization review?

## Review Result Format

- Status: Pass / Needs Changes
- Findings:
  - `[Severity] [File] [Issue]`
- Decision:
  - approve
  - revise
  - block for sanitization
