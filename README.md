# Nathan Vu

ML Engineer and Data Scientist based in Melbourne, Australia. Final-year Computer Science student (Data Science & AI) at Swinburne University of Technology, graduating November 2026.

I build applied AI systems — production inference pipelines, agentic workflows, computer vision, and data engineering tooling. I care about systems that actually run, not just notebooks that demonstrate a point.

Previously ML Engineer Intern at [Silverpond](https://silverpond.com.au), working on LLM-guided annotation workflows and computer vision pipelines for industrial drone imagery.

---

## What I build

- **ML inference services** — FastAPI + Docker + PostgreSQL, trained models served behind versioned REST endpoints
- **Agentic AI systems** — LangGraph and OpenAI Agents SDK, multi-agent pipelines with tool use, RAG, and SQL sub-agents
- **Computer vision pipelines** — YOLOv8 detection/segmentation, ResNet classifiers, automated annotation workflows with SAM
- **Data engineering** — ETL pipelines, time-series preprocessing, feature engineering on real-world sensor and traffic datasets
- **Full-stack ML products** — Next.js dashboards wired to ML backends, end-to-end from data to user interface

---

## Featured Projects

### [Predictive Maintenance Digital Twin](https://github.com/NathanVuSwinburne/predictive-maintenance-digital-twin-simulator)
No-code predictive maintenance platform for industrial machinery. Engineers query machine health in natural language, run what-if simulations, and receive AI-generated maintenance recommendations — no SQL or code required.

Stack: FastAPI · PostgreSQL · OpenAI Agents SDK · LangGraph · FAISS RAG · XGBoost · LSTM · Next.js · Docker Compose

Achieved 92% F1 on failure classification. Supervisor agent orchestrates a SQL sub-agent, ML classifier, and simulation engine with full trace logging.

---

### [Traffic Congestion Prediction & Route Guidance](https://github.com/NathanVuSwinburne/Google-Maps-Inspired-Traffic-volume-based-Routing-Guidance)
Deep learning forecasting on real-world SCATS traffic data from Melbourne's Boroondara area, integrated with A*, UCS, and greedy-best-first routing. Deployed on AWS EC2 with an interactive map interface.

Stack: LSTM · GRU · CNN-BiGRU · TensorFlow · Next.js · Streamlit · AWS EC2

R² = 0.962 across forecasting models.

---

### [Structural Defect Detection — Telecommunications Towers](https://github.com/NathanVuSwinburne/Structural-Defect-Detection-AI-for-Structural-Engineering)
YOLOv8 detection and segmentation pipeline trained on 572 high-resolution drone images for automated tower inspection. Live Streamlit demo available.

Stack: YOLOv8 · Python · Roboflow · Streamlit

Segmentation: Precision 0.966 · Recall 0.947 · mAP50 0.989

---

### [LLM Multi-Agent Cybersecurity System](https://github.com/NathanVuSwinburne/agentic-ai-cybersecurity)
LangGraph multi-agent pipeline with hybrid ChromaDB + BM25 retrieval to map security logs to MITRE ATT&CK techniques. Evaluated on 86 CTI Bench and Mordor logs.

Stack: LangGraph · ChromaDB · BM25 · Streamlit · Python

61–68% effectiveness across evaluation sets.

---

## Tech Stack

**Languages** — Python, TypeScript, SQL, JavaScript

**ML / AI** — PyTorch, TensorFlow, scikit-learn, XGBoost, YOLOv8, LSTM, GRU, CNN-BiGRU, ResNet

**Agentic AI** — LangGraph, OpenAI Agents SDK, FAISS, ChromaDB, BM25, RAG, multi-agent systems

**MLOps / Infra** — FastAPI, Docker, Docker Compose, AWS EC2, AWS Bedrock, PostgreSQL, SQLAlchemy

**Data** — pandas, NumPy, Power BI, Tableau, Power Query, DAX

**Evaluation** — F1, precision, recall, mAP, R², RMSE, ROC-AUC, macro F1

---

## Currently focused on

- MLOps patterns: model serving, containerisation, inference APIs
- Agentic AI systems with structured tool use and observability
- Computer vision for industrial inspection workflows
- AWS cloud infrastructure for ML workloads

---

## Links

- LinkedIn: [linkedin.com/in/nathanvu-ds](https://www.linkedin.com/in/nathanvu-ds)
- Email: nathanvutexting@gmail.com
