<div id="header" align="center">
  <img src="https://media.giphy.com/media/YYW0hHizzIOrlhimPG/giphy.gif" width="120" alt="waving-hand"/>
  <h1>Hi there, I'm <a href="https://alperonder.dev">Alper</a> 👋</h1>
  <h3>Software Engineer — Cloud Infrastructure • DevOps • AI/ML</h3>
  <p>
    <a href="https://alperonder.dev"><img alt="Website" src="https://img.shields.io/badge/website-alperonder.dev-0A0A0A?style=flat&logo=google-chrome"></a>
    <a href="https://www.linkedin.com/in/alper-onder-dev"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
    <a href="mailto:contact@alperonder.dev"><img alt="Email" src="https://img.shields.io/badge/Email-contact%40alperonder.dev-D14836?style=flat&logo=gmail&logoColor=white"></a>
  </p>
</div>

---

## 👨‍💻 About Me

I’m a Software Engineer at **SITA** focused on **cloud infrastructure** and **AI/ML solutions**. I design scalable systems, automate cloud workflows, and build intelligent applications that solve real-world problems. Previously, I’ve delivered projects spanning containerized ML serving, full-stack development, and end-to-end CI/CD.

- 🔭 Currently working on: cloud automation, reliable ML serving, and IaC at scale  
- 🌱 Learning more about: distributed systems, MLOps, and Rust for backend services  
- 🤝 Open to collaborate on: cloud-native platforms, AI tooling, and developer productivity

---

## 🚀 Featured Projects

**mlops_observe** is a comprehensive MLOps observability platform for ingesting ML events, monitoring drift and fairness, triggering alerts, and debugging models—with a small, reliable footprint.

**Why it’s interesting:**
- Thin API, rich pipeline. FastAPI endpoints for auth, projects/orgs, ingest, and query; Prometheus `/metrics`; gRPC preview for high‑throughput paths.
- ClickHouse‑backed events. Robust insert/query with retries and filterable queries (project, kind, since, model_id). In‑memory fake store for local/dev and tests.
- SDKs & CLI. Python and Node clients plus a Typer-based CLI. Structured logging with JSONL/Parquet for offline analysis.
- Monitoring & alerting. Drift, fairness, and explainability utilities; alert settings with channels (Slack, Email, Teams, PagerDuty, Jira), thresholds, and dedup keys.
- Multi‑team & SSO. Orgs/projects with RBAC; JWT auth and OIDC (Google/Okta) for lightweight SSO; per‑request structured logs for traceability.
- Ops & reliability. Dockerized services and Makefile workflows; docs with MkDocs Material; optional Prometheus metrics; resilient ClickHouse operations.
- Developer experience. Ruff/Black/Mypy/Pytest CI hygiene, clear tests and notebooks, and a dashboard MVP for quick visualization.

> 🔗 [Repository](https://github.com/artificialvirus/mlops_observe) 

**RefineX** is a system for **verification-guided LLM reasoning**. It couples a generator with **typed verifiers** (arithmetic, CAS-backed symbolic algebra, lightweight formal logic, general heuristics) and an **iterative controller** that performs detect → verify → aggregate/gate → revise loops.

**Why it’s interesting:**
- **Thin API, rich pipeline.** FastAPI endpoints (`/solve`, `/evaluate`) + WebSocket streaming for per-iteration telemetry.
- **Typed verification.** Arithmetic (AST-sandboxed), **SymPy** for algebraic equivalence, logic patterns/fallacies, general uncertainty cues.
- **Iterative controller.** Targeted revision prompts and early-exit heuristics (stable signatures, circuit breaker, rollback).
- **Offline evaluator harness.** Budget-matched baselines, stratified reports, ablations, and reproducibility artifacts.
- **LLM back-ends.** Supports OpenAI & Anthropic APIs and **local inference via Ollama**. For experiments: **publicly available lightweight local models (e.g., Llama 3.x Instruct)** for reproducibility.
- **Ops & reliability.** Dockerized, k8s-ready, with caching, timeouts, deterministic fallbacks, and structured logs for observability.

> 🔗 [Repository](https://github.com/artificialvirus/RefineX)

- **Fraud Detection in Financial Transactions**  
  Anomaly detection and feature-importance modeling to flag suspicious activity.  
  🔗 [View project list](https://github.com/artificialvirus?tab=repositories)

- **Antibiotic Discovery with Generative AI**  
  Exploration of candidate compounds using generative models for drug discovery.  
  🔗 [View project list](https://github.com/artificialvirus?tab=repositories) Not public yet


---

## 🧰 Tech Stack

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=flat&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-4.x-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-11%2B-007396?style=flat&logo=java&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-1.x-000000?style=flat&logo=rust&logoColor=white)

### Front-End
![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=000)
![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Responsive-1572B6?style=flat&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-Utility-38B2AC?style=flat&logo=tailwindcss&logoColor=white)

### Back-End & APIs
![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-4.x-000000?style=flat&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-REST-092E20?style=flat&logo=django&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-14%2B-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-6-47A248?style=flat&logo=mongodb&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Design%20%26%20Tuning-336791?style=flat)

### Cloud & DevOps
![Azure](https://img.shields.io/badge/Azure-Cloud-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Builder-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=flat&logo=github-actions&logoColor=white)
![Azure Pipelines](https://img.shields.io/badge/Azure%20Pipelines-CI%2FCD-2560E0?style=flat&logo=azure-pipelines&logoColor=white)

### MLOps & Data
![TensorFlow](https://img.shields.io/badge/TensorFlow-2-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-High%20Level-D00000?style=flat&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-ETL-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Compute-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting-11557C?style=flat&logo=plotly&logoColor=white)

### Version Control & Deployment
![Git](https://img.shields.io/badge/Git-Flow-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repos-181717?style=flat&logo=github&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-Apps-430098?style=flat&logo=heroku&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-Hosting-00C7B7?style=flat&logo=netlify&logoColor=white)

---

## 📈 By the Numbers


<p>
  <img src="https://github-readme-stats.vercel.app/api?username=artificialvirus&show_icons=true&hide_title=true&include_all_commits=true" height="140" alt="GitHub stats"/>
  <img src="https://streak-stats.demolab.com?user=artificialvirus" height="140" alt="GitHub streak"/>
</p>

---

## 🤝 Let’s Connect

- 🌐 Website: **<a href="https://alperonder.dev">alperonder.dev</a>**  
- 💼 LinkedIn: **<a href="https://www.linkedin.com/in/alper-onder-dev">alper-onder-dev</a>**  
- ✉️ Email: **contact@alperonder.dev**

> I love chatting about cloud infrastructure, AI/ML, and developer tooling. If you’ve got an idea, I’d love to hear it!

---

### 🌱 Currently learning
Advanced cloud architectures, distributed training, and performance tuning for Rust backends.

### ⚡ Fun fact
I enjoy hackathons and solving algorithmic challenges—nothing like a good time crunch to spark ideas!
