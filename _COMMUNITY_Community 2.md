---
type: community
cohesion: 0.25
members: 8
---

# Community 2

**Cohesion:** 0.25 - loosely connected
**Members:** 8 nodes

## Members
- [[CLAUDE.md Project Rules]] - document - CLAUDE.md
- [[Direct PostgreSQL Connection (port 5432)]] - code - backend/scripts/run-migrations.ts
- [[Migration Runner]] - code - backend/scripts/run-migrations.ts
- [[Rationale Migrations Use Direct Postgres (DDL + PgBouncer incompatibility)]] - document - backend/scripts/run-migrations.ts
- [[Rule Always Connect via PgBouncer (port 6432)]] - document - CLAUDE.md
- [[Rule Routes - Services - Models Architecture]] - document - CLAUDE.md
- [[Rule Zod Input Validation + Prepared Statements]] - document - CLAUDE.md
- [[_migrations Tracking Table]] - code - backend/scripts/run-migrations.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Community_2
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_Community 0]]
- 1 edge to [[_COMMUNITY_Community 1]]

## Top bridge nodes
- [[Migration Runner]] - degree 3, connects to 1 community
- [[Rule Always Connect via PgBouncer (port 6432)]] - degree 3, connects to 1 community
- [[Rule Zod Input Validation + Prepared Statements]] - degree 2, connects to 1 community