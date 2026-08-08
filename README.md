# Global Risk & Intelligence Engine

![Hero Banner](hero-banner.png)

An AI-powered Open-Source Intelligence (OSINT) risk monitoring and incident response platform. The system continuously processes global threat signals across public feeds, extracts structured context, deduplicates redundant reports, and provides real-time situational awareness for security operations.

📄 **Project Presentation**: [Executive Deck PDF](https://github.com/Imtiaz-laskar/global-risk-intelligence-engine-showcase/blob/main/Deck_Global_Risk_Intelligence_Engine.pdf)

---

### 📊 Key Performance Metrics

| Metric | Impact | Baseline Comparison |
| :--- | :--- | :--- |
| **Monitored Sources** | **46+ Global Feeds (24/7)** | Fragmented manual monitoring |
| **Alert Deduplication** | **85% Noise Elimination** | High alert fatigue & duplicate records |
| **Classification Accuracy** | **94%+ NLP Accuracy** | Manual tagging & categorization |
| **Average MTTR** | **< 12 Minutes** | ~45 Minutes average triage cycle |

---

## 📌 Public Showcase Notice

This repository serves as a **public case study and architectural showcase** of the Global Risk & Intelligence Engine. 

> **Note**: The production implementation—including full backend codebases, real-time AI processing pipelines, deployment scripts, live operational databases, and proprietary risk scoring models—remains private due to security, confidentiality, and intellectual property requirements.

---

## 🌟 Core Capabilities

* **Continuous OSINT Ingestion**: Auto-scales across 46+ global news and threat intelligence streams.
* **AI-Powered Enrichment**: Automatically extracts risk category, threat severity, affected countries, and structured metadata.
* **Graph-Based Story Deduplication**: Merges dozens of repetitive media alerts into a single unified Master Incident Record.
* **Interactive GIS Risk Map**: Displays geolocated threat vectors overlaid against asset footprint buffers.
* **Natural Language Analyst Assistant**: Grounded AI assistant allowing analysts to query live intelligence using natural language prompts.
* **SLA-Driven Escalation Console**: Kanban-style workflow tracking incident stages, ownership, SLA breach limits, and audit histories.

---

## 📸 Platform Preview

### 🔐 Secure Authentication
Access controls safeguard intelligence feeds, investigation boards, and analytical views.

![Authentication Console](login.png)

---

### 📈 Operational Intelligence Dashboard
Centralized workspace displaying live signal volumes, severity distributions, anomaly detection radars, and feed health statuses.

![Intelligence Dashboard](dashboard.png)

---

### 🌍 Interactive GIS Risk Map
Geospatial visualization console displaying threat concentrations, theater summaries, and country hotspot rankings.

![Interactive Risk Map](Risk_map.png)

---

### 💬 AI Analyst Assistant
Natural-language interface grounded in the live signal database for immediate executive summaries and regional deep dives.

![AI Analyst Chat](Analyst_chat.png)

---

### 🚨 Escalation Workflow & Case Management
Kanban-style triage workspace with rule-based routing, SLA tracking timers, and automated incident playbooks.

![Escalation Workflow](escalation-workflow.png)

---

## 🏗️ System Architecture & Workflow

The platform uses a layered pipeline architecture designed to handle high-throughput signal processing.

```text
[ 46+ OSINT Feeds ] ──► [ Ingestion Layer ] ──► [ AI Classification Engine ]
                                                          │
                                                          ▼
[ GIS Risk Map ] ◄── [ Outbound APIs ] ◄── [ Graph Clustering & Deduplication ]
       │                                                  │
       ▼                                                  ▼
[ Analyst Workspace ] ◄───────────────────────── [ Intelligence DB ]

🔄 Data Processing PipelineIngestion Layer: Continuously ingests structured and unstructured OSINT data 24/7.Normalization: Strips noise, sanitizes raw streams, and isolates spatial metadata.AI Enrichment: Transformer models classify risk categories and assign initial severity scores.Graph Clustering: Semantic vector embeddings group related articles into a single incident record via cosine similarity.Outbound API & UI: Feeds enriched records to real-time maps, analytics dashboards, and investigation workflows.🛡️ Ethical Standards & Responsible AIThis platform is engineered to align with established ethical AI guidelines, digital rights standards, and security protocols:Human-in-the-Loop Triage: AI models perform initial classification and routing, but critical triage decisions and escalations require explicit analyst review and verification.Public OSINT Integrity: Ingestion relies strictly on publicly accessible OSINT and media streams, respecting source terms of service and avoiding unauthorized data extraction.Source Attribution & Grounding: The AI Analyst Chat generates responses anchored directly in verified database records with explicit citation links to primary sources.Data Minimization & Privacy: Processing excludes Personally Identifiable Information (PII) to focus strictly on macro-level security risks and geographical events.Auditability: Complete state-change audit logs track rule matches, analyst overrides, and escalation histories for full governance compliance.💻 Tech StackLayerTechnologyFrontend FrameworkReact 19, TanStack StartLanguageTypeScriptStyling & UITailwind CSS v4, shadcn/uiBackend & DatabaseSupabase, PostgreSQLAI & Embedding ModelsOpenAI GPT APIMapping & Chartsd3-geo, RechartsRuntime & Package ManagerBunPrototyping & WorkflowLovable, Prompt Engineering

.
├── README.md
├── LICENSE
│
├── hero-banner.png
├── login.png
├── dashboard.png
├── Risk_map.png
├── Analyst_chat.png
│
├── architecture-diagram.png
├── escalation-workflow.png
│
├── Deck_Global_Risk_Intelligence_Engine.pdf
├── Risk_Engine.pdf
├── Source_of_Truth_OSINT.pdf
│
└── src/

📑 Supporting Documentation
Further details regarding product specifications, architectural choices, and system design are available in the repository files:

Deck_Global_Risk_Intelligence_Engine.pdf: Executive presentation deck and performance overview.

Risk_Engine.pdf: Product walkthrough and feature overview.

Source_of_Truth_OSINT.pdf: System design and detailed pipeline architecture.

Copyright (c) 2026 Imtiaz Hussain Laskar. All rights reserved.
