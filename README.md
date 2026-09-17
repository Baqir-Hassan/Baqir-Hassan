# Hi, I'm Baqir 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00C4FF&width=700&lines=Backend+Engineer+%7C+SRE+%26+DevOps+%7C+Full-Stack;Building+Production-Grade+Cloud+Infrastructure;Two+Live+SaaS+Products+%2B+a+Production+Business+Platform;Targeting+SRE+%2F+DevOps+Roles+in+Japan+🇯🇵)](https://git.io/typing-svg)

I don't just build prototypes — I ship things that stay up. My focus is on reliability, async architecture, and cost-conscious infrastructure design.

---

## 🚀 What I'm Working On

- **Wholesale Inventory & Dispatch Platform** — Designed, built, and currently operate a production platform used daily by 18 staff/admin users across two businesses, tracking hundreds of SKUs across 3 warehouses. Replaced phone-coordinated, paper-based dispatch logging with a digital dashboard, cutting an estimated ~30 minutes of coordination per dispatch.

- **[Sage Studio](https://studio.sageai.live)** — Live SaaS that auto-generates TikTok-style videos from Reddit stories. End-to-end pipeline: Reddit scraping → AI scriptwriting (Gemini) → voiceover & subtitle sync (faster-whisper + FFmpeg on Modal GPU) → cloud delivery via AWS.

- **[Sage](https://sageai.live)** — Live SaaS that converts PDF/PPTX notes into AI-generated audio lectures. Free for students (5 lectures/day). Running under $1/day through deliberate architectural tradeoffs.

---

## 🛠️ Tech Stack & Tools

[![](https://skillicons.dev/icons?i=aws,docker,linux,nginx,python,fastapi,django,redis,postgres,github,git,react,ts,flutter,bash)](https://skillicons.dev)

| Category | Tools |
|----------|-------|
| ☁️ Cloud & Infra | AWS (EC2, S3, RDS, SQS, Lambda, Secrets Manager, CloudWatch), Modal.com, Hetzner, Cloudflare |
| 🐳 DevOps & SRE | Docker, Nginx, systemd, GitHub Actions, CI/CD, monitoring & incident response, cost optimization |
| 🐍 Backend | Python, FastAPI, Django, Gunicorn/Uvicorn, Celery, SQLAlchemy, Alembic |
| 🗄️ Databases & Queues | PostgreSQL, Supabase, SQLite, Redis, Amazon SQS |
| 📱 Frontend & Mobile | React, TypeScript, Flutter |
| 🤖 AI / ML & Media | Gemini API, Groq API, OpenCV, TensorFlow, MediaPipe, faster-whisper, Edge-TTS, FFmpeg |
| 📜 Scripting | Bash, Python automation |

---

## 🏗️ How I Think About Systems

**Sage Studio — Video Pipeline:**
```
Reddit → AI Script → Voiceover/Subtitles → Rendered Video → S3
PRAW     Gemini      faster-whisper+FFmpeg   Modal GPU       CloudFront
         └──────────── SQS Queue (decoupled worker) ───────────┘
```

**Sage — Audio Pipeline:**
```
Upload → Queue  → Worker → AI Processing   → Storage → Playback
         SQS      Celery    Groq + Edge-TTS    S3        Flutter
```

I design for **failure by default** — async pipelines, graceful error handling, and cost optimization baked in from the start, not bolted on later.

---

## 💼 Experience

**Backend Developer** · Independent / Freelance · *2026 – Present*
Design, build, and operate a wholesale inventory and dispatch platform (Django, React, Supabase PostgreSQL) used daily by 18 staff and admin users across two businesses — frontend on Cloudflare, backend on Hetzner for a cost-efficient production architecture.

**SRE & DevOps Consultant** · Multiple Clients · *Oct 2025 – Present*
Deploy and maintain production REST APIs on AWS EC2 (Nginx, SSL, systemd, controlled update cycles) and a patient database management system for a healthcare facility, including backups and reliability monitoring. Achieved a 15% reduction in deployment and cloud operational costs (Q4 2025 – Q1 2026) through resource rightsizing and architectural optimization, and automated recurring DevOps workflows with Python/Bash.

**Flutter Mobile Developer (Intern)** · DHA Multan · *Jun 2024 – Sep 2024*
Built and deployed a billing management system for a golf and country club client, improving workflow efficiency across the organization.

---

## 🏆 Achievement

**1st Place — Innovista Agentic AI Hackathon 2025**: Built an AI-powered emergency response system for natural disasters during a 24-hour on-site competition, learning and applying agentic AI workflows from scratch.

---

## 📌 Featured Projects

| Project | Stack | Status |
|--------|-------|--------|
| [Sage Studio — AI Video Generator](https://studio.sageai.live) | FastAPI · SQS · Gemini · faster-whisper · FFmpeg · Modal · AWS | 🟢 Live |
| [Sage — AI Audio Lectures](https://sageai.live) | FastAPI · SQS · Groq · Edge-TTS · Flutter · AWS | 🟢 Live |
| Wholesale Inventory & Dispatch Platform | Django · React · Supabase · Cloudflare · Hetzner | 🟢 Live (Production) |
| ASL Recognition System | Python · OpenCV · MediaPipe · TensorFlow | ✅ Complete |

---

## 📊 GitHub Stats

![Baqir's GitHub Stats](https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Baqir-Hassan&layout=compact&theme=radical)

---

## 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/baqir-hassan-smbhn)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:baqirhassan007@gmail.com)
[![Sage Studio](https://img.shields.io/badge/Sage_Studio-Live-brightgreen?style=for-the-badge)](https://studio.sageai.live)
[![Sage](https://img.shields.io/badge/Sage-Live-brightgreen?style=for-the-badge)](https://sageai.live)

---

*Backend Engineer · SRE & DevOps · Full-Stack — currently open to SRE, DevOps, and backend engineering opportunities — based in Pakistan*
