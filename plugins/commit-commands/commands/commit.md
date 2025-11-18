---
allowed-tools: Bash(git status:*), Bash(git commit:*)
description: Create a git commit
---

## Context

-   Current git status: !`git status`
-   Current git diff (staged and unstaged changes): !`git diff HEAD`
-   Current branch: !`git branch --show-current`
-   Recent commits: !`git log --oneline -10`

## Your task

Based on the above changes, create a single git commit.

You have the capability to call multiple tools in a single response. Stage and create the commit using a single message. Do not use any other tools or do anything else. Do not send any other text or messages besides these tool calls.

## Important requirements

- **NEVER use `git add`**: Do not stage any files. Only create the commit with files that are already staged.
- **Commit message in Japanese**: Write the commit message in Japanese following the Semantic Commit Message format (e.g., `feat: 新機能を追加`, `fix: バグを修正`, `docs: ドキュメントを更新`)
