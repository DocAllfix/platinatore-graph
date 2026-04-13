---
source_file: "backend/src/config/env.ts"
type: "code"
community: "Environment & API Config"
location: "const envSchema"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Environment_&_API_Config
---

# Zod Environment Schema

## Connections
- [[GEMINI_API_KEY â€” LLM Integration Config]] - `implements` [EXTRACTED]
- [[GOOGLE_EMBEDDING_API_KEY â€” 768-dim Embedding Config]] - `implements` [EXTRACTED]
- [[JWT + CSRF Auth Secrets]] - `implements` [EXTRACTED]
- [[RAG Configuration Variables]] - `implements` [EXTRACTED]
- [[Rate Limit Configuration Variables]] - `implements` [EXTRACTED]
- [[Rule Zod Input Validation + Prepared Statements]] - `conceptually_related_to` [INFERRED]
- [[Stripe Payment Configuration (ProPlatinum tiers)]] - `implements` [EXTRACTED]
- [[WordPress API Config (WP_API_URL, App Password, Webhook Secret)]] - `implements` [EXTRACTED]
- [[loadEnv() Boot-time Validation]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Environment_&_API_Config