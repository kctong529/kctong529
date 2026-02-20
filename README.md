# Hi there, I'm Ki Chun 👋

I’m a third-year Digital Systems and Design student at Aalto University. I’m interested in domain modeling, constraint systems, and building production software that handles real-world complexity.

## 🌱 Sisukas — Constraint-Aware Course Planning System

Designed and built a production course discovery & planning platform used alongside SISU at Aalto.

* Domain-driven core (Plans, Blocks, Schedule Pairs, Decision Slots)
* Deterministic constraint-combination & ranking engine (no fake "optimal" schedules)
* Dual-dataset architecture (active + append-only historical), disjoint by construction
* Snapshot “patch layer” for missing instances — non-canonical data only graduates via deterministic CI backfill
* TypeScript (Express) backend, Svelte frontend, PostgreSQL (RLS) with DB-enforced invariants
* Offline-first PWA: course browsing works without internet via versioned cached datasets
* Fully deployed with environment isolation + health-verified releases

🔗 Live: https://sisukas.eu  
🔗 Code & docs: https://github.com/kctong529/sisukas

---

If you care about systems that make trade-offs explicit, survive real-world constraints, and are actually deployed and maintained, feel free to take a look :)
