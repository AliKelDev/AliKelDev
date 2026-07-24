### **Jordan Montée**

Recently completed a Master in Management (Programme Grande Ecole) specializing in Finance and Corporate & Investment Banking at NEOMA Business School.

### Professional Experience

**GitGuardian** 2024 - now

My role at GitGuardian is to enhance our GTM motion by building the tools and data systems our teams need to be more efficient and intelligent.

*   **AI Agent Development:** Architected and deployed a suite of AI agents to solve core business challenges. Key projects include an AI Sales Analyst for MEDDPICC deal scoring and a proactive CSM agent that analyzes product adoption signals to detect churn risk and identify upsell opportunities.
*   **Internal Tooling:** Developed and shipped a suite of internal tools that have a direct impact on team productivity. **Key achievement:** Built an automation that reduced a critical data processing task for the sales team **from several hours to under five minutes**.
*   **Data-Driven Strategy:** Led the data analysis for a major industry event, processing and enriching a +1000-attendee list to create a prioritized targeting strategy that saved the GTM team dozens of hours of manual work.

---

### Quantitative Research & Machine Learning

**Does Deep Learning Beat Simple Rules for Tactical Asset Allocation?** 
*Master's Thesis — A Leak-Free, Walk-Forward Study (2012–2024)*

*   **The Foundation:** Conducted an extensive empirical study comparing machine learning allocators (LSTMs, PPO Reinforcement Learning, Direct-Sharpe Allocators) against simple, rule-based strategies (like volatility targeting) for tactical asset allocation.
*   **The Methodology:** Built a highly rigorous, leak-free, walk-forward testing framework to audit and eliminate common quantitative research flaws, such as look-ahead bias and test-set leakage.
*   **The Findings:** Proved that while custom loss functions like the Conditional Sharpe Ratio (CoSR) can produce highly attractive backtests, they often suffer from "objective degeneracy" (e.g., lowering exposure to avoid all risk) and overfit to noisy data. Under strict conditions, transparent rules like volatility targeting offered more robust out-of-sample performance than the initial complex models.
*   **Current Focus (Active Development):** Building directly on these findings, I am actively iterating on the ML architectures (including Temporal Fusion Transformers and advanced LSTMs) to close the degeneracy loopholes. The ongoing goal is to train a deep learning allocator that effectively penalizes excessive turnover and cash-hoarding, genuinely generalizing out-of-sample to outperform simple baselines during systemic market crashes.

---

### Featured Project: Levkila Trade (DeepTrade)

*An autonomous trading agent framework built to test the viability of LLMs in financial decision-making.*

The agent operates in a continuous loop: it ingests real-time market data from the Binance Testnet, enriches it with technical indicators, and constructs a comprehensive prompt for an LLM (`deepseek-reasoner`). Governed by a rigid, rule-based constitution, the LLM returns a disciplined trading decision in JSON format, which the system then executes. The entire process is monitored via a real-time Dash control panel.

*   **Tech Stack:** Python, LLM, Prompt Engineering, Dash, Plotly, CCXT, Pandas
*   **[View on GitHub](https://github.com/AliKelDev/levkila-trade)** | [View presentation site](https://alikel-deeptrade.netlify.app/)

---

### Technical Skills

*   **AI Engineering & Agents:** Multi-Agent Orchestration, Model Context Protocol (MCP) Client Implementation, Tool/Function Calling, Prompt Engineering, Fallback Parsing & Schema Enforcement.
*   **LLMs & Vision:** DeepSeek (V4/R1), Google Gemini (3.6 Flash w/ Search Grounding), OpenRouter, Anthropic Claude, Moondream (Vision AI).
*   **Backend & Cloud Architecture:** Node.js, Serverless Functions (Netlify), Event-Driven Architecture, API Gateway Routing, Concurrency Control (ETags), Rate Limiting & Quota Management.
*   **Auth & Security:** OAuth 2.0 / PKCE / Dynamic Client Registration (DCR), Cryptography (AES-256-GCM Token Sealing), Firebase Auth, JWT Verification, SSRF Hardening.
*   **Data Engineering:** Firestore (NoSQL, Security Rules, Batch Writes), Netlify Blobs (KV Storage), Snowflake (SQL).
*   **Full-Stack Development:** React 18, Vite, React Router, Tailwind CSS, Framer Motion (Complex UI animations), Context API.
*   **DevOps & Tooling:** Netlify CLI, Firebase CLI, ESLint, PostCSS, CI/CD.
*   **Quant & Finance:** Time-Series Analysis, Leak-Free Walk-Forward Validation, Backtest Overfitting Prevention, Portfolio Optimization, Tactical Asset Allocation (ETFs).


### Core Philosophy

My approach is hands-on, pragmatic, and problem-focused. I believe the best way to understand a technology's value is to build with it—and rigorously test it. Whether I am architecting an AI agent to streamline a sales workflow or auditing a financial machine learning model for backtest leakage, my goal is to create practical, efficient, and robust tools that solve real business challenges without relying on unnecessary complexity.
