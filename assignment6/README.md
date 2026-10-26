# Assignment 6 — Collaboration & Merge Styles

PM: Chien0509
Collaborator A (pending invitation/acceptance): weichien0509
Collaborator B: pending
Grader (pending invitation): gut2003817

## Safety and scope
This setup branch is separate from the existing `master` branch, preserving Assignment 4/5 workflows. The repository currently uses `master`; branch rename and protection must be coordinated with CI trigger changes. No collaborator contributions, CI results, or conflict resolutions should be claimed until verified.

## Planned experiments
1. Same file, same lines: two real collaborator PRs from a common base; merge one, resolve conflict on the other; merge commit.
2. Same file, different lines: independent changes and squash merge.
3. Different files: independent changes and rebase merge.
4. Fast-forward: demonstrate on an isolated experiment branch, not by bypassing protected default branch.

## CI requirements
Create a dedicated PR-triggered CI gate (build, lint, unit and integration tests, Node.js matrix). Keep production deployment out of experimental PRs. Record a genuine failing check followed by a passing check before merging.

## Evidence checklist
Record PR links, author identities, branch protection screenshots, blocked PR, successful CI run, resolution snippets, `git log --graph`, and `git range-diff` or `git rerere` output. Report only observed evidence.
