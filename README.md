# Justin Güse | Technical Outlier & AI Architect 🚀

**Data Engineer | DevOps Specialist | Agentic AI & Quant Developer**

I architect mission-critical systems for global enterprises and contribute to the core infrastructure of the modern cloud. My work bridges the gap between **BaFin-regulated financial environments** and cutting-edge **autonomous agentic workflows**.


### 🏛️ Core Ecosystem Contributions
I contribute to the foundational tools that power the internet's infrastructure:

* **[Hetzner Cloud CSI Driver](https://github.com/hetznercloud/csi-driver):** Contributor to the primary K8s storage interface for Hetzner Cloud.
* **[Google Research / TimesFM](https://github.com/google-research/timesfm):** Contributor to Google’s SOTA Time Series Foundation Model for zero-shot forecasting.
* **[Bitnami Helm Charts](https://github.com/bitnami/charts):** Contributor to the industry-standard library for Kubernetes application deployment.
* **[Pandas-Dev / Pandas](https://github.com/pandas-dev/pandas):** Contributor to the world's most critical data manipulation library.
* **[Microsoft / Winget-pkgs](https://github.com/microsoft/winget-pkgs):** Active contributor to the Windows Package Manager repository.

### 🔬 Independent Research — Brain-Inspired Efficient LLMs

**[S²-MoE — Evolving Sparse Spiking Mixture-of-Experts](https://github.com/JustinGuese/llm-lean-neuro-algo)** · [📄 Paper (DOI: 10.5281/zenodo.20846758)](https://doi.org/10.5281/zenodo.20846758)

A from-scratch, brain-inspired language model that gets *cheaper* as it scales — Top-1 spiking-expert routing, a matrix-state Gated Linear Attention backbone, and an offline "sleep phase" that merges, prunes, and grows its own network topology.

* ⚡ **~1/21 → ~1/43 the active FFN compute** of a size-matched dense model, and **up to 7.1× less serving energy** (H100) — the efficiency lead *widens* as you add experts.
* 🎯 **Quality-competitive with its distilled dense teacher** (−5.15% perplexity on FineWeb-Edu, −4.4% on TinyStories at Nₑ=32, 3 seeds; BLiMP-neutral).
* 🔬 **47 logged, fully reproducible experiments** — including *six documented negative results* that bound the design space. Honest scoping over hype.
* 🧰 Built solo in `PyTorch` (cu128/Blackwell): custom autograd grouped-GEMM kernel, surrogate-gradient LIF neurons, SET/RigL structural plasticity, peer self-distillation.

> Published preprint (CC BY 4.0) · independent research, no lab affiliation.

### 🛡️ Professional Work History & "War Stories"

#### **DataFortress.cloud (Self-employed) | Oct 2020 – Present**
* **Atruvia (Banking IT):** Engineered high-availability **OpenShift** environments for Germany’s largest banking network, ensuring strict **BaFin compliance**.
    * *Key Achievement:* Mitigated a critical HashiCorp Vault cross-datacenter failure within a strict 2-hour window, preventing a mandatory federal reporting event with zero data loss.
* **Automotive (HPE/VW/Porsche/BMW):** Led petabyte-scale data replication across 60+ countries and designed hybrid cloud migrations.
* **Health & Bio (Buchinger Wilhelmi / NavicareNow):** CTO and Architect roles focusing on transferring sensitive health data to the cloud and building ML pipelines for fasting outcome prediction.
* **Quant (Jim Harris Corp):** Developed real-time stock prediction systems using Kafka, RabbitMQ, and Tensorflow.

#### **Porsche Holding | Oct 2016 – 2019**
* Specialized in **Data Warehousing** and high-profile innovation projects, including a **VR Motion Seat** for Formula E touring all over Europe.


### 🚀 The Product Foundry (SaaS, AI Agencies & Products)
I build, launch, and scale production-ready systems that solve complex algorithmic, hardware, and operational problems:

* **[AgentBureau](https://agentbureau.de/)**: An elite B2B AI agency platform focusing on deploying production-ready multi-agent workflows, custom LLM fine-tuning, and operational automation.
* **[DocumentChat](https://document-chat.com/)**: Enterprise-grade AI RAG assistant for high-accuracy semantic search across massive document sets.
* **[WiFiSenseBox](https://wifisensebox.com/)**: An innovative IoT hardware-software solution engineered for signal detection, environmental sensing, and smart infrastructure metrics.
* **[AI Investing Bots](https://ai-investing-bots.com/)**: Quant and Algorithmic trading frameworks running automated forecasting models and deep quantitative analysis.
* **[PsychDiary](https://psychdiaryapp.com/)**: AI-powered companion mobile app for automated cognitive tracking and emotional analytics.
* **[NavicareNow](https://navicarenow.de/)**: AI-driven medical navigation platform for patient documentation and guidance, backed by the **Now2 Next Accelerator**.
* **[Tiledom](http://tiledom.xyz/)**: A focused project within the Crypto, Web3, and economic simulation ecosystem.


### 🗄️ Featured Project Index

#### 🤖 Agentic AI & LLM Systems
* **[OpenShrimp](https://github.com/JustinGuese/openshrimp):** Persistent, task-driven LangGraph research agent with a modular plugin system and anti-bot evasion heuristics.
* **[AgenticSeek](https://github.com/JustinGuese/agenticSeek):** Fully local autonomous agent that thinks, browses, and codes (Open-source Manus AI alternative).
* **[KuberneteslocalGPT](https://github.com/JustinGuese/KuberneteslocalGPT):** Private, on-premise RAG implementation tailored for isolated Kubernetes infrastructure.

#### 📈 Quant & Algorithmic Trading
* **[Python Tradingbot Framework](https://github.com/JustinGuese/python_tradingbot_framework):** K8s-native algorithmic framework featuring **150+ technical indicators** and distributed hyperparameter optimization.
* **[Kubernetes Autonomous Trading Agent](https://github.com/JustinGuese/kubernetes-docker-autonomous-trading-agent):** LLM-powered Solana agent running market scraping and transaction execution via native K8s CronJobs.
* **[AI Hedge Fund](https://github.com/JustinGuese/ai-hedge-fund):** Multi-agent collaborative team for algorithmic market reasoning and portfolio risk management.

#### 🏗️ Infrastructure, DevOps & IoT
* **[Python-OpenObserve](https://github.com/JustinGuese/python-openobserve):** High-performance connector for sub-second OpenObserve telemetry and logging pipelines.
* **[Rspamd-Iscan](https://github.com/JustinGuese/rspamd-iscan):** Advanced IMAP mailbox spam-filtering chart leveraging Bayesian learning models.
* **[Picture Rotation Fixer](https://github.com/JustinGuese/picture-rotation-fixer):** Content-aware image processing pipeline using face detection algorithms to auto-orient scanned photos.


### 🧰 The Stack
* **Languages:** `Python` (Tensorflow, Keras, FastAPI), `Go` (K8s CSI Drivers), `Dart` (Flutter Mobile/Web), `Rust` (Solana contracts), `Java`, `TypeScript`, `HCL` (Terraform).
* **Orchestration & DevOps:** `Kubernetes`, `OpenShift`, `Helm`, `ArgoCD`, `Tekton Pipelines`.
* **Data Layers:** `Trino / Starburst`, `Kafka`, `RabbitMQ`, `PostgreSQL`, `MinIO`, `OpenObserve`.
* **Cloud Infrastructure:** `AWS Certified Solutions Architect`, `GCP`, `Azure`.


### 📫 Connect with Me
* **Primary Platform:** [DataFortress.cloud](https://www.datafortress.cloud)
* **Inquiries:** info@datafortress.cloud
* https://www.linkedin.com/in/justin-guese/
