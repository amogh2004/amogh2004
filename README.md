<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Amogh Ranganathaiah, Founding Forward Deployed Engineer at MoolAI: multi-agent systems, applied GenAI, platform architecture" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/amoghranganathaiah"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-amoghranganathaiah-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:amoghranganathaiah@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-amoghranganathaiah%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/San%20Francisco%2C%20CA-555?style=flat-square&logo=googlemaps&logoColor=white">
</p>

## About me

I'm the **Founding Forward Deployed Engineer (engineer #3) at MoolAI**. I build the platform that takes enterprise AI agents from pilot to production with deterministic guardrails, and I deliver those agents for paying customers in EPM, healthcare and network security.

Before MoolAI I was a **Data Engineer at LTIMindtree**, running PySpark, Kafka and Databricks pipelines at the terabyte scale. I hold an **MS in Analytics from San Francisco State University**.

## Impact at a glance

| Before | After | How |
| :--- | :--- | :--- |
| 4-day EPM financial review | **30 minutes** | A hierarchical multi-agent system: a supervisor that plans and delegates to retrieval, anomaly-flagging and narrative sub-agents |
| 7-day logistics reconciliation | **1 day** | A multi-agent pipeline that replaced manual coordination across disconnected supply-chain systems |
| Manual security alert triage | **50% lower latency, 99.9% uptime** | A ReAct-style LangGraph + MCP system deployed in an air-gapped, on-prem environment (I led a team of 3) |
| Per-seat licenses for EPM, ERP and accounting tools | **Usage-based access from Slack and Teams** | Conversational agents in production at 3 enterprise customers |

## What I've built at MoolAI

- **Judge Council** *(provisional patent filed)*: a multi-stage LLM-as-a-judge evaluation pipeline. Judges score independently, then it calibrates across judges, corrects for verbosity bias and combines the results into a consensus. It runs in the Experiment Engine and against sampled production outputs.
- **ContextForge** *(provisional patent filed)*: a declarative RAG/CAG context-engineering engine. It compiles context in five phases, and when validation fails it feeds the schema and runtime errors back into the prompt so the agent can try again.
- **Agent deployment plane**: turns configured agents into signed artifacts and reproducible Terraform deployments. It works in customer-tenant Azure and MoolAI-managed Azure, gives one-click pilot-to-production promotion and keeps staging and prod infrastructure identical.

## Experience

**MoolAI** · Founding Forward Deployed Engineer · *San Francisco, CA · May 2025 – present*
Platform architecture and end-to-end enterprise delivery, from technical scoping after the sale through production go-live. I'm the technical point of contact for customer leadership.

**LTIMindtree** · Data Engineer · *Bengaluru, India · Aug 2021 – Apr 2023*
- Processed 2TB+ of IoT data daily with PySpark streaming, **cutting end-to-end latency by 40%**.
- Built Delta Lakehouse pipelines in Databricks that unified ERP and cloud data, **reducing ETL from 7 days to 2**.
- Built a PySpark + Kafka ingestion framework that auto-registered **10,000+ records per cycle** in Alation.
- Set up Azure DevOps CI/CD, **raising deployment frequency by 40%** with zero-downtime releases.

## Research project: FogBrain

**Decentralized edge LLM deployment for private GenAI** · *Graduate research, SFSU (advisor: Prof. Sameer Verma)*
Private LLM inference on a Raspberry Pi cluster using MicroK8s, Ollama and Distributed Llama. On-device RAG with no cloud dependency achieved **under 150 ms responses**, **35% lower latency** than the baseline and **25% lower power use**.

## Toolkit

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Agents & GenAI**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-000000?style=flat-square&logo=anthropic&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8A2BE2?style=flat-square)
![Semantic Kernel](https://img.shields.io/badge/Semantic%20Kernel-5C2D91?style=flat-square)
![OpenAI SDK](https://img.shields.io/badge/OpenAI%20SDK-412991?style=flat-square&logo=openai&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)

**Cloud & infrastructure**
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Backend & data**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-003366?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Enterprise integrations:** Slack API, Microsoft Teams API, Workday Adaptive Planning, Pigment, SAP, Salesforce, QuickBooks

## Education & certifications

- 🎓 **MS, Analytics**, San Francisco State University (2023 – 2025)
- 🎓 **BE, Computer Science**, Visvesvaraya Technological University (2017 – 2021)
- 📜 Google Professional Data Engineer · AWS Solutions Architect – Associate · Microsoft Technology Associate (Python)

---

<p align="center"><sub>Always happy to talk about agent architectures, LLM evaluation or getting GenAI into production. Reach out on <a href="https://www.linkedin.com/in/amoghranganathaiah">LinkedIn</a>.</sub></p>
