<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg?v=5">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg?v=5">
  <img src="./assets/banner-dark.svg?v=5" alt="Ashwini Tiwari — AI Systems Engineer" width="100%"/>
</picture>

<br/>

<table border="0" width="100%">
<tr>
<td width="34%" align="left" valign="top">

<img src="./assets/status-card.svg?v=5" alt="System status card" width="320"/>

</td>
<td width="66%" valign="top">

### `cat about.md`

```
$ whoami
ai systems engineer -- pune, in (open to relocation)

$ cat experience.log
[jan 2024 - apr 2026]  hexaware technologies
                        genai & agentic ai + java backend, 2+ yrs
                        - built quido, hexavarsity's agentic rag assistant
                        - migrated 50+ legacy repos to aws (delta air lines)

[apr 2026 - present]   independent, post-hexaware
                        - designed + built aria from scratch: 3 phases, 6 weeks
                        - running commitra: a self-teaching, daily-commit engine

$ cat status.log
open to ai systems / agentic engineering roles.
commitra is what's driving the live panel below -- no manual edits.
```

</td>
</tr>
</table>

<br/>

## `> projects --featured`

### QUIDO -- AGENTIC RAG SYSTEM
Built at Hexaware, for Hexavarsity L&D
- Stack: Python -- FastAPI -- LangGraph -- LangChain -- Azure OpenAI -- BM25 -- Azure

<img src="./assets/quido-pipeline.svg?v=5" alt="Quido agentic RAG pipeline" width="100%"/>

```
$ cat quido/CHANGELOG.md

v1.0 -- production rag assistant
  - hybrid retrieval: dense (chromadb) + sparse bm25 + cross-encoder rerank
  - modular pipeline: qaorchestrator -> retriever -> guardrails -> formatter
  - hallucination check via sentence-level cosine similarity + grounding
  - rbac (13 scopes), jwt auth, pii redaction, prompt-injection prevention
  - result: 70% of support query volume eliminated, 106+ man-days saved/yr

v2.0 -- agentic rewrite (same codebase, self-directed)
  - fixed intent -> retrieval -> answer sequence replaced with a langgraph
    conditional-routing graph -- agent decides retrieval necessity, tool
    selection, and query decomposition per request
  - multi-hop retrieval loop: reflectionagent scores groundedness and
    completeness via cosine similarity, triggers bounded re-retrieval
  - multi-part questions decomposed into sub-queries, run in parallel via
    asyncio.gather, each through the hybrid retrieval pipeline
  - central toolrouter: retrieval, calculation, lms read/write -- single-
    purpose rag became general-purpose task execution

no public repo -- built inside hexaware's codebase. diagram above is the
closest thing to a walkthrough.
```

<br/>

### WORKFLOW AUTOMATION -- POWER PLATFORM
Built at Hexaware, for Hexavarsity L&D
- Stack: Power Automate -- Microsoft Graph API -- Outlook -- Teams

<img src="./assets/automate-pipeline.svg?v=5" alt="Workflow automation pipeline" width="100%"/>

```
$ cat automate/PIPELINE.log

[trigger]   scheduled + form-based triggers kick off the flow
[automate]  power automate + graph api -- teams messaging, outlook mail-merge
[user]      personalized message lands in teams + inbox, ack tracked
[owner]     responses roll up into a management dashboard, org-wide

result: 80%+ reduction in manual coordination effort, l&d + hr, org-wide
```

<br/>

### COMMITRA -- SELF-TEACHING PIPELINE
Independent, post-Hexaware
- Stack: Python -- GitHub Actions -- LLM cascade (multi-provider)

<img src="./assets/pipeline-commitra.svg?v=5" alt="Commitra live pipeline status" width="100%"/>

Commitra is a cron-driven engine I built and run myself: every day it picks the next topic from a roadmap, generates phase-aware, project-anchored lesson content through an LLM cascade, commits it to a public repo, and emails me a copy. Zero manual intervention. The invariant holds everywhere: **code controls the pipeline, the LLM only fills content.**

<details>
<summary>expand -- how it actually works</summary>

```
$ cat commitra/PIPELINE.log

[roadmap]      .md file per language defines the phase-by-phase curriculum
[llm cascade]  rotates across models proactively, before hitting token limits
[commit]       validated against the "history rule" -- only prior concepts allowed
[notify]       html email fires the moment the lesson lands

note: the numbers in the diagram above aren't typed by hand -- a separate
github action (.github/workflows/update-profile.yml) reads the three repos
below every day and regenerates it.
```

</details>

<br/>

**Live output, updated daily:**

| Language | Repo | Description |
|:---|:---|:---|
| PYTHON | [commitra-python](https://github.com/Cypherr01/commitra-python) | foundations -> dsa -> backend engineering -> llms & agentic ai |
| SQL | [commitra-sql](https://github.com/Cypherr01/commitra-sql) | relational foundations -> mysql/postgresql internals -> production ops |
| JAVA | [commitra-java](https://github.com/Cypherr01/commitra-java) | core java -> spring ecosystem -> microservices -> spring ai |

<br/>

### ARIA -- AGENTIC AI SYSTEM
Independent, post-Hexaware -- **[Cypherr01/Aria](https://github.com/Cypherr01/Aria)**
- Stack: Python -- LangGraph -- FastAPI -- Gemini / Groq / Cohere

<img src="./assets/aria-pipeline.svg?v=5" alt="ARIA reasoning pipeline" width="100%"/>

```
$ cat aria/ARCHITECTURE.log

[graph]   7-node langgraph core -- intent -> memory -> plan -> execute ->
          reflect -> synthesize -> remember
[router]  multi-model router, health-checked across 6 llms / 4 providers
[memory]  3-tier -- working (summarized) / episodic (time-decayed) / semantic (rag)
[tools]   8-tool suite behind a central registry
[safety]  responsible-ai layer running inline on every input and output

status: phase 4 of 4 in progress (voice, multi-user, plugin system)
shipped: 3 phases in 6 weeks, 168 tests written, 85% passing
```

<br/>

## `> stack -- what-i-build-with`

<img src="./assets/dashboard.svg?v=5" alt="Skills and stack" width="100%"/>

## `> milestones`

<img src="./assets/milestones.svg?v=5" alt="Milestones" width="100%"/>

<br/>

### `> connect with - Ashwini`

<a href="mailto:ashwinco7524@gmail.com"><img src="https://img.shields.io/badge/Email-A56F63?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/Cypherr01"><img src="https://img.shields.io/badge/GitHub-0F3040?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/ashwini-tiwari-83a65421a"><img src="https://img.shields.io/badge/LinkedIn-464858?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://www.instagram.com/_cipher01_?igsi=MXBiaGRnMDVwMDE2eQ=="><img src="https://img.shields.io/badge/Instagram-D99B7F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Cypherr01&color=a56f63&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views"/>

<br/>

*8 public repos — updated automatically, because apparently even my portfolio has a DevOps team.*
