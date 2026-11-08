<div align="center">

[![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,30:0d1117,70:161b22,100:0d1117&height=220&section=header&text=Sreenu%20Gopireddy&fontSize=62&fontAlignY=38&animation=fadeIn&fontColor=58a6ff&desc=AI%20%2F%20ML%20Engineer%20%E2%80%A2%20Cloud%20Infrastructure%20%E2%80%A2%20LLM%20Systems&descSize=18&descColor=8b949e&descAlignY=60)](https://github.com/sreenugopireddy)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3500&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=650&lines=Building+production-grade+LLM+infrastructure;Azure+%E2%80%A2+FastAPI+%E2%80%A2+Cosmos+DB+%E2%80%A2+GitHub+Actions;Healthcare+RAG+%E2%80%A2+Eval+Harnesses+%E2%80%A2+A%2FB+Routing;B.Tech+Data+Science+%40+Santhiram+Engineering+College)](https://github.com/sreenugopireddy)

</div>

---

```python
class Sreenu:
    role        = "AI / ML Engineer & Cloud Infrastructure Builder"
    education   = "B.Tech Data Science · Santhiram Engineering College (2023–2027)"
    location    = "Nandyal, Andhra Pradesh, India 🇮🇳"

    built = {
        "LLM Platform"   : "4-microservice Azure infra · Cosmos DB · GitHub Actions CI/CD",
        "Healthcare RAG" : "Domain-grounded QA pipeline · retrieval-augmented generation",
        "Eval Harness"   : "Semver prompt versioning · eval gates · deterministic A/B routing",
        "Anomaly Detect" : "Smart-grid energy demand forecasting + anomaly detection",
    }

    stack = {
        "AI/ML"  : ["LLMs", "RAG Pipelines", "LLM Evaluation", "Prompt Engineering"],
        "Cloud"  : ["Azure Container Apps", "Cosmos DB Serverless", "GCP Cloud Run"],
        "Dev"    : ["FastAPI", "Python", "Docker", "Bicep IaC"],
        "Data"   : ["Power BI", "SQL", "Pandas", "Jupyter"],
    }

    currently   = "Building FAANG-grade LLM systems · pursuing AI research opportunities"
    philosophy  = "Ship it, evaluate it, iterate relentlessly."
```

---

## ⚡ Flagship Project — Production LLM Platform on Azure

> A **FAANG-grade LLM infrastructure platform** built from scratch — four FastAPI microservices deployed to Azure Container Apps.

| Service | Responsibility |
|---|---|
| 🔀 **API Gateway** | Deterministic A/B routing · PTU-to-PAYG fallback |
| 🧠 **Inference Service** | Azure OpenAI (`gpt-4.1-mini`) · per-request cost chargeback |
| 📋 **Prompt Registry** | Semver prompt versioning · eval gates before promotion |
| 📊 **Eval Harness** | Automated evaluation · quality gates · metrics tracking |

**Live Gateway →** `llm-platform-gateway.greentree-67d78498.eastus.azurecontainerapps.io`
**Stack →** FastAPI · Azure Container Apps · Cosmos DB Serverless · Bicep IaC · GitHub Actions

### 🧭 How it works

A request hits the **API Gateway**, which applies deterministic A/B routing policy to select a prompt/model variant. The **Inference Service** calls Azure OpenAI, logs token usage and cost to **Cosmos DB**, and returns the response. Every prompt version lives in the **Prompt Registry** and must clear the **Eval Harness**'s quality gate before it's eligible for promotion to production traffic — so a bad prompt change never reaches real users.

### 🗺️ Architecture

```mermaid
flowchart LR
    U[Client Request] --> GW[🔀 API Gateway<br/>A/B Routing · Fallback]
    GW --> INF[🧠 Inference Service<br/>Azure OpenAI · Cost Tracking]
    INF --> DB[(Cosmos DB<br/>Serverless)]
    PR[📋 Prompt Registry<br/>Semver · Gates] --> GW
    EH[📊 Eval Harness<br/>Quality Gates] -->|promote| PR
    INF --> EH
    DB --> EH

    style GW fill:#0d1117,stroke:#58a6ff,color:#58a6ff
    style INF fill:#0d1117,stroke:#58a6ff,color:#58a6ff
    style PR fill:#0d1117,stroke:#58a6ff,color:#58a6ff
    style EH fill:#0d1117,stroke:#58a6ff,color:#58a6ff
    style DB fill:#0d1117,stroke:#8b949e,color:#8b949e
```
## 🛠️ Tech Stack

<div align="center">

![Python](https://skillicons.dev/icons?i=python,fastapi,azure,docker,git,github&theme=dark&perline=6)

![Tools](https://skillicons.dev/icons?i=postgres,vscode,linux,gcp,tensorflow,pytorch&theme=dark&perline=6)

![Badges](https://img.shields.io/badge/Azure_Container_Apps-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Badges](https://img.shields.io/badge/Cosmos_DB_Serverless-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Badges](https://img.shields.io/badge/RAG_Pipelines-FF6B35?style=flat-square&logoColor=white)
![Badges](https://img.shields.io/badge/LLM_Evaluation-58A6FF?style=flat-square&logoColor=white)
![Badges](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Badges](https://img.shields.io/badge/Bicep_IaC-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)

</div>

---

## 🎯 Core Focus Areas

| **`LLM Systems`** | **`Cloud Infrastructure`** | **`ML Engineering`** | **`Data & Analytics`** |
|---|---|---|---|
| Prompt versioning · Eval harnesses · A/B routing · Cost tracking | Azure · GCP · CI/CD · Containerization · Serverless | RAG Pipelines · Anomaly Detection · NLP | Power BI · SQL · Data modeling |

---

## 🔭 Now

- Building out the Eval Harness's automated regression suite for the LLM platform
- Reading up on retrieval quality metrics for the Healthcare RAG pipeline
- Applying to AI research / ML engineering internships for 2027

*(Update this section every few weeks — a live "now" signals momentum better than a static bio.)*

---

## 📜 Certifications

[![AWS ML](https://img.shields.io/badge/AWS_ML_Engineer_Associate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://github.com/sreenugopireddy)
[![RAG Expert](https://img.shields.io/badge/RAG_Systems_Expert-Ready_Tensor_2026-58A6FF?style=for-the-badge)](https://github.com/sreenugopireddy)
[![Oracle OCI](https://img.shields.io/badge/Oracle_OCI_AI_Foundations_2025-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://github.com/sreenugopireddy)
[![UC Davis SQL](https://img.shields.io/badge/SQL_for_Data_Science-UC_Davis_Coursera-0056D2?style=for-the-badge&logo=coursera&logoColor=white)](https://github.com/sreenugopireddy)
[![Power BI](https://img.shields.io/badge/Power_BI-Microsoft-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://github.com/sreenugopireddy)
[![Zscaler](https://img.shields.io/badge/Zscaler_Zero_Trust_Associate-ZTCA-003087?style=for-the-badge)](https://github.com/sreenugopireddy)

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=sreenugopireddy&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&count_private=true&include_all_commits=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sreenugopireddy&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=8"/>

[![GitHub Streak](https://streak-stats.demolab.com?user=sreenugopireddy&theme=dark&hide_border=true&background=0d1117&stroke=1a1a3e&fire=58a6ff&currStreakNum=58a6ff&sideNums=8b949e&currStreakLabel=8b949e&sideLabels=777777&dates=555577)](https://git.io/streak-stats)

</div>

---

## 🤝 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/3D_Portfolio-0d1117?style=for-the-badge&logo=vercel&logoColor=58a6ff&labelColor=0d1117)](https://portfolio-pearl-nu-85.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sreenu-gopireddy/)
[![GitHub](https://img.shields.io/badge/GitHub-sreenugopireddy-0d1117?style=for-the-badge&logo=github&logoColor=58a6ff&labelColor=0d1117)](https://github.com/sreenugopireddy)

```
AI/ML Engineer · Cloud Infrastructure Builder · Open to Research & Internship Opportunities
If you're working at the frontier of LLM systems — let's build something.
```

</div>

[![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0a0a0f&height=120&section=footer&animation=twinkling)](https://github.com/sreenugopireddy)
