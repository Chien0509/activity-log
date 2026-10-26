# Assignment 6 — Real collaborator tasks

Do not merge E1 PR #6 until B has independently branched from the original master and opened E1 B PR. Each collaborator must use their own account.

## E2 — same file, different lines
**A (weichien0509):** from `master`, create `feature/e2-a`. In `experiments/e2/settings.js`, edit ONLY `appTitle()` to return `'Activity Log - Team A'`. Commit `:sparkles: feat: customize app title for E2 A`. Open PR against **Chien0509/activity-log:master**.

**B (pending account):** from the same `master` base, create `feature/e2-b`. Edit ONLY `displayTheme()` in that same file to return `'dark'`. Commit `:sparkles: feat: customize theme for E2 B`. Open PR against the same base. Confirm no conflict and preserve both changes. Plan squash merge for E2.

## E3 — different files
**A:** from `master`, create `feature/e3-a`. Edit only `experiments/e3/feature-a.js`, return `'feature A completed'`. Commit `:sparkles: feat: implement E3 feature A`. Open PR against this repository.

**B:** from the same base, create `feature/e3-b`. Edit only `experiments/e3/feature-b.js`, return `'feature B completed'`. Commit `:sparkles: feat: implement E3 feature B`. Open PR against this repository. Plan rebase & merge for E3.

## Evidence checklist
Record each PR's author, base/head, checks (including failures), diff, merge style, and post-merge `git log --graph --oneline --decorate -20`. E1 hard conflict only appears **after** one competing PR merges. Record the conflict and resolution before completing E1.

## Caution
Use **Chien0509/activity-log** as the base repository, NOT the original upstream TheDanniCraft/activity-log. Avoid direct pushes to master. The PM must configure and verify branch protection before claiming enforcement.
