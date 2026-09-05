# OSWAP Potential Research Rules

This repository is for exploring possibilities without overstating implementation or evidence.

## Required claim labels

Use one of these labels for substantial ideas:

- `implemented`
- `prototype`
- `hypothesis`
- `speculative`

## Required separation

Keep these concepts distinct:

```text
syntax != execution
configuration != authorization
classical d-level state != quantum state
simulation != hardware
LLM proposal != deterministic validation
potential != implemented capability
```

## Preferred structure for a hypothesis

Document:

1. the proposed mechanism;
2. the current evidence;
3. assumptions;
4. an implementation path;
5. measurable tests;
6. failure or rejection criteria;
7. security and privacy boundaries;
8. relevant prior art.

## LLM-assisted research

LLMs may assist with literature discovery, comparison, drafting, code review, and hypothesis generation. Their output is not evidence by itself.

Technical claims should be traceable to source code, reproducible tests, primary literature, standards, or clearly identified assumptions.

Where model output materially contributes to a research artifact, preserving provenance is encouraged.

## Additive documentation policy

Historical design material should generally be preserved. New findings should clarify, supersede by reference, or add explicit status labels rather than silently erasing earlier experimental context.
