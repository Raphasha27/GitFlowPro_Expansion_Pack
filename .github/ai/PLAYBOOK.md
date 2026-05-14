# GitFlowPro AI Playbook

This playbook defines how AI agents (RepoPilot, AI reviewer bots, automation scripts) should behave when interacting with GitFlowPro repositories.

## 1. PR Review Behavior (RepoPilot)
- Summarize changes in human-readable language
- Identify risk category (low, medium, high)
- Detect workflow/security changes
- Detect missing tests when code changes

## 2. Commit Message Generator Rules
- Use Conventional Commits
- `<type>(<scope>): <short summary>`
