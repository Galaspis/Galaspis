# Hi, I'm Gal

I'm a hands-on digital marketer who got deeply excited about AI and started building with it.
After 15+ years in marketing, websites, SEO, PPC, automation and marketing technology, I began using AI tools to turn ideas into real working products. I work daily with Claude Code, and over the last year that turned into a set of apps my family and I use every day, running on a server I set up and operate myself.

This GitHub shows a selection of that work: a self-hosted platform of small apps, marketing and SFMC utilities, AI agents and a few productivity tools.

## gallab.top: a self-hosted platform of everyday apps

The apps below run on one Linux VPS (OVHcloud) that I provisioned and maintain:

- **Docker** containers per app, **Caddy** as reverse proxy with automatic HTTPS, one subdomain per tool
- **Single sign-on** with Google: every site sits behind the same login
- **Push-to-deploy**: a push to each repo's default branch runs a GitHub Actions workflow that syncs the code, rebuilds the container, installs the Caddy site and runs a smoke test
- Self-hosted on a small VPS over a private network, with app data backed up
- A hub page with tiles, health checks and a shared JSON document store that static tools use instead of browser storage, so phone and PC stay in sync

The hub itself stays private, but every app on it is open below.

## Projects

| Project | What it is | Stack |
|---------|-----------|-------|
| [carpenters-plans](https://github.com/Galaspis/carpenters-plans) | **Woody**: parametric furniture designs turned into IKEA-style build plans: 3D views, numbered parts, cut plan, shopping list, cost estimate. Hebrew, RTL, PWA | Vanilla JS, three.js, SVG |
| [Renewal_agent](https://github.com/Galaspis/Renewal_agent) | **Renewals**: forward a policy email or PDF, an LLM extracts the details, reminders go out before each deadline. Switchable Claude / OpenAI / Gemini | Next.js, TypeScript, SQLite, Docker |
| [kort](https://github.com/Galaspis/kort) | **Kort**: share an Instagram reel or Facebook post, get a clean Hebrew recipe with ingredients, shopping list and cooking mode | Expo (React Native), Node, Postgres, yt-dlp, ffmpeg, Claude |
| [cv-workbench](https://github.com/Galaspis/cv-workbench) | **CV Workbench**: resume studio with templates, one-page PDF export, job-description tailoring and ATS scoring | React, TypeScript, Vite |
| [digital-marketing-tools](https://github.com/Galaspis/digital-marketing-tools) | **Shivuk**: a marketing lab hub: SEO keyword research with live volumes and CPC, a Meta Ads agent with guard rails, a social publisher with approvals, per-run cost tracking | Node, Python, Claude, OpenAI |
| [mc-journey-builder](https://github.com/Galaspis/mc-journey-builder) | SFMC journey simulator: model and validate Journey Builder configs before production | HTML, JS |
| [crm-ai-agents](https://github.com/Galaspis/crm-ai-agents) | AI agent pipeline: CRM segmentation, A/B email writing, a 4-agent CrewAI crew | Python, CrewAI |
| [webapp-budget-tool](https://github.com/Galaspis/webapp-budget-tool) | Personal finance dashboard: upload bank CSVs, track spending by category | FastAPI, React, SQLite |
| [research-capture-extension](https://github.com/Galaspis/research-capture-extension) | Chrome extension that captures web research into Google Sheets, with optional AI extraction | JavaScript |
| [math-app](https://github.com/Galaspis/math-app) | Multiplication table practice for kids | Vanilla JS web app |

## What I build

Most of what I make starts at home. Someone in the family says "I wish there was a way to..." and a few evenings later there is: a recipe app so we stop screenshotting reels, a reminder tool so no insurance renews by surprise, a plan generator so the garden bench actually gets built. Hebrew first, phone first, and used every day, which is the only test that matters to me.

The other half comes from work. Fifteen years in marketing left me with a long list of things I wished existed, and AI finally made it practical to build them myself: SFMC utilities, keyword research with real numbers, agents that draft and segment but never act without approval.

Along the way I learned to run the whole thing: a server, Docker, HTTPS, single sign-on, automated deploys. Not because I love infrastructure, but because I wanted my apps to be real, reachable from any device, and still working months later.

## Stack

`TypeScript` `Next.js` `React` `React Native / Expo` `Node.js` `Python` `FastAPI` `SQLite` `Postgres` `Docker` `Caddy` `GitHub Actions` `Tailscale` `Claude API` `OpenAI API` `CrewAI` `Salesforce Marketing Cloud`

