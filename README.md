# Hi there, I'm Jacques Montagne 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/jacquesmontagne/)

</div>


### Senior Solutions Architect | Java & Agentic AI Specialist
*Transforming Legacy Monoliths into Intelligent, Spec-Driven Cloud Architectures.*

---

## 🚀 Engineering Portfolio: The 2025 Modernization Roadmap

Fresh from **AWS re:Invent 2025**, I am executing a strategic roadmap to migrate highly regulated enterprise systems (Banking/Insurance) into a **Serverless, Agentic, and Event-Driven platform**.

This portfolio moves beyond simple "Chatbots" to demonstrate **Agentic Workflows** (Agents that *act*), **Spec-Driven Development**, and **Hardened Security**.

---

### ✅ Phase 1: Production-Ready Serverless Java (Completed)
**The Challenge:** "Java is too slow and opaque for Serverless."
**The Solution:** A sub-500ms cold start architecture with enterprise-grade observability.
* **Core:** Java 21 + Spring Boot 3 + **AWS Lambda SnapStart** (CRaC).
* **Observability:** Integrated **AWS Lambda Powertools** for structured logging, distributed tracing (X-Ray), and Idempotency (crucial for payments).
* **GenAI Integration:** Connected to Claude 3.5 Sonnet via Bedrock using Spring Cloud Function.
* **Repo:** [🔗 Serverless Java 21 SnapStart + Bedrock API](https://github.com/jmontagne/poc_java_lambda_snapstart_bedrock)

---

### 🚧 Phase 2: Data & The "Model Context Protocol" (Next Up)
**The Challenge:** "Legacy SQL databases cannot scale with AI Agents."
**The Solution:** Exposing Legacy Data to AI via standardized protocols without ad-hoc connectors.
* **The Architecture:**
    * **AWS RDS Proxy** + **Aurora Limitless** (Handling massive concurrency from Agent swarms).
    * **MCP Server (Model Context Protocol):** A Java/Spring adapter exposing SQL data to Agents in a standardized way.
    * **Hibernate/JPA:** Optimized for short-lived Lambda contexts.

---

### 🧪 Phase 3: Agentic Workflows & Spec-Driven Development
**The Challenge:** "AI code generation is chaotic ('Vibe Coding')."
**The Solution:** Moving to **Spec-Driven Development (SDD)** where Agents implement verified requirements.
* **Methodology:** Utilizing **Kiro** to generate enterprise-grade code from structured specs (Requirements → Design → Code).
* **Agent Framework:** Building an **"Insurance Agent"** using **AWS Strands SDK** and **LangChain4j**.
* **Capabilities:**
    * **Action Groups:** Agents executing real API calls (e.g., "Cancel Policy").
    * **Strands SOPs:** Embedding Standard Operating Procedures as system prompts.

---

### 🛡️ Phase 4: AI Governance & "The Vision Claim Agent"
**The Challenge:** "We need to automate claims processing without hallucinations."
**The Solution:** A Multi-Modal Agent that analyzes images and enforces strict Guardrails.
* **Use Case:** "Vision Claim Agent" – Analyzing car accident photos to estimate damage costs.
* **Tech Stack:**
    * **Claude 3.5 Sonnet (Vision)** for image analysis.
    * **Guardrails for Amazon Bedrock** (PII redaction, Topic blocking).
    * **Automated Eval:** CI/CD pipeline using **LLM-as-a-Judge** to verify agent decisions before deployment.

---

### 🛠️ Phase 5: Automated Modernization Pipeline
**The Challenge:** "Refactoring Monoliths takes years."
**The Solution:** AI-Assisted Upgrades.
* **Tooling:** Implementing **Amazon Q Code Transformation** in the CI/CD pipeline to automate Java 8 → 21 upgrades and dependency analysis.

---

### ⚡ Phase 6: The Performance Benchmark (Rust vs. Java)
**The Goal:** "Extreme Low Latency - Is the rewrite worth it?"
**The Solution:** A side-by-side comparison of the same business logic.
* **Tech Stack:** **Cargo Lambda** (Rust) vs. **SnapStart** (Java).
* **KPIs:** Cold Start duration, Memory footprint cost, Developer Velocity trade-offs.

---

### 📫 Contact & Credentials
* **Role Focus:** Senior Cloud Architect / Tech Lead.
* **Core Stack:** Java, AWS, Terraform, Spring Boot, LangChain4j, Strands.
* **LinkedIn:** [linkedin.com/in/jacquesmontagne](https://www.linkedin.com/in/jacquesmontagne/)
