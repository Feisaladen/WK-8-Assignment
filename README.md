# 🤖 AI Agent Assignment

This repository contains my submission for the **AI Agent Assignment**, including short answer responses, a detailed case study analysis on implementing AI Agents in smart manufacturing, and a simulation of AI Agent decision-making.

---

## 📌 Overview

The assignment covers:

- Comparison of **LangChain** and **AutoGen** frameworks  
- Role of AI Agents in **supply chain management**  
- Concept of **Human-Agent Symbiosis**  
- Ethical considerations for AI in finance  
- Technical challenges of **memory and state management**  
- **Case study:** Smart Manufacturing Implementation at AutoParts Inc.  
- **Simulation:** AI Agent workflow modeled in n8n

---

## 📝 Section 1: Short Answer Questions

### 1. Compare and contrast LangChain and AutoGen
LangChain focuses on **orchestrating language models** for tasks like chatbots, multi-step reasoning, and structured workflows. It provides prompt management, memory handling, and integration with external data sources. AutoGen emphasizes **collaborative AI agents**, automating communication between agents to achieve complex goals. While LangChain is ideal for developer-centric tasks and structured workflows, AutoGen excels in multi-agent collaboration but may be computationally intensive. Both frameworks support modular AI development with distinct focuses.

### 2. AI Agents in Supply Chain Management
AI Agents enhance supply chains by **predicting demand, automating inventory, and monitoring machinery**. For example, DHL forecasts parcel volumes and reroutes shipments dynamically, while Walmart leverages AI for stock replenishment. These agents reduce errors, improve efficiency, and accelerate decision-making, creating more agile and resilient operations.

### 3. Human-Agent Symbiosis
Human-Agent Symbiosis describes **collaborative work between humans and AI**, where AI augments human capabilities instead of replacing them. Unlike traditional automation, humans maintain oversight and control. In manufacturing, AI can recommend optimal machine settings while humans approve actions. This enhances productivity, adaptability, and strategic focus.

### 4. Ethical Implications in Finance
Autonomous AI Agents in finance carry risks such as **bias, lack of transparency, and accountability issues**. Safeguards include explainable AI, human-in-the-loop approvals, continuous auditing, and regulatory compliance to prevent unethical or high-risk decisions.

### 5. Memory and State Management
Memory allows AI Agents to **retain context, learn from past interactions, and maintain continuity**. Challenges include efficient storage, consistency, and conflict resolution. Proper memory management is critical for reliability in real-world applications like industrial control or customer support.

---

## 🏭 Section 2: Case Study – Smart Manufacturing at AutoParts Inc.

### AI Agent Implementation Strategy
- **Quality Inspection Agent (CV):** Reduces defects from 15% → <5%  
- **Predictive Maintenance Agent (IoT + ML):** Predicts failures, reduces downtime 40–60%  
- **Workforce Optimization Agent:** Allocates tasks, reduces labor costs 10–15%  
- **Customization & Order Management Agent:** Automates custom production, reduces lead time 20–30%  

### Expected ROI & Timeline
- **Investment:** ~KES 106,300,000  
- **Annual Benefits:** ~KES 134,200,000  
- **Payback:** 10–12 months  
- **3-year projected savings:** KES 366M–427M  

**Implementation Timeline:**  
1. Assessment & Data Collection – 1–2 months  
2. Pilot Deployment – 2–3 months  
3. Scaling Up – 3–4 months  
4. Training & Change Management – Continuous  
5. Full Optimization – 10–12 months  

### Risks & Mitigation
- **Technical:** Model drift, integration challenges → retraining, IoT retrofitting  
- **Organizational:** Employee resistance → training, early involvement  
- **Ethical:** Job displacement, data privacy → human-in-the-loop, encrypted pipelines, explainable AI

---

## 🖥️ Simulation

A simulation of AI Agent decision-making was performed using **n8n**, modeling input conditions, agent logic, and output results. The simulation demonstrates predicted outcomes for:

- Negotiation agents  
- Defect reduction  
- Maintenance scheduling  
- Workforce optimization  

Simulation results are stored in `/simulation/simulation-output.json`.  
Example output:

```json
[
  {
    "case_id": "001",
    "agent_name": "AI Negotiation Agent",
    "problem": "Buyer wants discount, seller wants to keep margins high.",
    "constraints": {
      "buyer_budget_kes": 50000,
      "seller_min_kes": 65000
    },
    "agent_action": "Ran multi-step negotiation strategy",
    "outcome": "Settled at KES 57,500",
    "timestamp": "2025-12-07T20:00:00.000Z"
  }
]
