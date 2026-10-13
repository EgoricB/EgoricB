<div align="center">

<h1>Egor Borisov</h1>

<h3>Digital Humanities × AI × Data Engineering</h3>

<p>Researching and building tools for controlled delegation of tasks to AI agents, where humans set goals, constraints and checkpoints and stay in control of execution</p>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/LLM%20Agents-412991?style=flat" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/QGIS-589632?style=flat&logo=qgis&logoColor=white" />
<img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=plotly&logoColor=white" />
<img src="https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white" />
<img src="https://img.shields.io/badge/tidyverse-1A162D?style=flat&logo=tidyverse&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-003B57?style=flat&logo=sqlite&logoColor=white" />
<img src="https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/Zotero-CC2936?style=flat&logo=zotero&logoColor=white" />
<img src="https://img.shields.io/badge/Agile%2FScrum-0052CC?style=flat&logo=jira&logoColor=white" />
<img src="https://img.shields.io/badge/Paleography-8B5A2B?style=flat" />
<img src="https://img.shields.io/badge/Spatial%20Modeling-2E7D32?style=flat" />

</div>

---

## Current Projects

### Delegation Workbench
Research and development of a web system for controlled delegation of tasks to AI agents. The user defines the goal, context, constraints and allowed and forbidden actions. They review and approve or edit the agent's plan, set checkpoints and monitor the execution log, with the ability to pause, modify or stop the work at any moment.

**Research question:** how do task structure, upfront planning, mandatory clarifications and checkpoints affect the reliability, controllability, cost and efficiency of task execution across different LLMs?

**Planned outputs:** a working prototype, a set of reproducible tasks, agent trajectory logs, experimental data and design principles for human–AI delegation.

`status: research & development`

### Agent Autonomy under Uncertain Data (IA RAS)
An experimental environment, linked to Delegation Workbench, for studying the limits of AI agent autonomy on incomplete, noisy and ambiguous data. The agent compiles a description of an archaeological complex from a corpus of 372 excavation reports and links every claim to its sources. When it meets OCR errors, unreliable extractions or insufficient evidence, it has to choose between proceeding, checking the original, asking a human and withholding a conclusion.

**Experiment:** free execution vs. fixed checkpoints vs. uncertainty-triggered oversight, evaluated by correctness, completeness, unsupported claims, constraint compliance and cost of human interventions.

`status: corpus processed · agent layer and experiments in progress`

### Lavochkin Pipeline
A compact, independent Python + PostgreSQL pipeline for reproducible processing of digital collections. It is built on open NASA NTRS materials about NPO Lavochkin missions from 1965–1991, including later publications about these missions. The first sample of 30–50 PDFs goes through download, text extraction and normalization, and feature computation, with full provenance tracking of both documents and results.

**Core:** a queue of dependent jobs with retries and failure recovery. An ML model learns from measured job durations without a pre-labeled dataset, and the experiment compares a standard FIFO scheduler with duration-aware scheduling. A small web interface handles control.

`status: scaffold ready · NTRS metadata & document loader next` · [Repository](https://github.com/EgoricB/lavochkin_pipeline)

---

## Other Work

**NPO Lavochkin Virtual Museum.** Digitization and data structuring of the museum collection of NPO Lavochkin (Roscosmos). [Virtual museum](https://www.laspace.ru/virtual-museum/)

**DH Career Platform.** A career-guidance platform for humanities students, with DigComp-based self-assessment, skill-stack recommendations and job matching.

**Settlement Modeling with GIS.** Reconstruction of historical settlement patterns using Thiessen polygons, catchment zones and central place theory in QGIS. Results include a series of maps and 7 peer-reviewed publications.
