# 🚀 AI-Powered Logistics Contract Negotiation Engine

An end-to-end intelligent contract generation system that combines:

-  Retrieval-Augmented Generation (RAG)
-  Multi-Agent Negotiation Engine
-  Dynamic Surcharge Modeling
-  Automated Master Service Agreement Generation
-  Vector Database (Milvus)

This system simulates real-world logistics contract negotiations between a **Carrier** and a **Shipper**, dynamically adjusts commercial terms using live risk signals (fuel, weather, congestion), and generates enterprise-grade contracts.

---

## 🧠 Core Features

### 1️⃣ Intelligent Clause Retrieval (RAG)
- Scrapes logistics websites & PDFs
- Cleans and splits documents into clauses
- Classifies clauses using LLaMA (via Ollama)
- Stores embeddings in Milvus
- Performs semantic search + LLM re-ranking
- Generates legally structured responses

---

### 2️⃣ Multi-Agent Negotiation Engine

Simulates negotiation between:

-  Carrier Agent (revenue-maximizing)
-  Shipper Agent (cost-minimizing)

Implements:
- Utility-based decision modeling
- Iterative counter-offers
- Convergence detection
- Weighted final agreement

Negotiates:
- Fuel surcharge
- Peak season surcharge
- Residential fee
- Dimensional weight factor
- Congestion fee
- Risk surcharge
- Carbon emission fee

---

### 3️⃣ Real-Time Risk Adjustments

Dynamic surcharge modeling based on:

-  Weather API
-  Fuel price index
-  Traffic congestion index

Automatically increases risk & fuel surcharges when:
- Heavy rain
- Floods
- Cyclones
- High congestion

Fallback logic ensures robustness if APIs fail.

---

### 4️⃣ Intelligent Contract Generation

Generates:

- Hybrid MSA + ARC (40–60 pages)
- Commercial term annexures
- SLA sections
- Penalty & liability clauses
- Force majeure provisions
- API & data compliance sections
- Negotiated surcharge tables

Outputs:
- Structured legal contract
- Negotiated commercial summary
- Clause traceability
- AI reasoning

---


## 📈 Real-World Applications

- Logistics Contract Automation
- Freight Pricing Simulation
- Risk-Based Surcharge Modeling
- AI Legal Tech
- Supply Chain Negotiation Modeling
- B2B Contract Intelligence Systems

---

## 📌 Future Improvements

- Web-based dashboard (Streamlit / React frontend)
- FastAPI backend deployment
- Real-time monitoring dashboard
- Multi-country tax logic
- Clause version tracking
- Reinforcement learning for negotiation optimization

