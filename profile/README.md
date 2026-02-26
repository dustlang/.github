# Dust Programming Language (DPL)

Dust is a clean‑slate programming language and compute stack designed from first principles to support **Classical (K), Quantum (Q), and Phase (Φ)** computation within a single unified semantic system.

DPL is grounded in physical realism:

- Resources are explicit.
- Time is first-class.
- Irreversibility is typed.
- Global consistency is enforced through admissibility.

This organization hosts the canonical specification, runtime systems, toolchain components, and research documents that define and implement DPL.

---

## Mission

To establish a sovereign, physically-aligned foundation for computation capable of spanning:

- Deterministic control systems
- Linear quantum processes
- Admissibility‑governed phase computation
- Hybrid architectures

Dust treats computation as constrained evolution rather than abstract instruction sequencing.

---

## Core Concepts

### Regime-Typed Computation

Every executable process exists in exactly one regime:

- **K-Regime** — Deterministic classical computation with explicit time semantics.
- **Q-Regime** — Linear quantum resources, non-clonable by construction.
- **Φ-Regime** — Admissibility- and global-consistency-governed computation.

Regime boundaries are explicit and enforced.

---

### Constraint-First Semantics

Programs describe what must be satisfied, not merely ordered operations.

Execution succeeds only if constraints are admissible under the declared regime rules.

---

### Explicit Effects

Observation, emission, sealing, and coupling are typed effects.

Irreversibility is never implicit.

---

### Deterministic Conformance

The Dust Virtual Machine (DVM) defines canonical execution semantics.

All backends must be observationally equivalent to DVM execution.

---

## Repositories

### dustlang
Canonical language specification (normative definition).

### dustrun
Dust Virtual Machine (DVM), regime engine, and conformance harness.

### dust
Compiler toolchain targeting native binaries and DVM bytecode.

Additional repositories may include libraries, tooling, verification engines, and research extensions.

---

## Governance

- The **specification** is the authoritative definition of DPL semantics.
- Implementations must conform via deterministic tests and goldens.
- Semantic changes require specification alignment.
- Backward compatibility is enforced through versioning and IR stability.

---

## Security

Security vulnerabilities must be reported privately via GitHub Security Advisories.

Do not open public issues for security disclosures.

---

## Contributing

We welcome rigorous contributions that improve:

- Specification clarity
- Runtime correctness
- Determinism
- Conformance infrastructure
- Formal reasoning support

All contributions must pass CI and preserve semantic integrity.

---

## Philosophy

DPL is built for engineers and researchers who require programs to carry physical meaning.

If your work involves:

- Advanced systems engineering
- Hybrid compute architectures
- Deterministic infrastructure
- Foundational computation research

Dust is designed for you.

---

# License

Dust is licensed under the Dust Open Source License.

See LICENSE file for details.

---
