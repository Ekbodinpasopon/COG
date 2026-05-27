# Sanitize Project For Public Template

Use this prompt when a repository must be reviewed and cleaned for safe public template use.

## Repository

`[owner/repository]`

## Objective

Review the repository for private or identifying data and convert it into a public-safe template where possible.

## Scope

- inspect Markdown workflow files
- identify private or identifying content
- replace unsafe content with placeholders
- preserve reusable structure
- check for hidden tool metadata and local-only workspace residue

## Files to inspect

- `README.md`
- `AGENTS.md`
- `BRAIN_INDEX.md`
- `00_SYSTEM/`
- `07_SKILLS_PROTOCOLS/`
- `TEMPLATE/`
- `EXAMPLES/`

## Files to create/update

- `[List the files that need sanitization updates]`

## Constraints

- do not add new systems or features
- do not add code, packages, or automation
- keep the result generic and Markdown-first

## Safety rules

- remove or replace real names, contacts, credentials, incidents, prices, and local paths
- keep examples fictional and non-identifying
- remove local-only Obsidian workspace artifacts from tracked content
- block publication if any unresolved leak remains

## Acceptance criteria

- no obvious identifying or sensitive data remains
- placeholders are used consistently
- examples are sanitized
- repository remains reusable as a master template

## Report back format

1. Files created
2. Files modified
3. Assumptions used
4. Risks / rollback notes
5. Recommended next step
