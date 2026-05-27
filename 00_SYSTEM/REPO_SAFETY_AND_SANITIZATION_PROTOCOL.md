# Repo Safety And Sanitization Protocol

## Purpose

Keep the repository public-safe, reusable, and free of private operational data.

## Safety Boundary

This repository is a master template.

It must not contain:

- real client names
- personal names
- contact details
- credentials
- internal incidents
- real prices or financial records
- machine-specific local paths
- live operational screenshots or exports
- hidden tool metadata
- local-only Obsidian workspace artifacts

## Allowed Content

- placeholders
- generic examples
- reusable Markdown workflows
- public-safe instructions
- neutral repository templates

## Placeholder Rules

Use placeholders such as:

- `[Project Name]`
- `[Repository Name]`
- `[Objective]`
- `[Decision Owner]`
- `[Local Vault Path]`
- `[Contact Placeholder]`

Do not replace placeholders with real values in the master template.

## Sanitization Checklist

1. Search for real names and identifying nouns.
2. Search for emails, phone numbers, URLs, IDs, and tokens.
3. Search for local file system paths and device-specific references.
4. Search for hidden tool metadata or export residue.
5. Confirm examples are fictional and non-identifying.
6. Confirm no live operational data was copied from private repositories.
7. Confirm no hidden assumptions depend on a private environment.
8. Confirm the repository still reads as a reusable template.

## Local Artifact Rules

Do not track local-only Obsidian artifacts such as:

- `.obsidian/workspace.json`
- `.obsidian/plugins/`
- `.obsidian/themes/`

## Public Review Gate

Before publishing or sharing a derivative repository:

1. Review all Markdown files and tracked support files.
2. Confirm placeholders are preserved where appropriate.
3. Remove private history or project-specific details from examples.
4. Confirm `.gitignore` excludes local-only Obsidian workspace artifacts.
5. Confirm any publication-facing license text is intentional.
6. Re-run the review protocol.
7. Record the review outcome in a pull request, release note, or equivalent tracked review record.

## If A Leak Is Found

1. Stop publication or sharing.
2. Remove or replace the sensitive content.
3. Re-review all adjacent files for similar leakage.
4. Record the sanitization fix in a neutral log if needed.
