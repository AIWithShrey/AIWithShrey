# 👋 Hey! I'm Shreyas Mocherla

**Cloud-Native AI Engineer** | **CNCF Kubestronaut** | **NVIDIA University Ambassador**

Building production AI systems for Kubernetes governance and platform engineering—including core components of **Nirmata's AI Platform Engineering Assistant** launched at **KubeCon North America 2025**.

---

## 🚀 What I Do

- **AI Agent Development**: Building multi-agent systems for cloud-native infrastructure automation
- **Platform Engineering AI**: Creating intelligent assistants that transform natural language into validated Kubernetes policies
- **Policy Automation**: Developing AI-powered policy management with **Kyverno**, LLM-driven code generation, and automated remediation
- **Developer Tooling**: Architecting CLI agents, MCP servers, and Kubernetes controllers for cloud-native workflows
- **Open Source**: Contributing to upstream **Kyverno** — extending CLI testing capabilities for CEL, MutatingPolicy, and JSON payloads

---

## 💼 Currently

**Software Engineer @ [Nirmata](https://nirmata.com)** *(Cloud-Native Policy Management Platform)*

Building core components of **[Nirmata's AI Platform Engineering Assistant](https://nirmata.com)** — an AI copilot for Kubernetes security and governance launched at KubeCon 2025:

- **🎯 Owned and built the Kyverno MCP Server** — enables LLMs to generate, validate, and troubleshoot Kyverno policies through Model Context Protocol
- **🤖 Core developer on NCTL AI Agent** — intelligent CLI assistant that transforms natural language into production-ready policy-as-code
- **🔧 Architected multi-agent orchestration** for policy generation, validation, and remediation workflows across ValidatingPolicy, MutatingPolicy, GeneratingPolicy, and ImageValidatingPolicy types
- **📊 Built LLM benchmarking framework** — comprehensive test suite evaluating AI policy generation quality across 50+ scenarios including CEL patterns, OPA Gatekeeper conversion, and JSON mode (Terraform/Dockerfile)
- **📐 Developed policy conversion frameworks** for migrating OPA Gatekeeper policies to Kyverno at enterprise scale using LLMs

### Upstream Kyverno Contributions

Active contributor to [kyverno/kyverno](https://github.com/kyverno/kyverno) — extending the Kyverno CLI test framework:
- Added `mutateExisting` MutatingPolicy support in CLI test
- Added CEL expression `targetMatchConstraints` support in CLI test
- Fixed segfault when applying K8s-mode policies to JSON payloads
- Eliminated memcache error spam from fake client discovery polling

**Technologies**: Go | Kyverno | CEL | MCP Protocol | Kubernetes Controllers

---

## 🎯 Technical Expertise

**Kubernetes & Cloud Native**: CKA | CKAD | CKS | KCNA | KCSA (Kubestronaut) | CGOA | PCA | CAPA | Kyverno | OPA | Helm | Argo
**AI/ML Frameworks**: TensorFlow (Ex-Certified) | PyTorch | LangChain | LangGraph | CrewAI
**Agent Development**: MCP Protocol | Multi-Agent Systems | RAG Architecture | LLM Orchestration
**Infrastructure**: Linux Foundation Certified SysAdmin | Terraform | AWS | GCP | Docker
**Languages**: Go | Python | YAML | CEL

---

## 🏆 Certifications & Recognition

- 🌟 **CNCF Kubestronaut** (One of the youngest globally as of January 2025)
- 🎓 **NVIDIA Deep Learning Institute Certified Instructor** (Fundamentals of Deep Learning)
- ☁️ **Linux Foundation Certified Systems Administrator (LFCS)**
- 🤖 **TensorFlow Developer Certificate**
- 🔒 Kubernetes & Cloud Native: **CKA** | **CKAD** | **CKS** | **KCNA** | **KCSA** | **CGOA** | **PCA** | **CAPA**

---

## 🔥 Featured Projects

### **Kyverno MCP Server** *(Nirmata AI Platform Engineering Assistant)*
**Owner & Lead Developer** | Launched at KubeCon NA 2025

Model Context Protocol server enabling LLMs to intelligently generate, validate, and troubleshoot Kyverno policies. Powers the policy-as-code agent in Nirmata's AI Platform Engineering Assistant.

**Impact**: Transforms natural language infrastructure requirements into production-ready Kubernetes policies in seconds.

**Tech Stack**: Go | MCP Protocol | Kyverno | CEL

---

### **NCTL AI Agent** *(Nirmata AI Platform Engineering Assistant)*
**Core Contributor** | Launched at KubeCon NA 2025

Intelligent CLI agent that brings conversational AI to cloud-native policy development. Enables platform engineers to generate, test, and deploy Kyverno policies through natural language.

**Impact**: Reduces policy development time from hours to minutes while maintaining security and compliance standards.

**Tech Stack**: Go | Multi-Agent Systems | Kyverno | Kubernetes

---

### **LLM Policy Generation Benchmarks**
**Author** | Nirmata

Comprehensive benchmarking framework evaluating AI-generated Kyverno policy quality across 50+ test scenarios. Covers ValidatingPolicy, MutatingPolicy, GeneratingPolicy, Chainsaw tests, OPA Gatekeeper conversion, and JSON mode for Terraform/Dockerfile resources.

**Impact**: Provides measurable quality metrics for LLM-driven policy generation with automated schema validation and functional testing.

**Tech Stack**: Go | Kyverno | CEL | AWS Bedrock
