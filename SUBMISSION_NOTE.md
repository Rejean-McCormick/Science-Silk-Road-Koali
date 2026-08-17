# Submission Note
## From sociotechnical construction to an empirical research problem

Dear Professors Ahlers, Cheng, and Zhou,

I am writing because your project, *China’s Science Silk Road and the New Geopolitics of Knowledge Production*, intersects with a set of problems I reached independently from a different direction: not initially through the study of Chinese science, but through the design and implementation of a sociotechnical architecture called **kOA**.

The Science Silk Road project asks how China’s expanding international cooperation in science, technology, and innovation is reshaping global knowledge production through new infrastructures, networks, and partnerships. Its official framing emphasizes multi-level effects on research, society, development, partner countries, established science powers, and international scientific cooperation:

- https://sciencesilkroad.mpiwg-berlin.mpg.de/
- https://www.mpiwg-berlin.mpg.de/research/projects/chinas-science-silk-road-and-new-geopolitics-knowledge-production

While building kOA, I encountered a related but more general problem: **how capabilities survive transitions**.

A document does not automatically become knowledge. Knowledge does not automatically become expertise. Expertise does not automatically become legitimate authority. A decision does not automatically become executable work. An output does not automatically become an outcome. An outcome does not automatically become organizational learning. Training does not automatically become mastery. Access to an infrastructure does not automatically become the capability to maintain, modify, transmit, or reconfigure it.

Because kOA had to make such transitions operational, it formalized distinctions between evidence, validation, authority, execution, provenance, institutional memory, portability, and recovery. Examples are visible in the public architecture:

- kOA-Linux constitutional invariants: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/01-constitution/02-global-invariants.md
- explicit authority model: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/01-constitution/04-explicit-authority.md
- portability, restore, and exit: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/01-constitution/11-portability-restore-and-exit.md
- capability model: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/02-system/06-capability-model.md
- receipts and critical transitions: https://github.com/Rejean-McCormick/kOA-Linux/blob/main/docs/02-system/20-receipts-and-critical-transitions.md
- Konnaxion journeys: https://initkoa.org/platforms/konnaxion/journeys

One concrete example is **Kristal**, kOA's portable structured epistemic artifact model. Kristal v5 can represent hypotheses, scientific claims, research material, technical declarations, and disputed positions before final recognition while preserving provenance, certainty, scope, evidence, authority references, and lineage. Its documentation describes the format as AI-ready and queryable; paired with SemantiK Architect, the same structured meaning can be rendered into target-language text while retaining epistemic labels. This suggests a practical Science Silk Road question: whether cross-border scientific cooperation could exchange not only papers and datasets, but also structured, machine-readable, multilingual knowledge objects during earlier stages of research.

An invention disclosure can be represented in that same structure, but this should not be confused with patent registration: a Kristal is not a patent-office filing or a substitute for patent law. Patent-sensitive artifacts may also require restricted distribution before filing because public disclosure can affect novelty.

A parallel set of public essays documents the conceptual lineage behind this architecture: **Knowledge Peacebuilding** frames knowledge cooperation as a possible nonviolent common ground; **Knowledge Has Left the Temple** addresses contribution beyond institutional monopolies; **Kristal** provides the portable epistemic object; the semantic-web essay addresses meaning across languages; **Artificial Intelligences Need the World’s Manuals** extends the problem to machine-usable operational knowledge; and **Konnaxion and Orgo** connect knowledge to coordinated action. I treat these essays as design rationale and question-generating material, not as independent empirical evidence. They are mapped in `docs/11-conceptual-foundations.md`.

This design trajectory leads to a research proposition that I believe complements, rather than duplicates, your project:

> **How do transnational scientific infrastructures redistribute and reproduce the capabilities to operate, maintain, interpret, validate, adapt, govern, transmit, and reconfigure scientific activity across partner institutions over time?**

A second question follows:

> **What forms of dependency are co-produced with these capability gains, and under what conditions do those dependencies remain negotiable and reconfigurable rather than becoming rigid lock-in?**

I use **capability trajectory** as the unit of analysis. Instead of treating a laboratory, country, or partnership as having a single level of “capacity,” the research would follow a scientific function across transitions: procurement → installation → training → routine use → failure → maintenance → modification → staff turnover → retraining → new research uses. At every step, the empirical questions are: who can act, who can authorize, who can interpret, what evidence persists, what knowledge is transmitted, and which dependencies become decisive?

This creates specific points of dialogue with your work:

- **Han Cheng:** geographies and politics of knowledge production, *world-writing*, infrastructure, situated knowledge, and the translation, circulation, and reproduction of knowledge.
- **Anna Lisa Ahlers:** science systems, political steering, expertise, professional autonomy, evaluation regimes, and the coexistence of different forms of authority inside scientific organizations.
- **Hang Zhou:** ethnographic attention to China–Africa relations, infrastructure, development cooperation, state capacity, bureaucratic practice, local agency, and the everyday operation of transnational projects.

The aim is not to export kOA into the research setting as a normative model. It is to **extract falsifiable propositions from an architecture that has already had to formalize these problems**, then expose those propositions to external empirical cases where the actors, institutions, technologies, histories, and political conditions are not controlled by the architecture itself.

This repository provides the conceptual bridge, the source evidence, and a proposed empirical design.

Réjean McCormick  
https://initkoa.org/  
https://github.com/Rejean-McCormick
