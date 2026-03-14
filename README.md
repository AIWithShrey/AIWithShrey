# 👋 Hey! I'm Shreyas Mocherla

**Cloud-Native AI Engineer** | **CNCF Kubestronaut** | **NVIDIA University Ambassador**

Building production AI systems for Kubernetes governance and platform engineering, including core components of **[Nirmata's AI Platform Engineering Assistant](https://nirmata.com)** launched at **KubeCon North America 2025**.

🎤 **KubeCon India 2026 Speaker** · 📝 **[CNCF Blog Author](https://www.cncf.io/blog/2024/08/19/developing-an-ai-agent-for-smart-contextual-qa/)** · 🎯 **13/16 toward Golden Kubestronaut**

---

## 🚀 What I Do

- **Platform Engineering AI**: Creating intelligent assistants that transform natural language into validated Kubernetes policies
- **MCP Server Development**: Building Model Context Protocol servers that connect AI assistants to Kubernetes infrastructure
- **Policy Automation**: Developing AI-powered policy management with **Kyverno**, LLM-driven code generation, and automated remediation
- **AI Infrastructure**: Working with GPU Operator, Dynamic Resource Allocation (DRA), and vLLM on Kubernetes
- **Open Source**: Contributing to upstream **[Kyverno](https://github.com/kyverno/kyverno)**, extending CLI testing capabilities for CEL, MutatingPolicy, and JSON payloads

---

## 💼 Currently

**Software Engineer @ [Nirmata](https://nirmata.com)** *(Cloud-Native Policy Management Platform)*

Building core components of **[Nirmata's AI Platform Engineering Assistant](https://nirmata.com)**, an AI copilot for Kubernetes security and governance launched at KubeCon 2025:

- **💿 Owned and built the [Kyverno MCP Server](https://github.com/nirmata/kyverno-mcp)**: Open-source MCP server in Go that enables AI assistants to generate, validate, and troubleshoot Kyverno policies through Model Context Protocol
- **🤖 Core developer on NCTL AI Agent**: Intelligent CLI assistant that transforms natural language into production-ready policy-as-code
- **🔧 Architected multi-agent orchestration** for policy generation, validation, and remediation workflows across ValidatingPolicy, MutatingPolicy, GeneratingPolicy, and ImageValidatingPolicy types
- **📊 Built LLM benchmarking framework**: Comprehensive test suite evaluating AI policy generation quality across 50+ scenarios including CEL patterns, OPA Gatekeeper conversion, and JSON mode (Terraform/Dockerfile)
- **📐 Developed policy conversion frameworks** for migrating OPA Gatekeeper policies to Kyverno at enterprise scale using LLMs

### Upstream Kyverno Contributions

Active contributor to [kyverno/kyverno](https://github.com/kyverno/kyverno), extending the Kyverno CLI test framework:
- Added `mutateExisting` MutatingPolicy support in CLI test
- Added CEL expression `targetMatchConstraints` support in CLI test
- Fixed segfault when applying K8s-mode policies to JSON payloads
- Eliminated memcache error spam from fake client discovery polling

**Technologies**: Go | Kyverno | CEL | MCP Protocol | Kubernetes Controllers

---

## 🎯 Technical Expertise

**Kubernetes & Cloud Native**: CKA | CKAD | CKS | KCNA | KCSA | KCA | CGOA | PCA | CAPA | OTCA | CCA | CNPA | Kyverno | OPA | Helm | Argo  
**AI/ML Frameworks**: TensorFlow (Ex-Certified) | PyTorch | LangChain | LangGraph | CrewAI  
**MCP & Agent Development**: Model Context Protocol | Multi-Agent Systems | RAG Architecture | LLM Orchestration  
**AI Infrastructure**: GPU Operator | Dynamic Resource Allocation (DRA) | vLLM | Kubernetes AI workloads  
**Infrastructure**: Linux Foundation Certified SysAdmin | Terraform | AWS | GCP | Docker  
**Languages**: Go | Python | YAML | CEL

---

## 🏆 Certifications & Recognition

- 🌟 **CNCF Kubestronaut** (Earned while still in college at Missouri S&T, January 2025). Pursuing **Golden Kubestronaut** (13/16 complete).
- 🎤 **KubeCon India 2026 Speaker**: "Run Your Own AI Cluster on a DGX Spark: Kubernetes, GPUs, and DRA" (June 18-19, Mumbai)
- 📝 **CNCF Blog Author**: [Developing an AI Agent for Smart Contextual Q&A](https://www.cncf.io/blog/2024/08/19/developing-an-ai-agent-for-smart-contextual-qa/) (August 2024)
- 🎓 **NVIDIA Deep Learning Institute Certified Instructor** (Fundamentals of Deep Learning)
- ☁️ **Linux Foundation Certified Systems Administrator (LFCS)**
- 🤖 **TensorFlow Developer Certificate**
- 🔒 Kubernetes & Cloud Native: **CKA** | **CKAD** | **CKS** | **KCNA** | **KCSA** | **KCA** | **CGOA** | **PCA** | **CAPA** | **OTCA** | **CCA** | **CNPA**

---

## 🔥 Featured Projects

### **[Kyverno MCP Server](https://github.com/nirmata/kyverno-mcp)** *(Nirmata AI Platform Engineering Assistant)*
**Owner & Lead Developer** | Part of Nirmata's platform launched at KubeCon NA 2025

Open-source Model Context Protocol server in Go that enables AI assistants like Claude Desktop, Amazon Q, and Cursor to generate, validate, and troubleshoot Kyverno policies across multi-cluster Kubernetes environments. Supports compliance monitoring via PolicyReport CRDs and seamless context switching between clusters.

**Impact**: Transforms natural language infrastructure requirements into production-ready Kubernetes policies in seconds.

**Tech Stack**: Go | MCP Protocol | Kyverno | CEL

---

### **NCTL AI Agent** *(Nirmata AI Platform Engineering Assistant)*
**Core Contributor** | Part of Nirmata's platform launched at KubeCon NA 2025

Intelligent CLI agent that brings conversational AI to cloud-native policy development. Enables platform engineers to generate, test, and deploy Kyverno policies through natural language.

**Impact**: Reduces policy development time from hours to minutes while maintaining security and compliance standards.

**Tech Stack**: Go | Multi-Agent Systems | Kyverno | Kubernetes

---

### **[InSightful](https://github.com/infracloudio/insightful)** *(InfraCloud Technologies)*
**Author** | [Published on the CNCF Blog](https://www.cncf.io/blog/2024/08/19/developing-an-ai-agent-for-smart-contextual-qa/)

A ReAct AI agent for smart contextual Q&A in online tech communities (Slack, Discord, Reddit). Uses a Conversation Retriever (custom RAG with vector store), Stack Overflow search, and web search to reduce redundant questions from newcomers.

**Impact**: Demonstrated how ReAct agents can improve community knowledge management at scale.

**Tech Stack**: Python | LangChain | HuggingFace TGI/TEI | ChromaDB | Kubernetes

---

### **LLM Policy Generation Benchmarks**
**Author** | Nirmata

Comprehensive benchmarking framework evaluating AI-generated Kyverno policy quality across 50+ test scenarios. Covers ValidatingPolicy, MutatingPolicy, GeneratingPolicy, Chainsaw tests, OPA Gatekeeper conversion, and JSON mode for Terraform/Dockerfile resources.

**Impact**: Provides measurable quality metrics for LLM-driven policy generation with automated schema validation and functional testing.

**Tech Stack**: Go | Kyverno | CEL | AWS Bedrock

---

## 📫 Let's Connect

- 🌐 [shreyasm.com](https://shreyasm.com)
- 💼 [LinkedIn](https://linkedin.com/in/aiwithshrey)
- 🐦 [Twitter/X](https://twitter.com/ShreyasMocherla)
- 📧 [shreyas@shreyasm.com](mailto:shreyas@shreyasm.com)
- 🏅 [Credly Badges](https://www.credly.com/users/shreyas-mocherla/badges)
