# nestmail

Minimal disposable temporary-email website. Static site (HTML/CSS/JS) — no build step.

## Run locally
Open `index.html` in a browser, or run `npx serve .`

## Deploy
Import this repo in Vercel (Framework Preset: **Other**, no build command, output directory blank).

## Connect a real mail backend
The inbox is simulated. Edit the `api` object in `index.html` (`newAddress()` and `fetchMessages()`) to call a real service such as mail.tm, or your own Cloudflare Email Routing + Worker.
