# Hey 👋 I'm Adithya

**Backend & AI Engineer • Agentic Systems • Full-Stack Development**


I build AI systems that go beyond model inference — combining intelligent orchestration, reliable backend infrastructure, multimodal reasoning, and evidence-driven architectures.

Previously worked on **LLM/VLM-based defense intelligence systems at DRDO**. Currently building **clinical AI and healthcare infrastructure at PetOLife**.

🏆 **Two-Time Hackathon Runner-Up**
- **2nd Place — Fusion X National Hackathon** | AI/ML & Data Science Track | 150+ teams
- **2nd Place — ISACA Hackathon** | AI-Powered Fraud Detection | 80+ teams

---

## 🚀 Flagship Projects

### 🔍 [PRISM — Autonomous Digital Artifact Truth Engine](https://github.com/reanm09/PRISM)

*Agentic Security Investigation • Semantic Fracture Detection • Evidence-Based Verification*

An autonomous artifact intelligence platform designed to investigate what digital files actually contain, how different software interprets them, and whether those differences introduce security risks.

- **Semantic Fracture Detection:** Developed a deterministic investigation engine that executes independent parsers against identical file bytes, compares structural interpretations, and identifies security-relevant discrepancies.
- **Multi-Agent Investigation:** Built an orchestration framework coordinating Evidence, Hypothesis, Experiment, and Validation agents through bounded investigation and evidence-refinement loops.
- **AI-Powered Triage:** Integrated a fine-tuned Laya model for risk assessment and adaptive routing between `PASS`, `DEEP_SCAN`, and `PRISM_LAB` workflows.
- **Verified Experimentation:** Implemented typed experiment schemas, allowlisted execution plans, replay protection, and deterministic validation to ensure AI-generated hypotheses are independently verified.
- **Secure Containment:** Developed real-time artifact monitoring and encrypted quarantine using AES-256-GCM with Windows DPAPI-protected keys.
- **Explainable Investigation:** Built a full-stack interface exposing parser comparisons, investigation traces, experiment histories, and verified findings.

**Stack:** Python, FastAPI, Next.js, TypeScript, Laya, Ollama, BGE-M3, RAG, PyMuPDF, AES-256-GCM, SSE.

### 🛰️ SatQuery — Multimodal Satellite Intelligence Platform

*Geospatial AI • Vision-Language Models • Multi-Model Orchestration*

A multimodal Earth Observation intelligence platform that transforms natural-language questions and satellite imagery into traceable spatial evidence.

- **Multimodal Intelligence:** Architected analysis workflows supporting RGB, Sentinel-2 multispectral, Sentinel-1 SAR, and bi-temporal satellite imagery.
- **Specialist Model Orchestration:** Integrated GeoChat-7B, Grounding DINO, ChangeFormer V6, Chg2Cap, and optical–SAR representation encoders into a unified backend.
- **Change Detection:** Developed workflows combining learned change masks, semantic change descriptions, and radiometric fallback analysis.
- **Evidence-Grounded Reasoning:** Preserved model provenance, bounding boxes, segmentation masks, change regions, and execution traces to prevent unsupported spatial claims.
- **GPU Worker Architecture:** Designed isolated inference workers for computationally intensive vision-language models with configurable local and remote execution.
- **Interactive Analysis Studio:** Built a React-based geospatial workspace for satellite imagery, model outputs, spatial overlays, and project-scoped AI conversations.

**Stack:** Python, FastAPI, PyTorch, TorchGeo, CUDA, Rasterio, React, TypeScript, Supabase, RAG.

*Repository currently private.*

### ⚙️ [Vortex-Orc — Stateful Multi-Agent Orchestration Engine](https://github.com/reanm09/Vortex-Orchestration)

*Agentic Software Engineering • Stateful Execution • Human-in-the-Loop Workflows*

A multi-agent software engineering platform that transforms natural-language project requirements into structured research, architecture, implementation, and deployable workspaces.

- **Stateful Agent Orchestration:** Built cyclical LangGraph workflows coordinating Research, Feasibility, Architecture, and Review agents with shared state and iterative refinement.
- **Human-in-the-Loop Execution:** Implemented persistent interruption checkpoints allowing developers to inspect, approve, modify, and resume agent workflows.
- **Real-Time Infrastructure:** Engineered asynchronous WebSocket event streams for live token generation, agent execution status, and terminal output.
- **Structured Code Generation:** Developed schema-constrained LLM output pipelines with workspace patching, validation, and exportable project generation.
- **Interactive Developer Workspace:** Built a Next.js interface integrating React Flow, Monaco Editor, live execution feedback, and project visualization.

**Stack:** Python, FastAPI, LangGraph, LangChain, SQLAlchemy Async, WebSockets, Next.js 16, React 19, Zustand, Monaco Editor, React Flow.

### 🛡️ SENTINEL — Neuro-Symbolic Payment Fraud Intelligence

*2nd Place — ISACA Hackathon | 80+ Teams*

An AI-powered fraud intelligence platform designed to detect UPI payment scams, phishing URLs, malicious QR codes, and fraudulent transaction claims.

- **Hybrid Fraud Detection:** Combined fine-tuned DistilBERT, Qwen LLM reasoning, and deterministic verification for fraud assessment.
- **Phishing Intelligence:** Fine-tuned a DistilBERT classifier on a 210,000-record phishing and benign URL dataset, achieving **99.34% test accuracy and 0.9303 phishing F1-score**.
- **Multimodal Analysis:** Integrated QR-code parsing, OCR-based evidence extraction, and contextual reasoning to investigate suspicious payment requests.
- **Evidence-Based Decisions:** Designed fraud analysis workflows that distinguish verified technical signals from model-generated interpretations.

**Stack:** Python, FastAPI, PyTorch, Hugging Face Transformers, DistilBERT, Qwen, Scikit-learn.

### 🏙️ [CrimeGrid — National Crime Intelligence System](https://github.com/reanm09/Crime-Grid)

*2nd Place — Fusion X National Hackathon | 150+ Teams*

A predictive crime intelligence platform combining spatial risk modeling, temporal forecasting, explainable AI, and conversational analytics.

- **Hybrid Predictive Modeling:** Built an XGBoost + LSTM ensemble for spatial crime severity analysis and temporal crime-volume forecasting across 20,000+ records.
- **Dynamic Ensemble Architecture:** Developed a Meta-Dynamic Weighting System that adjusts model contributions based on regional data volatility.
- **Explainable AI:** Integrated interpretable risk analysis to surface important prediction drivers and support evidence-based decision-making.
- **Conversational Analytics:** Built a RAG-powered assistant using Gemma 3 and ChromaDB for natural-language interrogation of crime datasets.
- **Geospatial Dashboard:** Developed interactive maps and regional intelligence visualizations using Leaflet.js and Recharts.

**Stack:** Python, FastAPI, XGBoost, LSTM, TensorFlow, Gemma 3, ChromaDB, Next.js 14, Leaflet.js.

### 📄 [IntelliDocs — Hybrid RAG Document Intelligence](https://github.com/reanm09/Intellidocs-Retrieval-Augmented-Generation)

*Document AI • Hybrid Retrieval • Distributed Processing*

A full-stack document intelligence platform for evidence-grounded question answering across uploaded documents and external knowledge sources.

- **Hybrid Retrieval:** Combined dense vector retrieval through ChromaDB with live web retrieval for context-aware document analysis.
- **Distributed Ingestion:** Built asynchronous PDF processing pipelines using Celery workers and Redis message brokering.
- **Adaptive Model Routing:** Integrated Gemini Flash and Gemini Pro with query-complexity-based routing.
- **Interactive Citations:** Developed a PDF viewer with bidirectional citation navigation linking AI responses directly to document evidence.
- **Backend Infrastructure:** Implemented PostgreSQL-backed persistence and secure session management.

**Stack:** Python, FastAPI, Next.js, ChromaDB, Celery, Redis, PostgreSQL, Gemini.


---

## 🛠️ Technical Stack

| Domain | Technologies |
|---|---|
| **Languages** | Python, Java, JavaScript, TypeScript, SQL |
| **AI / Machine Learning** | PyTorch, TensorFlow, Scikit-learn, XGBoost, Hugging Face Transformers |
| **Agentic AI** | LangGraph, LangChain, Multi-Agent Orchestration, Human-in-the-Loop Systems |
| **LLMs & Multimodal AI** | LLaVA, GeoChat, Gemini, Gemma 3, Qwen, Ollama, Laya |
| **Retrieval & Search** | RAG, BM25, FAISS, ChromaDB, BGE-M3, SentenceTransformers |
| **Backend Engineering** | FastAPI, Flask, asyncio, WebSockets, Celery, Redis, SQLAlchemy |
| **Frontend Engineering** | Next.js, React, TypeScript, Tailwind CSS, Zustand, React Query, React Flow |
| **Databases & Infrastructure** | PostgreSQL, Supabase, SQLite, Docker, JWT, RLS |
| **Specialized Systems** | CUDA, TorchGeo, Rasterio, Geospatial AI, Document Intelligence, Security Automation |

---

## 🏆 Achievements

🥈 **Fusion X National Hackathon — 2nd Place (April 2026)**  
AI/ML & Data Science Track | 150+ Participating Teams  
Built **CrimeGrid**, combining predictive modeling, explainable AI, and retrieval-augmented intelligence.

🥈 **ISACA Hackathon — 2nd Place (September 2026)**  
80+ Participating Teams  
Built **SENTINEL**, a neuro-symbolic fraud detection platform integrating transformer-based classification, LLM reasoning, and multimodal payment security analysis.

---

## 📫 Connect

- **Email:** adithya.kri06@gmail.com

---

*Building AI systems that don't just generate answers — they reason, verify, and turn intelligence into reliable software.*
