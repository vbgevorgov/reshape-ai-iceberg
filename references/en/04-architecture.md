# Stage 4/5 — Architecture & AI Engineering

Start with business guarantees, then choose the smallest sufficient mechanism: deterministic rules/code, document retrieval, mathematical optimization, statistical prediction/ML, simulation, LLM text processing, or tool-using agents. For each component provide inputs, outputs, rationale, failure modes and a discriminating test.

Do not use LLMs for exact transactional computations. Do not introduce a custom harness unless an existing orchestration/runtime is insufficient. Distinguish the research agents used to analyze the idea from agents that would run in the customer's product.

If runtime agents are justified, define tools/permissions, context versioning, memory constraints, state machine, budget, retries, stop conditions, human confirmation, auditable decisions and recovery. Define Loop Engineering as `observe → analyze → act → evaluate → correct`, with entry, retry, stop and escalation conditions, separating developer-agent loops from customer business decisions. Consider security, observability, availability, deployment, rollback, backups and manual fallback.

Provide a simple component flow with data movement and trust boundaries. Explicitly mark what is **not required** for MVP. Avoid unnecessary Kubernetes and microservices.

Output: minimum viable blueprint, assumptions, guardrails, and conditions for adding ML or agents later.
