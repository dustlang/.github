# Branch protection checklist (recommended)

Apply to default branch (e.g., main):

- Require pull request reviews before merging
- Require status checks to pass
  - CI (build/test/fmt/clippy)
  - CodeQL (if enabled)
- Require branches to be up to date before merging (optional)
- Restrict who can push to matching branches (recommended)
- Require linear history (optional)

