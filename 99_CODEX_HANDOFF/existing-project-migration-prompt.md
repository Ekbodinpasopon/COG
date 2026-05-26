# Existing Project Migration Prompt

Read `AGENTS.md` first.

Standardize the existing project into the COG Workflow Template structure.

Inputs:
- Source project: `[Project Name]`
- Repository: `[Repository Name]`
- Purpose: `[Project Purpose]`
- Protected systems: `[Protected Systems]`

Migration rules:
- Keep only the requested scope
- Do not copy private operational data into template-safe files
- Replace protected values with placeholders
- Preserve Markdown and Obsidian compatibility
- Do not add tools, packages, or app architecture

Required review:
- `00_SYSTEM/REVIEW_PROTOCOL.md`
- `TEMPLATE/SANITIZATION_CHECKLIST.md`

Codex must report only:
1. Files created
2. Files modified
3. Assumptions used
4. Risks / rollback notes
5. Next recommended step
