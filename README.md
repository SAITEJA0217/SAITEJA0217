<!-- ─────────────────────────────────────────────────────────────
     Saiteja Reddy Karka · GitHub profile README
     Design: minimal / dark / project-first.
     ───────────────────────────────────────────────────────────── -->

<div align="center">

<h1>Saiteja Reddy Karka</h1>

<p><strong>AI Engineer &nbsp;·&nbsp; Full Stack Developer &nbsp;·&nbsp; Browser Agent Researcher</strong></p>

<p><sub>Final-year B.Tech, AI &amp; ML · Malla Reddy University · Hyderabad, India</sub></p>

**I build AI systems that can explain themselves — and ship them as real products.**

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-saiteja--space.netlify.app-0f172a?style=flat-square&logo=netlify&logoColor=60a5fa)](https://saiteja-space.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-saiteja--reddy--karka-0f172a?style=flat-square&logo=linkedin&logoColor=60a5fa)](https://www.linkedin.com/in/saiteja-reddy-karka/)
[![Email](https://img.shields.io/badge/Email-karkasaiteja4%40gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=60a5fa)](mailto:karkasaiteja4@gmail.com)
[![FormPilot](https://img.shields.io/badge/Research-FormPilot%20%E2%80%94%20IEEE%20paper%20in%20progress-0f172a?style=flat-square&logo=googlescholar&logoColor=a78bfa)](#-research--trustworthy-browser-agents)

</div>

<br/>

## About

Final-year B.Tech (AI & ML) student at Malla Reddy University, Hyderabad. I work at the intersection of **LLM-driven agents** and **full-stack product engineering**: designing systems where a model's decision is grounded in evidence, scored for confidence, and correctable by the user — then building the interface, backend and deployment around it.

Current focus is **trustworthy browser agents**. My research project, [FormPilot](#-formpilot--trustworthy-browser-agent-for-web-form-automation), treats web form automation as a reasoning problem (field dependencies, evidence grounding, per-field confidence) rather than a scripting problem, and is being written up for IEEE submission. On the product side I founded **InternLink**, an AI-assisted internship platform with student and employer dashboards.

<br/>

## What I build

<table>
<tr>
<td width="33%" valign="top">

**🧭 Agents & automation**<br/>
Browser agents (Chrome MV3), LLM tool-use, agentic workflows, correction-based learning loops.

</td>
<td width="33%" valign="top">

**🔍 Trustworthy AI**<br/>
Evidence grounding, confidence-aware decisions, explainable outputs, human-in-the-loop feedback.

</td>
<td width="33%" valign="top">

**⚡ Full-stack AI products**<br/>
React / Next.js front-ends, FastAPI & Node back-ends, Firebase infrastructure, Gemini / OpenAI integration.

</td>
</tr>
</table>

<br/>

## Featured projects

<!-- ───────────── FormPilot ───────────── -->
### 🧭 FormPilot — Trustworthy browser agent for web form automation

**A Chrome extension that reads a web form, reasons about it, and fills it — while telling you how confident it is in every field.**

| | |
|---|---|
| **Problem** | Form-filling automation is brittle: it ignores dependencies between fields, hallucinates values with no source, and gives the user no way to know which fields to double-check. |
| **What I built** | A Manifest V3 Chrome extension backed by the Gemini API and Firebase Firestore. It stores a secure user profile, performs dependency-aware semantic reasoning over the form, grounds each value in profile evidence, assigns a per-field confidence score, and learns from user corrections through a feedback loop. |
| **Research contribution** | Framing form automation as *dependency-aware semantic reasoning + evidence grounding + confidence-aware decision-making*, with human corrections as a learning signal. Being written up as an IEEE paper (in progress, targeting 2026 submission). |
| **Engineering implementation** | Extension architecture (MV3), form/DOM understanding, LLM prompting for field reasoning, confidence scoring surfaced in the UI, Firestore-backed profiles and correction history. |
| **Stack** | `Gemini API` `Chrome Extension (MV3)` `TypeScript / JavaScript` `Firebase Firestore` |
| **Status** | 🟡 Active development · IEEE paper in progress |
| **Links** | [Repository](https://github.com/SAITEJA0217/formpilot) |

<br/>

<!-- ───────────── InternLink ───────────── -->

### 🌐 InternLink — AI-assisted internship platform

**A two-sided platform where students find internships and employers find candidates, with AI resume matching in the middle.**

| | |
|---|---|
| **Problem** | Students and recruiters both spend hours on manual screening; most internship portals are static listings with no matching, tracking or analytics. |
| **What I built** | Student dashboard, employer dashboard and admin portal; authentication; AI resume-to-role matching via the Gemini API; certificate generation; analytics dashboard. Designed the product, built front-end and back-end, and set up the Firebase architecture and deployment. |
| **Architecture** | Next.js / React front-end with Tailwind CSS · Firebase for auth, data and hosting · Gemini API for matching. Public site built with Vite + React + Tailwind. |
| **Stack** | `Next.js` `React` `TypeScript` `Tailwind CSS` `Firebase` `Gemini API` |
| **Status** | 🟡 In development — launch site ready, platform pre-launch |
| **Links** | [Website repo](https://github.com/SAITEJA0217/internlink-website) · [Launch page](https://github.com/SAITEJA0217/internlink-comming-soon) |

<br/>

### More projects

| Project | What it does | Stack | Repo |
|---|---|---|---|
| **BharatSkill** | AI career guidance — career mapping, resume analysis, skill assessment, personalised learning paths | React · Node.js · MongoDB · LLM | [bharatskill-graph-ai](https://github.com/SAITEJA0217/bharatskill-graph-ai) |
| **Resume Tailor AI** | Tailors a resume to a job description using the OpenAI API | React · Firebase · OpenAI API | [resume-tailor-ai](https://github.com/SAITEJA0217/resume-tailor-ai) |
| **Jarvis** | Personal AI assistant — conversational interface, desktop automation and productivity workflows (early stage) | Python · FastAPI · LLMs | [jarvis](https://github.com/SAITEJA0217/jarvis) |

<br/>

## 🔬 Research · Trustworthy browser agents

**Working title:** *FormPilot: Trustworthy Browser Agent for Web Form Automation through Dependency-Aware Semantic Reasoning, Evidence Grounding, and Confidence-Aware Decision-Making*

| | |
|---|---|
| **Research problem** | LLM-based browser agents act on web pages with no explicit account of *why* a value was chosen, *what* it was grounded in, or *how sure* the agent is — which makes them hard to trust on consequential forms. |
| **Direction** | Make each agent decision auditable: model dependencies between fields, ground values in user-provided evidence, attach calibrated per-field confidence, and use human corrections as a learning signal. |
| **Core concepts** | Dependency-aware semantic reasoning · Evidence grounding · Confidence-aware decision-making · Human-feedback learning · Explainable agent behaviour |
| **Status** | 🟡 IEEE Research — In Progress (target submission: 2026) |
| **Broader interests** | Agentic workflows · Multi-agent systems · Human–AI interaction · RAG for grounded generation |

<br/>

## Technical stack

Ordered by depth of use in shipped projects, not alphabetically.

| Area | Technology → how I use it |
|---|---|
| **AI & LLM** | **Gemini API** — agent reasoning in FormPilot, matching in InternLink · **OpenAI API** — resume tailoring · **LangChain / LangGraph** — agent and workflow orchestration · **RAG & vector databases** — grounded retrieval for LLM apps · **Prompt engineering** — structured, evidence-grounded outputs |
| **Frontend** | **React / Next.js** — all product UIs (InternLink, BharatSkill, Resume Tailor) · **TypeScript** — primary language across recent repos · **Tailwind CSS** — UI systems · **Vite** — InternLink website · **Chrome Extension (MV3)** — FormPilot |
| **Backend** | **FastAPI** — Python APIs and AI services · **Node.js / Express** — BharatSkill backend · **Python** — agents, scripting, ML |
| **Databases & cloud** | **Firebase (Auth · Firestore · Hosting)** — primary infrastructure for FormPilot and InternLink · **MongoDB** — BharatSkill · **MySQL / Supabase** — relational projects · **Vercel / Netlify** — deployment · **Docker** — containerised services |
| **ML foundations** | **TensorFlow / PyTorch** — coursework and experiments |
| **Tools** | Git / GitHub · Postman · Figma · Linux · VS Code |

<br/>

## Experience

**Founder & Full Stack Developer — InternLink**<br/>
Designed the product and its student/employer/admin roles; architected the Firebase data and auth layer; implemented AI resume matching with the Gemini API; built certificate generation and analytics dashboards; deployed the public launch site.

**AI Researcher / Engineer — FormPilot (IEEE research project)**<br/>
Defined the research framing (dependency-aware reasoning, evidence grounding, confidence-aware decisions); implemented the Chrome MV3 agent, per-field confidence scoring and a correction-based feedback loop; preparing the manuscript for IEEE submission.

**Member — Venture Launcher**

**Certifications** · Oracle OCI Foundations · IBM AI Fundamentals · Machine Learning (Coursera) · Google Generative AI (in progress)

<br/>

## Current focus

- 🧭 Shipping **FormPilot** and finishing the IEEE manuscript on trustworthy browser agents
- 🌐 Taking **InternLink** from launch site to live platform
- 🤖 Multi-agent systems and agentic workflows with **LangGraph**; RAG for grounded generation
- ☁️ Scalable AI deployment — **Docker**, cloud infrastructure
- 🌍 Open-source contributions in the AI-agent tooling space
- 🎯 Open to **AI/ML and software engineering internships** and research collaborations

<br/>

## Connect

**Interested in AI agents, trustworthy AI, or building intelligent products? Let's talk.**

[Portfolio](https://saiteja-space.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/saiteja-reddy-karka/) · [karkasaiteja4@gmail.com](mailto:karkasaiteja4@gmail.com) · [GitHub](https://github.com/SAITEJA0217)

