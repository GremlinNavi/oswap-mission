# OSWAP Potential

`oswap-potential` is the research-hypothesis and future-applications repository for the Open-Source World Access Project (OSWAP).

Its purpose is to explore technically bounded possibilities without presenting unimplemented ideas as existing OSWAP capabilities.

## Status vocabulary

Every substantial proposal should be identifiable as one of:

- `implemented` — present in a referenced OSWAP codebase;
- `prototype` — experimentally implemented but not production-ready;
- `hypothesis` — a falsifiable research proposition;
- `speculative` — a possible direction requiring substantial validation.

## Current focus

### `qudit=(PEMDAS)`

Status: `prototype + hypothesis`

A restricted human-readable arithmetic expression resolves deterministically to a typed dimension `d`. The receiving subsystem then interprets that value according to an explicit domain contract.

```text
qudit=(9/3) -> d=3
```

Current OSWAP code demonstrates classical dimension mapping. It does not perform quantum computation.

Potential research directions include:

- classical d-level LLM routing and tool selection;
- mixture-of-experts cardinality/configuration experiments;
- auditable model-generated parameterization;
- quantum-inspired multi-state control abstractions;
- interfaces to future genuine qudit simulators or hardware adapters.

See [QUDIT_LLM_POTENTIAL.md](QUDIT_LLM_POTENTIAL.md).

## Related OSWAP repositories

- `GremlinNavi/oswap-qudit-simulation` — classical qudit-dimension proof of concept and thesis.
- `GremlinNavi/oswap-syntax` — OSWAP syntax reference work.
- `GremlinNavi/oswap-twin` — auditable multi-repository transport and replication work.
- `GremlinNavi/oswap-mission` — project mission, governance, scope, and public-interest documentation.

## Research discipline

This repository intentionally separates potential from implementation. Claims should name assumptions, current evidence, failure conditions, and the OSWAP component that would be required to test them.

See [RESEARCH_RULES.md](RESEARCH_RULES.md).

## Licensing

Unless a file states otherwise, OSWAP-authored material in this repository is intended for publication under the Apache License 2.0.
