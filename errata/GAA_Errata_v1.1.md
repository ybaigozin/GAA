# General Adaptive Agency (GAA) — Errata and Clarifications v1.1

**Author:** Yerbol Baigozin  
**Release date:** 20 October 2026  
**Against:** [Baigozin (2025), *The General Adaptive Agency Framework: A First-Principles Model of Adaptive Systems*, SSRN 5334620](https://doi.org/10.2139/ssrn.5334620).  
**Status:** Standalone corrections to the published 2025 historical paper; not a replacement theory and not an empirical validation.

## Scope and reading rules

This note preserves the original publication, identifies checkable defects (**E**), implementation ambiguities (**A**), and proposed research revisions (**R**). It neither silently rewrites the 2025 text nor promotes later experimental equations to universal laws. Historical names Ti/Te/Fi/Fe are used only to locate old claims; modern implementations require an explicit version and construct dictionary. Some originally ambitious physical analogies and emergence claims are withdrawn as established identities. A corrected type rule is not itself a validated mechanism.

## Correction register

### C1 — Stock–flow type mismatch (E)

**Location:** Original §§3.2, 4.2; glossary.  
**Problem:** The paper sums accumulated capability (a stock) with period external effects (flows). Under those definitions the expression is not a dimensionally valid accounting identity.  
**Correction / status:** Specify the observer, agent boundary, window, type and units of every term. Do not add a stock level to a period flow. Separate measured period TR/FR flows from capability and liability stocks; an empirical mapping from flow to stock change remains to be tested.

### C2 — Conflicting external traction signs (E)

**Location:** Original glossary, §§3.2, 4.2 and §6.  
**Problem:** External traction is used for action cost, returned value and favorable external position, with conflicting signs.  
**Correction / status:** Distinguish realized beneficial external effects, realized harms/burdens and resources expended. Classify measured effects, not merely the direction of an action. No one-to-one conservation identity between different agents is established.

### C3 — Emergence norm discards sign (E/R)

**Location:** Original §§5.2–5.3.  
**Problem:** The proposed threshold sqrt(nNSV1^2+nNSV2^2)>=1 can be passed by two negative-valued parents. The resulting child-potency calculation can be positive without observed emergence.  
**Correction / status:** Withdraw the threshold as a sufficient universal deterministic law. Signed viability, coherent interaction, independent causal integration and an operational definition of a higher-level agent remain research requirements. A positivity precondition alone does not validate the Euclidean norm.

### C4 — Learning efficacy is conflated with quantum step size (E/R)

**Location:** Original §4.3, glossary, §7.1.  
**Problem:** The published midpoint destination is independent of LER, and the draft types LER inconsistently as a bounded efficacy fraction and an absolute update quantum.  
**Correction / status:** Withdraw the midpoint/quantum iteration as a general learning law. Distinguish precision-weighted warranted belief update from realized adoption of that update; any two-stage update equation is a candidate for empirical testing, not a corrected universal identity.

### C5 — Accumulated history may help and hinder (A)

**Location:** Original §§3.2, 7.7.  
**Problem:** A historical artifact is classified both as retained traction/capability and as friction/mass without a discriminating protocol.  
**Correction / status:** Relative to a fixed purpose and boundary, separately measure deployable capability and its maintenance or coordination burden. Do not equate this bookkeeping distinction with physical mass.

### C6 — Free Energy Principle equivalence is unsupported (E)

**Location:** Original §2.3.1 and physical analogies.  
**Problem:** The paper asserts mathematical/conceptual identity between maximizing NSV and minimizing variational free energy without a derivation.  
**Correction / status:** Treat Free Energy Principle, thermodynamic and least-action comparisons as analogies or untested bridges. No formal equivalence or literal physical NSV conservation principle has been established.

### C7 — Equal NSV scalars hide different states (A)

**Location:** Original §§3.3, 4.2.  
**Problem:** T=F=0 and T=F=1 both give NSV=0 but differ in capability, effort and dynamical interpretation.  
**Correction / status:** Report component vectors, thresholds and uncertainty; use the scalar as a summary and never as a unique state descriptor.

### A1 — Prediction error assigned to external rather than internal state (E)

**Location:** Original §7.6.1.  
**Problem:** An incoming observation may originate outside an agent, but the mismatch between that observation and its internal model is a different, internal quantity.  
**Correction / status:** Fix the agent boundary first. Record adverse external input effects separately from model discrepancy, stale beliefs or internal errors. Avoid double-counting the same measured consequence.

### A2 — Inference-time internal capability reduced to frozen weights (E/A)

**Location:** Original §7.6.1.  
**Problem:** Equating internal traction with base-model weights excludes agent-level changes in context, memory, planning, tools and procedures.  
**Correction / status:** Distinguish model training from inference-time agent adaptation. Only verified, accessible, goal-relevant state counts as potential capability; stale or unusable context can be friction. Fixed weights do not imply a static agent system.

### A3 — Zero relapses do not validate retention mechanism (R)

**Location:** Later AI-agent observation, not a correction to a 2025 equation.  
**Problem:** A recorded 0/1466 exact-relapse observation lacks independent comparable retention opportunities; it cannot prove the absence of cross-episode learning.  
**Correction / status:** Do not elevate this null to confirmation of lambda. Under an independent Bernoulli assumption only, the rule-of-three upper bound would be about 3/1466=0.205%, not 1.2%; independence was not established. Test repeated opportunities with controlled memory and state persistence.

### A4 — Recipient-side information effects not defined (A)

**Location:** Original §7.6.1.  
**Problem:** Task correctness is not equivalent to a real informational improvement in a user's belief or decision.  
**Correction / status:** Name the recipient and separately measure predicted informational effect, observed recipient belief/decision change, and later outcome. Do not derive a predictor from the outcome it purports to predict.

### A5 — Human–AI component matrix mislabeled as internal/external (A)

**Location:** Original §7.6.2.  
**Problem:** When the human+AI collective is the focal agent, both components fall within its declared boundary.  
**Correction / status:** Treat Oracle/Centaur/Broken Machine/Golem as human-contribution × AI-contribution scenarios. Apply internal/external diagnostic labels only relative to a separately declared agent boundary.

### A6 — Binary archetypes lack empirical thresholds (A)

**Location:** Original §3.3; applied AI classification.  
**Problem:** Idealized 0/1 corners do not define repeatable classifications for continuous or ordinal scores.  
**Correction / status:** Use archetypes as qualitative ideal types unless scoring mappings, sign or distance thresholds, missingness, and near-zero confidence treatment are declared before analysis.

### A7 — Compensatory score cannot authorize a forbidden action (A/R)

**Location:** Original §7.6.1.  
**Problem:** Any finite penalty inside an additive score can be offset by a sufficiently large benefit.  
**Correction / status:** Apply independent safety, legal, permission and irreversibility gates before using NSV to authorize or rank an action. Diagnostic scores may still be logged after a failed gate, but cannot override it.

## What remains open

The following are **not settled by v1.1**: how to measure retained adaptive capability independently of task outcomes; whether period TR/FR flows reconcile with accumulated stocks; how to identify emergent agency using causal interventions rather than a numerical threshold; and whether NSV-based advice improves decision quality, inter-rater reliability or outcomes over equally informed baselines. Archetype predictive performance and any universal dynamical law remain research hypotheses.

## Research integrity and versioning

The July 2025 PDF is retained unchanged as the historical original. Future studies must declare their observer, agent boundary, observation horizon, model/measurement version, inputs, thresholds, comparison baseline and evidence status. Report negative and withdrawn results alongside positive findings. This note does not address unpublished working specifications or establish their formulas.

**Citation:** Baigozin, Y. (2026). *General Adaptive Agency (GAA) — Errata and Clarifications v1.1*. Public GitHub repository `ybaigozin/GAA`, 20 October 2026. Accompanies SSRN 5334620.
