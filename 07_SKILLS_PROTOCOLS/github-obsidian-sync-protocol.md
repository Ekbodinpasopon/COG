# GitHub Obsidian Sync Protocol

## Purpose

Keep a Markdown vault synchronized through GitHub without storing local-only Obsidian state.

## Rules

- Track Markdown content and approved support files only.
- Ignore `.obsidian/workspace.json`, `.obsidian/plugins/`, and `.obsidian/themes/`.
- Use pull requests for review-sensitive template changes.
- Keep commit scope narrow and descriptive.

## Sync Cycle

1. Pull the latest repository state.
2. Edit Markdown files in the vault.
3. Review changes for privacy and scope.
4. Commit only approved content.
5. Push and open or update the review request.
