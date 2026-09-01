# Jordan Montée

## Professional Experience

**GitGuardian — Growth Sales Engineer** *(Sep 2026 – now)*

Technical voice of GitGuardian for the Growth segment: product demos, technical discovery, and proofs of concept for security, DevOps, developer, and IAM teams. I own PoCs end to end (scoping, success criteria, execution) and relay prospect feedback and product gaps to Product & Engineering.

**GitGuardian — Technical Sales (Apprenticeship)** *(Nov 2024 – Aug 2026)*

Built the AI tooling and automation used by GitGuardian's Sales, CS, and Marketing teams.

- **AI Agent Development:** Architected and deployed a suite of AI agents to solve core business challenges. Key projects include an AI Sales Analyst for MEDDPICC deal scoring and a proactive CSM agent that analyzes product adoption signals to detect churn risk and identify upsell opportunities.
- **Internal Tooling:** Developed and shipped internal tools with direct impact on team productivity. Key achievement: built an automation that reduced a critical data processing task for the sales team from several hours to under five minutes.
- **Data-Driven Strategy:** Led the data analysis for a major industry event, processing and enriching a 1,000+ attendee list into a prioritized targeting strategy that saved the GTM team dozens of hours of manual work.

## Quantitative Research & Machine Learning

**Does Deep Learning Beat Simple Rules for Tactical Asset Allocation?**
*Master's Thesis, NEOMA Business School (2026) — A Leak-Free, Walk-Forward Study (2012–2024)*

- **The Foundation:** Conducted an extensive empirical study comparing machine learning allocators (LSTMs, PPO Reinforcement Learning, Direct-Sharpe Allocators) against simple, rule-based strategies (like volatility targeting) for tactical asset allocation.
- **The Methodology:** Built a rigorous, leak-free, walk-forward testing framework to audit and eliminate common quantitative research flaws, such as look-ahead bias and test-set leakage.
- **The Findings:** Showed that while custom loss functions like the Conditional Sharpe Ratio (CoSR) can produce highly attractive backtests, they often suffer from "objective degeneracy" (e.g., lowering exposure to avoid all risk) and overfit to noisy data. Under strict conditions, transparent rules like volatility targeting offered more robust out-of-sample performance than the complex models.
- **The Open Question:** The natural next step is closing the degeneracy loopholes: a deep learning allocator that penalizes excessive turnover and cash-hoarding enough to genuinely generalize out-of-sample during systemic market crashes. The framework is built; the models haven't earned it yet.

## Featured Project: Levkila Trade (DeepTrade)

An autonomous trading agent framework built to test the viability of LLMs in financial decision-making.

The agent operates in a continuous loop: it ingests real-time market data from the Binance Testnet, enriches it with technical indicators, and constructs a comprehensive prompt for an LLM. Governed by a rigid, rule-based constitution, the LLM returns a disciplined trading decision in JSON format, which the system then executes. The entire process is monitored via a real-time Dash control panel.

**Tech Stack:** Python, LLM, Prompt Engineering, Dash, Plotly, CCXT, Pandas

[View on GitHub](https://github.com/AliKelDev/levkila-trade) | [View presentation site](https://alikel-deeptrade.netlify.app/)

## Technical Skills

- **AI Engineering & Agents:** Multi-Agent Orchestration, Model Context Protocol (MCP) Client Implementation, Tool/Function Calling, Prompt Engineering, Fallback Parsing & Schema Enforcement.
- **LLMs & Vision:** Anthropic Claude, DeepSeek, Google Gemini, OpenRouter, Moondream (Vision AI).
- **Backend & Cloud Architecture:** Node.js, Serverless Functions (Netlify), Event-Driven Architecture, API Gateway Routing, Concurrency Control (ETags), Rate Limiting & Quota Management.
- **Auth & Security:** OAuth 2.0 / PKCE / Dynamic Client Registration (DCR), Cryptography (AES-256-GCM Token Sealing), Firebase Auth, JWT Verification, SSRF Hardening.
- **Data Engineering:** Firestore (NoSQL, Security Rules, Batch Writes), Netlify Blobs (KV Storage), Snowflake (SQL).
- **Full-Stack Development:** React, Vite, React Router, Tailwind CSS, Framer Motion (Complex UI animations), Context API.
- **DevOps & Tooling:** Netlify CLI, Firebase CLI, ESLint, PostCSS, CI/CD.
- **Quant & Finance:** Time-Series Analysis, Leak-Free Walk-Forward Validation, Backtest Overfitting Prevention, Portfolio Optimization, Tactical Asset Allocation (ETFs).

## Core Philosophy

My approach is hands-on, pragmatic, and problem-focused. I believe the best way to understand a technology's value is to build with it, and rigorously test it. Whether I am architecting an AI agent to streamline a sales workflow or auditing a financial machine learning model for backtest leakage, my goal is to create practical, efficient, and robust tools that solve real business challenges without relying on unnecessary complexity.

Currently poking at: multi-agent coordination. Eventually: drone swarms.
