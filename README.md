# Hush Machine

Calm noise machine and wake-up alarm for yeete.ai. One self-contained `index.html`, no build step, no audio files: every sound is synthesized in the browser (in a Web Worker).

- Live URL (once deployed): https://yeete.ai/hush-machine/
- Hosting: Hostinger Git auto-deploy, branch `main` → `public_html/hush-machine`
- Apps shelf: card in `apps.html` + row `hush-machine` in Supabase `app_registry` (see `registry.sql`)

## Update
Edit `index.html`, commit, push to `main`. Hostinger redeploys within about a minute.

## Before launch
- The Tip $1 button points to a Stripe **test-mode** link. Swap in a live Payment Link before taking real tips.
