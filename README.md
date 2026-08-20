<div align="center">

<a href="./README.md"><img src="https://img.shields.io/badge/EN-English-0D1117?style=for-the-badge&labelColor=E5813E"></a>
<a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/PT--BR-Portugu%C3%AAs-0D1117?style=for-the-badge&labelColor=212E38"></a>

<img width="100%" alt="Lucas Manoel — AI Systems Engineer" src="https://raw.githubusercontent.com/lucas-ai-max/lucas-ai-max/main/assets/hero.svg" />

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=21&duration=3200&pause=900&color=E5813E&center=true&vCenter=true&width=780&height=44&lines=I+build+AI+agents+that+run+in+production;Construo+agentes+de+IA+que+rodam+em+produ%C3%A7%C3%A3o;Multi-agent+orchestration+%C2%B7+WhatsApp+%C2%B7+Voice+%C2%B7+RAG;Not+demos.+Systems+that+invoice." />

</div>

---

> **I turn manual, people-dependent operations into AI systems that run on their own.**
>
> Conversational agents that sell and schedule. Pipelines that read regulated documents and cite their sources. Media automation that scales content production without an editor per video.
>
> Not demos. Not proofs of concept. Architecture built to survive contact with real users.

---

## What I build

<table>
<tr>
<td width="33%" valign="top">

### 🗣 Conversational Agents

Autonomous agents that prospect, qualify and schedule over WhatsApp and Instagram DM — with routing logic that decides which agent answers.

`Agentes-Avos` · `sistema-mentores`

</td>
<td width="33%" valign="top">

### 🧠 Applied Intelligence

Systems that read, classify and score — turning unstructured reality into decisions a team can act on, with citations instead of hallucinations.

`processia` · `ai-first` · `ragia`

</td>
<td width="33%" valign="top">

### ⚙️ Media & Ops Automation

Pipelines that erase manual work at scale: video captioning, voice cloning and commercial funnel analytics.

`pycaps-api` · `qwentts` · `dash-kommo`

</td>
</tr>
</table>

---

## Selected work

<table>
<tr>
<td width="50%" valign="top">

#### 🔺 ai-first — Automated Bug Triage
Mastra agents that classify incoming bugs in ClickUp: severity (P0–P3), affected module, origin channel and suggested owner — then post structured reasoning and move the ticket.

Ships with a **100% recall requirement on sensitive-data detection (LGPD)** — a false negative there is a compliance incident, not a bug.

`Multi-agent` `Mastra` `ClickUp` `LGPD`

[→ Repository](https://github.com/lucas-ai-max/ai-first)

</td>
<td width="50%" valign="top">

#### 🔺 Agentes-Avos — Two Agents, One Process
An SDR agent and a scheduling agent registered in the same Mastra runtime, sharing one Meta webhook port.

A router reads a Postgres whitelist to decide which agent owns each DM — **no HTTP hop between processes**, so there is no second service to deploy, monitor or lose.

`Multi-agent` `Instagram DM` `Google Calendar` `Postgres`

[→ Repository](https://github.com/lucas-ai-max/Agentes-Avos)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔺 processia — Legal Document Analysis
Reads full case files with Docling and answers questions about them through an LLM — **every answer carries the page and file it came from.**

In a regulated domain, an answer you cannot trace is worse than no answer.

`Document AI` `Docling` `Streamlit` `Supabase`

[→ Repository](https://github.com/lucas-ai-max/processia)

</td>
<td width="50%" valign="top">

#### 🔺 sistema-mentores — Debate as Architecture
A panel of AI mentors on WhatsApp. An orchestrator approves or rejects the incoming question, mentors debate across two fixed rounds, and the system delivers a single synthesized answer.

Structured disagreement instead of one model's first guess.

`Multi-agent` `FastAPI` `Evolution API` `WhatsApp`

[→ Repository](https://github.com/lucas-ai-max/sistema-mentores)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔺 pycaps-api — Video Captioning at Scale
FastAPI service that takes raw footage and returns it with animated captions burned in — containerized, so it scales horizontally instead of waiting on an editor.

`FastAPI` `Docker` `Video processing`

[→ Repository](https://github.com/lucas-ai-max/pycaps-api)

</td>
<td width="50%" valign="top">

#### 🔺 ragia — RAG from First Principles
Support conversations in, question/answer pairs out: OpenAI generates the pairs, embeddings are computed per pair, and everything lands in Supabase with pgvector.

Small on purpose — it is the retrieval layer, readable end to end.

`RAG` `Embeddings` `pgvector` `Python`

[→ Repository](https://github.com/lucas-ai-max/ragia)

</td>
</tr>
</table>

---

## Stack

<div align="center">

**Agents & Orchestration**

<img src="https://skillicons.dev/icons?i=typescript,python,fastapi&theme=dark" height="42">
<img src="https://img.shields.io/badge/Mastra-0D1117?style=for-the-badge&logoColor=E5813E">
<img src="https://img.shields.io/badge/CrewAI-0D1117?style=for-the-badge&logoColor=E5813E">
<img src="https://img.shields.io/badge/n8n-0D1117?style=for-the-badge&logo=n8n&logoColor=E5813E">

**Models & Retrieval**

<img src="https://img.shields.io/badge/OpenAI-0D1117?style=for-the-badge&logo=openai&logoColor=E5813E">
<img src="https://img.shields.io/badge/Claude-0D1117?style=for-the-badge&logo=anthropic&logoColor=E5813E">
<img src="https://img.shields.io/badge/Gemini-0D1117?style=for-the-badge&logo=googlegemini&logoColor=E5813E">
<img src="https://img.shields.io/badge/pgvector-0D1117?style=for-the-badge&logo=postgresql&logoColor=E5813E">

**Data & Infra**

<img src="https://skillicons.dev/icons?i=supabase,postgres,docker,redis,vercel,nextjs&theme=dark" height="42">

</div>

---

## Engineering rhythm

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lucas-ai-max/lucas-ai-max/output/snake-dark.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/lucas-ai-max/lucas-ai-max/output/snake-light.svg">
</picture>

</div>

---

<div align="center">

### Got a manual process that shouldn't be manual?

<a href="https://www.linkedin.com/in/lucas-manoel-9066a31a9/"><img src="https://img.shields.io/badge/LinkedIn-Lucas%20Manoel-0D1117?style=for-the-badge&logo=linkedin&logoColor=E5813E"></a>

<sub>Reply within 24h · Resposta em até 24h</sub>

</div>
