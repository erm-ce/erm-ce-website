# erm-ce-website

> Marketing & landing page for ERM-CE — Community Edition

## Overview
Static HTML/CSS/JS marketing site served by the ERM-CE backend at `/`.
No build step needed — it's a single `index.html`.

## Features Showcased
- Whinston Vision Engine (AI moderation)
- Watchdog (automated passive moderation)
- Departments, Applications, Documents
- Infractions, Sessions, Verification
- Shift Logging, Activity Monitoring, ER:LC Integration

## Deployment

### Serve via ERM-CE Bot (recommended)
Drop `index.html` into `webgui/` in the bot repo. It's automatically served at `http://your-host:8080/`.

### Serve standalone (any static host)
```bash
# Nginx, GitHub Pages, Netlify, Cloudflare Pages — just host index.html
```

## Editing
All content, colors, and copy are in `index.html`. Key CSS variables at the top of `<style>`:
```css
--accent:  #4f8ef7;   /* Primary blue */
--accent2: #a78bfa;   /* Purple */
--accent3: #34d399;   /* Green */
```
