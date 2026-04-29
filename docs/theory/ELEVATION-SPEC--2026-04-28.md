# ELEVATION SPECIFICATION: Transitioning Suggestions to Master Governance (SPEC-024)
**Date:** 2026-04-28
**Status:** DRAFT (Handoff to Universal Master)
**Framework:** Triadic Temporal Elevation (PAST → PRESENT → FUTURE)

## I. Executive Summary
This document formalizes the elevation of current project-level "suggestions" into governed "system interventions" managed by the Universal Master (`omni-dromenon-machina`). It addresses the immediate needs of the `hokage-chess` and `my-knowledge-base` repositories through the lens of meta-orchestration.

---

## II. Project Elevation: Hokage Chess (Group 1 - Deployment)

### 1. PAST (Contextual Audit)
*   **Previous Failures:** Vacuums V1–V10 identified (e.g., missing email Capture wiring, unregistered domain).
*   **State:** Local development complete; manual `console.log` placeholders remain.

### 2. PRESENT (Gap Analysis)
*   **Gap:** The current state is "un-shipped" and unmonitored. It exists as an isolated artifact rather than a live node.
*   **Intervention Type:** Permanent deployment node.

### 3. FUTURE (System Intervention - Plan)
*   **Genome Update:** Register `hokage-chess` in `metasystem.yaml`.
*   **Enforcement:** `omni-dromenon-machina` will execute the Vercel deployment and verify `hokagechess.com` connectivity.
*   **Verification:** Implement a mandatory `PROVE` phase using Playwright to ensure the email capture funnel is active after every build.

---

## III. Project Elevation: My-Knowledge-Base (Phase 5 - Theory)

### 1. PAST (Contextual Audit)
*   **State:** 150k+ units ingested; high failure rate (19k+) due to "model not found" (gemma3:4b) from legacy runs.
*   **Restoration:** Pruning script executed to stabilize the checkpoint.

### 2. PRESENT (Gap Analysis)
*   **Gap:** The scale of "Insight" units (147k) creates a synthesis bottleneck that exceeds current batch processing defaults.
*   **Intervention Type:** Algorithmic scaling policy.

### 3. FUTURE (System Intervention - Plan)
*   **Policy:** Implement "Semantic Pruning" as a core ingestion policy. 
*   **Mechanism:** `omni-dromenon-machina` to deploy a `TheoryEngine` abstraction that clusters units via vector embeddings before passing to synthesis.
*   **Generalization:** Distill this pattern into a global `Theory-Synthesis` skill for use across the entire ORGANVM ecosystem.

---

## IV. Universal Master Handoff Questions

The following questions must be answered by the Master during the elevation process:

1.  **Orchestration Logic:** Should the `Theory-Synthesis` skill be a global `omni-drom` capability or a project-specific module in `organvm-i-theoria`?
2.  **Quality Enforcement:** What is the acceptable "Failure Threshold" for large-scale ingestion before the Master triggers a system-wide halt?
3.  **Domain Migration:** Is `hokage-chess` ready to be promoted from the `4444J99` personal space to `organvm-iii-ergon` (Commerce) post-deployment?

---

## V. Next Actions (The Plan)

1.  **Patch `metasystem.yaml`:** Add `hokage-chess` and `my-knowledge-base` to the managed workspaces.
2.  **Execute Phase 1 (Hokage):** Deploy to Vercel and register `hokagechess.com`.
3.  **Execute Phase 2 (Theory):** Initialize the `TheoryEngine` and resume Wiki synthesis with the new clustering logic.
4.  **Audit:** Run `conductor patch` to verify all suggestions have been elevated to "Active Tasks."
