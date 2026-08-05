# Global Risk & Intelligence Engine

![Hero Banner](hero-banner.png)[cite: 2]

An AI-powered Open-Source Intelligence (OSINT) risk monitoring and incident response platform[cite: 2]. The system continuously processes global threat signals across public feeds, extracts structured context, deduplicates redundant reports, and provides real-time situational awareness for security operations[cite: 1, 2].

Project Deck: [ https://github.com/Imtiaz-laskar/global-risk-intelligence-engine-showcase/blob/main/Deck_Global_Risk_Intelligence_Engine.pdf ]

---

### 📊 Key Performance Metrics

| Metric | Impact | Standard Baseline |
| :--- | :--- | :--- |
| **Monitored Sources** | **46+ Global Feeds 24/7**[cite: 1] | Fragmented manual checks |
| **Alert Deduplication** | **85% Noise Elimination**[cite: 1] | High alert fatigue & duplicate records |
| **Classification Accuracy** | **94%+ NLP Accuracy**[cite: 1] | Manual tagging & categorization |
| **Average MTTR** | **< 12 Minutes**[cite: 1] | ~45 Minutes triage cycle |

---

## 📌 Public Showcase Notice

This repository serves as a **public case study and architectural showcase** of the Global Risk & Intelligence Engine[cite: 2]. 

> **Note**: The production implementation—including full backend codebases, real-time AI processing pipelines, deployment scripts, live operational databases, and proprietary risk scoring models—remains private due to security, confidentiality, and intellectual property requirements[cite: 2].

---

## 🌟 Core Capabilities

* **Continuous OSINT Ingestion**: Auto-scales across 46+ global news and threat intelligence streams[cite: 1, 2].
* **AI-Powered Enrichment**: Automatically extracts risk category, threat severity, affected countries, and structured metadata[cite: 2].
* **Graph-Based Story Deduplication**: Merges dozens of repetitive media alerts into a single unified Master Incident Record[cite: 1, 2].
* **Interactive GIS Risk Map**: Displays geolocated threat vectors overlaid against asset footprint buffers[cite: 1, 2].
* **Natural Language Analyst Assistant**: Grounded AI assistant allowing analysts to query live intelligence using natural language prompts[cite: 2].
* **SLA-Driven Escalation Console**: Kanban-style workflow tracking incident stages, ownership, SLA breach limits, and audit histories[cite: 2, 3].

---

## 📸 Platform Preview

### 🔐 Secure Authentication
Access controls safeguard intelligence feeds, investigation boards, and analytical views[cite: 2].

![Authentication Console](login.png)[cite: 2]

---

### 📈 Operational Intelligence Dashboard
Centralized workspace displaying live signal volumes, severity distributions, anomaly detection radars, and feed health statuses[cite: 2, 3].

![Intelligence Dashboard](dashboard.png)[cite: 2]

---

### 🌍 Interactive GIS Risk Map
Geospatial visualization console displaying threat concentrations, theater summaries, and country hotspot rankings[cite: 1, 2].

![Interactive Risk Map](Risk_map.png)[cite: 2]

---

### 💬 AI Analyst Assistant
Natural-language interface grounded in the live signal database for immediate executive summaries and regional deep dives[cite: 2, 3].

![AI Analyst Chat](Analyst_chat.png)[cite: 2]

---

### 🚨 Escalation Workflow & Case Management
Kanban-style triage workspace with rule-based routing, SLA tracking timers, and automated incident playbooks[cite: 1, 2, 3].

![Escalation Workflow](escalation-workflow.png)[cite: 2]

---

## 🏗️ System Architecture & Workflow

The platform uses a layered pipeline architecture designed to handle high-throughput signal processing[cite: 1, 2].

```text
[ 46+ OSINT Feeds ] ──► [ Ingestion Layer ] ──► [ AI Classification Engine ]
                                                          │
                                                          ▼
[ GIS Risk Map ] ◄── [ Outbound APIs ] ◄── [ Graph Clustering & Deduplication ]
       │                                                  │
       ▼                                                  ▼
[ Analyst Workspace ] ◄───────────────────────── [ Intelligence DB ]
```[cite: 1, 2]

![System Architecture](architecture-diagram.png)[cite: 2]

### 🔄 Data Processing Pipeline

1. **Ingestion Layer**: Continuously ingests structured and unstructured OSINT data 24/7[cite: 1, 2].
2. **Normalization**: Strips noise, sanitizes raw streams, and isolates spatial metadata[cite: 1].
3. **AI Enrichment**: Transformer models classify risk categories and assign initial severity scores[cite: 1].
4. **Graph Clustering**: Semantic vector embeddings group related articles into a single incident record via cosine similarity[cite: 1].
5. **Outbound API & UI**: Feeds enriched records to real-time maps, analytics dashboards, and investigation workflows[cite: 1, 2].

---

## 🛡️ Ethical Standards & Responsible AI

This platform is engineered to align with established ethical AI guidelines, digital rights standards, and security protocols[cite: 2]:

* **Human-in-the-Loop Triage**: AI models perform initial classification and routing, but critical triage decisions and escalations require explicit analyst review and verification[cite: 2].
* **Public OSINT Integrity**: Ingestion relies strictly on publicly accessible OSINT and media streams, respecting source terms of service and avoiding unauthorized data extraction[cite: 1, 2].
* **Source Attribution & Grounding**: The AI Analyst Chat generates responses anchored directly in verified database records with explicit citation links to primary sources[cite: 2, 3].
* **Data Minimization & Privacy**: Processing excludes Personally Identifiable Information (PII) to focus strictly on macro-level security risks and geographical events[cite: 1, 2].
* **Auditability**: Complete state-change audit logs track rule matches, analyst overrides, and escalation histories for full governance compliance[cite: 1, 3].

---

## 💻 Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend Framework** | React 19, TanStack Start[cite: 2] |
| **Language** | TypeScript[cite: 2] |
| **Styling & UI** | Tailwind CSS v4, shadcn/ui[cite: 2] |
| **Backend & Database** | Supabase, PostgreSQL[cite: 2] |
| **AI & Embedding Models** | OpenAI GPT API[cite: 2] |
| **Mapping & Charts** | d3-geo, Recharts[cite: 2] |
| **Runtime & Package Manager** | Bun[cite: 2] |
| **Prototyping & Workflow** | Lovable, Prompt Engineering[cite: 2] |

---

## 🛠️ Repository Structure

```text
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
```[cite: 2]

---

## 📑 Supporting Documentation

Further details regarding product specifications, architectural choices, and system design are available in the repository files[cite: 2]:

* **`Deck_Global_Risk_Intelligence_Engine.pdf`**: Executive presentation deck and performance overview[cite: 1, 2].
* **`Risk_Engine.pdf`**: Product walkthrough and feature overview[cite: 2, 3].
* **`Source_of_Truth_OSINT.pdf`**: System design and detailed pipeline architecture[cite: 2].

---

## 📄 License

Distributed under the [MIT License](LICENSE)[cite: 2].
