# Contributing to Dust

Thanks for your interest in contributing to Dust projects.

## High-level rules
- **The spec is canonical.** If an implementation disagrees with the spec, the spec wins.
- **Determinism is non-negotiable.** Prefer reproducible builds and deterministic traces.
- **CI must stay green.** Required checks: build, test, rustfmt, clippy (warnings denied).

## Issues
Use issue templates. Provide:
- Repo + commit SHA
- Reproduction steps
- Expected vs actual behavior
- Logs / traces / minimal fixtures if applicable

## Pull requests
- Keep PRs focused.
- Add or update tests and goldens when changing runtime behavior.
- Avoid semantic changes without spec alignment.
- Do not merge your own PRs without review (unless explicitly authorized).

## Licensing & IP
By contributing, you agree that your contributions may be included under the repository license terms. If a repository requires a CLA, follow the instructions in that repository.

© Dust LLC
