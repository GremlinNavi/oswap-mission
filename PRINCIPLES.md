# OSWAP Public-Interest Principles

These principles guide OSWAP design and documentation. They are directional requirements, not a claim that every experimental implementation already satisfies every principle.

## 1. Accessibility without ambiguity

Human-facing interfaces should accommodate ordinary language, localization, spelling variation, assistive input, and readable previews where practical. Accessibility at the interpretation layer must not weaken deterministic validation at the execution layer.

## 2. Human control and informed consent

Consequential actions should disclose their effect, target, authorization boundary, and material side effects before execution. Cancellation should be a normal outcome.

## 3. Auditability and provenance

Systems should record enough provenance to distinguish intent, interpretation, authorization, execution, and verification. Integrity evidence should not be misrepresented as proof of factual truth.

## 4. Privacy minimization

Public accountability should not require unnecessary publication of personal data. Pseudonymous or persona-based attribution may be supported where accountability can be preserved without compulsory legal-name disclosure.

## 5. Local-first operation

Where practical, users should be able to keep data, models, records, and workflow state under local control rather than being forced into remote services.

## 6. Portability and interoperability

Core OSWAP semantics should not depend unnecessarily on one AI model, vendor, repository forge, operating system, or proprietary backend.

## 7. Preservation and resilience

Open formats, reproducible environments, independently verifiable copies, and finite policy-gated replication should support long-term access and recovery.

## 8. Multilingual and international design

Localization should be treated as part of system architecture rather than an afterthought. Regional presentation and policy may vary while shared machine-readable semantics remain interoperable.

## 9. Transparent boundaries

OSWAP should state what a component does, what it does not do, what remains experimental, and what requires external authorization. Unknown capability or ambiguous effect should fail closed rather than be invented by an AI layer.

## 10. Open participation

OSWAP-authored source and documentation should use clear open licensing where appropriate, preserve attribution, and make it practical for others to inspect, test, fork, criticize, and improve the work.