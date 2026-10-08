# 02 — HR Questions and Answers

HR wants to know three things: **Can you do the job? Will you stay? Will you fit in the team?** Every answer should support one of these.

Keep each answer 30–60 seconds. Be positive. Never criticise a past company or manager.

---

## A. About you

**1. Tell me about yourself.**
Use the HR version in file 01, section 4.

**2. Describe yourself in three words.**
> "Responsible, hard-working and curious. Responsible because I own my work till production. Hard-working because I come from a farming family where I saw daily effort. Curious because I keep learning — from jQuery to AWS Lambda to queues and caching."

**3. What are your strengths?**
> "My first strength is ownership. At Atiya I handle features end to end — from requirement discussion to deployment and production support.
> My second strength is problem solving, especially performance problems. I brought a report query down from about 92 seconds to around 300 milliseconds.
> My third strength is adaptability. I've worked on healthcare, logistics, edtech, media and astrology projects, and with clients from four countries."

**4. What is your weakness?**
> "Earlier I used to take on too many tasks at once because I didn't like saying no. Sometimes it put pressure on deadlines. Now I break work into smaller tasks, give realistic timelines, and tell my manager early if something is at risk. It has improved my planning a lot."

*Other safe options:* "I sometimes spend extra time polishing code — now I time-box it." / "Public speaking — I'm improving by doing demos to stakeholders."

**5. How would your friends or colleagues describe you?**
> "As a hard-working and helpful person. Colleagues come to me for debugging help and deployment issues. Friends say I'm calm and fun-loving."

**6. What motivates you?**
> "Seeing my work used by real people. When call-centre agents use my CRM every day, or a manager gets a report in seconds instead of minutes, that motivates me."

**7. What are your hobbies?**
> "I play cricket, and I like guiding students who are starting in programming. I also like exploring new tech tools and reading about system design."

---

## B. About the job and company

**8. Why do you want to join our company?**
Research the company first (website, LinkedIn, Glassdoor, product). Then use this template:
> "I read that your company works on [product/domain]. Your stack — Node.js, [MongoDB/PostgreSQL/AWS] — matches my experience. I'm especially interested because [scale/product/clients]. I want to work in a strong engineering team on a product with real users, and this role is backend-focused, which is exactly where I want to grow."

**9. Why should we hire you?**
> "Three reasons. First, I have almost 4 years of hands-on Node.js backend experience — APIs, databases, queues, caching and deployment. Second, I've owned full projects in production, so I don't need hand-holding — I can take a requirement and ship it. Third, I've worked with international clients and different domains, so I adapt quickly. I'll be productive from the first few weeks."

**10. What do you know about our company?**
Prepare 4 points: what they build, who their customers are, tech stack (from job description), recent news or funding.

**11. Why are you looking for a change?**
> "I've learned a lot at Atiya — I own complete backend systems there. Now I want to work in a larger engineering team on a product at scale, with stronger code reviews and system design challenges. This role is backend-focused, which matches my long-term goal."

**12. Where do you see yourself in 5 years?**
> "In 5 years I see myself as a senior backend engineer or tech lead — someone who designs systems, mentors juniors and owns important services. I want to grow in system design, distributed systems and cloud. I'd like to do that growth within one company for the long term."

**13. What are your short-term and long-term goals?**
> "Short-term: join a good team, understand the product quickly and start delivering quality backend features. Long-term: become a strong backend architect who can design scalable systems and lead a team."

**14. How long will you stay with us?**
> "I'm looking for a long-term role. As long as I'm learning, growing and contributing, I don't see a reason to move. My goal is to grow into a senior role in the same company."

**15. What kind of work environment do you like?**
> "A team where people share knowledge, code is reviewed, and there is clear ownership. I'm comfortable in both fast-paced and structured environments."

---

## C. Working style and pressure

**16. Can you work under pressure?**
> "Yes. In production support at Atiya, when an issue affects agents during live calls, I have to fix it quickly. I stay calm, check logs first, find the root cause, apply a safe fix, and then document it. For example, when new code was not loading on IIS after deployment, I found that iisnode was not watching the source files, fixed the config and documented the restart steps."

**17. Are you a team player?**
> "Yes. At Morpheme I worked with cross-functional teams, and on TorahAnytime I coordinated developers — assigning tickets, reviewing PRs and helping them when they got stuck. Even at Atiya, where I'm the main developer, I work closely with call-centre managers, QA and the IT team."

**18. Can you work independently?**
> "Yes, that's one of my strengths. At Atiya I built 8 applications mostly on my own — from requirements to deployment. I also built ThePNAC.com and BikeShopShippers end to end."

**19. Are you comfortable working late or on weekends?**
> "Yes, when the work needs it — like a production issue or a release. I plan my work to avoid it regularly, but I'm committed when it's important."

**20. Are you willing to relocate?**
> "Yes, I'm open to relocation. I've already worked in Ahmedabad, Delhi and Greater Noida." *(Change if you are not open.)*

**21. Remote, hybrid or office?**
> "I'm comfortable with all three. I've worked remotely with international clients using Slack, Jira and Zoom, and I'm also comfortable in the office."

**22. How do you handle criticism?**
> "I take it positively. In code reviews, feedback helped me write cleaner code. I listen, ask questions if something is unclear, and improve. I don't take it personally."

**23. How do you handle a conflict with a colleague?**
> "I talk directly and calmly, focus on the problem and not the person, and use data. On one project there was a disagreement about retrying a dialer API automatically. I explained the risk — a retry could call a customer twice — and proposed a safer option. We agreed on it and I documented the decision."

**24. How do you prioritise when you have many tasks?**
> "First production issues, then deadline-based tasks, then improvements. I list tasks in Jira or a simple note, estimate them, and agree priorities with my manager when two things clash."

**25. How do you keep yourself updated?**
> "I follow Node.js release notes, read engineering blogs, watch system design videos and try new tools in small projects. For example, I learned BullMQ and Redis caching by using them in real projects."

---

## D. Achievements and failures

**26. What is your biggest achievement?**
> "Replacing the legacy ASP.NET CRM at Atiya with a Node.js and React system without changing the database. It had 460+ tables. I wrote a script that generated 463 model files from the SQL schema, which saved weeks of work. Today agents use it daily inside the dialer."

**27. Tell me about a failure.**
> "In one of my early projects, I kept environment files with credentials inside the repository to move faster. Later I realised it was a security risk. I learned from it — now I keep only a `.env.example` in git, inject secrets on the server, and rotate keys if they were exposed."

**28. Tell me about a mistake you learned from.**
> "Once I built a reporting feature that read data from a child table. Results were always empty for the last 30 minutes. I found that the table was filled by an hourly ETL job. I learned to always check how and when the source data is written before building on it. I switched to the live parent table and documented it."

**29. Have you ever led a team?**
> "Yes, on TorahAnytime at Morpheme. I assigned tickets, reviewed and merged pull requests, guided developers and handled production deployments for the Israeli client."

---

## E. Offer and joining

**30. What is your current CTC?**
> "My current CTC is [X] LPA fixed." *(Say the exact number. It will be checked with salary slips.)*

**31. What is your expected CTC?**
> "Based on my almost 4 years of experience, my backend skills and the market for this role, I'm expecting [Y] LPA. I'm open to discussion based on the overall offer and growth."
*Tip: research the range on Glassdoor/AmbitionBox for "Node.js developer 4 years" in your city. A 30–50% hike over current is normal for a switch.*

**32. What is your notice period?**
> "My notice period is [30/60/90] days. I can try to get early release if needed."

**33. Do you have any other offers?**
> If yes: "Yes, I have one offer, but this role is my first preference because [reason]."
> If no: "I'm in process with a few companies, but I'm most interested in this role."

**34. Why did you change companies so often?** → See file 08, it has a full answer.

**35. Are you overqualified for this role?**
> "I don't think so. I have the right experience to start contributing quickly, and there's still a lot I want to learn here, like [their tech/scale]."

---

## F. Classic "thinking" questions

**36. What is the difference between hard work and smart work?**
> "Hard work is putting in effort and time. Smart work is choosing the right method so the effort gives more results. For example, instead of hand-writing 463 model files, I wrote a script to generate them. Best results come from both together."

**37. What is the difference between confidence and overconfidence?**
> "Confidence is believing in yourself based on preparation. Overconfidence is believing you're right without preparation or ignoring risks. Confidence says 'I can do this'; overconfidence says 'I don't need to test this'."

**38. What is success for you?**
> "Success is when my work solves a real problem and people use it. Personally, it's growing every year and supporting my family."

**39. Who inspires you?**
> "My father. He's a farmer and works hard every day without complaining. He taught me discipline and patience."

**40. What makes you angry?**
> "I don't get angry easily. What disappoints me is careless work that breaks production — so I prefer clear processes and testing."

**41. Would you lie for the company?**
> "No. I'll always be loyal to the company, but honesty is important. I'll look for an honest solution that also protects the company."

**42. If you won a lottery, would you still work?**
> "Yes. I enjoy building software, and work gives me learning and purpose, not just money."

**43. What if we reject you?**
> "I'll take it as feedback, ask where I can improve, and work on it. I'd also like to apply again in the future."

**44. Rate yourself in Node.js out of 10.**
> "I'd say 7.5 out of 10. I'm strong in APIs, databases, async patterns, queues and deployment. I want to go deeper in Node internals and large distributed systems — that's what I'm working on."

**45. Do you have any questions for us?** — Always say YES. See file 08, section D.
