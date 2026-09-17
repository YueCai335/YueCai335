## Yue Cai

Backend / full-stack developer with a finance background. Montréal, Canada.

**Master of Applied Computing @ Wilfrid Laurier University (GPA 11.4 / 12.0)**  
**Master of Science in Finance · Passed Level I of the CFA Program**

I build backend services in Python (FastAPI) and Java (Spring Boot), and the React and Next.js frontends that go with them. What I care about is the unglamorous part: data models that hold up, migrations that actually run, tests that catch things, and reviewable AI features with visible source citations.

### Stack

`Python` `FastAPI` `SQLAlchemy` `Alembic` `Java` `Spring Boot` `Spring Security` `Spring Data JPA` `Flyway`  
`PostgreSQL` `MySQL` `SQLite` `pgvector` `SQL` `TypeScript` `Next.js` `React` `Chart.js`  
`pytest` `JUnit` `Vitest` `Playwright` `Docker` `GitHub Actions` `AWS (ECS Fargate, RDS, ECR, S3)` `Terraform`

### Projects

**[Garden Manager](https://github.com/YueCai335/garden-manager)** · [live demo](https://garden-manager-demo.vercel.app)

Full-stack garden operations and seasonal-planning app built with Next.js, TypeScript, FastAPI, and PostgreSQL. Automatic workspace sync uses revision checks to surface conflicting saves; crop-family rotation rules guide next-season planning. The local app includes pgvector RAG with citations and Chinese/English care-note extraction with review before saving. The hosted demo covers Garden, Care, and Season Planner. GitHub Actions checks lint, types, frontend and backend tests (SQLite and PostgreSQL), a Playwright save-and-reload flow, a production build, and Docker Compose health.

**[Fraud Detection System](https://github.com/YueCai335/fraud-detection-system)**

Scores PaySim-style transactions with a Spring Boot 3 REST service, Spring Security, Flyway-managed MySQL, and a Flask/scikit-learn model service with SHAP explanations. Asynchronous CSV jobs support progress tracking, idempotent submission, checkpoint recovery, and S3 result downloads; Resilience4j adds model-call retries and a circuit breaker. Built from a Java EE course project, with the migration documented in the repo. Verified on AWS ECS Fargate, RDS, and S3 using Terraform and GitHub Actions; the environment runs on demand ([deployment record](https://github.com/YueCai335/fraud-detection-system/blob/main/docs/deployment.md)). CI runs JUnit, pytest, and a Docker Compose smoke test.

**[Financial Ratio Analyzer](https://github.com/YueCai335/financial-ratio-analyzer)**

Enter the key figures from a company's annual report, get eight core financial ratios, and see multi-year trends and cross-company comparisons. FastAPI + SQLite, with the ratio layer written as pure functions so it can be tested without a database. The DuPont identity (ROE = ROA × equity multiplier) and the leverage identity are asserted in the test suite, so a mistyped formula fails rather than returning a plausible number. Health warnings use documented thresholds, with each warning tied to its ratio value and threshold.

### Currently

**Available immediately for full-time work.** Looking for a backend, full-stack, or financial-systems developer role in Montréal or remote; also open to co-op and internship terms. Completing a Master of Applied Computing (expected May 2027). Permanent resident, no sponsorship required.

📫 caiyue2011@gmail.com
