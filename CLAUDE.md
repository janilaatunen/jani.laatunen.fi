# CLAUDE.md — jani.laatunen.fi

Personal portfolio website.

## Tech Stack

- Pure HTML/CSS, no build system
- Variable fonts: Raleway, Lora (Google Fonts)
- Structured data with JSON-LD
- OpenGraph + Twitter Card metadata

## Development

No build step — edit files directly and open in browser.

## Deployment

Hosted on atk VPS (UpCloud Helsinki, `ssh atk`). Auto-deploys via GitHub webhook on push to main.

- Site root on server: `/var/www/static/jani.laatunen.fi`
- Deploy script: `/var/www/static/deploy-jani-laatunen-fi.sh`
- Webhook URL: `https://jani.laatunen.fi/webhook`
- nginx config: `/etc/nginx/sites-available/laatunen.fi`

See atk server memory for full webhook setup details.

## Git

Identity: personal (`jani@laatunen.fi` / janilaatunen)

## Rules

- Never increment version numbers without explicit confirmation
