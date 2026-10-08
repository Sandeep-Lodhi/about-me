# 09 — Last 30 Minutes Cheat Sheet

## My one-liner
"Node.js backend developer, almost 4 years, Node + Express + MongoDB/SQL + Redis, healthcare CRM and WhatsApp automation at Atiya, AWS serverless and TorahAnytime lead at Morpheme."

## Career in 4 lines
| Company | Dates | One line | Why left |
|---|---|---|---|
| Shaligram Infotech | Feb 2023 – Aug 2023 | JS, jQuery, MS SQL foundation; API +30%, SQL +20% | Role moving away from development |
| AB MSAI Research Labs | Aug 2023 – Oct 2024 | Astrology platform R&D (70%), ThePNAC.com end to end | Project handed to client, team released |
| Morpheme Webnexus | Nov 2024 – Jul 2025 | AWS Lambda, CI/CD, led TorahAnytime, built BikeShopShippers | Wanted full product ownership |
| Atiya Healthcare | Aug 2025 – now | CRM, WhatsApp platform, reports, automation; deploy on IIS/Cloudways | Want a bigger team and larger scale |

## Education
B.Tech CSE, TIT Bhopal (RGPV), 2019–2023, **CGPA 8.7**. 10th and 12th from Lalitpur, **76%** each.

## Resume projects in one line each
- **TorahAnytime:** Israeli media + donation platform; lead: tickets, PR review, deploys; likes, playlists, most-viewed; Node, MySQL, Redis, Docker, AWS.
- **Hospital Appointment CRM:** ASP.NET → Node + React on SQL Server; 47 API modules; 463 generated models; Ameyo, WhatsApp, SMS; IIS; ~30% faster.
- **BikeShopShippers:** Medusa.js + PostgreSQL; UPS rates/labels/tracking; Stripe with webhooks; GitHub Actions CI/CD.
- **WhatsApp Platform:** Exotel webhooks → MongoDB → Socket.IO; multi-number routing; idempotent upsert by message ID; PM2 on Cloudways.

## Numbers to drop
92 s → 300 ms · 45+ reports · 50M+ rows · 47 API modules · 463 models · 8 apps at Atiya · 16 dynamic forms · 30% faster processing · 40% faster deployments · 4 countries of clients

## 5 STAR stories (titles only)
1. Query 92 s → 300 ms (performance)
2. Event loop freeze in ViewReports (production issue)
3. 460+ table legacy migration (achievement)
4. Empty data from hourly ETL table (mistake learned)
5. Leading TorahAnytime (leadership)

## Tech one-liners
- **Event loop:** sync code → microtasks (nextTick, promises) → macrotasks (timers, I/O).
- **Don't block the loop:** heavy CPU → worker thread or queue.
- **Layered API:** routes → validation → controller → service → repository.
- **Indexes:** ESR rule (Equality, Sort, Range); check with explain.
- **Keyset pagination:** `WHERE id > last ORDER BY id LIMIT n`.
- **Cache-aside:** read cache → miss → DB → set with TTL; fall back if Redis is down.
- **Retry:** only network / 5xx / 429, exponential backoff, never on 4xx.
- **Webhook:** public route, verify signature, respond fast, idempotent upsert.
- **JWT:** short access + long refresh; bcrypt passwords; RBAC middleware.
- **Scale Node:** stateless + more instances + load balancer + Redis + queues.
- **Socket.IO scale:** Redis adapter + sticky sessions.
- **Lambda cold start:** smaller bundle, reuse connections, provisioned concurrency.
- **Docker:** copy package.json first for layer cache; `npm ci --omit=dev`.
- **iisnode:** PORT is a named pipe — never parseInt.

## Honesty rules
- Say exact experience if asked: about 3 years 8 months.
- Only claim what you can explain (WebRTC, Kubernetes, Nest.js — know your level).
- If you don't know: "I haven't used it in production, the closest I've done is…"

## Questions to ask them
1. What does the backend architecture and deployment pipeline look like?
2. What would success look like in the first 90 days?
3. What's the biggest technical challenge the team is facing now?

## Before you join the call
- [ ] Resume PDF open, same version you sent
- [ ] Water, charger, quiet room, camera at eye level
- [ ] Company research: product, customers, tech stack
- [ ] Current CTC, expected CTC and notice period ready
- [ ] Breathe slowly. Speak slowly. Smile.
