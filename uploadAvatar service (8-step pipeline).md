---
source_file: "il-platinatore-ai/backend/src/services/avatar.service.ts"
type: "code"
community: "Community 56"
tags:
  - graphify/code
  - graphify/EXTRACTED
  - community/Community_56
---

# uploadAvatar service (8-step pipeline)

## Connections
- [[assertPathSafe (path traversal defense)]] - `calls` [EXTRACTED]
- [[avatarLimiter (1024h per user)]] - `rationale_for` [INFERRED]
- [[detectImageType (PNGJPEGWEBP magic bytes)]] - `calls` [EXTRACTED]
- [[uploadsRouter (POST apiuploadsavatar)]] - `calls` [EXTRACTED]

#graphify/code #graphify/EXTRACTED #community/Community_56