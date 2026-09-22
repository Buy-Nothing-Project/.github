<!-- Title: GH-<issue number>: what changes, in plain words -->

**Issue:** GH-
<!-- Same repo: GH-123. Another repo: Refs: Buy-Nothing-Project/<repo>#123.
     Do not use "Fixes #123": it only works on the default branch, and status is moved by the ladder instead. -->

## What changes
<!-- Behaviour before and after, for someone who has not read the issue. -->

## Risk tier: High | Standard | Low
<!-- By what it can break, not by file type.
     High = money, entitlements, auth/ownership, security, migrations, data deletion or rewrites. -->

## Test evidence
<!-- What you ran and what it showed. For High: the one mutation check on each changed guard. -->

## Rollout
- Migrations: none | <name> — applied by hand, before the matching promotion
- Env vars / flags: none | <names>
- Ladder: develop → staging → main

## Rollback
<!-- How to undo it, and what state is left behind. -->
