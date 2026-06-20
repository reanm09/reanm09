# Hey 👋 I'm Adithya 

**AI Engineer • Full-Stack Developer • Problem Solver** ---

### 🚀 Flagship Projects

#### **Vortex-Orc | AI-Driven Project Orchestration Platform**
*Multi-Agent Workspace Generation via Stateful Graph Orchestration and AST Validation*
- **Stateful Multi-Agent Workflow**: Coordinated a stateful Directed Acyclic Graph (DAG) pipeline using **LangGraph** and **LangChain** to manage context across four specialized concurrent agents (**Research, Feasibility, Architecture, Review**) without context drift.
- **5-Pass AST Static Validation**: Engineered an Abstract Syntax Tree (**AST**) static analysis engine using a custom `SymbolAndUndefinedVisitor` to verify scoping chains, isolate unresolved global name errors, and check cross-file module contract compliance before filesystem serialization.
- **Autonomous Self-Correction**: Implemented a mathematical grading quality gate `Score = 10.0 - ({errors} x 1.5) - ({warnings} x 0.3)` that logs failure traces and automatically triggers up to 3 self-correction retry loops.
- **Human-in-the-Loop Interrupts**: Engineered bidirectional **WebSocket** channels to statefully suspend execution gates via LangGraph interrupt primitives, allowing developers to review blueprints via React Flow, audit live terminal logs, and inject real-time steering feedback.
- **Eager Sync & Previews**: Bound browser updates to a reactive **Zustand** store and cached **React Query** layers for eager keystroke synchronization, while the ASGI backend dynamically allocates ports to spawn isolated application live previews.
- **Stack**: FastAPI, LangGraph, Next.js 16 (React 19), ChromaDB, WebSockets, Tailwind CSS 4, React Flow.

#### **CrimeGrid | Unified Crime Intelligence System**
*Full-Stack Predictive Dashboard for Explainable Risk Modeling*
- **Meta-Dynamic Ensemble**: Engineered a hybrid model fusing **XGBoost** (spatial severity) and **LSTM** (temporal volume) forecasting across 20,000 national records.
- **Explainable AI (XAI)**: Integrated an interpretable logic layer to surface primary risk drivers, ensuring transparency for tactical decision-making.
- **Conversational Intelligence**: Built a **RAG-powered assistant** using **Gemma 3** and **ChromaDB** for natural language interrogation of vectorized datasets.
- **Stack**: FastAPI, Next.js 14, TensorFlow, XGBoost, Leaflet.js.

#### **IntelliDocs | Hybrid AI Document Platform**
- **Architecture**: Hybrid RAG merging **FAISS Vector Search** with live Web Search.
- **Engineering**: Built a non-blocking pipeline using **Celery & Redis** for async PDF processing.
- **UI/UX**: Custom PDF Viewer with bi-directional interactive citations and dynamic model switching (Gemini Flash/Pro).

#### **Defense RAG Systems @ DRDO**
*Research Internship*
- **Multimodal AI**: Fine-tuned **LLaVA** for technical multimodal tasks, improving accuracy in processing airworthiness and defense document intelligence.
- **Scalable R&D**: Authored deployment-ready documentation and optimized pipelines for high-security, defense-grade datasets.

---

### 🛠️ Tech Stack
- **AI/ML/Orchestration**: PyTorch, TensorFlow, XGBoost, Scikit-learn, LangGraph, LangChain, Ollama, HuggingFace.
- **Backend**: Python, FastAPI, Flask, PostgreSQL, Redis, Celery, SQLAlchemy, aiosqlite, Docker.
- **Frontend**: Next.js, React, React Flow, Monaco Editor, Zustand, React Query, Tailwind CSS 4, Recharts, Leaflet.js.
- **Databases**: SQL, ChromaDB, FAISS.

---

> Building things that make people’s lives easier — one project at a time.

---
