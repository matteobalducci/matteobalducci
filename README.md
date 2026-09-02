## Hi, I'm Matteo 👋

**Data Analyst** with 2.5+ years in enterprise BI consulting (SQL · Python · MicroStrategy · Power BI), specializing in **streaming & media product analytics**. I turn raw event data into the metrics that grow retention and revenue.

- 🎧 Building data products for the **music / streaming industry**
- 🔭 Working toward **Analytics Engineer** — dbt · BigQuery · dimensional modeling
- 🤖 Applied machine learning (scikit-learn): classification & ensemble models
- 🎓 Master in AI Solution Architect (ongoing) · Master in Data Analytics (Boolean)
- 📫 matteo.balducci14@gmail.com · [LinkedIn](https://www.linkedin.com/in/matteo-balducci/)

### 🚀 Featured projects

The three projects below are one loop: **model** streaming data, **query** it, and **operate a content system that produces it**.

**[Music Streaming Analytics](https://github.com/matteobalducci/music-streaming-analytics)** — end-to-end product analytics on a 1.23M-event streaming dataset: star-schema model, dbt staging + marts with data-quality tests, a SQL business-questions suite, and a Power BI dashboard. Measures skip rate, discovery efficiency (algorithmic ~42% skip vs ~22% editorial/search), device-level skip patterns, churn-based retention (~82%), and revenue/RPM by subscription plan.

**[Streaming Insights Copilot](https://github.com/matteobalducci/streaming-insights-copilot)** — natural-language analytics layer over the same warehouse: an LLM (Claude API) turns business questions into SQL behind a read-only guardrail layer, executed on DuckDB locally or BigQuery in production. Also ships a skip-prediction ML model (scikit-learn, gradient boosting) identifying discovery source as the dominant churn-risk driver.

**[Calciovich Content Pipeline](https://github.com/matteobalducci/calciovich-content-pipeline)** — the *upstream* side of the same domain: a production content system publishing daily to YouTube, Instagram and TikTok, and instrumented to generate its own performance data. Ships a historical metrics logger (no retention cutoff), an outlier detector that scores each release against its format's rolling median via the YouTube Analytics API, and a dashboard over the resulting time series. Idempotent publishers, file-locked concurrent runs, agent-orchestrated daily execution.

### 🛠️ Stack
`SQL` `Python (pandas, NumPy, scikit-learn, Seaborn, Beautiful Soup)` `dbt` `BigQuery` `Looker Studio` `Power BI` `Tableau` `MicroStrategy` `Git`
