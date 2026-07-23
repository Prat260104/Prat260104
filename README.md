<div align="center">

<img src="./aboutme.svg" width="100%" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:00ff9c&height=140&section=header&text=PRATEEK%20RAI&fontSize=42&fontColor=00ff9c&fontAlignY=40&animation=fadeIn&desc=backend%20//%20systems%20//%20open-source&descAlignY=60&descColor=39ff14" width="100%"/>

<a href="https://github.com/Prat260104">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2800&pause=900&color=39FF14&center=true&vCenter=true&width=640&lines=root%40prateek%3A~%24+whoami;GSoC+2026+%40+InVesalius+(PSF);20%2B+merged+PRs+in+production+code;Backend+%2B+Distributed+Systems+Engineer;Building+things+that+don't+fall+over" alt="Typing SVG" />
</a>

</div>

<br>

```bash
prateek@systems:~$ cat status.log
[OK]  Google Summer of Code 2026 -- InVesalius 
[OK]  Open Source Contributor -- CNCF , K8s , GSoC , LFX
[OK]  Technical Lead -- NextGen Supercomputing Club, KIET
prateek@systems:~$ _
```

<br>

## `$ cat about.md`

```yaml
role:       AI/ML & Full Stack Hybrid Engineer
building:    distributed systems, AI-integrated backends, open-source infra
education:
  - B.Tech, CS (AI specialization) @ KIET Group of Institutions   | 2024 - 2028
  - BS, Data Science @ IIT Madras                                  | 2024 - 2028
focus:       Java/Spring Boot backends, systems design, applied AI/ML, OSS, fastApi, django, Gen AI
```

<br>

## `$ ./run experience.sh`

<table>
<tr>
<td width="100%">

### 🩻 Google Summer of Code 2026 — InVesalius 
<sub><i>Open Source Software Engineer · May 2026 – Sept 2026</i></sub>

- Designed and shipped a full **.3MF export/import pipeline**, extending InVesalius's pubsub dispatcher to support the 3D-manufacturing format used by OrcaSlicer, PrusaSlicer, and Bambu Studio
- Engineered **bidirectional LPS ↔ Z-up coordinate transforms** with vectorized NumPy — no per-element loops, tested on meshes up to 5M triangles
- Built multi-surface export with per-vertex RGBA color mapping via the `lib3mf` ColorGroup API, scalar normalization, and safe fallback handling
- Wrote CI-grade unit tests (geometry round-trips at 1e-5mm tolerance) validated across macOS, Linux, and Windows
- **20+ merged PRs** — UI thread race-condition fix, VTK SSAO rendering integration, DICOM metadata extraction, multi-object UI workflows

</td>
</tr>
<tr>
<td width="100%">

### 🛰️ Open Source Contributor — CNCF , K8s , GSoC , LFX <sub>(CNCF)</sub>
<sub><i>Jun 2025 – Present</i></sub>

- Building **E2E crash-recovery tests** for a distributed replication system — validating satellite nodes resume layer-level sync after mid-replication failure with zero redundant re-replication
- Writing E2E coverage for **SPIFFE/SPIRE zero-trust registration** (join-token, x509pop, sshpop), including crash-during-handshake paths with no prior coverage
- Verifying fault-tolerant, idempotent replication across backends in **Go**

</td>
</tr>
<tr>
<td width="100%">

### 🧑‍🏫 Technical Lead — NextGen Supercomputing Club, KIET
<sub><i>Nov 2025 – Present</i></sub>

- Leading technical mentorship for 20+ students on backend systems, REST API design, and ML/CV
- Running sessions on DSA and system design for competitive programming prep

</td>
</tr>
</table>

<br>

## `$ ls projects/`

<table>
<tr>
<td width="50%" valign="top">

**⚡ Skill Loop** — *Distributed Skill Exchange Platform*
[`GitHub →`](https://github.com/Prat260104)

Horizontally scalable microservices backend — Spring Boot (Java 21) for auth/profile/session orchestration, FastAPI for AI evaluation. Token-bucket rate limiting, JWT refresh rotation, indexed PostgreSQL access layer designed for stateless horizontal scale. AI skill evaluator running RAG (LangChain + ChromaDB) for live technical interviews over WebSockets, with HuggingFace transformer sentiment analysis on session feedback.

`Java` `Spring Boot` `FastAPI` `PostgreSQL` `LangChain` `ChromaDB` `WebSockets`

</td>
<td width="50%" valign="top">

**🧊 .3MF Export/Import Pipeline** — *InVesalius (pre-GSoC proof of concept)*
[`GitHub →`](https://github.com/Prat260104)

Prototype proving full .3MF export with per-vertex RGBA via the `lib3mf` ColorGroup API and correct geometry orientation, built to validate feasibility before the GSoC coding period. NumPy-vectorized LPS→Z-up transform via `vtk_to_numpy()`, with ColorGroup/TriangleProperties XML validated for slicer compatibility.

`Python` `NumPy` `VTK` `lib3mf`

</td>
</tr>
</table>

<br>

## `$ cat stack.json`

<div align="center">

**Languages**
<br>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=39FF14&labelColor=0d1117" />

**Backend & Systems**
<br>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=39FF14&labelColor=0d1117" />

**ML / AI (Applied)**
<br>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=0d1117&labelColor=0d1117" />
<img src="https://img.shields.io/badge/ChromaDB-39FF14?style=for-the-badge&labelColor=0d1117" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Transformers-39FF14?style=for-the-badge&labelColor=0d1117" />

**Cloud & DevOps**
<br>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=39FF14&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=39FF14&labelColor=0d1117" />

</div>

<br>

## `$ cat certifications.md`

- 🎓 **AWS Certified AI Practitioner** — Amazon Web Services
- 🎓 **AWS Certified Cloud Practitioner** — Amazon Web Services
- 🎓 **Foundations of Programming and Data Science** — IIT Madras

<br>

## `$ curl stats/`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Prat260104&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39FF14&icon_color=39FF14&text_color=c9d1d9&ring_color=39FF14" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prat260104&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39FF14&text_color=c9d1d9" width="30%" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Prat260104&theme=github-dark-blue&hide_border=true&background=0d1117&ring=39FF14&fire=39FF14&currStreakLabel=39FF14" width="65%" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Prat260104&theme=github-compact&bg_color=0d1117&color=39FF14&line=39FF14&point=ffffff&hide_border=true" width="90%" />

</div>

<!--
  Optional: animated contribution snake — add .github/workflows/snake.yml (provided alongside this
  file) and this repo will auto-generate a dark/light snake SVG on a schedule. Once it's live, swap
  the img below in for the graph above, or place it underneath.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Prat260104/Prat260104/output/github-contribution-grid-snake-dark.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/Prat260104/Prat260104/output/github-contribution-grid-snake.svg" />
</picture>
-->

<br>

## `$ ./connect.sh`

<div align="center">

<a href="https://www.linkedin.com/in/prateek-rai">
  <img src="https://img.shields.io/badge/LinkedIn-Prateek_Rai-0A66C2?style=for-the-badge&logo=linkedin&logoColor=39FF14&labelColor=0d1117" />
</a>
<a href="https://github.com/Prat260104">
  <img src="https://img.shields.io/badge/GitHub-Prat260104-181717?style=for-the-badge&logo=github&logoColor=39FF14&labelColor=0d1117" />
</a>
<a href="mailto:prateekrai903@gmail.com">
  <img src="https://img.shields.io/badge/Email-prateekrai903-D14836?style=for-the-badge&logo=gmail&logoColor=39FF14&labelColor=0d1117" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=Prat260104&label=PROFILE%20VIEWS&color=39FF14&style=for-the-badge&labelColor=0d1117" />

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff9c,100:0d1117&height=100&section=footer" width="100%"/>

<sub><i>strong systems outlive fancy dashboards.</i></sub>

</div>
