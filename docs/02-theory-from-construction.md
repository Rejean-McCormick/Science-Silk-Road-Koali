# 02 — Theory from Construction

## 1. Why construction matters epistemically

kOA was not initially designed as a theory of the Science Silk Road. It was designed as an operating architecture for connecting knowledge, deliberation, decision, execution, evidence, and memory.

That matters because implementation forces distinctions that can remain underspecified in abstract discourse.

A software architecture must eventually answer:

- Which object is canonical?
- Which component owns it?
- Who may change state?
- Which evidence permits the transition?
- What survives the transition?
- Which authority has jurisdiction?
- What happens if the authority is unavailable?
- How is disagreement represented?
- How is rollback performed?
- How can a component or provider be replaced?
- What remains after the people who built the system leave?

The resulting theoretical contribution is best described as **theory from construction**: implementation generates disciplined hypotheses about coordination, authority, memory, and capability.

## 2. The transition is the primary analytical object

The kOA architecture repeatedly separates states that are often collapsed in ordinary language:

```text
claim → evidence → validation → recognition
knowledge → judgment → decision → mandate
mandate → task → execution → closure
result → evidence → review → institutional memory
learning → assessment → competence → credential
artifact → validation → activation → rollback / replacement
```

The recurring problem is not merely “workflow.” It is **controlled transformation**: what changes, what remains stable, what becomes authoritative, and what evidence preserves the lineage.

Public technical anchors:

- Global invariants: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/01-constitution/02-global-invariants.md
- Explicit authority: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/01-constitution/04-explicit-authority.md
- Critical transitions / receipts: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/02-system/20-receipts-and-critical-transitions.md
- Technical foundations of Konnaxion: https://initkoa.org/platforms/konnaxion/technical

## 3. Separation of authority types

kOA explicitly resists a single undifferentiated notion of authority. Different subsystems own different decisions, data, and transitions.

This becomes a research heuristic:

```text
scientific expertise
≠ data authority
≠ validation authority
≠ organizational authority
≠ agenda authority
≠ political authority
≠ operational permission
```

The point is not to impose kOA's technical authority model on empirical cases. It is to ask whether scientific collaborations also contain functionally distinct authority surfaces that ordinary categories such as “control” or “ownership” obscure.

## 4. Provenance as institutional memory

In kOA, provenance is not merely bibliographic citation. It supports reconstruction of how an object, decision, artifact, or capability reached its current state.

This generates an empirical question for scientific infrastructures:

> When a capability persists, what memory structures make persistence possible?

Possibilities include manuals, source code, tacit routines, mentoring, procurement records, calibration histories, institutional procedures, data lineages, maintenance logs, standards, credential systems, or communities of practice.

## 5. Portability and exit

kOA-Linux treats portability, restore, recovery, and exit as explicit architectural concerns:

- https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/01-constitution/11-portability-restore-and-exit.md
- https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/08-operations/10-portability-and-exit.md

The research translation should be weaker and more neutral than the software rule:

> **Can the scientific activity be reconfigured when a critical dependency changes?**

This avoids assuming that “exit” is always desirable. It makes change, rather than autarky, the test.

## 6. What is genuinely being claimed

This dossier does **not** claim:

- that kOA invented institutional memory;
- that kOA invented provenance;
- that kOA invented capacity building;
- that kOA invented theories of dependency;
- that kOA proves a social theory through software.

It claims something narrower:

> kOA independently **integrates and operationalizes** a cluster of problems—authority differentiation, provenance, transition evidence, institutional memory, portability, capability, and continuity—in one architecture. This combination generates a distinctive set of empirical questions that can now be tested outside the system.
