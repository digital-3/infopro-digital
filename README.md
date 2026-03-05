# infopro-digital — EMCORE Autonomous Marketing Agency

Funnels, landing pages and digital product assets for Hotmart.
Auto-deployed by JARVIS COO via JAMStack pipeline.

## Structure
- `/funnels/{slug}/` — Squeeze pages, VSL pages, Bridge pages
- Each funnel pre-wired with n8n webhook for lead capture
- Auto-deploys to Vercel on every push

## Tech Stack
- HTML + Tailwind CSS (zero runtime)
- n8n Webhooks for lead capture
- Supabase for CRM data (via Mission Control Dashboard)

---
*Powered by EMCORE Quantum v6.0*