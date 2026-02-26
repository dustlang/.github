# Repo bootstrap (recommended)

Add these files to new repos when appropriate:

- `LICENSE`
- `README.md`
- `SECURITY.md` (or rely on org default)
- `.github/workflows/ci.yml` that calls the reusable workflow:
  - uses: dustlang/.github/.github/workflows/reusable-rust-ci.yml@main
- `CODEOWNERS` (see sample)

