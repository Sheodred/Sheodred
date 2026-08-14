# Hi, ich bin Adrian 👋

**Sprache:** [English](README.md) | **Deutsch**

Backend-Entwickler mit Fokus auf **Suche/Elasticsearch** und **KI-Integration** (RAG, LLM-Anbindung).

## 🔎 Aktuelles Projekt

### [hybrid-search-api](https://github.com/Sheodred/hybrid-search-api)
Elasticsearch Hybrid Search (BM25 + kNN via Reciprocal Rank Fusion) mit einer
LLM-Schicht für quellenbasierte RAG-Antworten.

![CI](https://github.com/Sheodred/hybrid-search-api/actions/workflows/ci.yml/badge.svg)
![Python](https://img.shields.io/badge/python-3.12-blue)
![License: MIT](https://img.shields.io/badge/license-MIT-green)

- **Backend-Engineering** — FastAPI, containerisiert (Docker Compose), getestet (pytest), CI (GitHub Actions), gelintet (ruff)
- **Such-Spezialisierung** — custom Elasticsearch-Mapping/Analyzer, BM25 + Vektor-/kNN-Suche, Ranking-Fusion per RRF
- **KI-Integration** — produktionsnahe LLM-Anbindung über einen beliebigen OpenAI-kompatiblen Endpunkt (Retry-Logik, versionierte Prompts, RAG), lokale Embeddings via sentence-transformers, sowie ein Sprach-Toggle (EN/DE) zur Laufzeit

📖 [README](https://github.com/Sheodred/hybrid-search-api#readme) · [Architektur](https://github.com/Sheodred/hybrid-search-api/blob/main/docs/architecture.md)

## 🛠️ Stack

Python · FastAPI · Elasticsearch · Docker · pytest · ruff · GitHub Actions

## 📫 Kontakt

[LinkedIn](https://www.linkedin.com/in/adrian-kluge/) · [E-Mail](mailto:92444350+Sheodred@users.noreply.github.com)

---

# Lebenslauf

Adrian Kluge | Dortmund, Deutschland | [E-Mail](mailto:92444350+Sheodred@users.noreply.github.com)
[linkedin.com/in/adrian-kluge](https://www.linkedin.com/in/adrian-kluge/) · [github.com/Sheodred](https://github.com/Sheodred)

### Software Developer — Backend, Suche & KI-Integration

## Profil

Backend-Entwickler mit über 2 Jahren kontinuierlicher Entwicklung bei einem großen deutschen IT-Beratungsunternehmen —
vom Werkstudenten über die Traineephase zum Software Developer befördert —
spezialisiert auf Elasticsearch-Suchinfrastruktur und zunehmend auf LLM-/RAG-
Integration. Suchsysteme für Kunden aus Automotive, Elektrotechnik und dem
öffentlichen Sektor aufgebaut und ausgeliefert; zuletzt in Eigeninitiative eine
Hybrid-Suche (BM25 + kNN) mit RAG-Antwortschicht von der Idee bis zum getesteten,
CI-gebauten, englischsprachig dokumentierten Open-Source-Projekt gebracht (siehe
oben). Muttersprache Deutsch, verhandlungssicheres Englisch, mit mathematischem
B.Sc.-Fundament (Faktorisierungsalgorithmen) als Basis für die analytische Seite
von Relevanz- und Ranking-Arbeit.

## Kernkompetenzen

- **Sprachen & Frameworks:** Java (Experte), Kotlin, Spring Boot, Python, C++
- **Suche & Daten:** Elasticsearch (Experte — Indexmodellierung, Relevanz-Tuning, BM25 + kNN-/Vektorsuche, Reciprocal Rank Fusion), OpenSearch, Solr, Lucene, MongoDB, MySQL, Microsoft SQL Server
- **KI & RAG:** LLM-Anbindung über OpenAI-kompatible APIs, Retrieval-Augmented Generation, versionierte Prompt-Entwicklung, lokale Embeddings (sentence-transformers), Generative-AI-Grundlagen (Microsoft & LinkedIn zertifiziert)
- **Cloud & DevOps:** Microsoft Azure (4-fach zertifiziert), Oracle Cloud Infrastructure (3-fach zertifiziert), Docker/Docker Compose, Kubernetes, GitLab CI/CD, Gradle (Multi-Project-Konfiguration), Maven
- **Enterprise-Integration:** Jakarta EE, REST/OpenAPI, PIM-Systeme (NovaDB), FirstSpirit CMS (Modul- & Templateentwicklung), BPMN, Camunda BPM
- **Frontend:** Angular, Vue.js, React, TypeScript, Thymeleaf
- **Testing & Qualität:** JUnit, ArchUnit, Clean Code / Design Patterns
- **Sprachkenntnisse:** Deutsch (Muttersprache, C2) · Englisch (verhandlungssicher, C1)

## Beruflicher Werdegang

**Ein großes deutsches IT-Beratungsunternehmen, Dortmund**
Software Developer | Okt. 2025 – heute
*(zuvor Trainee, Mai 2024 – Sept. 2025 · Werkstudent Softwareentwicklung, Sept. 2023 – Apr. 2024 — durchgängige Entwicklung im selben Team)*

**Öffentlich-rechtliche Investitionsbank — Website- & Suchmodernisierung** *(aktuell)*
- Suche komplett neu auf Elasticsearch aufgebaut, den bisherigen crawlerbasierten Index durch eine direkt konfigurierte, redaktionell steuerbare Pipeline ersetzt.
- Verantwortlich für Indexaufbau, Query-Tuning und die CMS-seitige Erzeugung der Suchdokumente im Rahmen eines laufenden Website-Relaunches.

**Führender deutscher Premium-Automobilhersteller — Migration & Suche**
- Kostenpflichtige Drittanbieter-Crawler-Suche durch eine eigene Elasticsearch-Pipeline ersetzt: Indexschema, Dokument-Mapping und Relevanz-Tuning selbst konzipiert.
- JSON-basiertes Import-Modul entwickelt, das Quelldaten mit dem bereits indexierten Bestand abgleicht und nur veränderte Elemente aktualisiert — reduziert den Sync-Overhead gegenüber vollständigen Neu-Importen.

**Globaler Elektrotechnik- und Elektronikkonzern — Modernisierung**
- Geschäftskritische Build-Module von Maven auf Gradle migriert, inklusive Gradle-Multi-Project-Konfiguration für einen globalen Website-Relaunch.
- Legacy-Systeme auf aktuelle Jakarta-EE-Standards angehoben und einen Webforms-Modulstack auf Formcentric migriert, bestehende Funktionalität über den Versionssprung hinweg erhalten.

**Weltweit führender Hersteller von Vakuumpumpen — PIM-Systemintegration**
- Legacy-PIM-Importer auf eine moderne, OpenAPI-basierte Java-Schnittstelle migriert und damit die Produktdatenanbindung für einen globalen Multi-Brand-Website-Relaunch vereinheitlicht.

**Organisation des öffentlichen Sektors — Fehleranalyse & Optimierung der Suche**
- Einen Partial-Match-Fehler in einer TypeScript-/Elasticsearch-Middleware durch gezielte Codebasis-Analyse diagnostiziert, Indexierungs-/Query-Logik behoben und dabei eine kritische Sicherheitslücke entdeckt und geschlossen.

## Ausbildung

- **Master of Science (M.Sc.), Informatik, Schwerpunkt Optimierung** — TU Dortmund — *laufend*
- **Bachelor of Science (B.Sc.), Informatik, Nebenfach Mathematik** — TU Dortmund — Abschluss 2024. Thesis: *„Implementation and Comparison of Factorization Algorithms"* (SageMath/Python).
- **Industriekaufmann (IHK)** — Abschluss 2012

## Zertifikate

Microsoft Certified: Azure Fundamentals (AZ-900) · Azure Data Fundamentals (DP-900) · Azure AI Fundamentals (AI-900) · Microsoft 365 Fundamentals (MS-900)

Oracle Cloud Infrastructure Foundations Associate · Oracle Cloud Data Management Foundations Associate · Oracle Cloud Infrastructure AI Foundations Associate

Career Essentials in Generative AI (Microsoft & LinkedIn)

## Stärken

**Suchspezialist mit mathematischem Fundament.** Die Thesis zu Faktorisierungsalgorithmen liefert das analytische Rüstzeug für Ranking, Relevanz-Tuning und Retrieval-Qualität — nicht nur Tool-Bedienung.

**Branchenübergreifend bewährt.** Such- und Integrationsprojekte für Automotive, Elektrotechnik/Elektronik, öffentlichen Sektor und Finanzdienstleistungen umgesetzt.

**Brücke zwischen Business und IT.** Der doppelte Hintergrund als Industriekaufmann und Informatiker sorgt dafür, dass Business-/Compliance-Anforderungen sauber in technische Spezifikationen übersetzt werden.

**KI-Integration selbst gebaut, nicht nur zertifiziert.** Über die Zertifikate hinaus ein funktionierendes RAG-System selbst gebaut (hybrid-search-api: BM25 + kNN + LLM-Antwortsynthese, getestet, containerisiert, CI-gebaut, zweisprachig EN/DE).

*(Ein vollständiger, herunterladbarer Lebenslauf als PDF ist auf Anfrage verfügbar.)*
