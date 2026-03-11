# simpleproxy-function

Generated from core repo commit 71e043b7a59e3f9b0d1e8e8bae598138aa0bcfb0.

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
