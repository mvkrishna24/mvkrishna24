<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1e1b4b,50:4c1d95,100:7c3aed&height=200&section=header&text=Martha%20Vamshi%20Krishna&fontSize=42&fontColor=ffffff&fontAlignY=32&desc=Backend%20Engineer%20%7C%20AI%20Systems%20%7C%20Distributed%20Infrastructure&descAlignY=52&descSize=16" />

<a href="https://mvkrishna.me">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3000&pause=800&color=A855F7&center=true&vCenter=true&width=650&lines=Backend+Engineer+%C2%B7+Java+%C2%B7+Spring+Boot+%C2%B7+Distributed+Systems;AI+%26+ML+Engineering+%C2%B7+Automation+%C2%B7+LLM+Pipelines;Production+SaaS+%C2%B7+4.13ms+p99+%C2%B7+99.98%25+Cache+Hit;Building+systems+that+survive+real+traffic." alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Hyderabad-India-4C1D95?style=flat-square&labelColor=1E1B4B&logo=googlemaps&logoColor=A855F7" />

<br/><br/>

<a href="https://mvkrishna.me">
  <img src="https://img.shields.io/badge/PORTFOLIO-mvkrishna.me-7C3AED?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://linkedin.com/in/krishna-mv-38380a2b3">
  <img src="https://img.shields.io/badge/LINKEDIN-Connect-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>
<a href="mailto:marthavamshikrishna1024@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-Reach%20Out-5B21B6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://github.com/mvkrishna24">
  <img src="https://img.shields.io/badge/GITHUB-Follow-4C1D95?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=mvkrishna24&label=Profile%20Views&color=7c3aed&style=flat-square" />
<img src="https://img.shields.io/github/followers/mvkrishna24?label=Followers&style=flat-square&color=7c3aed&labelColor=1E1B4B" />
<img src="https://img.shields.io/github/stars/mvkrishna24?label=Total%20Stars&style=flat-square&color=7c3aed&labelColor=1E1B4B" />

</div>

---

## About

I build backend systems that hold up under load, and AI pipelines that do real work instead of demos.

A working freelance engineer. My focus is the unglamorous half of software: cache strategy, rate limiting, migration safety, auth boundaries, p99 latency. I've shipped a distributed URL shortener sustaining **100 RPS at 4.13ms p99 with a 99.98% cache hit rate**, a **live production facility-management SaaS** serving gated communities across Andhra Pradesh, and an **AI-driven CRM automation pipeline deployed to a paying client**.

I work across the full stack — Java/Spring Boot services, Next.js frontends, PostgreSQL/Redis data layers, Docker + CI/CD delivery — but I think like a product engineer. Understanding revenue, retention, and what actually breaks in production made me a materially better engineer than any tutorial did.

**Open To**
- Backend Engineering Internships — Java · Spring Boot · Distributed Systems
- AI / ML & Automation Engineering roles
- Full Stack Product Engineering
- Quantitative / AI-in-Finance engineering
- High-signal freelance & contract work

---

## Tech Stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=java,ts,js,python,cpp,c&theme=dark)](https://skillicons.dev)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=nextjs,react,tailwind,threejs,html,css&theme=dark)](https://skillicons.dev)

**Backend & Databases**

[![Backend](https://skillicons.dev/icons?i=spring,nodejs,express,postgres,redis,mysql,prisma,supabase&theme=dark)](https://skillicons.dev)

**Cloud, DevOps & Tooling**

[![DevOps](https://skillicons.dev/icons?i=docker,aws,vercel,githubactions,git,linux,postman,idea&theme=dark)](https://skillicons.dev)

</div>

---

## AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :---: | :--- |
| **LLM Application Engineering** | ![](https://img.shields.io/badge/Advanced-7C3AED?style=flat-square) | Prompt architecture, structured output, retrieval pipelines, Gemini & Claude API integration in production |
| **AI Workflow Automation** | ![](https://img.shields.io/badge/Advanced-7C3AED?style=flat-square) | n8n orchestration, event-driven agents, Gmail/Sheets/Apps Script pipelines shipped to a paying client |
| **Machine Learning Foundations** | ![](https://img.shields.io/badge/Proficient-6D28D9?style=flat-square) | Supervised learning, regression & classification, model evaluation, scikit-learn |
| **Natural Language Processing** | ![](https://img.shields.io/badge/Proficient-6D28D9?style=flat-square) | Fuzzy matching, landmark-to-entity resolution, semantic search, embedding retrieval |
| **Predictive Modelling** | ![](https://img.shields.io/badge/Proficient-6D28D9?style=flat-square) | Time-series ridership forecasting, demand & crowd prediction for transit systems |
| **Agentic Systems & Tooling** | ![](https://img.shields.io/badge/Advanced-7C3AED?style=flat-square) | Multi-agent orchestration, MCP tooling, agent harnesses layered over coding assistants |
| **Applied Deep Learning** | ![](https://img.shields.io/badge/Working-5B21B6?style=flat-square) | Neural network fundamentals, transformer architecture, transfer learning |

---

## Featured Projects

<details open>
<summary><b>&nbsp;Distributed URL Shortener &nbsp;·&nbsp; High-Throughput Link Infrastructure</b></summary>

<br/>

A production-grade link shortening service engineered for throughput, not for a portfolio screenshot. Base62 batch ID generation, a Redis read-through cache, a Lua sliding-window rate limiter executed atomically at the cache layer, and an asynchronous analytics pipeline that decouples click ingestion from the redirect hot path.

| | |
| :--- | :--- |
| **Stack** | Java 17 · Spring Boot 3 · PostgreSQL 16 · Redis 7 · Docker · Flyway · GitHub Actions |
| **Scale** | Sustained 100 RPS under load testing · 6 versioned Flyway migrations · 153 MB Docker image |
| **Performance** | **4.13 ms p99 latency** · **99.98% Redis cache hit rate** · async analytics off the critical path |
| **Security** | JWT authentication · BCrypt cost-12 hashing · Lua atomic sliding-window rate limiting |
| **Impact** | 39 passing tests · fully containerised CI/CD · live Swagger UI demo |
| **Repository** | [github.com/mvkrishna24/url-shortener](https://github.com/mvkrishna24/url-shortener) · [Live Demo](https://url-shortener-aimk.onrender.com/swagger-ui/index.html) |

The redirect path is the product. Every architectural decision — batch pre-allocated IDs to avoid per-request DB writes, read-through caching to keep Postgres out of the hot loop, fire-and-forget analytics — exists to protect that single millisecond budget.

</details>

<details>
<summary><b>&nbsp;Door Ducks &nbsp;·&nbsp; Production Facility Management SaaS</b></summary>

<br/>

A live, revenue-generating facility management platform for gated residential communities, currently operating across Andhra Pradesh on an AMC contract model. Built around a strict seven-role authorisation hierarchy running from super admin down to resident, with distinct authentication paths for staff and OTP-based customer access.

| | |
| :--- | :--- |
| **Stack** | Next.js (App Router) · TypeScript · Prisma v7 · Neon PostgreSQL · NextAuth v5 · Tailwind v4 · shadcn/ui · Vercel |
| **Scale** | Live production deployment · multi-tenant community model · roadmap to pan-India rollout |
| **Performance** | Edge-deployed · server components by default · minimal client JS on resident-facing routes |
| **Security** | 7-role RBAC · JWT session cookies · middleware route protection · dual staff/OTP auth spine |
| **Impact** | Paying AMC clients in production · scaling to Hyderabad, then national |
| **Repository** | [doorduckshome.in](https://doorduckshome.in) · private repository |

Real customers, real invoices, real 2 AM bugs. This project taught me more about authorisation boundaries and migration safety than any amount of reading could.

</details>

<details>
<summary><b>&nbsp;MetroNexis &nbsp;·&nbsp; Intelligent Metro Navigation Platform</b></summary>

<br/>

A smart transit navigation system that solves the problem real commuters actually have: they know the landmark, not the station. A geospatial landmark-to-transit resolver performs fuzzy natural-language matching from arbitrary place names to network nodes, then a multi-interchange graph optimiser computes the true optimal route.

| | |
| :--- | :--- |
| **Stack** | Spring Boot 3 · PostgreSQL · Redis · React Native · Dijkstra routing · NLP fuzzy matching |
| **Scale** | Full metro network graph · offline-capable map layer · crowd-prediction modelling |
| **Performance** | Redis-cached route computation · sub-second landmark resolution |
| **Security** | Token-based auth · rate-limited public API surface |
| **Impact** | **2nd place — University Startup Pitch** · judges formally recommended patent filing · ₹15–20 L funding ask established |
| **Repository** | [github.com/mvkrishna24/MetroNexis](https://github.com/mvkrishna24/MetroNexis) · [metronexis.app](https://metronexis.app) |

Three innovations documented for filing: the Geospatial Landmark-to-Transit Resolver, the Multi-Interchange Graph Optimizer, and the AI Ridership Prediction System.

</details>

<details>
<summary><b>&nbsp;LeadOps AI CRM &nbsp;·&nbsp; Autonomous Lead Operations Pipeline</b></summary>

<br/>

An AI-driven CRM automation system deployed to a paying client. Inbound leads are ingested, enriched and classified by an LLM, routed by intent, and answered with context-aware outreach — with the entire pipeline observable from a single sheet the client already knew how to use.

| | |
| :--- | :--- |
| **Stack** | n8n · Google Gemini API · Google Apps Script · Gmail SMTP · Google Sheets API |
| **Scale** | End-to-end automated lead lifecycle · zero manual triage |
| **Performance** | Event-driven execution · no polling waste · sub-minute lead response |
| **Security** | Scoped OAuth credentials · least-privilege API access |
| **Impact** | **Deployed to a paying client** · eliminated manual lead qualification entirely |
| **Repository** | [github.com/mvkrishna24/leadops-ai-crm](https://github.com/mvkrishna24/leadops-ai-crm) |

The best AI product is the one the client forgets is AI. This one just makes their inbox work.

</details>

<details>
<summary><b>&nbsp;RideMatch &nbsp;·&nbsp; Peer-to-Peer Student Ride Matching</b></summary>

<br/>

A zero-commission ride-sharing matchmaking engine for university campuses. Geospatial matching over PostGIS, scheduled batch pairing via Quartz, and push-driven coordination — built to prove that the coordination layer, not the payment rail, is the actual product.

| | |
| :--- | :--- |
| **Stack** | Java 17 · Spring Boot 3 · PostgreSQL 16 + PostGIS · Redis 7 · React Native · Firebase (Auth/FCM) · Quartz · Docker |
| **Scale** | MVP target: 50 active ride pairs at Sanskriti University · ₹10,000 bootstrapped budget |
| **Performance** | Redis-backed match candidate cache · scheduled batch pairing windows |
| **Security** | Firebase Auth · verified university-domain onboarding |
| **Impact** | **Winner — University Startup Pitch** · judges recommended patent filing |
| **Repository** | Private repository · co-founded with a senior JVM engineer |

</details>

---

## Experience

### Freelance Software Engineer &nbsp;·&nbsp; Independent
`2024 — Present` &nbsp;·&nbsp; Hyderabad, India

Design and ship production software for paying clients across SaaS, automation, and high-end web engineering — owning the work end to end, from discovery call and written scope through architecture, delivery, and post-launch support.

**Scope of work**
- Architected and deployed a live multi-tenant facility management SaaS with a seven-role authorisation model, now serving gated communities on AMC contracts
- Built and delivered an AI-driven CRM automation pipeline that removed manual lead qualification entirely for a paying client
- Delivered cinematic, performance-budgeted marketing sites for architecture and creative-industry clients, with scroll-driven canvas animation and accessibility fallbacks
- Own client engagement mechanics: written scope, staged deposits, milestone payments, international GBP invoicing
- Operate a Hyderabad-based creative growth practice targeting premium real estate and luxury wedding verticals

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `NextAuth` `n8n` `Gemini API` `Tailwind` `GSAP` `Vercel`

### Backend & Systems Engineer &nbsp;·&nbsp; Self-Directed Projects
`2023 — Present` &nbsp;·&nbsp; Hyderabad, India

Building distributed backend systems to production standards — benchmarked, containerised, migration-versioned, and CI-gated — rather than to tutorial standards.

**Scope of work**
- Engineered a distributed URL shortener sustaining 100 RPS at 4.13 ms p99 with a 99.98% cache hit rate
- Implemented atomic Lua sliding-window rate limiting at the Redis layer to keep enforcement off the application thread
- Designed Flyway-versioned schema migrations and a fully containerised GitHub Actions CI/CD pipeline
- Built geospatial NLP routing and predictive ridership modelling for an intelligent transit platform
- Maintain 39+ automated tests across services with CI gating on every push

`Java 17` `Spring Boot 3` `PostgreSQL` `Redis` `Docker` `Flyway` `JWT` `GitHub Actions` `JUnit`

---

## Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| **Winner — University Startup Pitch** | RideMatch selected as the winning venture; judging panel formally recommended patent filing |
| **2nd Place — University Startup Pitch** | MetroNexis awarded runner-up; three core innovations documented for IP filing |
| **Patent Track — 2 Products** | Geospatial Landmark Resolver · Multi-Interchange Graph Optimizer · AI Ridership Prediction |
| **Production SaaS in Revenue** | Door Ducks live with paying AMC clients across Andhra Pradesh |
| **Paying Client — AI Automation** | LeadOps AI CRM deployed and operational in a client's production workflow |
| **Sub-5ms p99 at 100 RPS** | Benchmarked distributed backend performance with a 99.98% cache hit rate |
| **297+ LeetCode Submissions** | Sustained algorithmic problem-solving practice |
| **CGPA 8.10 / 10** | B.Tech, Artificial Intelligence & Machine Learning |

</div>

---

## Certifications

> **TODO — replace with your actual credentials, or delete any provider block you don't hold. Do not ship this section with placeholder certifications.**

<div align="center">

**Amazon Web Services**

<img src="https://img.shields.io/badge/AWS-CERT_NAME_HERE-7C3AED?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=0D1117" />

**Oracle**

<img src="https://img.shields.io/badge/Oracle-CERT_NAME_HERE-6D28D9?style=for-the-badge&logo=oracle&logoColor=white&labelColor=0D1117" />

**NPTEL**

<img src="https://img.shields.io/badge/NPTEL-COURSE_NAME_HERE-5B21B6?style=for-the-badge&logo=googlescholar&logoColor=white&labelColor=0D1117" />

**Cisco**

<img src="https://img.shields.io/badge/Cisco-CERT_NAME_HERE-4C1D95?style=for-the-badge&logo=cisco&logoColor=white&labelColor=0D1117" />

</div>

---

## Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/vamshi_krishna_24">
  <img src="https://img.shields.io/badge/LeetCode-vamshi__krishna__24-7C3AED?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://www.geeksforgeeks.org/user/YOUR_GFG_HANDLE">
  <img src="https://img.shields.io/badge/GeeksforGeeks-YOUR__HANDLE-6D28D9?style=for-the-badge&logo=geeksforgeeks&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://www.hackerrank.com/profile/YOUR_HR_HANDLE">
  <img src="https://img.shields.io/badge/HackerRank-YOUR__HANDLE-5B21B6?style=for-the-badge&logo=hackerrank&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://www.codechef.com/users/YOUR_CC_HANDLE">
  <img src="https://img.shields.io/badge/CodeChef-YOUR__HANDLE-4C1D95?style=for-the-badge&logo=codechef&logoColor=white&labelColor=0D1117" />
</a>

</div>

---

## GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=mvkrishna24&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=C9D1D9&icon_color=7C3AED&ring_color=A855F7" />
<img width="49%" src="https://streak-stats.demolab.com?user=mvkrishna24&hide_border=true&background=0D1117&stroke=30363D&ring=A855F7&fire=7C3AED&currStreakLabel=A855F7&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" />

<br/><br/>

<img width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mvkrishna24&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=C9D1D9" />

</div>

---

## GitHub Trophies

<div align="center">

<img width="100%" src="https://github-profile-trophy.vercel.app/?username=mvkrishna24&theme=nord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" />

</div>

---

## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=mvkrishna24&bg_color=0D1117&color=A855F7&line=7C3AED&point=C084FC&area=true&area_color=4C1D95&hide_border=true&custom_title=Contribution%20Graph" />

</div>

---

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mvkrishna24/mvkrishna24/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mvkrishna24/mvkrishna24/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/mvkrishna24/mvkrishna24/output/github-snake.svg" />
</picture>

</div>

---

## Current Focus

```yaml
engineer: Martha Vamshi Krishna
role: Backend Engineer · AI Systems
location: Hyderabad, India

learning:
  - Distributed messaging: Kafka, event streaming, exactly-once semantics
  - Real-time delivery: WebSockets, Server-Sent Events, backpressure
  - Systems performance: JVM tuning, cache topology, tail-latency budgets

building:
  - Notification Service — Java 17 · Spring Boot 3 · Kafka · Redis · WebSockets
  - Door Ducks — production facility management SaaS, security spine hardening
  - mvkrishna.me — Cinematic Systems Telemetry portfolio

exploring:
  - Quantitative engineering and AI applied to markets
  - Agentic developer tooling and multi-agent orchestration
  - Product engineering: revenue, retention, and what actually breaks

open_to:
  - Backend Engineering Internships (Java · Spring Boot · Distributed Systems)
  - AI / ML & Automation Engineering
  - Full Stack Product Engineering
  - High-signal freelance and contract work

reach_me: marthavamshikrishna1024@gmail.com
```

---

## Connect

<div align="center">

<a href="mailto:marthavamshikrishna1024@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-marthavamshikrishna1024%40gmail.com-7C3AED?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://linkedin.com/in/krishna-mv-38380a2b3">
  <img src="https://img.shields.io/badge/LinkedIn-Martha%20Vamshi%20Krishna-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://github.com/mvkrishna24">
  <img src="https://img.shields.io/badge/GitHub-mvkrishna24-5B21B6?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://mvkrishna.me">
  <img src="https://img.shields.io/badge/Portfolio-mvkrishna.me-4C1D95?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" />
</a>

</div>

---

<div align="center">

### *"Anyone can make it work. Engineering is making it work at the ninety-ninth percentile."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:4c1d95,100:1e1b4b&height=140&section=footer" />

</div>
