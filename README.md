# auto-merge-top-level

Test repository for auto-merge workflow validation - Level 3 (top tier).

This repository demonstrates automatic PR creation and auto-merge functionality in a multi-tier setup.

## Purpose

- Contains `auto-merge-middle-level` as a submodule in `opt/auto-merge-middle-level`
- When the submodule is updated via auto-PR, auto-merge is enabled automatically
- PR merges when all checks pass
- This is the top level - no parent to trigger

## Part of Test Chain

auto-merge-bottom-level → auto-merge-middle-level → **auto-merge-top-level**

