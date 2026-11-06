# Stage 3/5 — Data Model & Integration Contracts

Build a compact `source → fields and meaning → transformation → consumer → cadence → access status` map. Distinguish confirmed available sources from proposed and unknown sources. Define identifiers, uniqueness, time zones, business-day boundaries, granularity, corrections, lineage, duplicates, histories and slowly-changing categories.

Integration contracts remain **proposals until documented or tested**. Specify schema and version, read/write rights, authentication, latency, delivery guarantees, idempotency, concurrency, partial failure and recovery ownership. Never invent a vendor's API or permissions.

Find semantic traps that can make an apparently correct calculation wrong: stock on hand versus sellable stock, document date versus event time, estimated versus observed values.

Set trust boundaries, sensitive data handling, external-LLM data access and permitted actions. For legal obligations, examine the literal rule and express exclusions before classifying applicability; otherwise mark it unverified.

Output: required MVP data, blocking unknowns, contract statuses, semantic checks and permission boundaries.
