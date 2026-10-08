# 03 — Company-wise Experience (what, role, work, why left)

For each company, remember 5 things: **What the company does → My role → What I worked on → What I learned → Why I moved.**

| Company | Role | Dates (as on final resume) | Location | One-line summary |
|---|---|---|---|---|
| Atiya Healthcare Pvt. Ltd. | MERN Stack Developer (backend focus) | Aug 2025 – Present | Karol Bagh, Delhi | Healthcare call-centre CRM, WhatsApp automation, reports, automation jobs |
| Morpheme Webnexus Pvt. Ltd. | MERN Stack Developer | Nov 2024 – Jul 2025 | Greater Noida | AWS Lambda serverless, CI/CD, led TorahAnytime, built BikeShopShippers |
| AB MSAI Research Labs Pvt. Ltd. | MERN Stack Developer | Aug 2023 – Oct 2024 | New Delhi | Astrology platform R&D, ThePNAC.com end to end, US "OD" project |
| Shaligram Infotech | Software Developer | Feb 2023 – Aug 2023 | Ahmedabad | Foundation: JavaScript, jQuery, Bootstrap, MS SQL Server |

> **BGV warning:** these dates must match your offer letters, relieving letters and PF/UAN records. Older resume drafts showed different dates and a "House of VSB" role. Use one consistent story.

---

## 1. Atiya Healthcare Pvt. Ltd. (current)

**What the company does**
> "Atiya Healthcare is a healthcare tele-consultation company. It runs clinics, a large call centre using the Ameyo dialer, and online medicine orders with courier delivery. Patients book clinic appointments through call-centre agents."

**My role**
> "I'm a MERN stack developer with a strong backend focus. I'm the main owner of the new Node.js systems — I gather requirements from managers, design APIs and queries, build backend and frontend, deploy, and support in production."

**What I worked on**

| Application | What it does | Key backend work |
|---|---|---|
| Hospital Appointment CRM | Agents book and manage clinic appointments inside the dialer. Replaced a legacy ASP.NET app. | Express 5, SQL Server (2 DBs), 47 API modules, Ameyo + WhatsApp + SMS integration, RBAC, IIS deployment |
| WhatsApp Automation Platform | Real-time shared WhatsApp inbox for agents | Exotel webhooks → MongoDB → Socket.IO, multi-number routing, retries with backoff, Cloudways + PM2 |
| ViewReports (BI platform) | 45+ call-centre reports | ETL sync from 50M+ row tables, Redis, BullMQ worker, JWT + OTP, Excel export guards |
| QMS (quality monitoring) | Full audit of one call + recording playback | Query from 92 s to 300 ms, audio streaming proxy with HTTP Range |
| Patient-CRM | Call history of a patient in one search | 3-tier cache: LRU → Redis → SQLite → PostgreSQL |
| CallDropAutoDial | Auto call-back of dropped calls | node-cron every 30 min, DRY_RUN flag, re-entrancy guard |

**What I learned**
> "End-to-end ownership, working with large legacy databases, query optimisation, caching strategies, background jobs, and Windows IIS deployment with iisnode."

**Why are you looking for a change?**
> "At Atiya I've owned complete systems, and I'm proud of that. Most of the time I'm the only developer on these codebases. Now I want to work in a bigger engineering team, with code reviews and larger-scale products, so I can grow faster as a backend engineer."

**Possible questions**
- *"How big is the team?"* → "I'm the main developer for these Node.js apps. I work with call-centre managers, QA, the IT team and seniors for decisions."
- *"Are these apps live?"* → "Yes. The CRM, reports, QMS and automation jobs run on Windows IIS internally; the WhatsApp platform runs on Cloudways."

---

## 2. Morpheme Webnexus Pvt. Ltd.

**What the company does**
> "Morpheme Webnexus is a SaaS and custom web development company. It builds products for international clients in the US, Israel, Spain and Australia."

**My role**
> "MERN stack developer. I started with serverless backend tasks and grew into leading a client project."

**What I worked on**

| Project | Domain | My work |
|---|---|---|
| **PERK** | Event management | Serverless CRUD APIs on AWS Lambda with TypeScript; PDF-to-image conversion; custom PDF editor for event layout maps (stalls, gates, routes); multi-role users |
| **Nosotros** | LMS for Spanish schools | Set up CI/CD with Bitbucket Pipelines; integrated Sentry (errors) and Codecov (test coverage); Jira and Slack notifications; worked on tickets |
| **FamilyOne** | Family discount network | Optimised Lambda functions; wrote serverless YAML configs for scaling; load tested APIs with JMeter; integrated Sentry and Codecov |
| **ShowTrail** | Coupon promotion (same admin as FamilyOne) | Trained Intercom AI workflows for customer support chatbot |
| **SmartBiz** | B2B onboarding | APIs and UI for dynamic forms per business sector (finance, medical, toys, technology) |
| **TorahAnytime** | Media + donation platform (Israel client) | Led the project: assigned tickets, reviewed and merged PRs, deployed to production; built features like likes, editable playlists, legacy speakers, most-viewed filter |
| **BikeShopShippers** | Logistics | Built from scratch on Medusa.js: UPS (rates, labels, tracking), Stripe payments, Google address autocomplete, CI/CD with GitHub Actions |

**Resume impact line:** "Improved deployment efficiency by 40% using AWS Lambda and CI/CD workflows."
*How to explain 40%:* "Before CI/CD, deployments were manual and took long, with mistakes. After pipelines with automated tests and deploy steps, release time dropped by about 40% and failed releases reduced."

**What I learned**
> "AWS serverless, TypeScript, CI/CD, monitoring with Sentry, load testing, Docker, and leading a project with code reviews."

**Why did you leave?**
> "I learned a lot at Morpheme, especially AWS and DevOps. But most work was short client projects. I wanted to work on long-term products where I own the system end to end. Atiya gave me that — complete ownership of backend systems used daily."

---

## 3. AB MSAI Research Labs Pvt. Ltd.

**What the company does**
> "AB MSAI Research Labs is an AI and software solutions company in Delhi that builds web platforms for clients."

**My role**
> "MERN stack developer."

**What I worked on**
- **Astrology platform (from scratch):** "I did more than 70% of the R&D. I defined the tech stack — backend, frontend, database — and integrated a third-party astrology API (Prokerala) for kundli making, kundli matching, horoscope and baby names. I built chat, audio and video call features for astrologer–user consultation, and built the first prototype of backend and frontend."
- **ThePNAC.com:** "An individual project I built from scratch to end — backend, frontend, database, fully responsive — and deployed on the company server using PM2 and NGINX."
- **OD (US-based project):** "I supported the team in validating services and setting access permissions for visitor data, and worked on responsive UI."

**Resume impact lines:** engagement +20% and user experience +30% through responsive UI.
*How to explain:* "After the responsive redesign, mobile users stayed longer and bounce rate dropped. The client reported around 20% more engagement."
*(Only quote numbers you can support. If asked "how did you measure it?", say "from Google Analytics reports shared by the client/manager".)*

**What I learned**
> "Building a product from zero, choosing a tech stack, third-party API integration, real-time features, and deploying on a Linux server with PM2 and NGINX."

**Why did you leave?**
> "The main project was completed and handed over to the client. After that, the company changed focus and the development team was released. It was a great learning experience."

---

## 4. Shaligram Infotech (first job)

**What the company does**
> "Shaligram Infotech is an IT services company in Ahmedabad that builds web applications for clients."

**My role**
> "Software developer — my first job after college."

**What I worked on**
> "I worked on web applications using HTML, CSS, JavaScript, jQuery, Bootstrap and MS SQL Server. I wrote stored procedures and queries, built APIs, and fixed performance issues. I improved some API response times by around 30% and SQL query performance by around 20% using indexes and better queries."
> "To strengthen my MERN skills, I also built a Real Estate platform and an E-commerce platform using React, Node.js, Express and MongoDB."

**What I learned**
> "Strong basics — SQL, JavaScript, debugging, working in a professional team, and using Git."

**Why did you leave?**
> "After training, the company's requirement changed and they wanted to move me to a non-development role like manual testing and UI work. I wanted to grow as a developer, so I moved to a MERN developer role at MSAI."

---

## 5. Common questions about your companies

**"Walk me through your career." / "Explain your job switches."**
> "Shaligram was my first job where I built foundations. I moved because the role was changing away from development. At MSAI I built full products, and moved when the project was handed over to the client. At Morpheme I learned AWS and DevOps and led a client project. I moved to Atiya to own complete products. Every move gave me a bigger responsibility."

**"Which company did you learn the most in?"**
> "Technically, Atiya — because I own everything, from database queries to deployment. For teamwork and cloud, Morpheme."

**"Which company did you like the most?"**
> "Each had something good. Morpheme had great international exposure; Atiya gave me ownership. I liked the learning in both."

**"Did you work with international clients?"**
> "Yes. At Morpheme with clients from Israel (TorahAnytime), Spain (Nosotros LMS), the US and Australia. I attended calls, understood requirements in English, and worked across time zones using Slack, Jira and GitHub."
