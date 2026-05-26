# ChatGPT Codex GitHub Workflow Protocol

## Purpose

Define the standard operating loop between ChatGPT, Codex, Obsidian, and GitHub.

## Workflow Roles

- ChatGPT defines instructions, guardrails, and project-specific guidance.
- Codex creates or edits repository files based on those instructions.
- Obsidian serves as the Markdown knowledge surface.
- GitHub records changes, review discussion, and publishing state.

## Standard Loop

1. Define the task in Markdown using project instructions.
2. Prepare a Codex handoff prompt with scope, constraints, and expected output.
3. Let Codex modify only the requested files.
4. Review changes against `00_SYSTEM/REVIEW_PROTOCOL.md`.
5. Run `00_SYSTEM/PUBLICATION_SAFETY_PROTOCOL.md` before public sharing.

## Control Notes

- Do not treat chat output as a source of truth until it is written into the repository.
- Keep review comments tied to files and decisions.
- Separate private operational content from reusable public-safe template content.
