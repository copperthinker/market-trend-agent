# Market Trend Agent

An agentic AI system for monitoring stock and crypto market trends.

**Goal**: Build a live, fully deployed agent that answers natural language queries about market trends using real-time + historical data, multi-agent reasoning, and visualizations.

Currently in active development following a structured plan:
- Step 1: Live agent API on GCP Cloud Run
- Step 2: Daily data pipeline + BigQuery
- Step 3: Migrate to LangGraph
- Step 4: Multi-agent orchestration + MLflow tracking
- Step 5: dbt transformations + Looker Studio dashboards
- Step 6: CI/CD + production polish

Built with:
- CrewAI → LangGraph
- Groq LLM
- yfinance + news sources
- FastAPI + Docker + GCP (Cloud Run, BigQuery, Scheduler)
- dbt + Looker Studio

**Step 1 in progress** — setting up the repository and local environment.

More details, live URL, architecture, and demos coming soon as each week ships.

Built by [copperthinker](https://github.com/copperthinker)
