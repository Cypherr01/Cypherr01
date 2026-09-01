<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg?v=1">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg?v=1">
  <img src="./assets/banner-dark.svg?v=1" alt="Ashwini Tiwari — GenAI & Agentic AI Engineer" width="100%"/>
</picture>

</div>

<br/>

<table align="center" border="0">
<tr>
<td width="34%" align="center" valign="top">

<img src="./assets/status-card.svg?v=1" alt="System status card" width="320"/>

</td>
<td width="66%" valign="top">

### `cat about.md`

GenAI & Agentic AI Engineer, 2+ years shipping production agentic systems at **Hexaware Technologies**. Built **Quido**, an enterprise Agentic RAG platform (Python / FastAPI / Azure OpenAI) that cut repetitive L&D support queries by 70% and freed 106+ man-days a year for a Fortune 500 client. Independently designed **ARIA**, a full autonomous AI operating system — LangGraph reasoning core, multi-model router, 3-tier memory, 5 specialist agents. Enterprise Java depth from a 50+ repo AWS migration at Delta Air Lines.

Also currently running **Commitra** — an autonomous pipeline that teaches itself Python, SQL and Java in public, one commit a day, no human in the loop. It's what powers the live panel below.

</td>
</tr>
</table>

<br/>

<div align="center">

## `> projects --featured`

</div>

### 🧠 ARIA — Agentic Reasoning & Intelligence Architecture
**[Cypherr01/Aria](https://github.com/Cypherr01/Aria)** · Python · LangGraph · FastAPI · Gemini / Groq / Cohere

A full autonomous AI operating system built from scratch: a 7-node LangGraph reasoning core (Intent → Memory → Plan → Execute → Reflect → Synthesize → Write), a multi-model router health-checking 6 LLMs across 4 providers, 3-tier memory with time-decay, an 8-tool suite, and a Responsible AI layer running inline on every input and output. 3 phases shipped in 6 weeks, 168 tests passing, Phase 4 (voice + multi-user + plugin system) in progress.

<br/>

<div align="center">

### 🤖 Commitra — the pipeline that's building this GitHub graph for me

<img src="./assets/pipeline-commitra.svg?v=1" alt="Commitra live pipeline status" width="100%"/>

</div>

Commitra is a cron-driven educational engine I built and run myself: every day it picks the next topic from a roadmap, generates phase-aware, project-anchored lesson content through an LLM cascade, commits it to a public repo, and emails me a copy — zero manual intervention, and the invariant holds everywhere: **code controls the pipeline, the LLM only fills content.**

<details>
<summary><b>→ expand: how it actually works</b></summary>
<br/>

- **Roadmap** — a `.md` file per language defines the phase-by-phase curriculum; dropping a new one in `roadmap/` is the entire onboarding step.
- **LLM Cascade** — content generation proactively rotates across models before hitting token limits, rather than waiting for a call to fail.
- **Commit** — each lesson is validated against the "History Rule" (only concepts already introduced may be used) before it's written to the repo.
- **Notify** — an HTML email goes out with the full lesson the moment it lands.
- The numbers in the panel above aren't typed in by hand — a separate [GitHub Action](./.github/workflows/update-profile.yml) reads the three repos below every day and regenerates that SVG.

</details>

<br/>

**Live output, updated daily:**

| Language | Repo | Description |
|:---|:---|:---|
| 🐍 Python | [commitra-python](https://github.com/Cypherr01/commitra-python) | Foundations → DSA → backend engineering → LLMs & agentic AI |
| 🗄️ SQL | [commitra-sql](https://github.com/Cypherr01/commitra-sql) | Relational foundations → MySQL/PostgreSQL internals → production ops |
| ☕ Java | [commitra-java](https://github.com/Cypherr01/commitra-java) | Core Java → Spring ecosystem → microservices → Spring AI |

<br/>

<div align="center">

## `> stack --resolved`

<img src="./assets/dashboard.svg?v=1" alt="Skills and stack" width="100%"/>

## `> milestones`

<img src="./assets/milestones.svg?v=1" alt="Milestones" width="100%"/>

<br/><br/>

### `> connect with - Ashwini`

<a href="mailto:ashwinco7524@gmail.com"><img src="https://img.shields.io/badge/Email-A56F63?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/Cypherr01"><img src="https://img.shields.io/badge/GitHub-0F3040?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/ashwini-tiwari-83a65421a"><img src="https://img.shields.io/badge/LinkedIn-464858?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Cypherr01&color=a56f63&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views"/>

<br/><br/>

*7 public repos // updated automatically, not manually.*

</div>



this avatar which is being reflected in the the banner and status card...is there anything that we can change that and make it look more human