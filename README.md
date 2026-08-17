# Hi, I'm Adrian 👋

**Language:** **English** | [Deutsch](README.de.md)

Backend developer focused on **search/Elasticsearch** and **AI integration** (RAG, LLM integration).
2+ years at a large German IT consulting company shipping Elasticsearch search infrastructure for automotive,
public-sector, and electronics/electrical clients — from crawler-to-pipeline
migrations to a from-scratch search relaunch for a public-sector investment bank.

Outside of work I build [HobbyHub](https://sheoforge.de): browsing Magic: The
Gathering cards, playing chess against an engine, and tracking board games.

## 🔎 Projects

### [hybrid-search-api](https://github.com/Sheodred/hybrid-search-api)
Elasticsearch hybrid search (BM25 + kNN via Reciprocal Rank Fusion) with an
LLM layer for source-grounded RAG answers.

![CI](https://github.com/Sheodred/hybrid-search-api/actions/workflows/ci.yml/badge.svg)
![Python](https://img.shields.io/badge/python-3.12-blue)
![License: MIT](https://img.shields.io/badge/license-MIT-green)

- **Backend engineering** — FastAPI, containerized (Docker Compose), tested (pytest), CI (GitHub Actions), linted (ruff)
- **Search specialization** — custom Elasticsearch mapping/analyzers, BM25 + vector/kNN search, ranking fusion via RRF, switchable demo / NFCorpus (~3.6K medical documents) datasets
- **AI integration** — production-style LLM integration over any OpenAI-compatible endpoint (retry logic, versioned prompts, RAG), local embeddings via sentence-transformers, and a runtime EN/DE language toggle
- **Agentic RAG** — an opt-in mode where the LLM decides when and how to search instead of following a fixed pipeline, calling the project's own MCP `search` tool in-process; that same tool is exposed to external MCP clients like Claude Desktop
- **Data sovereignty** — a one-command fully on-prem mode (llama.cpp behind a Docker Compose profile) so the RAG step never makes an external call — built for GDPR/regulated environments, with the trade-offs written up as an ADR

📖 [README](https://github.com/Sheodred/hybrid-search-api#readme) · [Architecture](https://github.com/Sheodred/hybrid-search-api/blob/main/docs/architecture.md)

#### Stack
Python · FastAPI · Elasticsearch · MCP · llama.cpp · Docker · pytest · ruff · GitHub Actions

### [HobbyHub](https://sheoforge.com)
A personal hobby site — Magic: The Gathering card/deck browsing, board game
lookups aggregated across rating sources, and a chess engine to play
against. Built end-to-end and self-hosted, from CI to deploy.

- **Backend** — PHP, MySQL, PHPUnit, external API integration (Scryfall, BGG, EDHREC) with caching and rate-limit handling
- **Frontend** — React, TypeScript, Vite, Tailwind CSS, React Router, TanStack Query
- **Ops** — GitHub Actions CI/CD, deployed to IONOS webspace via SFTP

📖 [Code](https://github.com/Sheodred/hobbyhub) · [Live site](https://sheoforge.com)

#### Stack
PHP · MySQL · PHPUnit · React · TypeScript · Vite · Tailwind CSS · GitHub Actions

## 🚧 Work in Progress

Two more projects, currently private while I document and refine them.

### Codex Notes
A private knowledge-base assistant that turns scattered docs into a queryable, source-cited index.

**Stack:** Python · Elasticsearch · LLM/RAG

### Agent Bench
A private harness for testing multi-step LLM agent workflows against reproducible tasks.

**Stack:** Python · FastAPI · LLM APIs

## 🛠️ Stack

**Backend:** Java · Kotlin · Spring Boot · Python
**Search & Data:** Elasticsearch · OpenSearch · Solr · Lucene · MongoDB · SQL
**AI & RAG:** LLM integration (OpenAI-compatible APIs) · RAG · prompt engineering · sentence-transformers
**Cloud & DevOps:** Azure · OCI · Docker · Kubernetes · GitLab CI/CD · GitHub Actions
**Frontend:** React · TypeScript · Angular · Vue.js

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/adrian-kluge/) · [Email](mailto:92444350+Sheodred@users.noreply.github.com)

---

# CV

Adrian Kluge | Dortmund, Germany | [Email](mailto:92444350+Sheodred@users.noreply.github.com)
[linkedin.com/in/adrian-kluge](https://www.linkedin.com/in/adrian-kluge/) · [github.com/Sheodred](https://github.com/Sheodred)

### Software Developer — Backend, Search & AI Integration

## Professional Profile

Backend developer with 2+ years of continuous growth at a large German IT consulting company — promoted from
working student to trainee to software developer — specializing in Elasticsearch
search infrastructure and, increasingly, LLM/RAG integration. Built and shipped
search systems for automotive, electronics, and public-sector clients; most recently
took a hybrid BM25+kNN search API with a RAG answer layer from idea to a tested,
CI'd, English-documented open-source project (see above). Native German speaker,
business-fluent in English, with a mathematical B.Sc. foundation (factorization
algorithms) that underpins the analytical side of search relevance and ranking work.

## Core Competencies

- **Languages & Frameworks:** Java (Expert), Kotlin, Spring Boot, Python, C++
- **Search & Data:** Elasticsearch (Expert — index modeling, relevance tuning, BM25 + kNN/vector search, Reciprocal Rank Fusion), OpenSearch, Solr, Lucene, MongoDB, MySQL, Microsoft SQL Server
- **AI & RAG:** LLM integration via OpenAI-compatible APIs, Retrieval-Augmented Generation, versioned prompt engineering, local embeddings (sentence-transformers), generative AI fundamentals (Microsoft & LinkedIn certified)
- **Cloud & DevOps:** Microsoft Azure (4x certified), Oracle Cloud Infrastructure (3x certified), Docker/Docker Compose, Kubernetes, GitLab CI/CD, Gradle (multi-project configs), Maven
- **Enterprise Integration:** Jakarta EE, REST/OpenAPI, PIM systems (NovaDB), FirstSpirit CMS (module & template development), BPMN, Camunda BPM
- **Frontend:** Angular, Vue.js, React, TypeScript, Thymeleaf
- **Testing & Quality:** JUnit, ArchUnit, Clean Code / Design Patterns
- **Languages:** German (native, C2) · English (business fluent, C1)

## Professional Experience

**A large German IT consulting company, Dortmund**
Software Developer | Oct 2025 – Present
*(previously Trainee, May 2024 – Sept 2025 · Working Student Software Development, Sept 2023 – Apr 2024 — continuous progression within the same team)*

**Public-Sector Investment Bank — Website & Search Modernization** *(current)*
- Rebuilt the site search from the ground up on Elasticsearch, replacing a legacy crawler-based index with a directly configured, editorially controlled pipeline.
- Own index setup, query tuning, and CMS-side search-document generation within an active website relaunch.

**Major German Premium Automotive Manufacturer — Migration & Search**
- Replaced a paid, third-party web-crawler search with a custom Elasticsearch pipeline: designed the index schema, document mapping, and relevance tuning myself.
- Built a JSON-based import module that reconciles source data against what's already indexed and updates only changed elements, cutting sync overhead versus full re-imports.

**Global Electronics & Electrical Engineering Group — Modernization**
- Migrated mission-critical build modules from Maven to Gradle, including a multi-project Gradle configuration for a global website relaunch.
- Upgraded legacy systems to current Jakarta EE standards and migrated a Webforms-based module stack to Formcentric, preserving existing functionality through the version jump.

**Leading Global Manufacturer of Vacuum Pumps — PIM System Integration**
- Migrated legacy PIM importers to a modern, OpenAPI-based Java interface, standardizing product data ingestion for a global multi-brand website relaunch.

**Public Sector Organization — Search Troubleshooting & Optimization**
- Diagnosed a partial-match search bug in a TypeScript/Elasticsearch middleware through targeted codebase analysis, then fixed the indexing/query logic and patched a critical security vulnerability found along the way.

## Education

- **Master of Science (M.Sc.), Computer Science, specialization in Optimization** — TU Dortmund University — *in progress*
- **Bachelor of Science (B.Sc.), Computer Science, minor in Mathematics** — TU Dortmund University — graduated 2024. Thesis: *"Implementation and Comparison of Factorization Algorithms"* (SageMath/Python).
- **Certified Industrial Clerk (Industriekaufmann, IHK)** — graduated 2012

## Certifications

Microsoft Certified: Azure Fundamentals (AZ-900) · Azure Data Fundamentals (DP-900) · Azure AI Fundamentals (AI-900) · Microsoft 365 Fundamentals (MS-900)

Oracle Cloud Infrastructure Foundations Associate · Oracle Cloud Data Management Foundations Associate · Oracle Cloud Infrastructure AI Foundations Associate

Career Essentials in Generative AI (Microsoft & LinkedIn)

## Key Strengths

**Search specialist with a math foundation.** Thesis work on factorization algorithms gives me the analytical grounding for ranking, relevance tuning, and retrieval quality — not just tool operation.

**Proven across industries.** Delivered search and integration work for automotive, electronics/electrical engineering, public-sector, and financial-services clients.

**Business-IT bridge.** A dual background as an industrial clerk and computer scientist means I translate business/compliance requirements into clean technical specs.

**AI-integration builder, not just a user.** Beyond certifications, I've shipped a working RAG system (hybrid-search-api: BM25 + kNN + LLM answer synthesis, an agentic MCP-driven search mode, and a fully on-prem deployment option — tested, containerized, CI'd, bilingual EN/DE).

*(A full, downloadable CV PDF is available on request.)*
