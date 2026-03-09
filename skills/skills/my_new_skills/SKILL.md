[SKILLS](../../README.md)

---
name: commit architect
description: Turn local commit messages into professional conventional commits and structured PR descriptions.
---

# Commit Architect
This skill guides the agent to transform raw code changes or informal messages into professional documentation.

## Workflow

### 1. Analyze Diff
- Examine the provided code changes or `git diff`.
- Categorize changes: `fix`, `feat`, `refactor`, `docs`, `style`, `test`, `chore`.

### 2. Standardize
- Generate a **Conventional Commit** message (e.g., `feat(ui): add dark mode toggle`).
- Identify "debug junk" (leftover print statements, `console.log`, or commented-out code) and flag it for removal.

### 3. Documentation
- Create a structured Pull Request statement:
    - **Summary**: 1-sentence overview.
    - **Key Changes**: Bullet points listing technical changes.
    - **Risk Level**: Low/Medium/High based on the impact of changes.