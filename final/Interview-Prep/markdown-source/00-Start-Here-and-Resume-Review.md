# 00 — Start Here + Final Resume Review

**Candidate:** Sandeep Lodhi | **Target role:** Node.js Backend Developer (MERN) | **Experience:** almost 4 years (Feb 2023 – today)

This folder is your complete interview kit. It is built from your final resume and everything inside your `about-me` folder (project notes, intros, HR notes, career journey, resume drafts).

---

## 1. Files in this kit and the order to read them

| # | File | What it gives you | When to read |
|---|---|---|---|
| 00 | Start Here + Resume Review | Study plan, resume fixes, golden rules | First |
| 01 | Self Introduction | 30-sec, 1-min, 2-min and backend-focused intros | Day 1, practise daily |
| 02 | HR Questions & Answers | 45+ HR questions with ready answers | Day 2 |
| 03 | Company-wise Experience | All 4 companies: what, role, work, why left | Day 2 |
| 04 | Project Explanations | Every resume project in a simple 5-step format | Day 3 |
| 05 | Education & Personal | College, school, family, hometown, hobbies | Day 3 |
| 06 | Role & Tech Stack Q&A | Node.js, Express, DB, Redis, AWS, Docker, security, system design | Day 4–5 |
| 07 | Experience & Scenario (STAR) | Real stories: challenges, conflict, production bugs, leadership | Day 6 |
| 08 | Tricky Questions, Salary, Closing | Gaps, job changes, salary, notice period, questions to ask | Day 6 |
| 09 | Last 30 Minutes Cheat Sheet | One-page revision before the interview | Interview day |

---

## 2. 7-day study plan

| Day | Task | Practise out loud |
|---|---|---|
| 1 | Read 01. Record yourself saying the 1-minute intro on your phone. | Intro 5 times |
| 2 | Read 02 and 03. Learn the "why did you leave" line for every company. | Company journey in 2 minutes |
| 3 | Read 04 and 05. For each project remember: Problem → What I built → Stack → Challenge → Result. | Explain 3 resume projects |
| 4 | Read 06 sections A to E (JavaScript, Node, Express, API, Auth). | 20 questions without reading |
| 5 | Read 06 sections F to K (Databases, Redis, AWS, Docker, CI/CD, System design). | Draw one architecture on paper |
| 6 | Read 07 and 08. Prepare your salary number and notice period. | 5 STAR stories |
| 7 | Mock interview with a friend. Then read 09. | Full mock, 45 min |

---

## 3. Golden rules for speaking in the interview

1. **Speak slowly and simply.** Short sentences are better than long ones. Pause after each point.
2. **Always use this order for any project or story:** Problem → What I did → Tech used → One challenge → Result (with a number).
3. **Use numbers.** 45+ reports, 50 million+ rows, 92 seconds to 300 ms, 30% faster, 40% faster deployment.
4. **Say "I", not "we", for your own work.** Use "we" only for team work.
5. **Only claim what you can explain.** If a skill is on your resume, expect a question on it.
6. **If you don't know, say so honestly.** "I haven't used that in production, but I have used X which solves a similar problem…"
7. **Connect every technical answer to your project.** "In my Hospital CRM, I did this…" sounds much stronger than a textbook answer.

---

## 4. Review of your final resume (important — read before applying)

Your final resume is clean, one page, ATS-friendly and well structured. These are the points to fix or prepare for:

### Must fix

| # | Issue | Why it matters | Suggested fix |
|---|---|---|---|
| 1 | The file is named "Backend Developer" but the title on the resume says **MERN Stack Developer**. | Recruiters searching for Node.js Backend roles match on the title. | Change the title to **"Node.js Backend Developer (MERN)"** and start the summary with backend words. |
| 2 | Atiya bullet says **"Managed Cloudflare hosting"**. Your project notes show deployment on **Cloudways** (PM2 + Apache). | If the interviewer asks about Cloudflare (DNS, CDN, WAF) and you used Cloudways, it looks wrong. | Write "Cloudways (PM2 + Apache)" or keep Cloudflare only if you really managed Cloudflare DNS/SSL. |
| 3 | Atiya bullet says **"WebRTC-based video consultation"**. Your Atiya project notes do not show WebRTC code. | WebRTC questions are deep (STUN, TURN, signaling, SDP). | Keep it only if you built it. Your astrology project at MSAI had audio/video calls, so you can talk about WebRTC concepts from there. Prepare file 06 section L. |
| 4 | Hospital Appointment CRM says "using **MERN stack** and SQL". That CRM uses **SQL Server**, not MongoDB. | A sharp interviewer will notice "MERN" with no MongoDB. | Write "Node.js, Express, React and SQL Server". |
| 5 | Old resumes list **House of VSB (Sep 2023 – Feb 2024)** and MSAI from **Mar 2024**. The final resume shows **MSAI Aug 2023 – Oct 2024**. | Background verification (BGV) checks offer letters, relieving letters, PF/UAN and Form 16. | Make sure the dates on the final resume match your documents exactly. Keep the same story in every interview. |

### Strongly recommended for a backend resume

Your best backend achievements are in your Atiya projects but are **missing** from the resume. Add 2–3 of these bullets under Atiya Healthcare:

- Optimised a slow SQL Server report query from **~92 seconds to ~300 ms** by bypassing a per-row view and adding targeted indexes.
- Built a BI reporting platform with **45+ reports** over **50M+ row** PostgreSQL and SQL Server tables, using an ETL sync into a local read-model, Redis caching and BullMQ workers.
- Built a cron-based automation service that detects dropped calls every 30 minutes and pushes them to dialer campaigns for auto call-back, with dry-run and re-entrancy guards.
- Designed a 3-tier cache (in-memory LRU → Redis → SQLite → PostgreSQL) that cut patient call-history lookups from minutes to milliseconds.
- Secured APIs with JWT, email OTP two-factor login, permission-based RBAC, Joi validation, Helmet and rate limiting.

### Suggested backend summary (copy-paste)

> Node.js Backend Developer with almost 4 years of experience building scalable REST APIs, background jobs and data-heavy systems with Node.js, Express, MongoDB, PostgreSQL, SQL Server and Redis. Experienced in query optimisation (92 s → 300 ms), queues (BullMQ, RabbitMQ), real-time systems (Socket.IO), serverless (AWS Lambda) and production deployment (Docker, PM2, NGINX, IIS, CI/CD). Delivered projects for clients in Israel, Spain, USA and Australia.

### Other small points

- You have two resume files (3+ years and 4 years) that are almost identical. Keep one so you don't send the wrong one.
- Experience from Feb 2023 to Oct 2026 is about **3 years 8 months**. "Almost 4 years" or "3.8 years" is safest in the interview. Don't say "more than 4 years".
- Skills like **Nest.js, Prisma, Microservices, OAuth, Kubernetes** are listed. Prepare at least the basic questions for each (file 06 has them).
- TorahAnytime stack on the resume says MySQL, Redis, AWS, Docker. Your notes also mention RabbitMQ, tRPC, ClickHouse, RethinkDB, DigitalOcean, Kubernetes. Be ready to explain where each was used, or don't mention it.
- Your notes put the **PDF editor** under Perk in some files and ShowTrail in others. Pick the correct one and keep it the same everywhere.

---

## 5. Your story in one line (memorise)

> "I'm a Node.js backend developer with almost 4 years of experience. I started with SQL and jQuery at Shaligram, built full MERN products at MSAI, learned AWS serverless and DevOps at Morpheme while leading an Israeli client project, and now at Atiya Healthcare I build and deploy backend systems for a large healthcare call centre — CRM, WhatsApp automation, reporting and automation jobs."
