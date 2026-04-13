---
type: community
cohesion: 0.19
members: 13
---

# Backend Env Config

**Cohesion:** 0.19 - loosely connected
**Members:** 13 nodes

## Members
- [[GEMINI_API_KEY â€” LLM Integration Config]] - code - backend/src/config/env.ts
- [[GOOGLE_EMBEDDING_API_KEY â€” 768-dim Embedding Config]] - code - backend/src/config/env.ts
- [[Il Platinatore AI â€” Gaming Guide Chatbot]] - document - README.md
- [[JWT + CSRF Auth Secrets]] - code - backend/src/config/env.ts
- [[RAG Configuration Variables]] - code - backend/src/config/env.ts
- [[RAG Pipeline Architecture (Hybrid HNSW + RRF)]] - document - README.md
- [[Rate Limit Configuration Variables]] - code - backend/src/config/env.ts
- [[Scraper Service Bootstrap (Fase 15)]] - code - scraper/src/index.ts
- [[Stripe Payment Configuration (ProPlatinum tiers)]] - code - backend/src/config/env.ts
- [[Technology Stack Overview]] - document - README.md
- [[WordPress API Config (WP_API_URL, App Password, Webhook Secret)]] - code - backend/src/config/env.ts
- [[Zod Environment Schema]] - code - backend/src/config/env.ts
- [[loadEnv() Boot-time Validation]] - code - backend/src/config/env.ts

## Live Query (requires Dataview plugin)

```dataview
TABLE source_file, type FROM #community/Backend_Env_Config
SORT file.name ASC
```

## Connections to other communities
- 2 edges to [[_COMMUNITY_DB Pool + Express Entry]]
- 1 edge to [[_COMMUNITY_Project Rules + Migration Policy]]

## Top bridge nodes
- [[Zod Environment Schema]] - degree 9, connects to 1 community
- [[Rate Limit Configuration Variables]] - degree 3, connects to 1 community
- [[loadEnv() Boot-time Validation]] - degree 2, connects to 1 community