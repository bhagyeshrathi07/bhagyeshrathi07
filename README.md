# Hi, I'm Bhagyesh 👋

**MS in Artificial Intelligence** at San Jose State University (expected May 2027), focused on **LLM agents, RAG systems, and adversarial ML**.

🔍 **Currently seeking Summer/Fall 2026 ML/AI Engineering internships.**

🌐 Portfolio: **[bhagyesh.dev](https://bhagyesh.dev)** &nbsp;•&nbsp; 💼 [LinkedIn](https://linkedin.com/in/bhagyeshrathi07) &nbsp;•&nbsp; 📧 bhageyesh2161@gmail.com

---

## What I'm building

I work on the intersection of **AI engineering and adversarial ML** — building production systems and stress-testing them against the failure modes that matter for real deployment.

### 🛠️ Featured Projects

#### [🤖 SRE Copilot](https://github.com/bhagyeshrathi07/SRE-Copilot) — AI Incident Triage Agent
A multi-tool ReAct agent for on-call SREs. Dual Qwen2.5 models (32B + 3B) running on a single A100-80GB via 4-bit NF4 quantization, with RAG over 768 GitLab runbooks, text-to-SQL, GCP status API, and OSV vulnerability lookups. Includes a head-to-head comparison of four prompting techniques across 80 evaluation runs and red-team testing against five prompt injection attack vectors.

`Python` `PyTorch` `LangChain` `ChromaDB` `Qwen2.5` `Gradio` `bitsandbytes`

#### [💬 RAG-Powered Interactive Portfolio](https://github.com/bhagyeshrathi07/Portfolio) — [Live](https://bhagyesh.dev/chat)
Production RAG chatbot serving real users on my live portfolio site. Full ingestion pipeline (PDF → recursive chunking → Pinecone), streaming responses via Vercel AI SDK + Gemini 2.5 Flash, prompt-injection-hardened with topic-scoped guardrails, and a 27-test integration suite covering retrieval accuracy, embedding quality, and adversarial defense.

`Next.js` `Pinecone` `Vertex AI` `Vercel AI SDK` `LangChain` `TypeScript`

#### [📊 AutoML Studio](https://github.com/bhagyeshrathi07/AutoML) — Green-AI Classification & Regression Platform
Full-stack AutoML platform that auto-detects classification vs regression and trains 11 models in parallel, exporting the winner as both a serialized `.pkl` and a reproducible standalone Python script. Hardware-aware leaderboard tracks RAM/CPU during training to enable model selection on a compute-budget axis. Currently being expanded into a conference paper (IEEE format) with a Green AI focus.

`Python` `Flask` `scikit-learn` `XGBoost` `React 18` `Recharts`

#### [👁️ Caption Lens](https://huggingface.co/spaces/bhagyeshrathi/CaptionLens) — Visual-Semantic Alignment via Attention
Three encoder-decoder image captioning models trained from scratch on MS-COCO 2014 — Show-and-Tell, Show-Attend-and-Tell with soft attention, and Visual Sentinel adaptive attention. ResNet-101 encoder feeding spatial features into an LSTM decoder with Bahdanau attention and doubly stochastic regularization. Beam-search width ablation, attention heatmap visualization, and an interactive Hugging Face Spaces demo.

`PyTorch` `Hugging Face` `ResNet-101` `LSTM` `Attention Mechanisms`

---

## Tech I work with

**Languages** — Python, Java, JavaScript/TypeScript, SQL, Kotlin

**ML / AI** — PyTorch, TensorFlow, scikit-learn, Hugging Face Transformers, LangChain, ChromaDB, Pinecone, Vertex AI, bitsandbytes

**Backend & Infra** — Flask, Next.js, Docker, Kubernetes, GCP, GitLab CI/CD, OpenTelemetry

**Foundation** — Distributed systems, REST/OAuth2, monitoring & alerting, integration testing

---

## A bit of background

Before MS AI, I built **Kotlin microservices for Social Authentication at Rakuten** (Google/Apple/Facebook OAuth across UK, Spain, and Germany properties), drove **40% adoption with a 37% lift in conversion** over password-based auth, and **TA'd Java OOP** for 50+ undergraduates at SJSU. I graduated **Magna Cum Laude in CS** before starting graduate work in AI.

That backend-engineering foundation shapes how I build AI systems — I care about evaluation rigor, deployment realities, observability, and the failure modes that show up only in production.

---

## What I'm thinking about right now

- **Inference-time compute scaling** — when test-time reasoning (self-reflection, planning) substitutes for parameter scale, and when it doesn't
- **Adversarial ML for LLM agents** — mapping prompt injection, RAG poisoning, and tool-use exploits to the MITRE ATLAS taxonomy
- **Green AI** — making compute cost a first-class ranking dimension in model selection (currently writing this up for an IEEE conference submission)
- **LLM training data extraction** — following Carlini et al.'s 2021 work and its 2023 diffusion-model extension

---

## Let's talk

If you're hiring for AI/ML internships — or if any of the above sounds like the kind of work your team does — I'd love to hear from you.

📧 **bhageyesh2161@gmail.com** &nbsp;•&nbsp; 💼 **[LinkedIn](https://linkedin.com/in/bhagyeshrathi07)** &nbsp;•&nbsp; 🌐 **[bhagyesh.dev](https://bhagyesh.dev)**

<p align="center"><i>"Build the systems and red-team them simultaneously."</i></p>
