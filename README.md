# Jong / 三浦宗民 — Portfolio

Static portfolio hosted on Cloudflare Workers.

Production URL: https://misty-unit-f4cc.jongminworks.workers.dev/

## Cloudflare Builds

- Production branch: main
- Root directory: repository root
- Build command: leave empty
- Deploy command: npx wrangler deploy

The Worker name is misty-unit-f4cc. Assets are served from public/.
Changes pushed to main are published after Cloudflare Git integration is connected.
Notebook updates require changing public/notebook.json; editor drafts are browser-local.
