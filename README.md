# Granite Giving Initiative website

## What's in here
- `public/index.html` — the whole website (Home, About, Team, Our work, Contact, Gigi, Guides)
- `functions/api/claude.js` — the small server code that connects Gigi to Claude using your secret API key

## Cloudflare Pages settings
- Framework preset: **None**
- Build command: **(leave blank)**
- Build output directory: **public**
- Secret: `ANTHROPIC_API_KEY` (Settings > Variables and Secrets > type: Secret)

Never put the API key in any file in this repo.

## What's different from the test page
- Gigi's plans save in each visitor's browser.
- Volunteer sign-up pages and the contact form aren't connected yet (coming in a later update).
