# 13 — Pressure-Test and Falsification Method

## 1. Purpose

A general architecture can easily become self-confirming. The pressure-test discipline exists to make explicit what evidence should **kill, narrow, or revise** a claim.

The basic loop is:

```text
ArchitecturalClaim
→ InstitutionalConstraint
→ FailureTest
→ Evidence
→ Reject / Narrow / Revise / Continue
```

The key question is:

> **What should kill the idea?**

## 2. Epistemic statuses

Project claims should be labeled rather than blended:

- **DOCUMENTED** — explicitly present in architecture/specification;
- **IMPLEMENTED / REPORTED** — implementation exists or is reported, with verification limits stated;
- **VALIDATED** — independently tested in the relevant sense;
- **PARTIALLY VALIDATED** — some tests support the claim, with known gaps;
- **UNVERIFIED** — not yet tested;
- **DERIVED** — analytical inference from documented architecture;
- **FUTURE DESIGN** — proposed direction, not present reality.

## 3. Science Silk Road pressure tests

### Claim: interface integrity matters

**Possible failure:** outcomes are adequately explained by node-level resources and institutional characteristics; interface tracing adds little.

### Claim: explicit authority separation helps

**Possible failure:** formal separation creates delay, ambiguity, or administrative burden while informal negotiated authority performs better.

### Claim: provenance improves reconstructibility

**Possible failure:** the recording burden exceeds practical value or creates surveillance risks.

### Claim: composition without absorption is desirable

**Possible failure:** shared standards or centralized semantic structures materially improve cooperation without meaningful loss of local agency.

### Claim: reconfigurability matters

**Possible failure:** stable long-term dependencies are efficient, resilient, and preferred; substitution capacity adds little value.

### Claim: local reproduction indicates durability

**Possible failure:** distributed specialization provides equal or greater continuity without local reproduction of the relevant function.

## 4. Governance burden

Any proposed interface mechanism creates administrative cost.

The relevant test is not simply whether a mechanism provides a benefit, but whether:

```text
GovernanceBenefit - AdministrativeBurden > 0
```

This is a heuristic, not a calibrated equation.

## 5. Avoiding architecture by analogy

A mechanism that works in software does not automatically work in science, government, medicine, or international cooperation.

Safeguards include:

- external literature;
- domain-specific counterexamples;
- interviews and field observation;
- implementation verification;
- explicit failure conditions;
- permission to split an over-generalized primitive again.

## 6. Why this matters academically

The Science Silk Road is valuable precisely because it is **external** to Koali. The actors, histories, power relations, infrastructures, and institutional logics were not designed to fit the architecture.

Therefore:

```text
GeneralProblem → Architecture → PressureTestMethod → TransnationalEmpiricalTest
```

A case that contradicts Koali is not a nuisance. It is evidence needed to determine the scope of the theory.
