# 👋 Hi, Jacob

**Full-Stack Developer & AI Engineer** building production systems across the entire stack — from data pipelines and AI assistants to web apps.

Most of my work lives in private repositories. Below is an overview of every project, what it does, and the technologies behind it.

---

## 📂 Projects

### 🔄 EANRunner — E-commerce Data Pipeline
> *Multi-customer product feed synchronization platform*

A production-grade data pipeline that ingests, enriches, and distributes product data to multiple e-commerce customers. Built on a **Medallion Architecture** (raw → consolidated → enriched) with delta-loading to eliminate redundant processing. Features AI-driven Swedish content generation, Icecat product enrichment, exchange rate handling, and automated scheduled syncs via Cloud Run.

| | |
|---|---|
| **Stack** | TypeScript, Python, Azure Data Factory, Google Cloud (Firestore, GCS, Cloud Run), Bicep |
| **Key Features** | Medallion data architecture, multi-customer sync (IP Agency, Elektronikspecialisten), AI content generation, Icecat enrichment, webhook delivery, delta-loading |
| **Repo** | `EANRunner` (TypeScript) · `EANrunner_old` (Go — legacy version) |

---

### 🐰 Rappit — Business Intelligence Platform
> *AI-powered email-to-project conversion system*

A full-stack SaaS application that transforms email conversations into actionable business projects with AI analysis, recommendations, and automated offer generation. Features an Outlook add-in, queue-based worker architecture, and a React frontend. Currently undergoing a **Domain-Driven Design transformation** across 13 architectural phases.

| | |
|---|---|
| **Stack** | Python (FastAPI), React 18, Vite, Supabase, Redis + RQ, OpenAI, SQLAlchemy, Playwright |
| **Key Features** | Email parsing & AI analysis, project/offer generation, queue workers, OAuth, Outlook add-in, DDD transformation roadmap |
| **Repos** | `rappit-app` (monorepo: backend + frontend) · `rappit` (architecture docs) · `rappit-landing` (marketing site, Next.js + TypeScript) |

---

### 🪖 AI_MIL — Intelligence Assistant
> *Privacy-first RAG system for intelligence operations*

A **completely local, air-gapped** Retrieval-Augmented Generation system designed for intelligence operations. Processes classified documents (intelligence reports, OSINT, SIGINT) with hybrid search (keyword + semantic) via OpenSearch, OCR document processing, and local LLM integration through Ollama. Built for secure, disconnected environments with zero cloud dependencies.

| | |
|---|---|
| **Stack** | Python, Streamlit, OpenSearch, Ollama, Sentence Transformers, Docker |
| **Key Features** | 100% local processing, hybrid search, OCR pipeline, JIPOE preparation support, air-gapped deployment |

---

### 👮 AI_COP — Knowledge Assistant
> *AI-powered procedural guidance for law enforcement*

An intelligent assistant for law enforcement that provides real-time access to procedures, laws, regulations, and fine schedules. Officers describe their situation in natural language and receive step-by-step guidance — from on-scene actions to paperwork completion. The knowledge base stays current as laws and departmental policies change.

| | |
|---|---|
| **Stack** | TypeScript, HTML, Shell |
| **Key Features** | Natural language Q&A, action card database, field decision support, end-to-end case workflow guidance, dynamic knowledge base |

---

### 🎓 AIVI — AI Learning Assistant
> *Study companion with source-verified answers*

A Danish-language AI teaching assistant that answers student questions strictly from their uploaded course material — with precise source citations (document + page/section). Three specialized chat modes: **Pensum** (curriculum Q&A), **Opgaver** (assignment help with hints, not answers), and **Eksamen** (exam prep with oral/written modes). Never makes claims without a source reference.

| | |
|---|---|
| **Stack** | TypeScript (backend + frontend), React, Vite |
| **Key Features** | RAG with strict source attribution, three specialized modes, exam preparation (oral & written), note-taking, Danish language |
| **Repos** | `aivi-backend` · `aivi-frontend` |

---

### 📊 EAI — Excel AI Analyzer
> *Intelligent Excel-to-SQL migration tool*

Upload any Excel file and get a complete structural analysis: cell data, formulas, cross-sheet references, VBA macros, charts, pivot tables, and complexity metrics. Uses AI to generate migration recommendations and target database schemas. Phase 1 (extraction + UI) is complete with 144 tests.

| | |
|---|---|
| **Stack** | Python (FastAPI), React 18, TypeScript, Vite, openpyxl, Claude (Anthropic) |
| **Key Features** | Formula extraction & pattern grouping, VBA macro analysis, dependency graphs, circular reference detection, complexity scoring, drag-and-drop UI |

---

### 💼 WorkLink — B2B Job Matching Platform
> *"Tinder for work opportunities" — swipe-based freelancer matching*

A cross-platform (web + mobile) job matching platform where companies and freelancers connect through a swipe interface. Monorepo architecture with shared TypeScript core across Next.js 16 web app and React Native (Expo) mobile app. Backend powered by Supabase with Drizzle ORM.

| | |
|---|---|
| **Stack** | TypeScript, Next.js 16, React Native (Expo), Express, Supabase, Drizzle ORM, pnpm + Turborepo |
| **Key Features** | Swipe-based matching, cross-platform (web + mobile), shared core package, tag-based matching (25+ categories), real-time chat |
| **Repos** | `worklink-frontend` (monorepo: web + mobile + core) · `worklink-backend` |

---

### 🏥 A-SCAN — Medical Clinic Website Rebuild
> *Performance-focused rebuild of a pregnancy scanning clinic website*

Complete technical deep-dive and rebuild of [a-scan.dk](https://a-scan.dk), a pregnancy scanning clinic in Hillerød, Denmark. Started with a comprehensive audit of the existing WordPress site (26 pages, 926 customers, 4,070 bookings), identified critical SEO gaps, and rebuilt as a modern Astro static site with the WordPress booking system as backend.

| | |
|---|---|
| **Stack** | Astro, JavaScript, CSS |
| **Key Features** | WordPress → Astro migration, full SEO audit & optimization, BookingPress integration, Google Search Console analysis, schema markup |

---

### 🎮 Roblox Ninefold — Dante's Inferno Game
> *Journey through the 9 Circles of Hell*

A Roblox game inspired by Dante's Inferno where players descend through all nine circles — from Limbo's gray ruins through Lust's whirling storms, Violence's three rings, Fraud's maze of trenches, to Treachery's frozen lake. Built with a modular map generation system, player data persistence via ProfileService, and client-server networking.

| | |
|---|---|
| **Stack** | Lua, Rojo, ProfileService |
| **Key Features** | 9 procedurally-themed circle maps, client-server architecture, persistent player data, modular map generators |

---

## 🛠️ Tech Stack Overview

| Category | Technologies |
|----------|-------------|
| **Languages** | TypeScript, Python, Go, Lua, HTML/CSS |
| **Frontend** | React, Next.js, Vite, Astro, React Native (Expo), Streamlit |
| **Backend** | FastAPI, Express, Node.js |
| **AI/ML** | OpenAI, Claude (Anthropic), Ollama, RAG, Sentence Transformers, OpenSearch |
| **Cloud** | Google Cloud (Firestore, GCS, Cloud Run), Azure (Data Factory, Functions, Bicep) |
| **Databases** | Supabase (PostgreSQL), Redis, SQLAlchemy, Drizzle ORM |
| **DevOps** | Docker, Turborepo, pnpm, Rojo |

---

## 📫 Get in Touch

Feel free to reach out if you'd like to discuss any of these projects or potential collaboration opportunities.
