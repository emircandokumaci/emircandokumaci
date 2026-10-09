# Emircan Dokumacı

**AI Automation & Systems Architecture**  
Python · n8n · APIs · Docker · Cloud Infrastructure

I design and build automation systems that connect AI tools, APIs, workflow engines, media pipelines, and cloud infrastructure.

My focus is turning fragmented manual or SaaS-based workflows into **reliable, observable, self-hosted systems** with explicit safety boundaries and minimal manual intervention.

## What I Build

- AI-powered workflow and process automation
- API and webhook integrations
- Self-hosted n8n orchestration
- Python automation services and backend APIs
- Dockerized cloud infrastructure
- Media and publishing pipelines
- Reliability patterns: retries, idempotency, reconciliation, logging, and fail-closed controls
- Migrations from workflow prototypes to maintainable system architectures

## Selected Work

### AI Content Automation Engine

A reliability-first, self-hosted pipeline for AI-assisted content production and YouTube publishing.

**Stack:** Python · Node.js · FFmpeg · n8n · YouTube Data API · OAuth · Docker

**Engineering highlights:**
- manifest and asset validation before rendering
- video quality-control gates
- durable publish claims and upload receipts
- SHA-256 content deduplication
- channel-level upload mutex
- daily publishing circuit breaker
- idempotent retry behavior
- post-upload verification and reconciliation

**Repository:**  
https://github.com/emircandokumaci/ai-content-automation-engine

### Binance Futures Automation & Risk Engine

A self-hosted Binance Global USDⓈ-M Futures research and paper-trading system evolved from Make.com prototypes into a modular Python architecture.

**Stack:** Python · FastAPI · PostgreSQL · Docker · Binance REST/WebSocket APIs

**Engineering highlights:**
- deterministic risk and position-sizing engine
- liquid USDT perpetual universe selection
- multi-timeframe market analysis and shadow signals
- paper execution with fees, slippage, funding, and PnL tracking
- exchange-rule and liquidation safeguards
- PostgreSQL event journal and reconciliation layers
- fail-closed safety architecture
- **35 automated tests passing**

**Repository:**  
https://github.com/emircandokumaci/binance-futures-automation-engine

## Engineering Principles

I prefer systems that are:

- **Observable** — state, failures, and outcomes can be inspected
- **Deterministic where it matters** — safety and risk rules live in code, not prompts
- **Idempotent** — retries do not create duplicate external side effects
- **Fail-closed** — missing or stale inputs block unsafe actions
- **Modular** — services and integrations can evolve independently
- **Cost-aware** — self-hosted components are used where they make operational sense
- **Automation-first** — routine operations should not require constant manual intervention

## Core Stack

`Python` · `FastAPI` · `PostgreSQL` · `Docker` · `n8n` · `Make.com` · `REST APIs` · `Webhooks` · `OAuth` · `FFmpeg` · `Node.js` · `Ubuntu` · `DigitalOcean`

## Current Direction

Building toward **AI Automation / Systems Architecture** roles and international freelance work focused on practical, production-oriented automation systems.

## Connect

**LinkedIn:**  
https://www.linkedin.com/in/emircan-dokumacı-2a2685a8

**GitHub:**  
https://github.com/emircandokumaci
