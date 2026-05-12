# Alex Belafostau — AI Developer (Quereinsteiger aus Aviation)

Ich baue produktive KI-Anwendungen mit Python und LLM-APIs. Fokus: ehrliche Implementierungen, die funktionieren — kein Hype.

## Live & Public

| Projekt | Was es ist | Stack |
|---------|------------|-------|
| **[mastermAInd.ai](https://mastermaind.ai)** | Live Demo-Plattform. Aktuell produktiv: Prompt Optimizer (Anthropic API). Weitere Tools (RAG, NL-to-SQL, MindLight, Multi-Agent-Orchestrator) sind als UI/Demo-Seiten gebaut und werden mit den Triple-Alpha-Backend-Modulen verbunden. FastAPI + Jinja2 + Tailwind, auf Render deployed. | FastAPI, Supabase, Render |
| **[rag-fastapi-cloud-onprem](https://github.com/adstronglv/rag-fastapi-cloud-onprem)** | Document Q&A mit austauschbarem LLM-Backend (Anthropic Cloud ↔ Ollama On-Premise) über eine Env-Variable. Demo des Cloud/On-Premise-Switches für DSGVO-sensitive Use Cases. **Kein klassisches RAG mit Vector-Store** — Dokument wird inline an das LLM übergeben. | Python, FastAPI, Anthropic SDK, Ollama, Docker |
| **[mastermAind-showcase](https://github.com/adstronglv/mastermAind-showcase)** | Architektur-Doku und Design-Entscheidungen für mastermAInd.ai. Source ist privat, weil aktives Projekt. | Markdown, Screenshots, Diagramme |

## Lokal / On-Premise (Demo via Bildschirm-Share möglich)

| Projekt | Was es ist | Stack |
|---------|------------|-------|
| **Triple Alpha Agents** | Multi-Agent-System (Scout, Analyst, Planner, World-Agent) für tägliche Markt-Reports. Mit echter RAG-Pipeline (nomic-embed-text Embeddings via Ollama, Cosine-Similarity über numpy, Chunk-Extraktion) und NL-to-SQL (sqlcoder:7b, SELECT-only Safety). Alles on-premise. | Python, FastAPI, SQLite, Ollama, numpy, httpx |
| **Megamind Orchestrator** | Persönlicher AI-Projektmanager mit Gmail-Integration und heuristik-basiertem Job-Score-System (7-Layer-Filterlogik: Hard-Filter, Distance, Logistik-Domain, Tech-in-Logistics, Negative-Keywords, Geo, Triple-Filter-Bonus). Kein ML/LLM im Score-Pfad — bewusst deterministisch. | Python, FastAPI, SQLite, Gmail API, n8n, Telegram |

## Tech Stack — was ich tatsächlich produktiv nutze

`Python` · `FastAPI` · `Claude API (Anthropic)` · `Ollama` (qwen3, sqlcoder, nomic-embed-text) · `SQLite` · `Supabase/Postgres` · `Docker` · `n8n` · `Jinja2` · `Tailwind CSS` · `Git`

**Konzeptionell durchdrungen, aber nicht produktiv eingesetzt:** Model Context Protocol (MCP), LangChain/LlamaIndex, pgvector/Chroma als Vector-Store. Sind nächste Lern-Schritte.

## Hintergrund

Fast 14 Jahre operative Verantwortung bei DHL Airways am Frankfurter Flughafen, davon 7 Jahre als stellvertretender Supervisor in der Network Control Group. ILS-Fernkurs Fachinformatiker Anwendungsentwicklung abgeschlossen (Note 1.8, 688 Stunden, neben Vollzeitjob).

Seit Mitte 2025 baue ich AI-Systeme produktiv — Claude Code als Daily Driver, Vibe-Coding-Workflow. Ziel: Quereinstieg in eine deutsche IT-Stelle mit AI-Fokus, langfristig Wohnsitz Portugal.

## Sprachen

Deutsch (C1) · English · Russisch (Muttersprache) · Spanisch (Grundkenntnisse)

## Kontakt

- **Web:** [mastermaind.ai](https://mastermaind.ai)
- **E-Mail:** info@mastermaind.ai
- **LinkedIn:** [Aliaksandr Belafostau](https://www.linkedin.com/in/aliaksandr-belafostau-a793393aa)
