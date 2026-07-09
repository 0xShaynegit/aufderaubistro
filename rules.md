# PROJECT RULES aufderaubistro

Read before touching anything. These rules do not change between sessions.

## Project Identity
- Project Name: Auf der Au Bistro
- What it is: Static website for a bistro, migrated as a full-site export.
- Owner: Shayne
- Local folder: C:\ZZZWebsites\aufderaubistro

## Stack and Deploy
- Pure static HTML, CSS, JS. Pages live in pages/, scripts in scripts/.
- Deploy: Cloudflare Pages only. Never Vercel. wrangler.jsonc present for CLI deploys.
- sitemap.xml, robots.txt, humans.txt, llm.txt maintained. Keep them in sync when pages change.

## Hard Rules
- No dev servers unless explicitly requested.
- This is an export-based site: preserve existing URL structure, do not rename pages.
- 404.html must remain valid.
- Update handover.md at the end of every session.
