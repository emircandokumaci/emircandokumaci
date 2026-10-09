# Emircan Dokumacı

**AI Automation & Systems Architecture**  
Python · n8n · APIs · Docker · Cloud Infrastructure

I design and build automation systems that connect AI tools, APIs, workflow engines, data pipelines, and cloud infrastructure.

My focus is turning fragmented manual or SaaS-based workflows into **reliable, observable, self-hosted systems** with clear safety boundaries and minimal manual intervention.

## What I Build

- AI-powered workflow and process automation
- API and webhook integrations
- Self-hosted n8n orchestration
- Python automation services and backend APIs
- Dockerized cloud infrastructure
- Reliability, retries, idempotency, logging, and fail-closed controls
- System migrations from prototype workflows to maintainable architectures

## Selected Work

### Binance Futures Automation & Risk Engine

A self-hosted Binance Global USDⓈ-M Futures research and paper-trading system that evolved from Make.com workflow prototypes into a modular Python architecture.

**Architecture:** Python · FastAPI · PostgreSQL · Docker · Binance REST/WebSocket APIs

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

## Engineering Approach

I prefer systems that are:

- **Observable** — state, failures, and outcomes can be inspected
- **Deterministic where it matters** — risk and safety rules live in code, not prompts
- **Fail-closed** — missing or stale inputs block unsafe actions
- **Modular** — services and integrations can be changed independently
- **Cost-aware** — self-hosted components are used where they make operational sense
- **Automation-first** — routine operations should not require constant manual intervention

## Core Stack

`Python` · `FastAPI` · `PostgreSQL` · `Docker` · `n8n` · `Make.com` · `REST APIs` · `Webhooks` · `OAuth` · `FFmpeg` · `Ubuntu` · `DigitalOcean`

## Current Direction

Building toward **AI Automation / Systems Architecture** roles and international freelance work focused on practical, production-oriented automation systems.

## Connect

**LinkedIn:**  
https://www.linkedin.com/in/emircan-dokumacı-2a2685a8

**GitHub:**  
https://github.com/emircandokumaci
