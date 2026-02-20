# ECN: Evolutionary Contradiction Network

**ECN (Evolutionary Contradiction Network)** is a symbolic cognitive architecture intended to evolve reasoning through internal contradiction detection, belief mutation, and goal realignment, rather than token prediction.

Paired with **CREH (Contradiction Re-Entry Hooks)**, ECN revisits failed hypotheses and attempts repair by rewriting internal symbolic structure. It stores unresolved reasoning paths in a **Latent Novelty Buffer (LNB)** and triggers corrective pressure via a **Goal Drift Monitor (GDM)**.

Unlike probabilistic LLMs, ECN does not depend on tokens, embeddings, large-scale corpora, or gradient-based learning. It operates within a self-modifying symbolic space, where reasoning strategies can be generated, tested, retained, or replaced under explicit governance and utility constraints.

## What is in this repo

- **ECN_Academic_Paper_2026_v2.docx**  
  Public redacted paper describing the architecture, modules, and intended research direction. Some scoring and tuning details are intentionally withheld.

## What is not in this repo (yet)

- A complete reference implementation of ECN
- Reproducible benchmarks and test suites
- Full parameterization details for utility scoring and gating

## Roadmap

1. Finish the ECN proof-of-concept and publish a reproducible demo with clear evaluation tasks.
2. Expand the paper with formal definitions, proofs/guarantees where applicable, and verifier integrations.
3. File patent coverage for commercially sensitive mechanisms (where appropriate), then publish the remaining details.

## What is done
1. Basic POC v1 - In a small classical-logic domain, ECN Code reproduces human-like inference behavior by autonomously synthesizing and promoting standard inference rules as executable DSL programs. In successful fresh runs, synthesis is 100% enumeration with 0% template fallback, rediscovering Modus Ponens (DETACHMENT) and Modus Tollens (INVERSION), and also Hypothetical Syllogism (COMPOSITION).

## License

Copyright © 2025 Abhishek Srivastava  
Licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You may **share and adapt** this work for **non-commercial purposes**, provided you give **appropriate credit** and license derivatives under the **same terms**.

**Commercial use** (including monetization, product integration, or use in paid services) requires a separate commercial license.  
To inquire about commercial licensing: **abhisri [at] gmail.com**

### Dual-license clarification (Updated 1 July 2025)

In addition to CC BY-NC-SA 4.0:

> If this work, or substantial derivatives, are used in commercial AI systems, logic engines, reasoning agents, or symbolic frameworks (including inference modules and problem-solving architectures), a separate commercial license is mandatory.

No patent rights are granted under this license. Use of ECN-derived mechanisms in commercial reasoning systems may require additional patent licensing, pending filings.

## References

- OSF Registration (timestamped prior art): https://osf.io/c2va4  
- Zenodo DOI upload: coming soon

## Tags

Symbolic AI · Cognitive Architecture · CREH · ECN · Novelty Buffer · Goal Drift · Post-LLM Reasoning · Volitional Mutation · Non-Probabilistic AI