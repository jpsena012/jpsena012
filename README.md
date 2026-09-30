<h1 align="center">Joao Sena 🇧🇷</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=36BCF7&center=true&vCenter=true&width=435&lines=AI+Engineer+%40+DAVID+AI" alt="Typing SVG" />
</p>

---

## About Me:

I'm an AI Engineer at **DAVID AI**, where I build production AI agents for clinical and B2B SaaS clients — voice agents that answer real patient calls, RAG support agents, and an autonomous QA agent running in a client's own AWS.

I'm also a Software Engineering student at Utah Valley University (B.S., expected Dec 2029), founder of **Flux**, and I build transformers from scratch in PyTorch for fun.

I'm from Brazil, but I love all things to do with people & culture. I speak Portuguese, English, and Spanish.

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=jpsena012&label=Visitor%20count&color=0e75b6&style=flat" alt="visitor count" />
</p>

---

## What I'm Building:

### Avilys Sleep — AI Voice Agent (DAVID AI)
> A sleep clinic couldn't staff its phone line. Now an agent answers it.

- **100%** of calls answered, **95%** resolved correctly
- **234 calls/week** closed with no person involved — roughly **39 staff-hours** returned
- **545** chart notes written that nobody had to type
- Outbound cron works a deep-freeze referral list on its own: **178 calls placed**, patient reached on **85%**, books and schedules its own callbacks
- Identity verified before any PHI is spoken · ElevenLabs + FastAPI on Railway

### Snoball — RAG Support Agent (DAVID AI)
> Their support history was the knowledge base. It just wasn't searchable.

- **2,627 threads** mined into **1,445 cited Q&A pairs** across **442 accounts**
- Hybrid retrieval + rerank, grounded drafts with citations, human approves before anything sends
- Client called the drafts accurate and the knowledge base golden

### Snoball — Autonomous QA Agent (DAVID AI)
> Reads a ticket, drives the app in a real browser, and escalates instead of guessing.

- Verifies a ticket in **~90s for ~$0.03** — **919 recorded runs** against a **589-card board**
- Claude on **Bedrock** + **AgentCore**, deployed to the client's own AWS via CDK
- HMAC-verified webhook, deduped retries, SQS + DLQ, visibility timeout above the worker's so runs never overlap
- Merge-blocking test suite grown **163 → 753**

### RUSTY — Offline AI Repair Copilot 🏆
> **Top 5, On-Device AI** — Google Gemma JustBuild Hackathon

- **Gemma E2B** running entirely on the phone, network disabled
- Speech in, speech out — a mechanic never touches the screen
- Photographs the engine bay and reports PASS / FAIL / UNKNOWN / BLOCKED, admitting what it physically can't see

### Flux — AI Student Life Balance App
> I got tired of juggling Canvas, Google Calendar, and my social life in separate tabs. So I built an app that does it for me.

- **1,700+** calendar events tracked across beta users
- **68%** acceptance rate on AI-generated study plans
- Cut AI plan generation from **150s** (past Supabase's gateway timeout) to **under 35s**
- Conversational AI assistant powered by Google Gemini · Supabase + PostgreSQL Edge Functions

### LLM From Scratch & GPT-2 Fine-Tuning
> Building a transformer from the ground up to understand what's actually happening under the hood.

- Tokenization, embeddings, and forward-pass logic in PyTorch
- Fine-tuned GPT-2 for 7-class support ticket classification: **LoRA beat full fine-tuning, 100% vs 97.4% test accuracy, with 47x fewer trainable parameters**

### Contract Engineering — UVU e2i Program *(Feb – July 2026)*
> Two clients at once, no senior engineer, full ownership.

- **College of Education** — Replaced a Streamlit app with a React/Tailwind web app for STER rubric evaluations. Wireframed in Figma, iterated with the client — now adopted department-wide.
- **Randon Aviation** — Shipped billing and directory features into their React/Ionic/Capacitor app with Zustand stores and skeleton states. Closed an XSS token-theft path by moving the JWT out of localStorage into memory on web and the Keychain on native, with a regression test.

### ParkShare
> College parking is a nightmare. So I'm building a marketplace for it.

- Flutter mobile app · Firebase Auth + Firestore · $500 development grant

---

## 📜 Certifications:

- **Claude in Amazon Bedrock** — Anthropic (Aug 2026)
- **Building Agentic AI Applications with LLMs** — NVIDIA (Mar 2026)

---

## 🛠 Tech Stack:

**Languages**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**AI & Agents**
<p align="left">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logo=elevenlabs&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/LoRA-5A29E4?style=for-the-badge&logo=huggingface&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG_%2B_pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

**Frameworks**
<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white" />
  <img src="https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=capacitor&logoColor=white" />
</p>

**Cloud & Data**
<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

**Tools**
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Linear-5E6AD2?style=for-the-badge&logo=linear&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</p>

---

## Random Dev Quote:

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote" />
</p>

---

## 📫 Let's Connect:

<p align="left">
  <a href="https://www.linkedin.com/in/joaodesena"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:jpsena012@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/jpsena012"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

If you're working on something cool or hiring, I'd love to chat!
