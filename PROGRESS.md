# Progress Log

This file tracks ongoing planning, decisions, and next steps for the
**PolyPhase_DPD** project. New entries are appended at the top so the most
recent activity is always visible first.

---

## 2026-05-05 — Planning session

### Next moves (assigned to Chen)

1. **Add justification for the LOS assumption.**
   Provide a clear discussion of when and why the line-of-sight (LOS)
   modeling assumption is reasonable in the considered scenario, so that the
   premise of the subsequent analysis is well grounded.

2. **Investigate a negative-definite quadratic approximation restricted to
   the main-lobe interior of the sinc function.**
   Examine whether a negative-definite quadratic approximation holds on the
   strictly-positive portion of the sinc within the main-lobe bandwidth
   (i.e., the central lobe between its two bounding zero-crossings, where
   the function takes positive values). The goal is to determine whether
   **unimodality can be established without relying on a single global
   approximation**: a local concavity argument confined to the main lobe,
   combined with the fact that the side-lobe peaks are strictly below the
   main-lobe peak, would suffice to conclude unimodality.

3. **Revise and clarify the path-loss exponent term.**
   Update the relevant derivations involving the path-loss exponent and add
   the explanatory text needed to make the modeling choice transparent to
   the reader.

4. **Add CRLB analysis to Section IV.**
   Incorporate a Cramér–Rao Lower Bound (CRLB) analysis into Section IV of
   the manuscript, alongside the existing results.

---

<!-- Append new dated entries above this line. -->
