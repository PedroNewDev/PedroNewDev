# Pedro Farias

Full-stack developer in São Mateus do Sul, Brazil. I build SaaS platforms,
internal tools and conversion-focused web apps — and run the Linux
infrastructure they ship on.

Contact: [pedroalbuquerquedefarias@gmail.com](mailto:pedroalbuquerquedefarias@gmail.com)
— open to freelance projects and full-time roles.

## Featured projects

### [Conferente](https://github.com/PedroNewDev/conferente) — automated invoice reconciliation

Mini-SaaS for purchasing, inventory and accounts payable. Its core is an
unattended pipeline: it receives Brazilian electronic invoices (NF-e) over
IMAP, validates the XML, reconciles each item against the purchase order,
blocks divergences and posts the effects to inventory and finance — no human
in the loop. Role-based access, scheduled runs and PDF reporting included.

**Try it live, no login:** [conferente-neon.vercel.app](https://conferente-neon.vercel.app)
— the demo seeds a clean database with 15 test invoices per visitor, so you
can run the full cycle from scratch.

`Python` · `FastAPI` · `SQLAlchemy 2` · `PostgreSQL` · `Alembic` · `APScheduler` · `Docker Compose`

### [WebGenios Command Center](https://github.com/PedroNewDev/Cronograma-Webgenios) — task management product

Replaced an agency's Google Sheets workflow with a real product: kanban with
drag-and-drop, structured review stages and realtime updates, with AI features
built on the Anthropic SDK.

`Next.js 15` · `React 19` · `TypeScript` · `Tailwind v4` · `Drizzle ORM` · `TanStack Query` · `dnd-kit` · `Docker`

## Client work (private)

Most of my code is private client work — source stays confidential, but I'm
happy to walk through the architecture of any of these in a conversation:

- **SaaS platform** — Next.js 14 + Supabase: server-side auth, realtime
  subscriptions, Playwright E2E coverage.
- **PWA with payments** — Node.js backend, offline-first service worker,
  payment webhooks, transactional email via Brevo.
- **Multi-tier web app** — Express + MySQL behind Nginx, JWT auth, independent
  api/backend/database/frontend layers.
- **Landing pages** — Next.js and Vite + React, static builds tuned for Core
  Web Vitals, deployed to self-managed VPS infrastructure.
- **Discord analytics bot** — Python (discord.py), cogs architecture, runs as
  a systemd service.

## Stack

- **Frontend:** TypeScript, React, Next.js (App Router), Tailwind CSS, Framer Motion, Vite
- **Backend:** Node.js, Express, Python, FastAPI, REST APIs
- **Data & auth:** PostgreSQL (Supabase), MySQL, SQLAlchemy, Drizzle ORM, JWT, better-auth
- **Infra:** Docker, Nginx, Cloudflare, Linux VPS administration

## Study projects

- [projeto-extensao](https://github.com/PedroNewDev/projeto-extensao) — full-stack college project (Node + Express)
- [Conex-o-API](https://github.com/PedroNewDev/Conex-o-API) — REST API exercise
- [ProjetoPessoal](https://github.com/PedroNewDev/ProjetoPessoal) — CSS layout and animation experiments
- [Atividade-docker](https://github.com/PedroNewDev/Atividade-docker) / [Luis-docker](https://github.com/PedroNewDev/Luis-docker) — Docker exercises
