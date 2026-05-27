# GitHub PR Review Protocol

## Purpose

Review repository changes with a consistent quality and safety standard.

## Review Focus

Review for:

- scope adherence
- clarity
- missing files
- safety and sanitization
- Markdown quality
- workflow consistency

## Review Questions

1. Does the pull request match the issue scope?
2. Were unrelated changes introduced?
3. Are all required files present and coherent?
4. Does any content leak private or identifying data?
5. Is the result still reusable as a generic template?

## Review Output Format

- `Status:` Pass or Needs Changes
- `Findings:` file-specific issues only
- `Decision:` approve, revise, or block for sanitization

## Reviewer Discipline

- Prefer concrete findings over general commentary.
- Flag missing acceptance criteria coverage.
- Flag public-safety risks immediately.
- If no issues are found, say that explicitly.
