<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:000000,50:1E40AF,100:3B82F6&height=220&section=header&text=Ashutosh%20Gauniyal&fontSize=52&fontColor=FFFFFF&fontAlignY=40&desc=AI%20Engineer%20and%20Full-Stack%20Developer%20%7C%20Christchurch%2C%20NZ&descSize=18&descColor=E2E8F0&descAlignY=60&animation=fadeIn" width="100%" alt="Ashutosh Gauniyal" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=3B82F6&center=true&vCenter=true&width=760&lines=%24+whoami+%E2%86%92+AI+engineer+and+full-stack+developer;%24+stack+%E2%86%92+Python+%7C+C%23+.NET+%7C+React+%7C+TypeScript+%7C+PostgreSQL;%24+shipping+%E2%86%92+production+platforms+for+paying+clients;%24+building+%E2%86%92+DataLens%2C+a+natural-language+data+query+agent;%24+principle+%E2%86%92+compute+the+answer%2C+never+guess+it" alt="Typing SVG" />

<br/>

![Degree](https://img.shields.io/badge/BSc-Computer_Science-1E40AF?style=flat-square&labelColor=0D1117)
![University](https://img.shields.io/badge/University_of-Canterbury-1E40AF?style=flat-square&labelColor=0D1117)
![Location](https://img.shields.io/badge/Christchurch-New_Zealand-1E40AF?style=flat-square&labelColor=0D1117)
![Work Rights](https://img.shields.io/badge/Full_NZ-Work_Rights-1E40AF?style=flat-square&labelColor=0D1117)

<br/>

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-000000?style=for-the-badge&logo=vercel&logoColor=FFFFFF)](https://ashutoshgauniyal.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-1E40AF?style=for-the-badge&logo=linkedin&logoColor=FFFFFF)](https://linkedin.com/in/ashutosh-gauniyal)
[![Email](https://img.shields.io/badge/EMAIL-3B82F6?style=for-the-badge&logo=gmail&logoColor=FFFFFF)](mailto:ashutoshgauniyal2004@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-0D1117?style=for-the-badge&logo=github&logoColor=FFFFFF)](https://github.com/ashgaun)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ashgaun&style=flat-square&color=1E40AF&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/ashgaun?style=flat-square&color=1E40AF&labelColor=0D1117&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/ashgaun?style=flat-square&color=1E40AF&labelColor=0D1117&label=STARS)

</div>

---

## `~$ cat about.md`

I build software end to end, from the first client conversation through to handover, and I have delivered production systems for two paying clients since starting my practice. My work sits where full-stack engineering meets applied AI, and I care most about systems where answers are computed rather than generated on a guess. Before anything ships, I audit it against its own specification as a sceptical reviewer.

```bash
ROLE     = "AI Engineer and Full-Stack Developer"
EXP      = "Contracting since Feb 2026 | UC graduate, Aug 2025"
DOMAIN   = ["Professional Services", "Industrial Automation", "Manufacturing", "EdTech"]
STACK    = ["Python", "C# .NET", "TypeScript", "React", "PostgreSQL", "FastAPI"]
OPEN_TO  = ["Software Engineer", "Full-Stack Developer", "AI Engineer"]
```

---

## `~$ ls tech-stack/`

<div align="center">

**Languages**

![Languages](https://skillicons.dev/icons?i=python,cs,ts,js,cpp,java,bash)

**Backend and APIs**

![Backend](https://skillicons.dev/icons?i=fastapi,dotnet,nodejs,express)

**Frontend**

![Frontend](https://skillicons.dev/icons?i=react,tailwind,vite,threejs,html,css)

**Data and Infrastructure**

![Data](https://skillicons.dev/icons?i=postgres,supabase,mongodb,docker,git,github,azure)

</div>

---

## `~$ cat specialisation.txt`

<div align="center">

![RAG](https://img.shields.io/badge/RAG_Pipelines-1E40AF?style=for-the-badge&logoColor=FFFFFF)
![Agents](https://img.shields.io/badge/Agentic_Workflows-1E40AF?style=for-the-badge&logoColor=FFFFFF)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-1E40AF?style=for-the-badge&logoColor=FFFFFF)
![TextToSQL](https://img.shields.io/badge/Text_to_SQL-3B82F6?style=for-the-badge&logoColor=FFFFFF)
![RBAC](https://img.shields.io/badge/Role_Based_Access_Control-3B82F6?style=for-the-badge&logoColor=FFFFFF)
![CI](https://img.shields.io/badge/CI_Quality_Gates-3B82F6?style=for-the-badge&logoColor=FFFFFF)

</div>

---

## `~$ cat expertise.md`

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| Full-Stack Development | Advanced | React with TypeScript on the frontend, FastAPI and ASP.NET Core on the backend, shipped to production for paying clients |
| AI Engineering | Advanced | RAG pipelines, multi-agent orchestration, tool-calling, context engineering, MCP server integration |
| Database Design | Advanced | PostgreSQL schema design, versioned migrations, Entity Framework Core, row-level security policies |
| API and Security | Intermediate | REST design, JWT authentication, deny-by-default authorisation, rate limiting, request validation |
| Data and Analytics | Intermediate | ETL pipeline design, data quality auditing, star schema modelling, Power BI with DAX |
| Engineering Practice | Intermediate | Trunk-based Git workflow, GitHub Actions, test-driven development, code review, Docker |

---

## `~$ ls projects/`

<details open>
<summary><b>DataLens — Natural-Language Data Query Agent</b></summary>

<br/>

Upload any CSV or Excel file and ask questions about it in plain English. Answers stream back as they compute, with an expandable panel showing the plan, the generated SQL and the result set.

| | |
| :--- | :--- |
| **Stack** | FastAPI, React, TypeScript, DuckDB, CrewAI, Tailwind |
| **Scale** | Exact aggregates over 100,000+ rows returned in milliseconds |
| **Impact** | Text-to-SQL architecture executes real SQL rather than passing rows to the model, so answers are computed rather than inferred |

Narrowed the attack surface to a single validated read-only SQL tool over multiple loosely validated ones, keeping failure modes auditable. Audited the finished system as a sceptical reviewer and found seven defects, including a silent aggregation bug returning wrong rankings, each fixed against independently computed ground truth.

</details>

<details>
<summary><b>CRM Platform — Nexia Christchurch (Client Work)</b></summary>

<br/>

A full-stack CRM covering a five-stage sales pipeline, client records and follow-up tracking, replacing a manual spreadsheet process.

| | |
| :--- | :--- |
| **Stack** | React, FastAPI, Supabase, PostgreSQL, Tailwind |
| **Scale** | Built for 20 users across three roles, shipped in six weeks |
| **Impact** | Replaced manual spreadsheet reporting with live dashboard analytics |

Designed the database schema with versioned migrations and a REST API over it. Enforced access across three user roles with row-level security, validated by automated integration tests across every endpoint. Gathered requirements from the CEO and Marketing Head, wrote the specification, and demoed the finished system to secure sign-off at handover. Source is private client work.

</details>

<details>
<summary><b>LEION Engineering Website (Client Work)</b></summary>

<br/>

A production website and enquiry channel for a weighing systems manufacturer with no prior search presence.

| | |
| :--- | :--- |
| **Stack** | React, FastAPI, MongoDB Atlas, Tailwind, Render |
| **Scale** | Four international markets, 18 pages indexed |
| **Impact** | Lifted inbound enquiries by 25% |

Built the backend with request validation, email integration, rate limiting and first-party analytics, turning a static brochure brief into a working enquiry channel. Deployed with DNS and SSL, implemented technical SEO with structured data and sitemaps, and documented handover so the client runs the site independently.

**[Live site](https://www.leiongroup.com)**

</details>

<details>
<summary><b>TechSolve Support Analytics — Pipeline and Dashboard</b></summary>

<br/>

An end-to-end analytics pipeline and operational dashboard over an IT service desk ticket dataset.

| | |
| :--- | :--- |
| **Stack** | Python, pandas, Power BI, DAX |
| **Scale** | ~100,000 tickets across 49 columns, July 2023 to March 2025 |
| **Impact** | Caught a misleading SLA KPI before it reached management |

Traced a 41-point SLA reporting discrepancy to a flat 120.5h median across all priority tiers, identifying it as a data artefact rather than team performance. Consolidated 32 inconsistent category values into a five-category taxonomy with automated coverage checks on every pipeline run, correcting a 2,304-ticket undercount. Modelled a star schema with 15 DAX measures to deliver a four-page dashboard, self-taught within the project window.

</details>

<details>
<summary><b>Petition Platform API</b></summary>

<br/>

A backend REST API for a petition platform.

| | |
| :--- | :--- |
| **Stack** | TypeScript, Node.js, MySQL |
| **Scale** | Full CRUD API with authentication and image handling |
| **Impact** | Covers user authentication, petition management, supporter tiers and MySQL persistence |

**[View repository](https://github.com/ashgaun/petition-platform-api)**

</details>

---

## `~$ git log --experience`

### `Aug 2026 — Present` &nbsp;·&nbsp; **AI Engineer and Software Developer** &nbsp;·&nbsp; Southern Alps Automation (Contract)

- Build and ship production features end to end on a commercial platform, working with .NET on the backend and React with TypeScript on the frontend
- Engineer LLM agent workflows in production, covering multi-agent orchestration, context engineering and MCP server integration with Claude Code
- Model the domain in PostgreSQL with Entity Framework Core, keeping business rules in shared modules so they are defined once
- Implement JWT authentication with role-based access and deny-by-default authorisation
- Develop in a shared codebase alongside another engineer, writing tests first on schema, authentication and calculation paths, with every merge gated on CI

`.NET 8` `React 19` `TypeScript` `PostgreSQL` `Entity Framework Core` `Claude Code` `MCP`

### `Feb 2026 — Present` &nbsp;·&nbsp; **Contract Software Developer** &nbsp;·&nbsp; Self-Employed (Sole Trader)

- Won client engagements through direct outreach and fixed-fee proposals, delivering each solo and retaining them on ongoing support after handover
- Scoped each project into a written specification before building, holding scope steady and keeping both deliveries on schedule
- Presented finished systems to non-technical decision-makers through live demos and plain-language documentation, securing sign-off from both clients
- Delivered a full-stack CRM and a production website across two industries, covering database design, API development and deployment

`React` `FastAPI` `Supabase` `PostgreSQL` `MongoDB Atlas` `Render`

### `Nov 2023 — Present` &nbsp;·&nbsp; **Mathematics Tutor** &nbsp;·&nbsp; NumberWorks'nWords (Part-time)

- Tutored up to 12 students a day across Year 1 to Year 13, designing individual learning plans and adjusting difficulty after each assessment
- Ran centre operations alongside tutoring, covering scheduling, attendance and progress reporting to parents

`Curriculum Design` `Assessment` `Stakeholder Communication`

---

## `~$ cat achievements.md`

<div align="center">

| Achievement | Detail |
| :--- | :--- |
| Two paying clients delivered | Full-stack systems shipped solo, both retained on ongoing support |
| President, UC Indian Student Association | Grew membership past 500 and secured official campus affiliation |
| Events programme profit | Ran a programme generating over $5K in profit across events of 200 to 300 attendees |
| Mathematics GPA | 8.5 out of 9 across mathematics courses in the Computer Science degree |
| Inbound enquiry lift | 25% increase for LEION Engineering after launch |
| SLA reporting defect caught | Traced a 41-point discrepancy to a data artefact before it reached management |

</div>

---

## `~$ cat education.txt`

<div align="center">

[![University of Canterbury](https://img.shields.io/badge/University_of_Canterbury-BSc_Computer_Science_·_Minor_in_Mathematics_·_2022--2025-1E40AF?style=for-the-badge&logoColor=FFFFFF&labelColor=0D1117)](https://www.canterbury.ac.nz)

![Bootcamp](https://img.shields.io/badge/Outskill-Generative_AI_Engineers_Bootcamp_·_2025-3B82F6?style=for-the-badge&labelColor=0D1117)

</div>

---

## `~$ github --stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ashgaun&show_icons=true&count_private=true&hide_border=true&bg_color=000000&title_color=3B82F6&icon_color=1E40AF&text_color=FFFFFF" height="165" alt="GitHub Stats" />
<img src="https://streak-stats.demolab.com?user=ashgaun&hide_border=true&background=000000&ring=3B82F6&fire=3B82F6&currStreakLabel=3B82F6&sideLabels=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=94A3B8&stroke=1E40AF" height="165" alt="GitHub Streak" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ashgaun&layout=compact&langs_count=8&hide_border=true&bg_color=000000&title_color=3B82F6&text_color=FFFFFF" height="150" alt="Top Languages" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=ashgaun&theme=discord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" width="100%" alt="Trophies" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ashgaun&bg_color=000000&color=FFFFFF&line=3B82F6&point=1E40AF&area=true&area_color=1E40AF&hide_border=true" width="100%" alt="Activity Graph" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ashgaun&theme=github_dark" width="100%" alt="Profile Details" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ashgaun&theme=github_dark" height="180" alt="Repos per Language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ashgaun&theme=github_dark" height="180" alt="Most Commit Language" />

<br/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ashgaun&theme=github_dark" height="180" alt="Stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ashgaun&theme=github_dark&utcOffset=13" height="180" alt="Productive Time" />

<br/><br/>

<img src="https://raw.githubusercontent.com/ashgaun/ashgaun/output/github-snake-dark.svg" width="100%" alt="Contribution Snake" />

</div>

---

## `~$ cat current-focus.yaml`

```yaml
learning:
  - Advanced agentic patterns and evaluation for LLM systems
  - Azure services and cloud deployment for .NET workloads

building:
  - Oasis Ops platform at Southern Alps Automation (.NET 8, React 19, PostgreSQL)
  - DataLens, a natural-language data query agent over any uploaded dataset
  - A RAG knowledge-base assistant over a documentation corpus

exploring:
  - Model Context Protocol servers and Claude Code agent workflows
  - Text-to-SQL architectures and query-plan transparency

open_to:
  - Software Engineer
  - Full-Stack Developer
  - AI Engineer
  - Based in Christchurch, open to relocation NZ-wide
```

---

<div align="center">

## `~$ ./connect.sh`

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-000000?style=for-the-badge&logo=vercel&logoColor=FFFFFF)](https://ashutoshgauniyal.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-1E40AF?style=for-the-badge&logo=linkedin&logoColor=FFFFFF)](https://linkedin.com/in/ashutosh-gauniyal)
[![Email](https://img.shields.io/badge/EMAIL-3B82F6?style=for-the-badge&logo=gmail&logoColor=FFFFFF)](mailto:ashutoshgauniyal2004@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-0D1117?style=for-the-badge&logo=github&logoColor=FFFFFF)](https://github.com/ashgaun)

<br/>

*Build systems that compute the answer, then audit them before anyone else has to.*

<img src="https://capsule-render.vercel.app/api?type=wave&color=0:3B82F6,50:1E40AF,100:000000&height=140&section=footer" width="100%" alt="Footer" />

</div>
