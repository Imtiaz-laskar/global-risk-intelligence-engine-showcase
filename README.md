<div align="center">

<br/>

```
 ██████╗ ██████╗ ██╗███████╗    ██╗███╗   ██╗████████╗███████╗██╗     
██╔════╝ ██╔══██╗██║██╔════╝    ██║████╗  ██║╚══██╔══╝██╔════╝██║     
██║  ███╗██████╔╝██║███████╗    ██║██╔██╗ ██║   ██║   █████╗  ██║     
██║   ██║██╔══██╗██║╚════██║    ██║██║╚██╗██║   ██║   ██╔══╝  ██║     
╚██████╔╝██║  ██║██║███████║    ██║██║ ╚████║   ██║   ███████╗███████╗
 ╚═════╝ ╚═╝  ╚═╝╚═╝╚══════╝   ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚══════╝╚══════╝

     ──────── GLOBAL RISK & INTELLIGENCE ENGINE ────────
     Real-Time OSINT · AI Enrichment · Geospatial Threat Ops
```

<br/>

[![Feeds](https://img.shields.io/badge/OSINT%20Feeds-46%2B%20Global%20(24%2F7)-0057B8?style=for-the-badge&logo=rss&logoColor=white)](#)
[![Deduplication](https://img.shields.io/badge/Alert%20Deduplication-85%25%20Noise%20Eliminated-1a7f37?style=for-the-badge&logo=filter&logoColor=white)](#)
[![NLP Accuracy](https://img.shields.io/badge/NLP%20Accuracy-94%25%2B-e67e00?style=for-the-badge&logo=openai&logoColor=white)](#)
[![MTTR](https://img.shields.io/badge/Avg%20MTTR-%3C%2012%20Minutes-c0392b?style=for-the-badge&logo=speedtest&logoColor=white)](#)

<br/>

> An AI-powered Open-Source Intelligence **(OSINT)** risk monitoring and incident response platform. The system continuously processes global threat signals across public feeds, extracts structured context, deduplicates redundant reports, and delivers real-time situational awareness for security operations.

<br/>

📄 **Executive Deck** → [`Deck_Global_Risk_Intelligence_Engine.pdf`](https://github.com/Imtiaz-laskar/global-risk-intelligence-engine-showcase/blob/main/Deck_Global_Risk_Intelligence_Engine.pdf) &nbsp;|&nbsp; 📑 **Pipeline Design** → [`Source_of_Truth_OSINT.pdf`](./Source_of_Truth_OSINT.pdf) &nbsp;|&nbsp; 🗂️ **Product Walkthrough** → [`Risk_Engine.pdf`](./Risk_Engine.pdf)

<br/>

---

</div>

## 📊 Performance at a Glance

<div align="center">

| Metric | Result | vs. Baseline |
|:---:|:---:|:---:|
| 🌐 **Monitored Sources** | **46+ Global Feeds (24/7)** | Fragmented manual monitoring |
| 🔕 **Alert Deduplication** | **85% Noise Elimination** | High alert fatigue & duplicate records |
| 🎯 **Classification Accuracy** | **94%+ NLP Accuracy** | Manual tagging & categorization |
| ⚡ **Average MTTR** | **< 12 Minutes** | ~45 min average triage cycle |

</div>

---

## 🌟 Core Capabilities

```
┌─────────────────────────────────────────────────────────────────────────┐
│                        PLATFORM CAPABILITIES                            │
├──────────────────────────────┬──────────────────────────────────────────┤
│  🔄  Continuous OSINT        │  Auto-scales across 46+ global news &   │
│      Ingestion               │  threat intelligence streams             │
├──────────────────────────────┼──────────────────────────────────────────┤
│  🤖  AI-Powered Enrichment   │  Extracts risk category, severity,      │
│                              │  affected countries & structured metadata│
├──────────────────────────────┼──────────────────────────────────────────┤
│  🕸️  Graph-Based Story       │  Merges dozens of duplicate alerts into  │
│      Deduplication           │  a single Master Incident Record         │
├──────────────────────────────┼──────────────────────────────────────────┤
│  🗺️  Interactive GIS         │  Geolocated threat vectors overlaid      │
│      Risk Map                │  against asset footprint buffers         │
├──────────────────────────────┼──────────────────────────────────────────┤
│  💬  NL Analyst Assistant    │  Query live intelligence with natural    │
│                              │  language; grounded in verified records  │
├──────────────────────────────┼──────────────────────────────────────────┤
│  🚨  SLA-Driven Escalation   │  Kanban workflow with SLA breach timers, │
│      Console                 │  ownership chains & full audit history   │
└──────────────────────────────┴──────────────────────────────────────────┘
```

---

## 📸 Platform Preview

### 🔐 Secure Authentication

> Access controls safeguard intelligence feeds, investigation boards, and analytical views.

![Authentication Console](login.png)

---

### 📈 Operational Intelligence Dashboard

> Centralized workspace displaying live signal volumes, severity distributions, anomaly detection radars, and feed health statuses.

![Intelligence Dashboard](dashboard.png)

---

### 🌍 Interactive GIS Risk Map

> Geospatial visualization console displaying threat concentrations, theater summaries, and country hotspot rankings.

![Interactive Risk Map](Risk_map.png)

---

### 💬 AI Analyst Assistant

> Natural-language interface grounded in the live signal database for immediate executive summaries and regional deep dives.

![AI Analyst Chat](Analyst_chat.png)

---

### 🚨 Escalation Workflow & Case Management

> Kanban-style triage workspace with rule-based routing, SLA tracking timers, and automated incident playbooks.

![Escalation Workflow](escalation-workflow.png)

---

## 🏗️ System Architecture

```
                        ┌─────────────────────────┐
                        │     46+ OSINT FEEDS      │
                        │  News · Intel · Social   │
                        └────────────┬────────────┘
                                     │ continuous ingest
                                     ▼
                        ┌─────────────────────────┐
                        │    INGESTION LAYER       │
                        │  Normalize · Sanitize    │
                        │  Strip PII · GeoExtract  │
                        └────────────┬────────────┘
                                     │
                                     ▼
                        ┌─────────────────────────┐
                        │   AI CLASSIFICATION      │
                        │  Transformer NLP Models  │
                        │  Risk Category · Severity│
                        └────────────┬────────────┘
                                     │
                                     ▼
                        ┌─────────────────────────┐
                        │  GRAPH CLUSTERING &      │
                        │  DEDUPLICATION ENGINE    │
                        │  Cosine Similarity       │
                        │  Vector Embeddings       │
                        └──────┬──────────┬────────┘
                               │          │
                    ┌──────────▼──┐  ┌────▼──────────┐
                    │ INTELLIGENCE│  │  OUTBOUND APIs │
                    │     DB      │  │  & REAL-TIME   │
                    │ PostgreSQL  │  │  WEBSOCKETS    │
                    └──────┬──────┘  └────┬───────────┘
                           │              │
              ┌────────────┼──────────────┼────────────┐
              ▼            ▼              ▼            ▼
        ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐
        │ GIS RISK │ │ANALYTICS │ │ ANALYST  │ │ESCALATION│
        │   MAP    │ │DASHBOARD │ │  CHAT    │ │ CONSOLE  │
        └──────────┘ └──────────┘ └──────────┘ └──────────┘
```

### Pipeline Breakdown

| Stage | Process | Technology |
|:---|:---|:---|
| **① Ingestion** | Continuous structured & unstructured OSINT ingest 24/7 | Bun, RSS/HTTP adapters |
| **② Normalization** | Strips noise, sanitizes raw streams, isolates spatial metadata | Custom ETL pipeline |
| **③ AI Enrichment** | Transformer models classify risk categories & assign severity | OpenAI GPT API |
| **④ Graph Clustering** | Semantic vector embeddings group articles into single incident records | Cosine similarity engine |
| **⑤ Outbound Layer** | Feeds enriched records to maps, dashboards & investigation workflows | Supabase Realtime, REST |

---

## 🛡️ Ethical Standards & Responsible AI

<table>
<tr>
<td width="30"><b>👤</b></td>
<td><b>Human-in-the-Loop Triage</b> — AI performs initial classification, but critical escalations require explicit analyst review and verification.</td>
</tr>
<tr>
<td><b>🌐</b></td>
<td><b>Public OSINT Integrity</b> — Ingestion relies strictly on publicly accessible streams, respecting source terms of service; zero unauthorized data extraction.</td>
</tr>
<tr>
<td><b>🔗</b></td>
<td><b>Source Attribution & Grounding</b> — AI Analyst Chat responses are anchored directly in verified database records with explicit citation links to primary sources.</td>
</tr>
<tr>
<td><b>🔒</b></td>
<td><b>Data Minimization & Privacy</b> — Processing excludes PII entirely, focusing strictly on macro-level security risks and geographical events.</td>
</tr>
<tr>
<td><b>📋</b></td>
<td><b>Auditability</b> — Complete state-change audit logs track rule matches, analyst overrides, and escalation histories for full governance compliance.</td>
</tr>
</table>

---

## 💻 Tech Stack

```
┌──────────────────────────────────────────────────────────────┐
│               GLOBAL RISK & INTELLIGENCE ENGINE              │
│                       TECH STACK                             │
├──────────────────────┬───────────────────────────────────────┤
│  Frontend Framework  │  React 19, TanStack Start             │
│  Language            │  TypeScript                           │
│  Styling & UI        │  Tailwind CSS v4, shadcn/ui           │
│  Backend & Database  │  Supabase, PostgreSQL                 │
│  AI & Embeddings     │  OpenAI GPT API                       │
│  Mapping & Charts    │  d3-geo, Recharts                     │
│  Runtime             │  Bun                                  │
│  Prototyping         │  Lovable, Prompt Engineering          │
└──────────────────────┴───────────────────────────────────────┘
```

---

## 📁 Repository Structure

```
global-risk-intelligence-engine-showcase/
│
├── 📄  README.md
├── 📜  LICENSE
│
├── 🖼️  hero-banner.png
├── 🖼️  login.png
├── 🖼️  dashboard.png
├── 🖼️  Risk_map.png
├── 🖼️  Analyst_chat.png
├── 🖼️  architecture-diagram.png
├── 🖼️  escalation-workflow.png
│
├── 📑  Deck_Global_Risk_Intelligence_Engine.pdf   ← Executive deck
├── 📑  Risk_Engine.pdf                            ← Product walkthrough
├── 📑  Source_of_Truth_OSINT.pdf                 ← Architecture design
│
└── 📂  src/
```

---

## 📑 Supporting Documentation

| Document | Contents |
|:---|:---|
| [`Deck_Global_Risk_Intelligence_Engine.pdf`](https://github.com/Imtiaz-laskar/global-risk-intelligence-engine-showcase/blob/main/Deck_Global_Risk_Intelligence_Engine.pdf) | Executive presentation deck and performance overview |
| [`Risk_Engine.pdf`](./Risk_Engine.pdf) | Full product walkthrough and feature overview |
| [`Source_of_Truth_OSINT.pdf`](./Source_of_Truth_OSINT.pdf) | System design and detailed pipeline architecture |

---

## 📌 Public Showcase Notice

> This repository is a **public case study and architectural showcase** of the Global Risk & Intelligence Engine.
>
> The production implementation — including full backend codebases, real-time AI processing pipelines, deployment scripts, live operational databases, and proprietary risk scoring models — **remains private** due to security, confidentiality, and intellectual property requirements.

---

<div align="center">

**Built for operators who can't afford to be the last to know.**

<br/>

*Global Risk & Intelligence Engine — Turning signal noise into decisive action.*

<br/>

```
Copyright (c) 2026 Imtiaz Hussain Laskar. All Rights Reserved.
```

</div>
