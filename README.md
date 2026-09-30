## Yue Cai

Backend / full-stack developer with a finance background. Montréal, Canada.

**Master of Applied Computing @ Wilfrid Laurier University (GPA 11.4 / 12.0)**  
**Master of Science in Finance · Passed Level I of the CFA Program**

I build backend services in Python (FastAPI) and Java (Spring Boot), and the React and Next.js frontends that go with them. What I care about is the unglamorous part: data models that hold up, migrations that actually run, tests that catch things, and reviewable AI features with visible source citations.

### Stack

`Python` `FastAPI` `SQLAlchemy` `Alembic` `Java` `Spring Boot` `Spring Security` `Spring Data JPA` `Flyway`  
`PostgreSQL` `MySQL` `SQLite` `pgvector` `SQL` `TypeScript` `Next.js` `React` `Chart.js`  
`pytest` `JUnit` `Vitest` `Playwright` `Docker` `GitHub Actions` `Jenkins` `AWS (ECS Fargate, RDS, ECR, S3)` `Terraform`  
`OpenAI API` `Resilience4j` `Databricks` `PySpark` `Delta Lake`

### Projects

**[Fraud Detection System](https://github.com/YueCai335/fraud-detection-system)**

Spring Boot 3 REST service and a Flask/scikit-learn model service that score transactions and explain each flag with SHAP, migrated from a Java EE/SOAP course project ([migration write-up](https://github.com/YueCai335/fraud-detection-system/blob/main/docs/migration.md)). Large CSVs run as resumable asynchronous jobs on S3, with Resilience4j retries around the model call. Verified on AWS ECS Fargate, RDS and S3 with Terraform ([deployment record](https://github.com/YueCai335/fraud-detection-system/blob/main/docs/deployment.md)), tested on GitHub Actions and [Jenkins](https://github.com/YueCai335/fraud-detection-system/blob/main/docs/ci-jenkins.md), plus a separate [Databricks PySpark pipeline](https://github.com/YueCai335/fraud-detection-system/tree/main/databricks-etl) with reconciliation checks.

**[Garden Manager](https://github.com/YueCai335/garden-manager)** · [live demo](https://garden-manager-demo.vercel.app)

Full-stack Next.js, FastAPI and PostgreSQL app for garden records and next-season planning, with revision-checked auto-save and crop-rotation rules; the live demo covers Garden, Care and Season Planner. The local app adds cited pgvector RAG answers and a small tool-calling agent whose [paid evaluation](https://github.com/YueCai335/garden-manager/blob/main/docs/agent.md) is published with its failures. CI runs lint, type checks, backend tests on SQLite and PostgreSQL, and a Playwright end-to-end flow.

**[Financial Ratio Analyzer](https://github.com/YueCai335/financial-ratio-analyzer)**

Eight core financial ratios from annual-report figures, with multi-year trends and cross-company comparison (FastAPI + SQLite). The DuPont and leverage identities are asserted in the test suite, so a mistyped formula fails instead of returning a plausible number.

### Currently

**Available immediately for full-time work.** Looking for a backend, full-stack, or financial-systems developer role in Montréal or remote; also open to internships. Completing a Master of Applied Computing part-time, one course per term (expected May 2027). Permanent resident, no sponsorship required.

📫 caiyue2011@gmail.com
