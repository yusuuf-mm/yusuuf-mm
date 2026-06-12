<div align="center">

# 👋 Yusuf Muhammad Musa
### AI Systems Engineer · Operations Research · Data Infrastructure

*Building systems where AI orchestrates deterministic optimization engines*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yusuufmm)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/yusuufmm)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@yusuufmm)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yusuf2000mm@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://yusuufmm.is-a.dev)

</div>

---

## 🧠 Who I Am

```python
class YusufMM:
    def __init__(self):
        self.role = "AI Systems Engineer"
        self.foundation = "Operations Research (B.Tech)"
        self.location = "Nigeria 🇳🇬"

    def approach(self):
        return {
            "ai_orchestrates": "LLMs handle language, solvers handle math",
            "clean_boundaries": "testable, auditable, debuggable systems",
            "fail_explicitly": "INFEASIBLE is a valid answer"
        }

    def sectors(self):
        return ["Energy ⚡", "Logistics 🚛", "Infrastructure 🏗️"]
```

I build systems at the intersection of AI, optimization, and data infrastructure. My foundation is Operations Research — finding the mathematically best decision under constraints. Everything else is how I deploy that thinking into production.

---

## 🎯 What I'm Interested In

Building systems that help people and organizations make better decisions under real-world constraints — particularly in **energy & electrification**, **logistics & supply chain**, **data infrastructure**, and **AI-powered decision support**.

My OR background shapes how I work: understand the constraints, model the system, build solutions that improve outcomes at scale.

---

## ⚡ Engineering Philosophy

> **AI should orchestrate, not replace.** An LLM cannot enforce a hard constraint — a solver enforces constraints as mathematical inequalities, and the output is provably optimal or provably infeasible. There is no maybe. I ask which parts need contextual reasoning and which need hard guarantees, then build the boundary between them.
>
> **Clean boundaries matter more than clever code.** The solver doesn't read policy documents. The LLM doesn't compute route distances. The pipeline doesn't run the optimizer. The dashboard doesn't write to production.
>
> **Fail explicitly, not silently.** INFEASIBLE is a valid answer — returned with a human-readable explanation, never masked by a silent retry.

| Project | AI Role | Solver Role |
|---|---|---|
| EcoGrid-Agent | Parse intent, summarize results | LP optimization of battery schedule |
| HERMES | Monitor disruptions, decide when to re-solve | OR-Tools CVRPTW route planning |
| NETI-HyOptima | *(planned)* ML surrogate for Monte Carlo | Pyomo MILP for energy sizing |
| Titanic Engine | Predict survival probability | PuLP MILP for lifeboat allocation |

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🔋 [EcoGrid-Agent](https://github.com/yusuuf-mm/ecogrid-agent)**
*Autonomous VPP orchestrator — LLM + LP solver*

Send a plain-English grid optimization request. The system retrieves policy from a vector DB, forecasts solar with XGBoost, and runs an OR-Tools LP solver for a provably optimal 24h battery schedule — every constraint traced to a policy doc, every decision audited.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![OR-Tools](https://img.shields.io/badge/OR--Tools-FF6F00?style=flat-square&logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
<td width="50%" valign="top">

**🚛 [HERMES](https://github.com/yusuuf-mm/hermes)**
*Event-driven logistics — multi-agent orchestration*

Pairs a CVRPTW solver with a five-agent LLM decision layer over a Lagos delivery network. Agents monitor disruptions, classify severity, score SLA risk, and decide when to re-invoke OR-Tools — skipping 70% of LLM calls on nominal ticks.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OR-Tools](https://img.shields.io/badge/OR--Tools-FF6F00?style=flat-square&logo=google&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🌍 [NETI-HyOptima](https://github.com/yusuuf-mm/NETI-HyOptima)**
*Energy transition optimization platform*

Computational policy environment converting Nigeria's Energy Transition Plan into investment decisions. A Pyomo MILP optimizer sizes solar, gas, and battery capacity against location-specific resources, costs, and policy constraints — wrapped in a Monte Carlo layer for uncertainty.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pyomo](https://img.shields.io/badge/Pyomo-FF6F00?style=flat-square&logo=python&logoColor=white)
![MILP](https://img.shields.io/badge/MILP-HiGHS-green?style=flat-square)

</td>
<td width="50%" valign="top">

**⏰ [HabitOS](https://github.com/yusuuf-mm/HabitOS)**
*AI-driven behavioral optimization platform*

Transforms life goals into mathematically optimized daily schedules. Users define objectives and habits with time/energy budgets; a PuLP CBC solver schedules each into 15-minute blocks in under 500ms, with real-time WebSocket updates.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🚢 [Titanic Optimization Engine](https://github.com/yusuuf-mm/Titanic-Survival-Prediction-Optimization-Engine)**
*ML + MILP decision intelligence*

Two-stage system: XGBoost predicts survival probability (85% accuracy, 0.82 F1), then PuLP MILP allocates lifeboat seats under capacity, demographic minimums (30% children, 50% women), and family-cohesion constraints. The ML model is a component, not the product.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logo=xgboost&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

</td>
<td width="50%" valign="top">

**⚡ [Real-Time EOP](https://github.com/yusuufdevops/realtime-energy-optimization-pipeline)**
*Streaming energy optimization pipeline*

IoT simulator streams sensor data through Kafka into PostgreSQL and S3, transformed with dbt, then run through a two-stage OR optimizer (fairness LP + transportation routing) — orchestrated by Airflow, visualized in Streamlit.

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Core**

<a href="https://www.python.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40"/></a>
<a href="https://www.typescriptlang.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40"/></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40"/></a>
<a href="https://www.postgresql.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" width="40" height="40"/></a>
<a href="https://www.gnu.org/software/bash/"><img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" width="40" height="40"/></a>

**Backend & AI**

<a href="https://fastapi.tiangolo.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="40" height="40"/></a>
<a href="https://flask.palletsprojects.com/"><img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" width="40" height="40"/></a>
<a href="https://nextjs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" width="40" height="40"/></a>
<a href="https://redis.io/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" width="40" height="40"/></a>
<a href="https://kafka.apache.org/"><img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" width="40" height="40"/></a>

**Optimization & ML**

<a href="https://developers.google.com/optimization"><img src="https://www.vectorlogo.zone/logos/google_optimizationtools/google_optimizationtools-icon.svg" width="40" height="40"/></a>
<a href="https://pytorch.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="40" height="40"/></a>
<a href="https://xgboost.readthedocs.io/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/xgboost/xgboost-original.svg" width="40" height="40"/></a>
<a href="https://scikit-learn.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40"/></a>
<a href="https://www.tensorflow.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="40" height="40"/></a>

**Cloud & Infrastructure**

<a href="https://www.docker.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="40" height="40"/></a>
<a href="https://kubernetes.io/"><img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" width="40" height="40"/></a>
<a href="https://aws.amazon.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="40" height="40"/></a>
<a href="https://azure.microsoft.com/"><img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" width="40" height="40"/></a>
<a href="https://www.nginx.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="40" height="40"/></a>
<a href="https://git-scm.com/"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="40" height="40"/></a>

**Frontend & Data Viz**

<a href="https://reactjs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40" height="40"/></a>
<a href="https://tailwindcss.com/"><img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="40" height="40"/></a>
<a href="https://streamlit.io/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/streamlit/streamlit-original.svg" width="40" height="40"/></a>
<a href="https://plotly.com/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/plotly/plotly-original.svg" width="40" height="40"/></a>
<a href="https://threejs.org/"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/threejs/threejs-original.svg" width="40" height="40"/></a>

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=yusuuf-mm&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yusuuf-mm&layout=compact&theme=tokyonight&hide_border=true" />

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=yusuuf-mm&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🌱 Currently

- **Project Endgame** — RAG knowledge system using NVIDIA NIM, Qdrant, LangGraph, and Supabase
- **LLM Zoomcamp** — RAG pipelines, agentic retrieval, hybrid search, evaluation
- **Open to** Senior AI Systems Engineer, Data Engineer, and ML Engineer roles — remote or relocation

---

## 📜 Certifications

| Certification | Provider | Status |
|---|---|---|
| Data Engineering Zoomcamp | DataTalks.Club | ✅ |
| ML Engineering Zoomcamp | DataTalks.Club | ✅ |
| AI Dev Tools Zoomcamp | DataTalks.Club | ✅ |
| LLM Zoomcamp | DataTalks.Club | 🔄 In progress |
| ALX Software Engineering | ALX Africa | ✅ |
| HNG Backend & DevOps | HNG | ✅ |
| Data Engineering (DeepTech) | DSN / 3MTT | ✅ |
| Cloud Engineering (AWS) | SchullTech | ✅ |
| AI & ML | 3MTT Nigeria | ✅ |

---

<div align="center">

### 💬 Let's Connect
*Open to interesting projects and technical discussions — especially in energy, logistics, and infrastructure*

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yusuuf-mm)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yusuufmm)
[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yusuf2000mm@gmail.com)

<img src="https://komarev.com/ghpvc/?username=yusuuf-mm&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile Views" />

*The solver never lies, but the prompts sometimes hallucinate* 🚀

</div>