# simpleproxy-function

Generated from core repo commit 088a881c6278c6df6a7e3f33f2ea7ff110a21e44.

Entrypoint: src/runtime/runtime_entry.js
Deploy: npx wrangler deploy

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/codenada/simpleproxy-function)

Default: Cloudflare one-click deploy (button above).
Platform adapter default is Cloudflare via `src/platform/index.js`.

You can replace adapter wiring and use any deployment pipeline in your own repo.

Cloudflare Import-Repo settings (recommended default):
- Build command: (leave blank)
- Deploy command: npx wrangler deploy
- Root directory: /
