# Hi, I'm Ahmed Elbadawy 👋

**AI Product Owner · ML, LLM and platform products in regulated industries** · Madrid, Spain

I own LLM, RAG and production ML products: I decide which AI use cases get built, set the evaluation criteria, guardrails and release thresholds that take a model from use case to production, and keep it defensible under audit. Six years in AI products, inside a 20-year technology delivery career across financial services, pharma and life sciences, digital health and energy.

My role on the products below is product ownership: vision, roadmap, backlog, acceptance criteria and release decisions. Engineering and data science teams built them. This GitHub is where I do hands-on ML work in Python.

---

## 🧭 Products I've owned

### ⚡ Siemens Energy · AI Product Owner and AI Solution Architect · 2026 – present

I set the AI product vision across Global Data & AI and Grid Technology, and choose which use cases to build by weighing operational value, data availability and safety risk.

- **Grid Operator RAG Assistant.** Generative AI assistant that answers grid operators' and field engineers' questions from operating procedures, outage reports and asset manuals, citing the source document for every answer. The team built retrieval on LangChain and LangGraph with vector search, traced in LangSmith. I made LLM-as-a-judge evaluation the release gate (faithfulness, relevance and citation accuracy against engineer-reviewed answers) and specified the guardrails: input and output filtering, refusal outside the approved document scope, and no autonomous action on grid control systems.
- **Grid Orchestration Forecasting.** ML models for severe-weather forecasting, preemptive risk detection and power restoration. I own the roadmap, release criteria and the accuracy threshold each model must clear, with a human sign-off at every operational decision point. Models go to production on Docker and Kubernetes with CI/CD and drift monitoring.
- **Grid AI Lab and Noedra.** ML inference pipelines feeding the Noedra platform, serving grid models at low latency across hybrid cloud and edge. I write the product requirements for ETL, feature stores, model serving and inference optimisation, running on NVIDIA AI compute.
- **Genesis Mission.** Reinforcement-learning agents for grid-topology control. I define the data contracts and model specifications, and kept the agents in recommend mode, with a human approving every action on the live grid.
- **Hidden Grid Analytics.** Power-flow optimisation and dynamic line-rating analytics that raise usable transmission capacity from existing assets. I own the analytics roadmap and release criteria.

### 🏥 Roche Diagnostics · Technical Product Owner · 2025 – 2026

- **Navify Cloud Platform: IAM and DevOps consolidation.** Lead Product Owner for consolidating the Navify Cloud Platform and the Diabetes Care Platform onto one identity backbone. Owned two squads: IAM (4 backend engineers, 1 QA) and DevOps (6 engineers).
  - Led the Okta-to-Keycloak migration across 10+ regulated healthcare applications with zero downtime.
  - Defined a consolidated RBAC model: multi-tenant segmentation, token lifecycle, OAuth2/OIDC flows, webhook identity events, SDK/API definitions for product teams, and GDPR-compliant audit logging.
  - Introduced release governance with the DevOps squad: Sandbox → QA → Production promotion gates, a pen-test remediation backlog and an 80/20 run/improve capacity model.
  - Drove the Datadog-to-Grafana log migration, AWS cost dashboards, and Istio/Kubernetes upgrade governance across the US, EU and India.

### 🏦 Deutsche Bank · AI Product Owner and Product Manager · 2023 – 2025

Owned two AI products end to end, leading a cross-functional team of 10 (3 data scientists, 2 risk and compliance analysts, 3 engineers, DevOps, Scrum Master, QA).

- **Loan Intelligence Platform.** Turned spreadsheet-based corporate credit assessment into an AI decision system: ML credit scoring, LLM analysis of annual reports and legal filings, and SHAP/LIME explainability, with every model output recorded for regulatory inspection.
  - Cut corporate loan approval time from over 30 days to under 48 hours and automated 70% of manual credit-risk reviews.
  - Improved fraud detection accuracy by 85% against the pre-AI baseline (anomaly detection plus synthetic minority examples, as fraud labels were sparse).
  - Raised underwriter adoption of AI recommendations by 30% and analyst productivity by 25% by making every score explainable at the point of decision.
  - Lifted first-pass UAT from about 60% to over 90%; held a 99.9% uptime SLA with risk profiles rendering in under 2 seconds.
- **Risk Analytics Platform.** Owned the roadmap for real-time portfolio monitoring and stress testing (ECB, Basel III, FRTB). Worked with quants to turn PD, LGD and VaR into interactive client dashboards. Passed the ECB audit with zero findings.

### 💊 Almac Group · Senior Programme Manager and Product Owner · 2022 – 2023

- **Salesforce client platform.** Consolidated four divisional legacy systems into Salesforce as the single client record, integrated with SAP ERP, LabWare LIMS, Veeva Vault and a Heroku client portal through MuleSoft.
  - Owned the MuleSoft integration design across four APIs (99.94% uptime after go-live).
  - Migrated 47,000+ records over one weekend at 97.3% completeness with zero data loss.
  - Raised adoption from 38% to 91% in ten weeks through a fortnightly UX feedback loop.
  - 12 months after go-live: lead response time down 60%, case resolution time down 43%, forecast variance from ±35% to ±14%, client CSAT from 3.6 to 4.4.

### 🚀 Earlier products

- **FinTech and innovation platforms, Qatar Science and Technology Park (2021 – 2022).** Onboarded 50+ FinTech startups onto the regional platform; discovery-led prioritisation lifted adoption by 25% and retention by 18%. Built SQL KPI dashboards that drove roadmap prioritisation.
- **E-commerce and TravelTech platform, Dubai Science Park (2020 – 2021).** Owned the roadmap for a travel platform with 1,000+ airline and 100,000+ hotel integrations: transaction success up 20%, checkout abandonment down 15%, monthly active users up 22%.
- **2001 – 2019:** Scrum Master at GE Aerospace; IT Project Manager at GE HealthCare; Project Manager at UNICEF and UNHCR.

---

## 💻 Hands-on projects

- **[machine-learning-portfolio](https://github.com/ahmedelbadawy2020/machine-learning-portfolio)**: hands-on ML in Python, working through a 30-day ML challenge. Day 1: Titanic data analysis with NumPy, pandas and Matplotlib, feature engineering, and a rule-based baseline.
- **[credit-card-fraud-detection](https://github.com/ahmedelbadawy2020/credit-card-fraud-detection)**: fraud detection on a highly imbalanced dataset (284,807 transactions, 0.172% fraud), comparing Logistic Regression and Random Forest.

---

## 🛠 Tech stack

**Languages:** Python · Go · TypeScript · SQL

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**LLM and agent frameworks:** LangChain · LangGraph · LangSmith · LlamaIndex · OpenAI Agents SDK · Claude Agent SDK

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-000000?style=flat)
![OpenAI](https://img.shields.io/badge/OpenAI%20Agents%20SDK-412991?style=flat&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Agent%20SDK-D97757?style=flat&logo=claude&logoColor=white)

**AI/ML methods:** RAG pipelines · prompt engineering · LLM fine-tuning and transfer learning · LLM-as-a-judge evaluation · guardrails · explainable AI (SHAP, LIME) · reinforcement learning · model serving and inference optimisation · AI agents

**ML frameworks and libraries:** PyTorch · TensorFlow · Hugging Face · scikit-learn · pandas · NumPy · Matplotlib · Jupyter

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Data and vector stores:** PostgreSQL · pgvector · Pinecone · Weaviate · Chroma · Redis

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat)
![Weaviate](https://img.shields.io/badge/Weaviate-00C29A?style=flat)
![Chroma](https://img.shields.io/badge/Chroma-FF6446?style=flat)

**Cloud, infrastructure and MLOps:** AWS · Google Cloud · Azure · Docker · Kubernetes · CI/CD · MLOps · distributed training · GPU optimisation

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

**Identity and platform:** Okta · Keycloak · OAuth2 · OIDC · SAML · RBAC · REST APIs and integration

![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white)
![Okta](https://img.shields.io/badge/Okta-007DC1?style=flat&logo=okta&logoColor=white)

**Delivery:** SAFe (PI Planning, ART) · Scrum · Kanban · WSJF · MoSCoW · Jira · Confluence · Azure DevOps

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat&logo=confluence&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)

**Regulatory:** GDPR · HIPAA · GxP · Basel III · MiFID II · ECB · FRTB · PCI-DSS · KYC/AML

<details>
<summary><b>Platforms my product teams built on</b> (I set requirements and release criteria; the teams implemented)</summary>

- **Siemens Energy:** NVIDIA AI compute · feature stores · hybrid cloud/edge serving
- **Roche:** AWS EKS · Terraform · Istio · ArgoCD · GitLab · Grafana · Datadog · JWT · mTLS
- **Deutsche Bank:** Flask · Angular · D3.js · Azure · Kubernetes · Terraform
- **Almac:** Salesforce Sales Cloud and Service Cloud · MuleSoft Anypoint · Heroku (Node.js/React) · Tableau CRM · SAP ERP · LabWare LIMS · Veeva Vault · DocuSign · Conga Composer

</details>

---

## 🎓 Certifications and education

- AWS Certified Solutions Architect – Professional · Google Cloud Professional Cloud Architect
- Certified SAFe 6 Product Owner/Product Manager · Release Train Engineer · Practice Consultant · Scrum Master
- ICAgile ICP-ENT Enterprise Agile Coaching · ICP-CAT Coaching Agile Transformations
- Machine Learning Specialization (Andrew Ng), DeepLearning.AI and Stanford Online
- Post Graduate Program in AI and Machine Learning, Purdue University and IBM (Purdue Graduate Certificate in Foundations of AI, Outstanding Distinction)
- Applied Generative AI Specialization, Purdue University and IBM
- IBM: Deep Learning with TensorFlow · Python for Data Science
- Diploma in Cloud Computing Systems (AWS and GCP), Cloud Formación, Madrid
- BSc Computer Science

Badges are verifiable on [Credly](https://www.credly.com/users/ahmed-mamdouh-abdelhamed-elbadawy).

---

## 📊 GitHub stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ahmedelbadawy2020&show_icons=true&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ahmedelbadawy2020&layout=compact&hide_border=true" alt="Most used languages" />
</p>
<p>
  <img height="165" src="https://streak-stats.demolab.com?user=ahmedelbadawy2020&hide_border=true" alt="GitHub streak" />
</p>

---

## 🎯 A bit more

- 🌱 **Currently learning:** hands-on machine learning in Python, one project at a time in [machine-learning-portfolio](https://github.com/ahmedelbadawy2020/machine-learning-portfolio)
- 💬 **Ask me about:** LLM evaluation and release gates, RAG products, explainable AI in credit decisions, identity platform migrations, SAFe product ownership
- 🌍 **Languages:** Arabic (native) · English (C1) · Spanish (B2)

---

## 📫 Contact

- 🔗 LinkedIn: [linkedin.com/in/ahmed-mamdouh-elbadawy](https://www.linkedin.com/in/ahmed-mamdouh-elbadawy)
- 📧 Email: ahmadmamdooh2014@gmail.com
- 🏅 Credentials: [credly.com/users/ahmed-mamdouh-abdelhamed-elbadawy](https://www.credly.com/users/ahmed-mamdouh-abdelhamed-elbadawy)
