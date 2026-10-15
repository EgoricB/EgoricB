<div align="center">

<h1>Egor Borisov</h1>

<h3>Digital Humanities × AI × Data Engineering</h3>

<p>Researching and building tools for controlled delegation of tasks to AI agents, where humans set goals, constraints and checkpoints and stay in control of execution</p>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-003B57?style=flat&logo=sqlite&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/LLM%20Agents-412991?style=flat" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white" />
<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white" />
<img src="https://img.shields.io/badge/YOLO-111F68?style=flat&logo=ultralytics&logoColor=white" />
<img src="https://img.shields.io/badge/NLP-2B6CB0?style=flat" />
<img src="https://img.shields.io/badge/OCR-4A5568?style=flat" />
<br/>
<img src="https://img.shields.io/badge/QGIS-589632?style=flat&logo=qgis&logoColor=white" />
<img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=plotly&logoColor=white" />
<img src="https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white" />
<img src="https://img.shields.io/badge/tidyverse-1A162D?style=flat&logo=tidyverse&logoColor=white" />
<img src="https://img.shields.io/badge/Zotero-CC2936?style=flat&logo=zotero&logoColor=white" />
<img src="https://img.shields.io/badge/Paleography-8B5A2B?style=flat" />

</div>

---

## What I Work With

| Area | Scope |
|---|---|
| **Data Science** | Exploratory and statistical analysis, hypothesis testing, visualization |
| **Machine Learning** | Classification, regression, clustering, dimensionality reduction, anomaly detection |
| **Python & SQL** | Automation, data processing, optimization of computations and queries |
| **Databases & ETL** | PostgreSQL, schema design, data collection, cleaning, normalization and integration |
| **Web Scraping & APIs** | Large-scale data collection, asynchronous requests, incremental updates |
| **GIS** | Georeferencing and map digitization, vector and raster data, spatio-temporal analysis |
| **Document Processing** | OCR, extraction of text, tables and structure from PDF, building and organizing corpora |
| **NLP** | Text classification, topic modeling, entity and relation extraction |
| **LLM** | Hugging Face, prompt engineering, API usage, structured generation, local inference, fine-tuning and quantization |
| **Search** | Embeddings, vector databases (Qdrant, FAISS), full-text, semantic and hybrid search, RAG |
| **AI Agents** | Task planning, tool calling, context and state management, action control, human-in-the-loop |
| **Computer Vision & Multimodal AI** | Image classification, object detection (YOLO), segmentation, joint text–image analysis |
| **Interactive Visualization** | Maps, charts, dashboards and research applications |
| **Computational Systems** | Modular architecture, task queues, parallel processing, testing, Git and Docker |
| **Reproducible Research** | Data and config versioning, data provenance, computational experiment management |

---

## Current Projects

### Delegation Workbench
Research and development of a web system for controlled delegation of tasks to AI agents. The user defines the goal, context, constraints and allowed and forbidden actions, reviews and approves or edits the agent's plan, sets checkpoints and monitors the execution log, with the ability to pause, modify or stop the work at any moment.

**Research question:** how do task structure, upfront planning, mandatory clarifications and checkpoints affect the reliability, controllability, cost and efficiency of task execution across different LLMs?

**Planned outputs:** a working prototype, a set of reproducible tasks, agent trajectory logs, experimental data and design principles for human–AI delegation.

`AI agents` `LLM` `human-in-the-loop` `tool calling` · `status: research & development`

### Agent Autonomy under Uncertain Data (IA RAS)
An experimental environment, linked to Delegation Workbench, for studying the limits of AI agent autonomy on incomplete, noisy and ambiguous data. The agent compiles a description of an archaeological complex from a corpus of 372 excavation reports, linking every claim to its sources. When it faces OCR errors, unreliable extractions or insufficient evidence, it must choose between proceeding, checking the original, asking a human and withholding a conclusion.

**Experiment:** free execution vs. fixed checkpoints vs. uncertainty-triggered oversight, evaluated by correctness, completeness, unsupported claims, constraint compliance and cost of human interventions.

`OCR` `layout analysis` `entity extraction` `RAG` `AI agents` · `status: corpus processed · agent layer in progress` · [Repository](https://github.com/EgoricB/archaeo-doc-pipeline)

### Lavochkin Pipeline
A compact, independent Python + PostgreSQL pipeline for reproducible processing of digital collections, built on open NASA NTRS materials about NPO Lavochkin missions of 1965–1991 and later publications about them. The first sample of 30–50 PDFs goes through download, text extraction and normalization, and feature computation, with full provenance tracking of documents and results.

**Core:** a queue of dependent jobs with retries and failure recovery. An ML model learns from measured job durations without a pre-labeled dataset; the experiment compares a standard FIFO scheduler with duration-aware scheduling. Control via a small web interface.

`Python` `PostgreSQL` `ETL` `task queue` `ML` `provenance` · `status: scaffold ready · NTRS loader next` · [Repository](https://github.com/EgoricB/lavochkin_pipeline)

---

<details>
<summary><b>Other Work</b></summary>
<br/>

**Russian Apocryphal Studio.** A scraper for apokrif.fullweb.ru that builds a corpus of apocryphal texts for humanities research. [Repository](https://github.com/EgoricB/Russian-apocryphal-studio)

**NPO Lavochkin Virtual Museum.** Digitization and data structuring of the museum collection of NPO Lavochkin (Roscosmos). [Virtual museum](https://www.laspace.ru/virtual-museum/)

**DH Career Platform.** A career-guidance platform for humanities students: DigComp-based self-assessment, skill-stack recommendations and job matching.

**Settlement Modeling with GIS.** Reconstruction of historical settlement patterns using Thiessen polygons, catchment zones and central place theory in QGIS; a series of maps and 7 peer-reviewed publications.

</details>
