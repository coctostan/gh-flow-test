# Project: gh-flow-test

## Description
A minimal test project for validating PALS GitHub Flow enforcement end-to-end.

## Core Value
Prove that branch creation → PR → CI gate → merge → next-phase works correctly.

## Requirements

### Active
- [ ] Validate feature branch creation on phase start
- [ ] Validate PR creation after APPLY
- [ ] Validate merge gate in UNIFY
- [ ] Validate branch cleanup after merge

## Constraints
- Modules disabled (focus on git flow only)
- ci_checks: false (no CI configured on test repo)
- No code changes needed — just workflow validation

---
*Created: 2026-03-24*
