<!-- Header -->
<div align="center">

<img src="./banner.svg" alt="Pranav Sagar — Backend Engineer · Distributed Systems · Java & Spring Boot" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=680&lines=SDE+%40+Glance%2C+InMobi+Group+%7C+Bengaluru;Kafka+%C2%B7+gRPC+%C2%B7+Spring+Boot+%C2%B7+Aerospike;800K%2B+QPS+%E2%80%A2+100M%2B+Users+%E2%80%A2+%3C30ms+p95;M.Tech+AI%2FML+%40+BITS+Pilani+(WIL)" alt="Typing SVG" />

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://pranavsagar.pages.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranavsagar)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@prnv1009)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/prnvsgr)

</div>

---

## 🧑‍💻 About Me

```java
public class PranavSagar {

    String  company  = "Glance, InMobi Group — Bengaluru, India";
    String  role     = "SDE 1 · Backend Developer (Sept 2023 – Present)";
    String  learning = "M.Tech AI & ML @ BITS Pilani (Work Integrated)";

    String[] impact  = {
        "800K+ QPS · <30ms p95 latency · 100M+ users",
        "35–60% compute & API cost reductions",
        "Zero-downtime migrations via dual-write architecture",
        "Reusable observability framework across 5+ services",
        "90% reduction in deployment time via GKE automation",
    };

    String[] passions = {
        "Distributed Systems",
        "Event-Driven Architecture",
        "Performance Engineering",
        "Observability & Reliability",
        "MLOps & Production AI",
    };
}
```

---

## ⚙️ Tech Stack

<div align="center">

**Languages · Backend · Messaging**

[![Skills](https://skillicons.dev/icons?i=java,python,spring,kafka,flask&perline=8)](https://skillicons.dev)

&nbsp;![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
&nbsp;![Protobuf](https://img.shields.io/badge/Protobuf-336791?style=flat-square&logoColor=white)
&nbsp;![Kafka Streams](https://img.shields.io/badge/Kafka_Streams-231F20?style=flat-square&logo=apache-kafka&logoColor=white)

<br/>

**Databases · Caching**

[![Skills](https://skillicons.dev/icons?i=redis,postgres,mysql&perline=8)](https://skillicons.dev)

&nbsp;![Aerospike](https://img.shields.io/badge/Aerospike-C22032?style=flat-square&logoColor=white)
&nbsp;![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)

<br/>

**Data Processing**

![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
&nbsp;![PySpark](https://img.shields.io/badge/PySpark-3670A0?style=flat-square&logo=apache-spark&logoColor=white)
&nbsp;![ETL Pipelines](https://img.shields.io/badge/ETL_Pipelines-444?style=flat-square&logoColor=white)

<br/>

**Infrastructure · DevOps · Observability**

[![Skills](https://skillicons.dev/icons?i=kubernetes,docker,gcp,prometheus,grafana,git&perline=8)](https://skillicons.dev)

&nbsp;![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
&nbsp;![GKE](https://img.shields.io/badge/GKE-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
&nbsp;![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=github-actions&logoColor=white)
&nbsp;![Distributed Tracing](https://img.shields.io/badge/Distributed_Tracing-7B61FF?style=flat-square&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=PranavSagar&theme=github-dark-blue&hide_border=true" height="165"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=PranavSagar&theme=github-compact&hide_border=true&area=true&area_color=58a6ff&color=58a6ff&line=58a6ff&point=ffffff" width="96%"/>

</div>

---

## 🚀 Featured Projects

### 🎯 [Content Intelligence Pipeline](https://github.com/PranavSagar/content-intel-pipeline) — End-to-End MLOps

**[🌐 Live Demo](https://pranavsagar.github.io/classify/)** · **[🤖 API Docs](https://pranavsagar10-content-intel-classifier.hf.space/docs)** · **[🧪 MLflow](https://dagshub.com/PranavSagar/content-intel-pipeline.mlflow)** · **[📊 Grafana](https://pranavsagar.grafana.net/d/content-intel-pipeline)**

Real-time news classifier serving fine-tuned **DistilBERT** at **94.64% accuracy** with **p95 latency of 23 ms** on CPU. Production MLOps stack — streaming pipeline with at-least-once delivery, distributed caching with deduplication, drift monitoring, live dashboards, and automated CI/CD — all running on free-tier managed services with **$0 recurring cost**.

- 🧠 **Model**: DistilBERT fine-tuned on AG News (120K articles) · 94.64% test acc · 94.65% F1 macro · MLflow tracked
- ⚡ **Serving**: FastAPI on HuggingFace Spaces · async lifespan · full 4-class probability breakdown · p50 19 ms, p95 23 ms
- 🔄 **Streaming**: Redpanda Kafka → Redis cache (SHA-256 dedup) → SQLite · at-least-once delivery · 230 ms pipeline lag
- 📈 **Observability**: Prometheus client → Grafana Alloy (pull + remote_write) → Grafana Cloud · 6-panel live dashboard
- 🔍 **Drift**: weekly Evidently statistical tests (Jensen-Shannon + Wasserstein) → HTML report + MLflow on DagsHub
- 🤖 **CI/CD**: ruff lint + import smoke on every push · weekly drift cron · path-filtered auto-deploy to HF Spaces
- 📚 **Docs**: 12 ADRs · 15-problem build log · HLD + LLD with Mermaid sequence diagrams · layman newsroom analogy

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_HuggingFace-FFD21E?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

---

<table>
<tr>
<td width="50%" valign="top">

### [📊 Amazon Review Sentiment Analysis](https://github.com/PranavSagar/ReviewSentiments)
NLP pipeline achieving **87% accuracy** using Naive Bayes, SVM, and Random Forest classifiers. Full preprocessing with tokenization, stemming, and TF-IDF. Deployed as a real-time Flask web app.

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-76B900?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000?style=flat-square&logo=flask&logoColor=white)

</td>
<td width="50%" valign="top">

### [🗣️ Project Vaani — SIH 2022](https://github.com/PranavSagar/Project-Vaani---SIH)
Scholarship disbursement platform eliminating 150+ km of rural travel per applicant. Built for **Smart India Hackathon 2022** — **National Runner-Up** out of 1M+ participants.

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000?style=flat-square&logo=flask&logoColor=white)
![ML](https://img.shields.io/badge/Machine_Learning-E25A1C?style=flat-square)

</td>
</tr>
</table>

---

## 🏆 Achievements

<div align="center">

| | |
|:---|:---|
| 🏆 **Avengers Award** — Glance (InMobi) | Top engineering recognition for high-impact system design |
| 🥈 **Silver Medalist** — B.Tech CS, RTU | CGPA 9.10 / 10.00 |
| 🥈 **Smart India Hackathon 2022** | National Runner-Up (1M+ participants) |
| 📜 **Microsoft Certified** | Azure AI & Data Fundamentals |
| 💻 **LeetCode** | Rating 1577 · Top 25% globally |
| ✍️ **Published on Medium** | _Monte Carlo Simulation_ — most-read post |

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=PranavSagar&theme=algolia&no-frame=true&no-bg=true&margin-w=6&row=1&column=6" alt="trophies"/>

</div>

---

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=110&section=footer" alt="footer"/>
