# Dr. Raja Abdullah Raja Ahmad – Academic Profile

Live site: https://raja-abdullah-profile.raj-abdul88.workers.dev/

Static academic profile page for Dr. Raja Abdullah Raja Ahmad, Senior Lecturer, Faculty of Intelligent Computing, Universiti Malaysia Perlis (UniMAP).

## Files

- `index.html` – the whole site (HTML + CSS, no build step)
- `photo.jpg` – profile photo
- `wrangler.jsonc` – Cloudflare Workers static-assets config
- `.assetsignore` – files that are not published (README, config)

## Deployment

Hosted on Cloudflare Workers (static assets), connected to this repository. Every push to `main` redeploys the site automatically.

- Build command: (empty)
- Deploy command: `npx wrangler deploy`
