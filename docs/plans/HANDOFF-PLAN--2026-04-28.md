# HANDOFF PLAN: Elevation Execution (PLAN-088)
**Date:** 2026-04-28
**Target:** omni-dromenon-machina (Universal Master)
**Objective:** Execute the elevation of Hokage Chess and My-Knowledge-Base per SPEC-024.

## I. Immediate Execution Stream (Surgical Actions)

### Step 1: Metasystem Registration
*   **Action:** Update `organvm/metasystem-master/.config/metasystem.yaml`.
*   **Payload:**
    ```yaml
    workspaces:
      - name: "hokage-chess"
        path: "../../4444J99/hokage-chess"
        type: "landing-page"
        status: "elevation-pending"
        tech_stack: ["next.js", "tailwind"]

      - name: "my-knowledge-base"
        path: "../../organvm/my-knowledge-base"
        type: "knowledge-engine"
        status: "active"
        tech_stack: ["typescript", "sqlite", "ollama"]
    ```

### Step 2: Hokage Chess Node Activation
*   **Action:** Execute build and deployment.
*   **Sub-tasks:**
    1.  `cd /Users/4jp/Workspace/4444J99/hokage-chess`
    2.  Register domain `hokagechess.com` (Manual intervention required for payment/DNS setup).
    3.  Configure Vercel project and link to GitHub.
    4.  Wire ConvertKit API keys to `.env.production`.
    5.  Run `npm run build` and verify output.
    6.  Run `npx playwright test` to verify email funnel integrity.

### Step 3: Theory Scaling (Wiki Compiler)
*   **Action:** Implement `TheoryEngine` and resume synthesis.
*   **Sub-tasks:**
    1.  Initialize `VectorDatabase` with existing 154k embeddings.
    2.  Run `TopicClusteringAnalyzer` to reduce 147k "Insights" into ~50-100 high-fidelity clusters.
    3.  Modify `WikiCompiler.ts` to use `TheoryEngine` synthesis instead of raw unit extraction.
    4.  Resume `Phase B` (Page Synthesis) in background mode.

---

## II. Strategic Elevation Questions (For Master Deliberation)

*   **Pattern Extraction:** Can the `BatchProcessor` logic in `my-knowledge-base` be promoted to a core `omni-dromenon-machina` package for all large-scale LLM tasks?
*   **Personal Space Cleanliness:** Should `4444J99/hokage-chess` be migrated to a dedicated `organvm-iii-ergon` (Commerce) repository post-elevation?
*   **Failure Protocol:** At 154k units, a 10% failure threshold is 15.4k errors. Is this too high? Should the Master implement a "Tiered Sampling" verification phase for massive datasets?

---

## III. Verification & Closure
*   **Validation:** Run `conductor patch` to verify all unvetted suggestions are now recorded as "Live Tasks."
*   **Artifact:** Confirm the existence of `docs/theory/ELEVATION-SPEC--2026-04-28.md`.
