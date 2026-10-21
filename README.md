# Hi, I'm Baqir 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00C4FF&width=800&lines=Backend+Engineer+%7C+SRE+%26+DevOps;Co-Founder+at+Rykards;Building+and+Operating+Production+Systems)](https://git.io/typing-svg)

I'm a **backend engineer, SRE & DevOps practitioner, and co-founder of [Rykards (PRIVATE) LIMITED](https://www.rykards.com)**, based in Pakistan.

My work focuses on backend services, asynchronous processing, reliable deployments, and cost-conscious infrastructure. At Rykards, I handle **backend engineering, infrastructure, and deployments** across our products, working with the team to deliver complete business platforms. I also build and operate my own SaaS projects: **Sage** and **Sage Studio**.

---

## 🏢 What We're Building at Rykards

We build **customizable base platforms** that we adapt to each client's workflows and operational needs. These are team-built products; my contributions focus on their backend systems, infrastructure, and deployments.

| Product | What it supports | Current stage |
|---------|------------------|---------------|
| **Wholesale Inventory & Dispatch** | Wholesale inventory and dispatch operations | Deployed at **5 businesses** |
| **Cafe POS** | Cafe billing and point-of-sale operations | Deployed at **approximately 10 businesses** |
| **Dental POS** | Dental clinic billing and point-of-sale operations | Deployed at **1 clinic** |
| **Restaurant IMS + POS** | Restaurant inventory management and point of sale | **Production-ready; awaiting first deployment** |
| **Golf Club Management System** | Golf club management workflows | **In final development** |

The wholesale platform replaces phone-coordinated, paper-based dispatch logging with a shared digital workflow. My backend and deployment work includes **Django, Supabase PostgreSQL, Hetzner, and Cloudflare**, supporting the team's React application.

🌐 [Rykards](https://www.rykards.com) · [Our Work](https://www.rykards.com/work)

---

## 🚀 My Personal Projects

### [Sage Studio — AI Video Generator](https://studio.sageai.live)

A live SaaS product that turns Reddit stories into TikTok-style videos. The pipeline covers Reddit scraping, AI scriptwriting with Gemini, voiceover and subtitle synchronization, video rendering with faster-whisper and FFmpeg on Modal GPU, and delivery through AWS.

**Stack:** FastAPI · PRAW · Gemini · Amazon SQS · faster-whisper · FFmpeg · Modal · S3 · CloudFront

### [Sage — AI Audio Lectures](https://sageai.live)

A live SaaS product that converts PDF and PPTX notes into AI-generated audio lectures. It offers students **5 free lectures per day** and runs on an infrastructure budget of **under $1/day** through deliberate architectural tradeoffs.

**Stack:** FastAPI · Amazon SQS · Celery · Groq · Edge-TTS · S3 · Flutter · AWS

---

## 🛠️ Tech Stack & Tools

[![My tools](https://skillicons.dev/icons?i=aws,docker,linux,nginx,python,fastapi,django,redis,postgres,github,git,react,ts,flutter,bash)](https://skillicons.dev)

| Category | Tools |
|----------|-------|
| ☁️ Cloud & Infrastructure | AWS: EC2, S3, RDS, SQS, Lambda, Secrets Manager, CloudWatch · Modal · Hetzner · Cloudflare |
| 🐳 DevOps & SRE | Docker · Nginx · systemd · GitHub Actions · CI/CD · Monitoring & incident response · Cost optimization |
| 🐍 Backend | Python · FastAPI · Django · Gunicorn/Uvicorn · Celery · SQLAlchemy · Alembic |
| 🗄️ Databases & Queues | PostgreSQL · Supabase · SQLite · Redis · Amazon SQS |
| 📱 Frontend & Mobile | React · TypeScript · Flutter |
| 🤖 AI, ML & Media | Gemini API · Groq API · OpenCV · TensorFlow · MediaPipe · faster-whisper · Edge-TTS · FFmpeg |
| 📜 Scripting & Automation | Bash · Python |

---

## 🏗️ How I Think About Systems

I design around failure: decouple long-running work, handle errors gracefully, and consider operating costs from the start.

**Sage Studio — video pipeline**

```text
Reddit → AI script → Voiceover & subtitles → Video rendering → Delivery
PRAW     Gemini     faster-whisper / FFmpeg  Modal GPU         S3 / CloudFront

                 Amazon SQS decouples background processing
```

**Sage — audio pipeline**

```text
Upload → Queue → Worker → AI processing → Storage → Playback
         SQS     Celery   Groq / Edge-TTS  S3        Flutter
```

Across client platforms and personal projects, I focus on maintainable backend services, predictable deployments, backups, monitoring, and infrastructure that fits the workload.

---

## 💼 Experience

**Co-Founder · Backend & DevOps Engineer — [Rykards (PVT) LTD](https://www.rykards.com)**

Work with the team to build and customize business software across wholesale, cafes, dental clinics, restaurants, and golf clubs. Handle backend engineering, infrastructure, and deployments across all five product platforms, with deployment status detailed above.

**Backend Developer · Independent / Freelance · 2026–Present**

Backend development and production operations for a wholesale inventory and dispatch platform built with Django, React, and Supabase PostgreSQL. Work includes a cost-conscious deployment architecture using Cloudflare for the frontend and Hetzner for the backend. This work also forms part of my Rykards product experience.

**SRE & DevOps Consultant · Multiple Clients · Oct 2025–Present**

Deploy and maintain production REST APIs on AWS EC2 using Nginx, SSL, systemd, and controlled update cycles. Maintain a healthcare facility's patient database management system, including backups and reliability monitoring. Achieved a **15% reduction in deployment and cloud operating costs between Q4 2025 and Q1 2026** through resource rightsizing and architectural optimization, and automated recurring DevOps workflows with Python and Bash.

**Flutter Mobile Developer (Intern) · DHA Multan · Jun 2024–Sep 2024**

Built and deployed a billing management system for a golf and country club client, improving operational workflows.

---

## 🏆 Achievement

**1st Place — Innovista Agentic AI Hackathon 2025**

Built an AI-powered emergency response system for natural disasters during a **24-hour, on-site competition**, learning and applying agentic AI workflows during the event.

---

## 📌 Other Work

**ASL Recognition System** — Completed a sign-language recognition project using Python, OpenCV, MediaPipe, and TensorFlow.

---

## 📊 GitHub Stats

![Baqir's most-used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Baqir-Hassan&layout=compact&theme=radical)

---

## 📫 Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/baqir-hassan-smbhn)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:baqirhassan007@gmail.com)
[![Rykards](https://img.shields.io/badge/Rykards-Company-111827?style=for-the-badge)](https://www.rykards.com)
[![Sage Studio](https://img.shields.io/badge/Sage_Studio-Live-brightgreen?style=for-the-badge)](https://studio.sageai.live)
[![Sage](https://img.shields.io/badge/Sage-Live-brightgreen?style=for-the-badge)](https://sageai.live)

---

*Backend Engineering · SRE & DevOps · Co-Founder at Rykards — based in Pakistan.*
