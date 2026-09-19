# Hi, I'm Bhagyesh 👋

**MS in Artificial Intelligence** at San Jose State University (expected May 2027), focused on **LLM agents, RAG systems, and adversarial ML**.

🔍 **Seeking full-time ML/AI Engineer and Software Engineer roles starting Summer 2027.**

🌐 Portfolio: **[bhagyesh.dev](https://bhagyesh.dev)** &nbsp;•&nbsp; 💼 [LinkedIn](https://linkedin.com/in/bhagyeshrathi07) &nbsp;•&nbsp; 📧 bhageyesh2161@gmail.com

---

## What I'm building

I work at the intersection of **AI engineering and adversarial ML**: building production systems and stress-testing them against the failure modes that matter for real deployment.

### 📄 Research

#### [🔬 RAG Evaluation Pipeline](https://github.com/bhagyeshrathi07/rag_eval) | First-author paper, IEEE AIxSET 2026
A modular evaluation pipeline comparing six retrieval strategies (Classic, ColBERT, Fusion, Query Rephrased, Reranked, and an agentic Tool Call approach) over a ~460K-paper arXiv corpus. SPECTER2 embeddings with task-specific adapters, Llama 3.1 8B as generator with Qwen2.5 32B as LLM judge, and paired comparisons against the Classic baseline with 95% confidence intervals. Runs end to end on an NVIDIA DGX Spark (ARM64).

`Python` `ColBERT` `SPECTER2` `Ollama` `LLM-as-Judge` `DGX Spark`

#### 🛡️ AI Agent Safety (in progress)
Studying how LLM agent safety behavior varies with the source of an instruction (user vs. tool output vs. retrieved content), including reproducing AgentHarm benchmark results with a focus on RAG-based attacks.

### 🛠️ Featured Projects

#### [🤖 SRE Copilot](https://github.com/bhagyeshrathi07/SRE-Copilot) | AI Incident Triage Agent
A multi-tool ReAct agent for on-call SREs. Dual Qwen2.5 models (32B + 3B) running on a single A100-80GB via 4-bit NF4 quantization, with RAG over 768 GitLab runbooks, text-to-SQL, GCP status API, and OSV vulnerability lookups. Includes a head-to-head comparison of four prompting techniques across 80 evaluation runs and red-team testing against five prompt injection attack vectors.

`Python` `PyTorch` `LangChain` `ChromaDB` `Qwen2.5` `Gradio` `bitsandbytes`

#### [💬 RAG-Powered Interactive Portfolio](https://github.com/bhagyeshrathi07/Portfolio) | [Live](https://bhagyesh.dev/chat)
Production RAG chatbot serving real users on my live portfolio site. Full ingestion pipeline (PDF → recursive chunking → Pinecone), streaming responses via Vercel AI SDK + Gemini 2.5 Flash, prompt-injection-hardened with topic-scoped guardrails, and a 27-test integration suite covering retrieval accuracy, embedding quality, and adversarial defense.

`Next.js` `Pinecone` `Vertex AI` `Vercel AI SDK` `LangChain` `TypeScript`

#### [📊 AutoML Studio](https://github.com/bhagyeshrathi07/AutoML) | Green-AI Classification & Regression Platform
Full-stack AutoML platform that auto-detects classification vs regression and trains 11 models in parallel, exporting the winner as both a serialized `.pkl` and a reproducible standalone Python script. Hardware-aware leaderboard tracks RAM/CPU during training to enable model selection on a compute-budget axis. Currently being expanded into a conference paper (IEEE format) with a Green AI focus.

`Python` `Flask` `scikit-learn` `XGBoost` `React 18` `Recharts`

#### [👁️ Caption Lens](https://huggingface.co/spaces/bhagyeshrathi/CaptionLens) | Visual-Semantic Alignment via Attention
Three encoder-decoder image captioning models trained from scratch on MS-COCO 2014: Show-and-Tell, Show-Attend-and-Tell with soft attention, and Visual Sentinel adaptive attention. ResNet-101 encoder feeding spatial features into an LSTM decoder with Bahdanau attention and doubly stochastic regularization. Beam-search width ablation, attention heatmap visualization, and an interactive Hugging Face Spaces demo.

`PyTorch` `Hugging Face` `ResNet-101` `LSTM` `Attention Mechanisms`

---

## Tech I work with

**Languages:** Python, Java, JavaScript/TypeScript, SQL, Kotlin

**ML / AI:** PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, LangChain, ColBERT, Ollama, ChromaDB, Pinecone, Vertex AI, bitsandbytes

**Backend & Infra:** Flask, Next.js, Docker, Kubernetes, GCP, GitLab CI/CD, OpenTelemetry

**Foundation:** Distributed systems, REST/OAuth2, monitoring & alerting, integration testing

---

## A bit of background

Most recently, I was a **Forward Deployed Engineering Intern at Scalar Field (YC-backed)** in Summer 2026, where I [ONE LINE: what you built and its impact].

Before MS AI, I built **Kotlin microservices for Social Authentication at Rakuten** (Google/Apple/Facebook OAuth across UK, Spain, and Germany properties), drove **40% adoption with a 37% lift in conversion** over password-based auth, and **TA'd Java OOP** for 50+ undergraduates at SJSU. I graduated **Magna Cum Laude in CS** before starting graduate work in AI.

That backend-engineering foundation shapes how I build AI systems: I care about evaluation rigor, deployment realities, observability, and the failure modes that show up only in production.

---

## What I'm thinking about right now

- **RAG evaluation:** when fancier retrieval (reranking, fusion, agentic tool calls) actually beats a classic dense baseline, and how to measure it honestly
- **Agent safety by instruction source:** how LLM agents treat harmful instructions differently depending on where they come from
- **Adversarial ML for LLM agents:** mapping prompt injection, RAG poisoning, and tool-use exploits to the MITRE ATLAS taxonomy
- **Inference-time compute scaling:** when test-time reasoning (self-reflection, planning) substitutes for parameter scale, and when it doesn't
- **Green AI:** making compute cost a first-class ranking dimension in model selection

---

## Let's talk

If you're hiring new grad ML/AI or software engineers for 2027, or if any of the above sounds like the kind of work your team does, I'd love to hear from you.

📧 **bhageyesh2161@gmail.com** &nbsp;•&nbsp; 💼 **[LinkedIn](https://linkedin.com/in/bhagyeshrathi07)** &nbsp;•&nbsp; 🌐 **[bhagyesh.dev](https://bhagyesh.dev)**
