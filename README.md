# Action Board — Vanderbyl Labs

Personal productivity kanban board. Deployed at vanderbyllabs.com via Cloudflare Pages.

## Deploy
- Push `index.html` to GitHub
- Cloudflare Pages auto-deploys on push
- No build step required — pure static HTML

## Config (already set in index.html)
- Supabase URL + key hardcoded (publishable key, safe to commit)
- Each user signs up and gets their own private data row
- API keys (Anthropic, OpenAI) stored only in user's localStorage

## Password Reset
Hosted at: https://actionboard-reset.netlify.app
Supabase redirect URL configured to point there.
