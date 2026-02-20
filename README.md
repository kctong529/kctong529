# Hi there, I'm Ki Chun 👋

I’m a third-year Digital Systems and Design student at Aalto University. I’m interested in domain modeling, constraint systems, and building production software that handles real-world complexity.

## 🌱 Sisukas — Constraint-Aware Course Planning

Creator and maintainer of **Sisukas**, a production course discovery and planning system built to coexist with SISU at Aalto.

**Core system design**

* Planning-first domain model (Plans, Blocks, Schedule Pairs, Decision Slots)
* Deterministic schedule combination & ranking engine
* Explicit trade-offs instead of "optimal" schedules
* Active + historical datasets with invariant-based design

**Architecture & infrastructure**

* TypeScript (Express) backend + Svelte frontend
* Public FastAPI services + type-safe Python client
* PostgreSQL (Supabase) with RLS
* Controlled data promotion (dev → prod) via CI workflows
* Snapshot & backfill pipelines with single-writer guarantees
* Health checks with build metadata

🔗 Live: https://sisukas.eu  
🔗 Code & docs: https://github.com/kctong529/sisukas

---

If you care about systems that make trade-offs explicit, survive real-world constraints, and are actually deployed and maintained, feel free to take a look :)
