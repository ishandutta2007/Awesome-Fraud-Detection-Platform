# Awesome-Fraud-Detection-Platform

# Top Fraud Detection Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Payment Fraud, Account Abuse, Chargeback Prevention, Identity Risk & Real-Time Decisioning*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Fraud Detection**. These systems score and decide on transactions, accounts, and identities in real time to reduce payment fraud, chargebacks, and abuse while preserving good customer experience.

**Examples** include Sift, Forter, Riskified, SEON, Sardine, Feedzai, Kount, Fraud.net, Signifyd, and Ravelin (the category leaders).

**Open-source emphasis**: Enterprise fraud platforms with global identity networks and chargeback guarantees are commercial. Practical open options include rule + ML transaction-monitoring projects (e.g., Jube), graph-based fraud intelligence prototypes, and general ML pipelines. This section lists the strongest available open resources and is realistic about the commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Sift](https://sift.com/)**  
  Machine-learning fraud and abuse platform providing risk scores, workflows, and decision support for e-commerce, marketplaces, and digital businesses (merchant retains final decision and liability).

- **[Forter](https://www.forter.com/)**  
  Identity-network fraud decisioning platform that returns approve/decline decisions and can support liability models for large retailers and digital commerce.

- **[Riskified](https://www.riskified.com/)**  
  E-commerce fraud prevention platform offering chargeback guarantees on approved orders and AI-driven review for merchants seeking to transfer fraud-loss risk.

- **[SEON](https://seon.io/)**  
  Fraud prevention platform popular with fintech and iGaming, combining device, email, phone, and behavioral signals with transparent pricing tiers.

- **[Sardine](https://www.sardine.ai/)**  
  Risk and compliance platform combining fraud detection, behavioral biometrics, and AML-oriented signals for fintech and financial services.

- **[Feedzai](https://www.feedzai.com/)**  
  Enterprise AI platform for fraud and financial crime prevention used by banks and payment processors at large scale.

- **[Kount (Equifax)](https://kount.com/)**  
  Digital fraud prevention platform providing risk scoring and decisioning for payments and account activity.

- **[Fraud.net](https://www.fraud.net/)**  
  AI-powered fraud detection platform focused on financial services and complex fraud patterns.

- **[Signifyd](https://www.signifyd.com/)**  
  Commerce protection platform offering fraud guarantees and decisioning for online merchants.

- **[Ravelin](https://www.ravelin.com/)**  
  Machine-learning fraud detection platform specializing in payment fraud and account takeover prevention for digital businesses.

## Open-Source GitHub Projects
- **[Jube (AML & Fraud Transaction Monitoring)](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  
  Open-source (AGPLv3) platform for real-time transaction monitoring, hybrid rule + ML detection, and case management aimed at AML and fraud prevention.

- **[Rift and graph-based fraud intelligence projects](https://github.com/)**  
  Open graph + ML platforms for entity resolution, anomaly detection, and investigative workflows in fraud contexts.

- **[Real-time fraud ML microservices (XGBoost/ONNX examples)](https://github.com/)**  
  Community projects demonstrating real-time scoring pipelines with XGBoost, ONNX, and FastAPI for transaction fraud.

- **[Rule engines open libraries](https://github.com/)**  
  Open business-rule engines used to encode velocity, blacklist, and policy checks alongside ML scores.

- **[Feature-store and event-streaming open stacks](https://github.com/)**  
  Kafka, Flink, and feature-store patterns commonly used to feed real-time fraud models.

- **[Graph databases and network analysis open tools](https://github.com/)**  
  Neo4j, NetworkX, and related tools for detecting linked accounts, devices, and collusive rings.

- **[Anomaly detection open libraries](https://github.com/)**  
  Scikit-learn, PyOD, and similar libraries for unsupervised and semi-supervised fraud signals.

- **[Case management open workflows](https://github.com/)**  
  Lightweight open tools for queueing, investigating, and auditing suspected fraud cases.

- **[Synthetic fraud data and benchmark open datasets](https://github.com/)**  
  Public datasets and generators used to train and evaluate fraud models.

- **[Documentation and research open repositories](https://github.com/)**  
  Papers, notebooks, and playbooks for building transparent fraud detection pipelines.

### Additional Strong Open-Source Options
- Prototyping real-time monitoring with **Jube** or similar open AML/fraud platforms.
- Building internal scoring services with open ML + rule engines on your own event stream.
- Combining open graph analysis with commercial decisioning for hybrid architectures.
- Accepting that global identity networks, chargeback guarantees, consortium data, and battle-tested production SLAs still require commercial platforms (Sift, Forter, Riskified, Feedzai, SEON, Signifyd, etc.).
- Focusing open-source efforts on transparency, auditability, and data ownership for regulated environments.

**Frameworks for building custom systems**: Stream transactions and events → engineer features (device, velocity, graph) → score with open ML + rules → route high-risk to case management → continuously retrain. Suitable for organizations with strong data science and engineering capacity. Most merchants and banks rely on commercial fraud platforms for scale, liability options, and network effects.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Fraud systems make high-stakes decisions affecting customers and financial risk. Incorrect models or rules can cause losses or discrimination. Open-source tools require careful validation, monitoring, and compliance with applicable laws. This list is not legal, compliance, or risk-management advice.

---
**Made for risk, payments, and fintech teams fighting fraud.**
Let's keep detection accurate, explainable, and as open as practical.
