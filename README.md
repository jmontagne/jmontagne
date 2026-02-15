# Hi there, I'm Jacques Montagne. 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect_with_the_Architect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/jacquesmontagne/)
[![AWS](https://img.shields.io/badge/AWS-7x_Certified-232F3E?style=for-the-badge&logo=amazon-aws)](https://www.credly.com/)
[![Java](https://img.shields.io/badge/Java-Legacy_Modernization-ED8B00?style=for-the-badge&logo=openjdk)](https://github.com/jmontagne)

**Senior Cloud Architect & Tech Lead** based in Normandy, France.
*Bridging the gap between 20-year-old Monoliths and Enterprise Generative AI.*

</div>

---

## 🏛️ The Mission: "Safe Modernization"

I help Banking and Insurance sectors migrate **Legacy Java Systems** to the Cloud.
My focus is on **Engineering Rigor**: Security, Compliance, and Observability in the age of AI.

---

## 📂 The Engineering Portfolio

### 🏆 1. [Serverless Java 21 SnapStart + Bedrock](https://github.com/jmontagne/poc_java_lambda_snapstart_bedrock)
> **Status:** `Production Ready` | **Type:** `Reference Architecture`

A high-performance serverless function with sub-500ms cold starts, full observability, and Infrastructure as Code.
* **Stack:** Java 21, Spring Boot 3.2, Spring Cloud Function, AWS Lambda SnapStart (CRaC), Amazon Bedrock (Claude), Terraform.
* **Observability:** AWS Lambda Powertools (structured logging, CloudWatch EMF metrics, X-Ray tracing).
* **Use Case:** Real-time transaction analysis, fraud detection, domain Q&A for regulated enterprises.

### 🧪 2. [The AWS GenAI Architect Lab](https://github.com/jmontagne/aws-genai-architect-lab)
> **Status:** `Active Development` | **Type:** `Learning Laboratory`

A collection of isolated POCs — **"One Concept, One POC"** — covering AWS GenAI Professional (AIP-C01) exam domains. Each POC includes Java source code, unit tests, and Terraform IaC.

**Completed:**
* **POC-01 — Bedrock Inference & Observability:** REST API with streaming, model comparison (Sonnet vs Haiku), TTFT metrics, API Gateway + Lambda + SnapStart deployment, Bedrock invocation logging to CloudWatch & S3.
* **POC-02 — RAG Pipeline & Knowledge Bases:** Full Retrieve & Generate pipeline with citations, hybrid/semantic search, metadata filtering, LLM-as-Judge evaluation (relevance + groundedness), OpenSearch Serverless vector store. *62 unit tests.*
* **POC-03 — Tool Use & Bedrock Agents:** Comparison of programmatic tool use (Converse API + manual ReAct loop) vs managed Bedrock Agents. Flight booking domain with DynamoDB, OpenAPI schema, Lambda Action Groups. *(In progress — Terraform partially complete.)*

**Planned:**
* **POC-04 — Security Guardrails & PII Redaction:** Bedrock Guardrails, PII filtering, GDPR compliance patterns.
* **POC-05 — Automated Evaluation:** LLM-as-Judge with Ragas, faithfulness & relevance metrics.
* **POC-06 — Multi-modal Vision:** Claude Vision for insurance claim photo processing.
* **POC-07 — Model Fine-tuning:** JSONL dataset preparation, Bedrock fine-tuning workflows.

---

## 🛠️ Technical Arsenal

| Domain | Stack |
| :--- | :--- |
| **Application Logic** | **Java 21 (LTS)**, Spring Boot 3.x, Spring Cloud Function, LangChain4j |
| **Ops & Evaluation** | **Python 3.12**, Boto3, Ragas |
| **Infrastructure** | **AWS** (Lambda, ECS, Bedrock, API Gateway, OpenSearch Serverless), **Terraform** |
| **Data & Retrieval** | PostgreSQL (pgvector), OpenSearch Serverless, DynamoDB |
| **Observability** | AWS Lambda Powertools, CloudWatch, X-Ray, structured JSON logging |

---

## ✍️ Insights
* **[Dev.to](https://dev.to/jmontagne)**: Technical deep-dives on Legacy Modernization & GenAI Architecture.
* **[LinkedIn](https://www.linkedin.com/in/jacquesmontagne/)**: Insights on Cloud Architecture & Safe Modernization.

<div align="center">
    <a href="https://www.linkedin.com/in/jacquesmontagne/">Contact me for B2B Architecture Consulting</a>
</div>
