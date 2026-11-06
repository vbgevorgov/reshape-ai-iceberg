# Stage 2/5 — Domain Engineering

Reconstruct `event → data → decision → execution → measured result`, including actors, authority and verification checkpoints. Identify entities, states, valid transitions, domain invariants, constraints, exceptional cases, manual overrides and competing KPIs.

Show a concrete counterexample to one tempting but unsafe simplification. For example, the nearest field technician may lack the part needed for a first-time fix; zero sales can mean stockouts rather than zero demand. Never transplant examples into unrelated domains as facts.

Define three critical cases: prohibited action, competing priorities, and rare high-impact exception. Specify who can correct a decision and how failure degrades safely.

**Guided:** ask only if a material invariant/approval depends on the answer; one question per message and four total maximum. **Autonomous:** treat guessed rules as hypotheses and ask no questions.

Output: domain model, process, constraints, 2–3 critical hypotheses and tests.
