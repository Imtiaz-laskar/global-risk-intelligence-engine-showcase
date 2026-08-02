# 🌍 Global Risk & Intelligence Engine

![Global Risk & Intelligence Engine](./hero-banner.png)

> **A proactive OSINT platform that continuously collects global signals, classifies them with AI, detects emerging risks, and enables faster, data-driven incident response.**

---

## Overview

Global Risk & Intelligence Engine is a full-stack Open-Source Intelligence (OSINT) platform designed to automate the end-to-end intelligence lifecycle.

The platform continuously monitors global news and OSINT sources, enriches every article with AI-generated intelligence, identifies affected countries and regions, removes duplicate stories, detects emerging trends, and provides analysts with actionable insights through an interactive dashboard and structured escalation workflow.

Originally built as a Google Sheets automation, the project evolved into a scalable web application capable of supporting real-time intelligence operations.

---

# Public Showcase

This repository contains a **showcase version** of the **Global Risk & Intelligence Engine**.

The production implementation—including the complete source code, backend services, AI pipelines, infrastructure, configurations, automation workflows, and operational datasets—is intentionally kept **private** due to confidentiality, security, and intellectual property considerations.

This public repository focuses on demonstrating the platform's:

- Product design
- System architecture
- Core capabilities
- Intelligence workflows
- Technical approach
- User experience
- Supporting documentation

The included documentation, diagrams, and screenshots are representative of the platform while intentionally omitting proprietary implementation details.

---

# Highlights

| Feature | Description |
|---------|-------------|
| 🌐 **40+ Live Intelligence Sources** | Continuous monitoring of global news and OSINT feeds |
| 🤖 **AI Classification** | Automatic categorization, geo-resolution, and severity scoring |
| 🔄 **Story De-duplication** | Cluster related articles into a single incident |
| 📈 **Trend & Spike Detection** | Detect emerging patterns using statistical analysis |
| 🌍 **Interactive Risk Map** | Visualize incidents geographically |
| 🚨 **Escalation Workflow** | Structured incident management with SLA tracking |
| 💬 **Analyst Assistant** | Natural-language interaction with intelligence data |
| 📑 **Google Sheets Sync** | Bidirectional synchronization with analyst workflows |

---

# Documentation

The repository includes additional documentation describing the platform.

| Document | Description |
|----------|-------------|
| 📄 **Risk_Engine.pdf** | Product walkthrough and feature overview |
| 📄 **Source_of_Truth_OSINT.pdf** | System architecture, workflows, and data model |
| 🖼 **architecture-diagram.png** | High-level system architecture |
| 🖼 **escalation-workflow.png** | Incident lifecycle |

---

# The Problem

Monitoring global risks manually is time-consuming, repetitive, and difficult to scale.

Traditional workflows often rely on spreadsheets, RSS readers, keyword searches, and manual reviews, making it challenging to identify emerging events before they become significant.

This platform automates the intelligence lifecycle—from collection to escalation—allowing analysts to spend less time gathering information and more time investigating, prioritizing, and responding.

---

# The Solution

The platform continuously:

- 📡 Collects intelligence from global OSINT and news sources
- 🤖 Classifies every article using AI
- 🌍 Resolves countries and regions
- 🔄 Removes duplicate stories
- 📈 Detects trend spikes and anomalies
- 🗺️ Visualizes risks through dashboards and maps
- 🚨 Supports structured investigation and escalation workflows

---

# Key Features

## 📡 Live Intelligence Collection

- Continuous monitoring of 40+ news and OSINT sources
- Automatic background synchronization
- Retry logic and fallback feeds
- Feed health monitoring

---

## 🤖 AI Classification

Every incoming article is automatically enriched with:

- Risk category
- Severity
- Country
- Region
- Structured metadata

---

## 🔄 Story De-duplication

The same incident is often reported by multiple publishers.

The platform clusters related stories into a single incident, reducing duplicate investigations and improving signal quality.

---

## 📈 Trend & Anomaly Detection

Automatically identifies unusual activity using statistical analysis.

Examples include:

- Country-specific spikes
- Category-specific trends
- Emerging incidents
- Sudden increases in reporting volume

---

## 🌍 Interactive Risk Map

Visualize incidents geographically.

- Country filtering
- Regional analysis
- Global overview
- Interactive exploration

---

## 🚨 Escalation Workflow

A Kanban-style workflow supporting:

- New
- In Progress
- Escalated
- Resolved

with ownership, priority, and SLA tracking throughout the investigation lifecycle.

---

## 💬 Analyst Assistant

Natural-language interface for exploring intelligence.

Example queries:

- Summarize today's incidents
- Show recent cyber threats
- Explain spike activity
- Search historical events

---

## 📑 Google Sheets Integration

Supports bidirectional synchronization.

Analysts can continue using familiar spreadsheet workflows while benefiting from automated intelligence enrichment and workflow tracking.

---

# How It Works

```text
Global News & OSINT Sources
            │
            ▼
     Feed Collection Layer
            │
            ▼
      Article Processing
            │
            ▼
      AI Classification
(Category • Country • Severity)
            │
            ▼
      Story De-duplication
            │
            ▼
     Intelligence Database
            │
     ┌──────┴─────────────┐
     ▼                    ▼
Google Sheets      Trend Analysis
     │                    │
     └────────────┬────────┘
                  ▼
Dashboard • Risk Map • Analyst Chat • Escalation Console
```

---

# Architecture

![Architecture](./architecture-diagram.png)

The platform follows a layered architecture:

1. Collection Layer
2. Intelligence Layer
3. Processing Layer
4. Analysis Layer
5. Presentation Layer

Each layer is designed to transform raw information into actionable intelligence while maintaining a clear separation of responsibilities.

---

# Escalation Workflow

![Escalation Workflow](./escalation-workflow.png)

Every incident progresses through a structured lifecycle.

```text
New
 │
 ▼
In Progress
 │
 ▼
Escalated
 │
 ▼
Resolved
```

Ownership, severity, SLA, and investigation history remain attached throughout the lifecycle.

---

# Technology Stack

| Layer | Technology |
|--------|------------|
| Frontend | React 19 |
| Framework | TanStack Start |
| Language | TypeScript |
| Styling | Tailwind CSS v4 |
| UI Components | shadcn/ui |
| Backend | Supabase |
| Database | PostgreSQL |
| Authentication | Supabase Auth |
| AI | OpenAI |
| Maps | d3-geo |
| Charts | Recharts |
| Package Manager | Bun |

---

# Repository Structure

```text
.
├── README.md
├── LICENSE
├── hero-banner.png
├── architecture-diagram.png
├── escalation-workflow.png
├── Risk_Engine.pdf
├── Source_of_Truth_OSINT.pdf
└── src/
```

---

# Project Status

🚧 **Public Showcase Repository**

This repository showcases the architecture, design decisions, workflows, and capabilities of the **Global Risk & Intelligence Engine**.

It is intended to demonstrate the overall system design and user experience while intentionally omitting confidential implementation details.

The complete production engine—including backend services, automation pipelines, AI integrations, infrastructure, and operational components—remains private.

---

# Future Enhancements

- Email notifications
- PDF intelligence reports
- Additional intelligence sources
- Mobile optimization
- Advanced analytics
- Multi-language intelligence support
- Configurable alert rules
- Enhanced reporting dashboards

---

# License

Copyright © 2026 **Imtiaz Hussain Laskar**.

**All rights reserved.**

This repository is shared publicly for demonstration, educational, research, and portfolio purposes only.

No part of this repository—including its source code, documentation, designs, diagrams, reports, images, or other materials—may be copied, reproduced, modified, distributed, published, sublicensed, or used without prior written permission from the copyright holder.

See the **LICENSE** file for the complete license terms.

---

# Acknowledgements

Designed and developed by **Imtiaz Hussain Laskar** as an exploration of AI-assisted Open-Source Intelligence (OSINT), risk analytics, and intelligence workflow automation.

If you found this project interesting, consider giving the repository a ⭐.
