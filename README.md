# simpleproxy-function

Generated from core repo commit cf25ccad2aee1c70bb7540ea27b19a50976e9dcf.

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
