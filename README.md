# Kirill Zhigalov

**ML Engineer / Data Scientist** · Saint Petersburg / remote

I build ranking, recommendation and scoring models end to end: leakage-safe datasets and features, offline evaluation (NDCG, PR-AUC, MAE), experiment tracking, and the service around the model — FastAPI, Next.js, Docker, CI.

## Experience

| Period | Company | Role | Focus |
| --- | --- | --- | --- |
| 2025 – 2026 | Yandex Lavka | ML Developer | Product recommendations: feature checks for stale events and out-of-stock items, ranking comparison by NDCG@10 before A/B tests |
| 2024 – 2025 | Avito | ML Engineer | Job ranking in Avito Jobs: leakage-safe training data, feature pipeline rewrite, MLflow tracking |
| 2023 – 2024 | T-Bank | Systems Analyst | Marketing consent API specs, SQL checks of data mismatches between services |

## Featured projects

| Project | Result | Stack |
| --- | --- | --- |
| **[Job Ranker](https://github.com/kzhigalov-dev/job-ranker)** | Two-stage job recommender on CareerBuilder data (71k users, 284k jobs): NDCG@10 **1.8×** the best baseline, confirmed on a second time window | Python, LightGBM LambdaRank, TF-IDF, MLflow, pytest |
| **[FraudLens](https://github.com/kzhigalov-dev/fraudlens)** | Calibrated fraud model catches **53.7%** of fraud while reviewing 5% of applications (**10.7×** random), with PSI drift monitoring | Python, LightGBM, FastAPI, Next.js, Docker |
| **[Retail Demand Planner](https://github.com/kzhigalov-dev/retail-demand-planner)** | LightGBM cut MAE by **4.7%** vs a seasonal baseline; inventory simulation lowered cost by **£17,909** | Python, LightGBM, FastAPI, Next.js, Docker |
| **[MarketAI](https://github.com/kzhigalov-dev/marketai)** | Deployed AI SaaS generating WB/Ozon/Amazon listings, with auth and Stripe + YooKassa billing | Next.js, Supabase, Claude API |
| **[Creatix](https://github.com/kzhigalov-dev/creatix)** | URL → video creative pipeline | Firecrawl, GPT-4o, ElevenLabs, Next.js |
| **[Series Shorts Agent](https://github.com/kzhigalov-dev/series-shorts-agent)** | Multimodal agent that scripts, renders and publishes bilingual YouTube Shorts | TypeScript, Gemini Vision, Remotion, YouTube API |

Also: [Playwright E2E suite](https://github.com/kzhigalov-dev/f2f-bank-tests) for a banking web app (25 tests, real Vue + FastAPI + PostgreSQL) and a [museum website](https://github.com/kzhigalov-dev/gubakha-museum) on Next.js + Tailwind.

## Skills

- **ML:** Python, pandas, NumPy, scikit-learn, LightGBM, learning to rank, recommender systems, forecasting, classification
- **Evaluation:** temporal validation, leakage prevention, NDCG, MAP, PR-AUC, recall@k, MAE, calibration, PSI drift, A/B tests
- **Data & MLOps:** SQL, PostgreSQL, MLflow, Git, Docker Compose, CI, pytest, mypy, Ruff
- **Services:** FastAPI, REST, Pydantic, Swagger/OpenAPI, Next.js, React, TypeScript, Supabase, Vercel

## Education

- Applied Informatics, SPbSUITD · Bachelor's degree expected in 2027
- Anthropic Academy · Claude 101 and AI Fluency: Framework & Foundations

## Contact

[Email](mailto:jigaloffkir@gmail.com) · [GitHub](https://github.com/kzhigalov-dev)
