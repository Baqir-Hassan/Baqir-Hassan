# Hi, I'm Baqir 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00C4FF&width=700&lines=AWS+DevOps+%26+SRE+Engineer;Building+Production-Grade+Cloud+Infrastructure;Two+Live+SaaS+Products+on+AWS;Targeting+SRE+%2F+DevOps+Roles+in+Japan+🇯🇵)](https://git.io/typing-svg)

I don't just build prototypes — I ship things that stay up. My focus is on reliability, async architecture, and cost-conscious infrastructure design.

---

## 🚀 What I'm Working On

- **[Sage Studio](https://studio.sageai.live)** — Live SaaS that auto-generates TikTok-style videos from Reddit stories. End-to-end pipeline: Reddit scraping → AI scriptwriting (Groq) → voiceover (Whisper + Edge TTS) → subtitle rendering (FFmpeg on Modal GPU) → cloud delivery via AWS.

- **[Sage](https://sageai.live)** — Live SaaS that converts PDF/PPTX notes into AI-generated audio lectures. Free for students (5 lectures/day). Running under $1/day through deliberate architectural tradeoffs.

---

## 🛠️ Tech Stack & Tools

[![](https://skillicons.dev/icons?i=aws,docker,linux,nginx,python,fastapi,redis,postgres,github,git,react,ts,flutter,bash)](https://skillicons.dev)

| Category | Tools |
|----------|-------|
| ☁️ Cloud & Infra | AWS (EC2, S3, RDS, SQS, CloudWatch), Modal.com |
| 🐳 DevOps | Docker, Nginx, systemd, GitHub Actions, CI/CD |
| 🐍 Backend | Python, FastAPI, Celery, SQLAlchemy, Alembic |
| 🗄️ Databases & Queues | PostgreSQL, SQLite, Redis, Amazon SQS |
| 📱 Frontend & Mobile | React, TypeScript, Flutter |
| 📜 Scripting | Bash, Python automation |

---

## 🏗️ How I Think About Systems

**Sage Studio — Video Pipeline:**
```
Reddit → AI Script → Voiceover → Subtitles → Rendered Video → S3
PRAW     Groq        Whisper      FFmpeg       Modal GPU       CloudFront
         └──────────── SQS Queue (decoupled worker) ───────────┘
```

**Sage — Audio Pipeline:**
```
Upload → Queue  → Worker → AI Processing → Storage → Playback
         SQS      Celery    Groq + TTS       S3        Flutter
```

I design for **failure by default** — async pipelines, graceful error handling, and cost optimization baked in from the start, not bolted on later.

---

## 📌 Featured Projects

| Project | Stack | Status |
|--------|-------|--------|
| [Sage Studio — AI Video Generator](https://studio.sageai.live) | FastAPI · SQS · Groq · Whisper · FFmpeg · Modal · AWS | 🟢 Live |
| [Sage — AI Audio Lectures](https://sageai.live) | FastAPI · SQS · Groq · Flutter · AWS | 🟢 Live |
| ASL Recognition System | Python · OpenCV · MediaPipe · TensorFlow | ✅ Complete |

---

## 🌏 Goals

- 🇯🇵 Relocating to Japan — JLPT N3 (July 2026) → N2 (December 2026)
- 🏆 1st Place — Innovista Agentic AI Hackathon 2025
- 📚 CS Graduate — Bahauddin Zakariya University, July 2026

---

## 📊 GitHub Stats

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Baqir-Hassan&layout=compact&theme=radical)](https://github.com/Baqir-Hassan)
---

## 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/baqir-hassan-smbhn)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:baqirhassan007@gmail.com)
[![Sage Studio](https://img.shields.io/badge/Sage_Studio-Live-brightgreen?style=for-the-badge)](https://studio.sageai.live)
[![Sage](https://img.shields.io/badge/Sage-Live-brightgreen?style=for-the-badge)](https://sageai.live)

---

*Currently open to SRE, DevOps, and backend engineering opportunities — based in Pakistan, targeting Japan (visa sponsorship required).*
