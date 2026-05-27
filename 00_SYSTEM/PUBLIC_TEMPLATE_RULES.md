# Public Template Rules

## Purpose

Keep COG reusable as a public-safe master template.

## Template Rules

- Write for reuse, not for one specific project.
- Prefer neutral language over domain-specific operational detail.
- Keep placeholders visible and easy to replace in derivative repositories.
- Keep repository guidance Markdown-first.
- Keep examples sanitized and fictional.

## Prohibited Additions

- private operational records
- client-specific instructions
- machine-specific paths
- credentials or secrets
- application runtime code
- dependencies and package setup
- environment automation scripts

## Naming Rules

- Use clear Markdown filenames in uppercase or stable title case patterns already used by the repository.
- Prefer descriptive file names over abbreviations.
- Keep folder purposes obvious from the name alone.

## Reuse Rules

- A derivative repository may replace placeholders with approved project values.
- The master template should keep placeholder values only.
- If a derivative project needs extra folders, add them there, not to the master template without review.

## Publication Rules

- Review before publishing changes to the template.
- Confirm examples remain sanitized after every update.
- Treat public-safe status as a maintained property, not a one-time cleanup step.
