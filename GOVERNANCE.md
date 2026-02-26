# Governance

## Authority model
- The **specification** is the authoritative definition of semantics.
- Implementations are required to conform (via tests, fixtures, traces, and conformance rules).

## Decision making
- Maintainership decisions are made by designated maintainers.
- Semantic changes require:
  1) spec update (or an accepted spec draft), and
  2) conformance updates (tests/goldens) where relevant.

## Backward compatibility
- Backward compatibility is enforced via versioning and conformance checks.
- Behavior changes must be reflected in deterministic goldens.

## Releases
- Releases are tagged and should be reproducible from source.
- CI must be green on the release commit.

© Dust LLC
