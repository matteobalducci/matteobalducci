## Hi, I'm Matteo 👋

**Data Analyst** with 2.5+ years in enterprise BI consulting (SQL · Python · MicroStrategy · Power BI), specializing in **streaming & media product analytics**. I turn raw event data into the metrics that grow retention and revenue.

- 🎧 Building data products for the **music / streaming industry**
- 🔭 Working toward **Analytics Engineer** — dbt · BigQuery · dimensional modeling
- 🤖 Applied machine learning (scikit-learn): classification & ensemble models
- 🎓 Master in AI Solution Architect (ongoing) · Master in Data Analytics (Boolean)
- 📫 matteo.balducci14@gmail.com · [LinkedIn](https://www.linkedin.com/in/matteo-balducci/)

### 🚀 Featured projects

**[Music Streaming Analytics](https://github.com/matteobalducci/music-streaming-analytics)** — end-to-end product analytics on a 1.22M-event streaming dataset: star-schema model, dbt staging + marts with data-quality tests, a SQL business-questions suite, and a Power BI dashboard. Measures skip rate, discovery efficiency (algorithmic ~42% skip vs ~22% editorial/search), device-level skip patterns, churn-based retention (~82%), and revenue/RPM by subscription plan.

**[Streaming Insights Copilot](https://github.com/matteobalducci/streaming-insights-copilot)** — natural-language analytics layer over the same warehouse: an LLM (Claude API) turns business questions into SQL behind an AST-parsed, adversarially-tested read-only guardrail (sqlglot — blocks injection via table functions, comma joins and cross-dataset references), executed on DuckDB locally or BigQuery in production. Also ships a skip-prediction ML model (scikit-learn, gradient boosting) identifying discovery source as the strongest skip-risk driver.

**[Calciovich Content Pipeline](https://github.com/matteobalducci/calciovich-content-pipeline)** — a production system that generates and publishes video content daily to YouTube, Instagram and TikTok, agent-orchestrated and running unattended. Idempotent publishers, file-locked concurrent runs, per-format outlier detection against a rolling median, and a metrics logger accumulating channel time series with no retention cutoff. On top of that data: a BigQuery star-schema layer (staging → dimensional marts) feeding a 5-page Looker Studio report — engagement over time, cross-platform reach, category performance — every figure checked against the warehouse directly, with upstream data gaps documented rather than hidden (e.g. a confirmation timestamp that stays null by design until the next real publish event).

### 🛠️ Stack
`SQL` `Python (pandas, NumPy, scikit-learn, Seaborn, Beautiful Soup)` `dbt` `BigQuery` `Looker Studio` `Power BI` `Tableau` `MicroStrategy` `Git`
