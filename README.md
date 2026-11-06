<h1 align="center">Joao Sena 🇧🇷</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=36BCF7&center=true&vCenter=true&width=435&lines=AI+Engineer+%40+DAVID+AI" alt="Typing SVG" />
</p>

---

## About Me

AI engineer at **DavidAI** and Software Engineering student at Utah Valley University. I build agents that talk to real customers, mostly voice and support. The part I care about most is making sure they are honest about what they actually did. I'm originally from Brazil and speak Portuguese, English and Spanish.

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=jpsena012&label=Visitor%20count&color=0e75b6&style=flat" alt="visitor count" />
</p>

---

## What I'm Building

### Voice Agent | DavidAI
The clinic couldn't keep its phone line staffed, and I took over the agent as its main owner. Most failures came from the model calling tools with bad inputs, so I moved the tool contracts server side, where they can be checked instead of trusted. I also made scheduling confirm a booking only after AdvancedMD accepts it, because telling a patient they're booked when they aren't is worse than transferring the call. Tool errors dropped from **90% to 0%**, there have been **0 false confirmations in 798+ calls**, and **98% of 10,696 calls** resolve correctly.

### RAG Support Agent | DavidAI
A client's answers were buried in 2,627 old support threads that nobody could search. I built a RAG agent that turns those threads into cited Q&A pairs. A person approves every draft, since one wrong answer sent to a customer costs more than a slow one. The result was **1,445 pairs across 442 accounts**, and the client called the knowledge base golden.

### RUSTY | Offline AI Repair Copilot
**Top 5, On-Device AI at the Google Gemma JustBuild Hackathon.** Repair work happens with dirty hands and often without signal. I built a voice-driven checklist that runs Gemma E2B fully offline and checks each step from a photo. A deterministic step machine makes the final call, because the model shouldn't be the one deciding a repair is done. It had **0 false passes on 12 labeled photos**.

### Flux | AI Student Scheduling App
I was juggling Canvas, Google Calendar and the rest of my life in separate tabs, so I built an app that turns them into a study plan. Plan generation took 150 seconds, which went past Supabase's gateway timeout, so I reworked it to finish in **under 35 seconds**. Then I opened the build to real students to see if they would actually follow the plans. It now has **6 beta users and 1,700+ events**, and **68% of plans were accepted**.

### LLM From Scratch & GPT-2 Fine-Tuning
I built transformer components from scratch in PyTorch to understand what actually happens inside an LLM. Then I tested whether parameter-efficient tuning gives up accuracy on a small task. On 7-class support ticket classification, LoRA scored **100% against 97.4%** for full fine-tuning, with **47x fewer trainable parameters**.

### Client Contracts | UVU e2i *(Feb – July 2026)*
I worked on two client projects at once without a senior engineer. UVU's College of Education was reviewing STER rubrics in a slow Streamlit prototype, so I rebuilt it in React and Tailwind, and the department now uses it. For Randon Aviation, I found that their app stored login tokens in localStorage, where any injected script could read them. I moved the tokens into memory on web and the Keychain on mobile, and added a regression test so the fix stays in place.

### ParkShare
Parking near campus is hard to find, so I'm building a marketplace for it. ParkShare is a Flutter app on Firebase Auth and Firestore, funded by a **$500 development grant**.

---

## Certifications

- **Claude in Amazon Bedrock**, Anthropic (Aug 2026)
- **Building Agentic AI Applications with LLMs**, NVIDIA (Mar 2026)

---

## Tech Stack

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

## Random Dev Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote" />
</p>

---

## Let's Connect

<p align="left">
  <a href="https://www.linkedin.com/in/joaodesena"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:jpsena012@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/jpsena012"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

If you're building something interesting or hiring, I'd love to chat.
