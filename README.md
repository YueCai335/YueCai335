## Yue Cai

Backend / full-stack developer with a finance background. Montréal, Canada.

**Master of Applied Computing @ Wilfrid Laurier University (GPA 11.4 / 12.0)**  
**Master of Science in Finance · Passed Level I of the CFA Program**

I build Python backends with FastAPI and PostgreSQL, and the React and Next.js frontends that go with them. What I care about is the unglamorous part: data models that hold up, migrations that actually run, tests that catch things, and AI features that cite their sources instead of guessing.

### Stack

`Python` `FastAPI` `SQLAlchemy` `Alembic` `PostgreSQL` `SQLite` `pgvector` `SQL` `TypeScript` `Next.js` `React` `Chart.js` `pytest` `Vitest` `Docker` `GitHub Actions` `Java`

### Projects

**[Garden Manager](https://github.com/YueCai335/garden-manager)** · [live demo](https://garden-manager-demo.vercel.app)

Full-stack garden operations and seasonal-planning app. Next.js + TypeScript frontend; FastAPI + PostgreSQL backend with Pydantic validation and Alembic migrations; deterministic crop-family rotation logic; and a pgvector RAG assistant that shows its citations and asks for review before anything is written to the database. CI runs type checks, frontend and backend tests, a production build, and a Docker Compose health check.

**[Financial Ratio Analyzer](https://github.com/YueCai335/financial-ratio-analyzer)**

Enter the key figures from a company's annual report, get eight core financial ratios, and see multi-year trends and cross-company comparisons. FastAPI + SQLite, with the ratio layer written as pure functions so it can be tested without a database. The DuPont identity (ROE = ROA × equity multiplier) and the leverage identity are asserted in the test suite, so a mistyped formula fails rather than returning a plausible number. The health check is documented thresholds, not a model — every warning traces back to a specific number crossing a specific line.

**[Fraud Detection System](https://github.com/YueCai335/fraud-detection-system)**

Fraud-detection web app built on a Random Forest model trained on PaySim transaction data. A Flask REST endpoint returns predictions through an end-to-end browser workflow, and SHAP explanations surface the features behind each prediction so a reviewer can judge the output instead of accepting it blindly.

### Currently

**Available immediately for full-time work.** Looking for a backend, full-stack, or financial-systems developer role in Montréal or remote; also open to co-op and internship terms. Completing a Master of Applied Computing (expected May 2027). Permanent resident, no sponsorship required.

📫 caiyue2011@gmail.com
