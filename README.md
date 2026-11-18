<div align="center">

# Hi, I'm Paul 👋

**Python Backend Developer** · async services, queues, load testing
2nd-year student at SamGTU · Samara, Russia

![Status](https://img.shields.io/badge/status-open_to_work-2ea44f?style=for-the-badge)
![Roles](https://img.shields.io/badge/roles-Junior_%7C_Intern_%7C_Part--time-0366d6?style=for-the-badge)
![Availability](https://img.shields.io/badge/availability-20--25_hrs%2Fweek-orange?style=for-the-badge)
![Format](https://img.shields.io/badge/format-remote_%2F_hybrid_(Samara)-8957e5?style=for-the-badge)

[![Telegram](https://img.shields.io/badge/Telegram-@Zeufo-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Zeufo)
[![Email](https://img.shields.io/badge/Email-p.yudin.work@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:p.yudin.work@gmail.com)

</div>

---

## 🧭 About

I build asynchronous backends in Python and **back architectural decisions with measurements**, not guesses.
I like the part of the job where you find out *what a piece of infrastructure actually buys you*,
and I document trade-offs and known limitations in my READMEs.

- 🔬 Load-test my own designs with Locust: ramp-up scenarios, p95 and RPS, one change at a time
- 🚀 Run a real Telegram service in production on a Linux VPS: 1000+ registered users, 300+ WAU
- ⚡ Shipped a working backend MVP in 48 hours at a hackathon (🥉 3rd place)
- 🎯 Clean code: SOLID, KISS, DRY, typed (pyright), linted (Ruff)

---

## 🚀 Projects

### 🤖 [Samgtu-new](https://github.com/Zeufo/Samgtu-new) — Telegram schedule service (in production)
Group schedules for SamGTU students with instant notifications about changes.
- **1000+ registered users, 300+ WAU**, running on a Linux VPS via Docker Compose
- University API parsing, optimized DB schema and queries (~0.5 ms per query, measured from logs)
- Logging and monitoring for hands-off operation
- 🧰 `aiogram 3` `SQLAlchemy` `PostgreSQL` `Docker`
- Try it: [@samgtu_rasp_bot](https://t.me/samgtu_rasp_bot)

### 🗼 [Lighthouse](https://github.com/Zeufo/Lighthouse) — AI news digest from Telegram (solo)
Daily digest: collected, de-duplicated, clustered and fact-scored by an LLM.
- Async collection from **50+ channels** with Telethon (FloodWait handling, ad filtering)
- LLM clustering by event and category, with **credibility badges** (✅ confirmed · ⚠️ partial · ❓ unverified)
- Scheduled pipeline (APScheduler), retries (Tenacity), delivery via aiogram 3 with a TTL anti-spam middleware
- 🧰 `Telethon` `aiogram 3` `PostgreSQL 16` `SQLAlchemy 2.0` `OpenAI-compatible API` `Docker`
- Try it: [@LightHouse_Digest_bot](https://t.me/LightHouse_Digest_bot)

### 🏆 [DecisionHub](https://github.com/NeuroBreaker/DecisionHub) — hackathon platform (🥉 3rd place)
Team project built in 48 hours; I developed the backend.
- REST API on FastAPI, **JWT auth with three roles** (participant, jury, organizer)
- Auto-check module: **static code analysis** (LOC, cyclomatic complexity, secret detection), PDF/DOCX analysis
- Weighted scoring and a live leaderboard with CSV export
- 🧰 `FastAPI` `PostgreSQL` `SQLAlchemy` `Docker Compose`

---

## 💻 Tech Stack

**Backend & async**
![Python](https://img.shields.io/badge/Python_3.12+-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi)
![Pydantic](https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square&logo=pydantic&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-3670A0?style=flat-square&logo=python&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram_3-2CA5E0?style=flat-square&logo=telegram&logoColor=white)
![httpx](https://img.shields.io/badge/httpx%20%7C%20aiohttp-555?style=flat-square)

**Data, cache & messaging**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_2.0-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-555?style=flat-square)
![asyncpg](https://img.shields.io/badge/asyncpg-316192?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-07405e?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ_(aio__pika)-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Load & testing**
![Locust](https://img.shields.io/badge/Locust-load_testing-2f855a?style=flat-square)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![HTTPX](https://img.shields.io/badge/HTTPX-555?style=flat-square)
![Allure](https://img.shields.io/badge/Allure-8A2BE2?style=flat-square)

**AI integration**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Telethon](https://img.shields.io/badge/Telethon-2CA5E0?style=flat-square&logo=telegram&logoColor=white)

**Infrastructure & tooling**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_(Debian%2C_Arch)-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)
![pyright](https://img.shields.io/badge/pyright-555?style=flat-square)

---

## 🏅 Achievements

- 🥉 **Bronze medalist** — Samara Region Product Programming Championship 2026 ([DecisionHub](https://github.com/NeuroBreaker/DecisionHub))
- 🎯 **Finalist** — Avito spring internship selection 2026 (QA track)
- 🎓 **Certified** — "AI & Generative Models", T-Education (2026)
- 👥 Member of the SamGTU development team
- 🌍 English: B2 (technical docs, written communication)

---

## 📈 GitHub Stats

<div align="center">

![Streak](https://streak-stats.demolab.com/?user=Zeufo&theme=dark&hide_border=true)
<br/>
![Top Langs](https://github-readme-stats.shion.dev/api/top-langs/?username=Zeufo&theme=dark&hide_border=true&include_all_commits=true&count_private=false&layout=compact)

</div>

---

<div align="center">

🌱 Currently exploring: **AI agents & LLM tooling**, **Go**

💬 *Got a Junior / Intern / Part-time backend role? Ping me on [Telegram](https://t.me/Zeufo).*

</div>
