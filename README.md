## Hi there 👋, I'm Xinzhe Yuan
**AI Engineer** building autonomous LLM agents and production-grade AI systems.

## 🧠 What I Do
- Build LLM-powered autonomous agents (browser automation, end-to-end task execution)
- Design RAG pipelines, context management, and semantic search systems
- Optimize LLM workloads for cost, latency, and retrieval relevance
- Ship and operate production AI services on AWS

## 🚀 Featured Projects

### 🔹 Extends — Autonomous Web Agent · [extends.one](https://extends.one)
LLM-powered Chrome extension that drives real browsers via **Chrome DevTools Protocol** to complete real-world web tasks.
- **~98% accuracy** on the WebVoyager benchmark across 15 sites — outperforming **browser-use (89%)** and **OpenAI Operator (87%)**
- Robust on highly dynamic platforms (Booking.com, Wolfram Alpha)
- Built **from-scratch LLM orchestration**: recursive summarization, semantic filtering, PDF parsing — reduces per-request token usage while improving relevance
- Integrated **AWS AgentCore Memory** for cross-session personalization
- GitHub Actions CI/CD + CloudWatch centralized error reporting for production observability

**Tech:** TypeScript · React · Next.js · Flask · CDP · OpenAI / Gemini SDK · AWS  
🔗 Eval repo: [Virtu-llc/web_agent_eval](https://github.com/Virtu-llc/web_agent_eval)

### 🔹 Currents — Intelligent Social Search Engine · [currents.one](https://currents.one)
A search engine that surfaces how online communities actually talk about products, brands, and topics — turning scattered social discussion into structured insight.
- Refactored NLP keyword-extraction logic → **cut third-party LLM API calls by 66%**
- Migrated vector storage **Milvus → AWS S3 Vector DB** → saved **$400/month** infra cost with no RAG retrieval regression
- Extended the platform with a **distributed RESTful B2B API** (FastAPI + EC2 / SQS / Lambda / S3, orchestrated via Boto3) to expose LLM-driven semantic search to partners through async task pipelines
- GitHub Actions CI/CD + CloudWatch centralized error reporting for production observability

**Tech:** RAG · Embeddings · FastAPI · MySQL · AWS (EC2, SQS, Lambda, Boto3, S3 Vector, DynamoDB)  

## 🛠️ Stack
**LLM & AI:** OpenAI · Gemini · Agent Orchestration · Prompt Engineering · RAG · Context Management  
**Backend & Infra:** Python · FastAPI · Flask · Node.js · Redis · MySQL · PostgreSQL  
**Frontend:** TypeScript · React · Next.js · Tailwind  
**Cloud:** AWS (EC2, S3, SQS, Lambda, DynamoDB, AgentCore, CloudWatch) · GitHub Actions  
**Vector & Retrieval:** Milvus · AWS S3 Vector DB · AWS AgentCore Memory · Embedding Search

## 📫 Connect
[LinkedIn](https://linkedin.com/in/xzyuan/) · xzhe121@gmail.com
