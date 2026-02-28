# Spanda Architectural Framework – Papers Series

This repository contains the foundational architectural papers underlying the **Spanda Engine** simulation framework.

These documents define a constraint-grounded approach to artificial agents that are:

- **Non-omniscient**
- **Structurally bounded**
- **Temporally persistent**
- **Field-coupled but stability-aware**
- **Governance-closed under deviation**
- **Reflex-capable under short-horizon salience**
- **Entry-governed at the representation → memory boundary**

The series formalizes dimensional inference, stratified memory persistence, multi-agent reference dynamics, drift governance, representational standardization, short-horizon salience, and experience entry admissibility as **architectural principles**, not philosophical claims.

---

## Overview

Spanda is built around a single design commitment:

**Artificial agents must infer only what their constraint surfaces justify.**

From this foundation, the series develops:

1. Constraint-grounded dimensional inference  
2. Stratified time-scaled memory architecture  
3. Reference-shift field dynamics in multi-agent systems  
4. Drift detection and governance closure (constraint deviation)  
5. Modular representation standardization (typed tagging / TVS)  
6. Short-horizon salience (Reflex Attention)  
7. Experience entry admissibility (representation → memory boundary contract)  

Each paper stands independently, but together they define the structural logic of the Spanda Engine.

Papers 1–3 define what agents may infer, how they persist, and how they destabilize collectively; Paper 4 defines how deviation is detected and governed before collapse propagates; Papers 5–7 define optional representation, reflex, and entry-contract layers that improve interoperability and real-time stability without creating new prerequisites.

---

## Papers

### Paper 1
**Constraint-Grounded Dimensional Inference in Artificial Agents**  
Zenodo: https://zenodo.org/records/18700957  

Establishes the epistemic boundary condition for non-omniscient agents.

Key contributions:
- Representation as a structural requirement for agency  
- Constraint surfaces as epistemic limits  
- Higher-dimensional inference only via invariant boundary effects  
- Explicit rejection of architectural omniscience  

---

### Paper 2
**Stratified Memory and Time-Scaled Persistence in Artificial Agents**  
Zenodo: https://zenodo.org/records/18701137  

Introduces a three-tier memory architecture:
- Short-term volatile state  
- Intermediate compressed regularity  
- Structural priors  

Key contributions:
- Hybrid continuous/discrete memory semantics  
- Pressure- and viscosity-gated assimilation  
- Residual activation as regulated imbalance  
- Identity-binding as weighted persistence  

---

### Paper 3
**Reference Shift and Constraint-Field Dynamics in Multi-Agent Systems**  
Zenodo: https://zenodo.org/records/18701215  

Extends the framework to distributed systems.

Key contributions:
- Reference alignment as the primary instability predictor  
- Concentration density over mean activation  
- Asymmetric amplification modeling  
- Dissipation capacity and stability boundaries  
- Two cascade regimes (amplification-dominant vs inhibition-dominant)  

Collective instability is framed as a structural phase transition within shared constraint fields.

---

### Paper 4
**Constraint Deviation Engine: Drift Detection and Governance in Stratified Agent Architectures**  
Zenodo: https://zenodo.org/records/18717239  

Introduces the governance closure mechanism for the series: drift is detected as enforceable constraint deviation rather than as sentiment labels.

Key contributions:
- Multi-layer deviation vectors over interaction-derived signals  
- Scope-stratified baselines (global, per-agent, per-task, per-scene)  
- Persistence + hysteresis event formation  
- Replayable rationale artifacts via evidence spans and provenance  
- Guarded baseline updates with conservative multi-scope gating  
- Promotion of persistent instability into explicit governance modes  

---

### Paper 5
**Tone Vector System (TVS): A Modular Representation Layer for Interoperable Signals**  
Zenodo: https://zenodo.org/records/18728170  

Defines an optional representation interface layer for standardizing interaction-derived state across modules.

Key contributions:
- Typed tagging grammar (domain id, routing id, payload)  
- Commit-class semantics (canonical vs associative traces)  
- Versioned dictionaries and provenance requirements  
- Minimal memory record contract and rationale pointers  
- Optional cross-domain transforms under declared routing  

---

### Paper 6
**Reflex Attention in Stratified Agent Architectures: A Short-Horizon Deviation Flag for Non-Persistent Anomaly Detection**  
Zenodo: https://zenodo.org/records/18733074  

Defines an optional short-horizon salience layer that elevates attention without implying persistence or governance escalation.

Key contributions:
- Micro-baseline reflex scoring under bounded horizons  
- Optional criticality weighting (C0–C3) for prioritization  
- Non-persistence guarantees (no baseline updates, no memory writes)  
- Deterministic low-impact routing (clamps, prompts, review band)  
- Minimal replay/audit logging requirements for falsifiability  

---

### Paper 7
**Experience Entry Contract (EEC): Admissibility Constraints for Interaction-Derived Memory Records**  
Zenodo: https://zenodo.org/records/18752181  

Defines a boundary-layer contract governing how interaction-derived events become admissible memory records in stratified agent architectures.

Key contributions:
- Boundary contract: Interaction-derived Event → EEC → Memory Record  
- Commit-class admissibility (associative vs canonical)  
- Promotion invariants (multi-evidence support; no repetition-only promotion)  
- Failure modes and containment constraints for downstream governance  
- Provenance and replayability requirements for entry audit  
---

### Paper 8
**Normative Interface Contracts for Stratified Agent Architectures: Conformance Specifications and Demo-Validated Governance Constraints (N01–N30)**
Zenodo: https://doi.org/10.5281/zenodo.18791708

Defines normative MUST/MUST NOT interface contracts (N01–N30) and binds each requirement to proof/break micro-demos in a deterministic conformance harness.

Key contributions:
- Normative surface for stratified agent stacks (N01–N30)
- Demo-validated conformance mapping (proof/break fixtures)
- Fixed JSONL audit record requirements (decision + evidence + replay metadata)
- Strict envelope rule (demo-specific assertions carried as key:value evidence tokens)
- A falsifiable interface-level contract for governance, persistence, reflex non-persistence, and entry control
  
---

### Paper 9

**Reference Architecture & Interface Contracts for a Stratified, Constraint-Governed Agent Stack: Harness-Aligned Conformance Specification**
Zenodo: https://doi.org/10.5281/zenodo.18810122

Consolidates Papers 1–8 into a single “wiring spec” that maps module boundaries and formalizes the cross-module contracts needed for integration and replayable verification.

Key contributions:
- Reference stack map (EEC → CGDI → Reflex → TVS → CDE → Memory → Field) with explicit boundary rules
- Canonical interface IDs (EWI / GEI / TVI / MWI / FUI) for seam-level integration
- Standardized evidence token grammar + decision vocabulary for deterministic validation
- Publishable enum tables for gate levels and review bands
- Minimum tool side-effect taxonomy (non-destructive / reversible / destructive) + gating fields
- Capability lease and rollback artifact proof fields for high-risk actuation governance
- Temporal semantics for in-band gate assertions + deterministic replay requirements (seed/artifact ID when applicable)

---

## Design Philosophy

This series is **not**:
- A psychological theory  
- A sociological theory  
- A metaphysical claim  

It is **technical documentation** describing how the Spanda Engine is architected.

The framework prioritizes:
- Bounded inference  
- Explicit structural limits  
- Measurable instability criteria  
- Simulation-ready formalism  
- Non-omniscient design discipline  
- Governed drift and auditable deviation events  

All claims are architectural and falsifiable within simulation contexts.

---

## License

This repository is licensed under **Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)**.

- You may share and adapt the material **for non-commercial purposes**
- You must provide **attribution**
- Commercial use requires **separate permission**

See [`LICENSE`](LICENSE) for the full legal text.

---

## Contact

**Stephen A. Putman**  
Email: putmanmodel@pm.me  

---

## Status

Architectural paper series: **v0.2**  
Published via Zenodo with DOI assignment.

Future revisions may expand formalization and simulation validation; this series establishes the architectural foundation.
