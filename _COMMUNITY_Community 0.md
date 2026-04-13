---
type: community
cohesion: 0.27
members: 11
---

# Community 0

**Cohesion:** 0.27 - loosely connected
**Members:** 11 nodes

## Members
- [[Exported env Singleton]] - code - backend/src/config/env.ts
- [[Express Application Entry Point]] - code - backend/src/index.ts
- [[Health Check Endpoint health]] - code - backend/src/index.ts
- [[Pino Logger Singleton]] - code - backend/src/utils/logger.ts
- [[PostgreSQL Pool via PgBouncer (port 6432)]] - code - backend/src/config/database.ts
- [[Trust Proxy Config (AUDIT FIX R6-1)]] - code - backend/src/index.ts
- [[getClient() for Multi-statement Transactions]] - code - backend/src/config/database.ts
- [[ioredis Client Instance]] - code - backend/src/config/redis.ts
- [[query() Wrapper with Logging]] - code - backend/src/config/database.ts
- [[testConnection() DB Health Check]] - code - backend/src/config/database.ts
- [[testRedisConnection() Health Check]] - code - backend/src/config/redis.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Community_0
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_Community 2]]
- 2 edges to [[_COMMUNITY_Community 1]]

## Top bridge nodes
- [[PostgreSQL Pool via PgBouncer (port 6432)]] - degree 6, connects to 1 community
- [[Exported env Singleton]] - degree 5, connects to 1 community
- [[Trust Proxy Config (AUDIT FIX R6-1)]] - degree 2, connects to 1 community