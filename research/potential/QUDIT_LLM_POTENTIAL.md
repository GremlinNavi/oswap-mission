# Qudit / LLM Potential

Status: `hypothesis`

## Thesis interface

```text
qudit=(PEMDAS)
```

A restricted OSWAP arithmetic expression resolves deterministically to an integer dimension `d`. The value is then interpreted by a typed receiving subsystem.

Example:

```text
qudit=(3*4) -> d=12
```

## LLM hypothesis

A classical LLM system could use `d` as an auditable multi-state configuration parameter, for example:

- number of routing states;
- number of candidate tools;
- number of expert slots;
- number of policy branches;
- discrete memory or decision states.

The research question is whether preserving the original human-readable expression plus the resolved typed value improves auditability, reproducibility, or controllability compared with opaque numeric configuration alone.

## Possible pipeline

```text
natural-language intent
        ↓
LLM proposes typed OSWAP expression
        ↓
deterministic OSWAP parser
        ↓
resolved d-level parameter
        ↓
validation / consent / policy
        ↓
classical LLM adapter OR future quantum adapter
```

The LLM should not be trusted to execute arbitrary expressions. A deterministic parser and domain validator remain separate from model output.

## Quantum boundary

The present OSWAP qudit repository is classical. Mapping an expression to `d` does not create a quantum state and does not simulate superposition, phase, gates, measurement, or entanglement.

A future genuine qudit adapter would require a real state representation and quantum operations. The current interface is only a candidate parameter contract.

## Why investigate higher-dimensional structures?

Current research shows that qudits are not merely theoretical extensions of qubits. In 2026, a 25-level trapped-ion qudit was used for coherent quantum logic and algorithms. Recent qutrit-based neural quantum kernel work also investigates richer multi-level embeddings and multiclass classification.

References:

- Low et al., Nature Communications (2026): https://www.nature.com/articles/s41467-026-72662-8
- Cristiano-Romero et al., arXiv:2607.23683 (2026): https://arxiv.org/abs/2607.23683

These papers motivate the dimensionality question. They do not validate OSWAP's proposed interface or imply that classical LLMs gain quantum properties.

## Minimum experiments

1. Compare plain integer configuration against preserved `expression + resolved d` configuration.
2. Test deterministic agreement across independent parsers.
3. Test LLM tool-routing or expert-selection tasks at several values of `d`.
4. Measure reproducibility, error rates, configuration transparency, and operator comprehension.
5. Reject the hypothesis if the OSWAP abstraction adds complexity without measurable benefit.

## Related implementation

See `GremlinNavi/oswap-qudit-simulation` for the current classical proof of concept and `THESIS.md` for the claim boundary.
