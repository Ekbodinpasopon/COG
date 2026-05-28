# ChatGPT Project Instruction Types

This folder is reserved for future project-type-specific ChatGPT Project Instruction templates.

All project-type instruction templates must begin with this required section before roles, workflows, routing, or safety rules:

```text
## Repository Identity

Primary repository:
...

Local workspace:
...

Source of truth:
...

This instruction governs:
...

This instruction does not govern:
...

Related projects and handoff targets:
...
```

## Core Rule

Every project instruction must name the exact repository and local workspace it governs before defining roles or workflows.

## Scope

- Use placeholders only.
- Keep templates public-safe and sanitized.
- Do not include private project data, client data, credentials, pricing, incidents, local machine secrets, or operational details.
- Do not overwrite existing project-specific instructions blindly.
- Add project-type templates here only when their type boundary is clear.
