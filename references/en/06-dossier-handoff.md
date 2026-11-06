# Complete dossier and coding handoff — optional

Load **only** when the user asks for a comprehensive dossier, coding handoff or detailed implementation plan.

1. Executive brief: decision, goal, users, boundaries and decision owner.
2. Evidence ledger: observed/documented facts, deductions, hypotheses, unknowns, source dates.
3. Up to three meaningful discoveries, each with an altered design or decision.
4. Seven levels: status, inputs, responsibilities, dependencies, false assumptions, tests and owner.
5. Workflow and data model: states, critical invariants, access and contract verification.
6. Minimum architecture, decision engines, agents only if required, trust boundaries and recovery.
7. Three golden cases: inputs, expected outputs and failure conditions.
8. Phases and graduation gates: Discovery → Prototype → Working MVP → Production → Scale.
9. Financial model: verified versus assumed rates, labor, licensing, 12-month TCO, sensitivities.
10. Build/Buy/Hybrid/Don't Build Yet, counterargument, reversal condition and next test.

Coding-agent handoff:

```text
PROJECT_CONTEXT:
CONFIRMED_REQUIREMENTS:
HYPOTHESES_AND_UNVERIFIED_ASSUMPTIONS:
DOMAIN_MODEL_AND_INVARIANTS:
DATA_SOURCES_AND_CONTRACT_STATUS:
ARCHITECTURE_AND_TRUST_BOUNDARIES:
AI_AGENTS_SKILLS_HARNESS_IF_NEEDED:
GOLDEN_TESTS_AND_EVALUATION:
DELIVERY_BLOCKERS_AND_GATES:
COSTS_AND_TCO_ASSUMPTIONS:
BUILD_BUY_AND_REVERSAL_TRIGGER:
IMPLEMENTATION_RULES: verify first; no unapproved production mutations
```

Do not represent empty placeholders as requirements confirmed by users or evidence.
