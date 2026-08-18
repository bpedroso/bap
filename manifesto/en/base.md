# I. BASE — Domain, Foundation & Resilience

[← Back to manifesto](README.md)

Every great vision needs firm ground. High-scale, high-availability systems do not accept improvisation; they are born from a deep understanding of the business.

## Principles

* **Business understanding as a premise:** There is no strong architecture without domain context. Understanding the business domains the software touches is the first step in determining how it should be designed and built.
* **Stability precedes innovation:** No advanced algorithm replaces a fragile foundation. Infrastructure and data modeling must be designed to withstand high load, severe concurrency, and exponential growth.
* **Isolation and predictability:** Components must be autonomous and fault-tolerant. The base infrastructure must be strictly deterministic, observable, and resilient, ensuring that localized failures never compromise the ecosystem.
* **Architecture at every level:** Every IT professional needs to understand architecture, at different depths depending on their role. From the shallowest knowledge to the deepest, each layer improves the quality of decisions.

## Architecture at every level

Architecture is not a craft reserved for whoever has the title on a badge. It is literacy: every IT professional needs it, to different degrees. Those who see the system beyond their own task choose better, communicate better, and make fewer mistakes.

Depth changes with the role. What does not change is the effect: even a shallow cut already improves the decision; a deep cut makes guidance possible.

### Examples by depth

**Junior developer** — wanting to know how a request arrives (client → network → API → service → data) already locates their own work in the system, whether back or front. That minimum map reduces “code in a vacuum”: the person understands where the data comes from, where the error goes, and why a contract exists.

**Designer** — a little architecture expands ideas and possibilities. Knowing that latency, cache, loading states, or API contract limits exist changes what is worth designing — and what is worth defending. Without that cut, design competes with the system; with it, design uses the system.

**Architecture professional** — needs much deeper knowledge to decide and guide. Trade-offs, limits, evolution, and risk do not fit in a high-level diagram: they demand criteria. Without that depth, guidance becomes opinion; with it, it becomes responsibility.
