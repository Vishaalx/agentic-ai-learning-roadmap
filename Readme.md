# 🤖 Agentic AI Learning Roadmap

![Status](https://img.shields.io/badge/status-in%20progress-38E1C6) ![Level](https://img.shields.io/badge/level-beginner%20friendly-blue) ![Last Updated](https://img.shields.io/badge/updated-2026-lightgrey)

> I'm learning Agentic AI from scratch and mapping out my path as I go. Sharing it here in case it helps someone else starting out too — feel free to fork, star, or suggest what I'm missing via an issue or PR.

---

## 📋 Table of Contents

- [How to use this roadmap](#-how-to-use-this-roadmap)
- [Module 1 — Programming & Data Foundations](#module-1--programming--data-foundations)
- [Module 1.5 — Math You Actually Need](#module-15--math-you-actually-need)
- [Module 2 — Machine Learning & Deep Learning](#module-2--machine-learning--deep-learning)
- [Module 3 — NLP & Large Language Models](#module-3--nlp--large-language-models)
- [Module 4 — API Development for AI](#module-4--api-development-for-ai)
- [Module 5 — Prompt Engineering](#module-5--prompt-engineering)
- [Module 6 — Vector Databases & RAG](#module-6--vector-databases--rag)
- [Module 7 — LangChain & LangGraph](#module-7--langchain--langgraph)
- [Module 8 — Multi-Agent Systems](#module-8--multi-agent-systems)
- [Module 9 — No-Code Agent Automation](#module-9--no-code-agent-automation)
- [Module 10 — Voice Agents](#module-10--voice-agents)
- [Module 11 — Guardrails & Security](#module-11--guardrails--security)
- [Module 12 — Production & Deployment](#module-12--production--deployment)
- [Practice Projects](#-practice-projects)
- [Contributing](#-contributing)

---

## 🧭 How to use this roadmap

Work through the modules in order and check them off as you go. Each module lists the resources I'm using — some are courses, some are docs, some are just a single good YouTube video. Nothing here requires a paid course; everything linked is free unless noted.

```
[ ] Not started   [~] In progress   [x] Done
```

---

## Module 1 — Programming & Data Foundations

- [ ] Python — [https://youtu.be/QGAuolgCTHE](https://youtube.com/playlist?list=PL-Y17yukoyy0SupAJSPQYg_Lvre9Kt9EG&si=DT1fkwDgsmkZgskG)
- [ ] SQL — https://youtu.be/IzyebUSMVa0
- [ ] Async Python (asyncio) — https://realpython.com/async-io-python/
  - *Why:* Agents wait on tool calls and run sub-agents in parallel — async understanding matters early.

---

## Module 1.5 — Math You Actually Need

*(Zero-to-useful — no proofs, no advanced stats. ~3–4 weeks at a relaxed pace.)*

- [ ] **Linear Algebra** — [3Blue1Brown: Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
  Focus: vectors, dot product, matrix multiplication, dimensions. Skip eigenvalues for now.
- [ ] **Probability & Statistics** — [StatQuest: Statistics Fundamentals](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9)
  Focus: mean/variance, distributions, conditional probability.
- [ ] **Calculus (intuition only)** — [3Blue1Brown: Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
  Focus: what a derivative means, what gradient descent is doing.
- [ ] **Graph Theory (light)** — [Graph Theory Basics — freeCodeCamp](https://www.youtube.com/watch?v=09_LlHjoEiY) (first 30–40 min)
  Focus: nodes, edges, directed graphs — this is literally what agent workflows are.

**Self-check before moving on:** can you explain, in your own words, what a dot product is, what "temperature" does to a probability distribution, what a derivative tells you, and why an agent workflow is a graph? If yes, move to Module 2.

---

## Module 2 — Machine Learning & Deep Learning

- [ ] [Machine Learning Specialization (Andrew Ng)](https://youtube.com/playlist?list=PLkDaE6sCZn6FNC6YRfRQc_FbeQrF8BwGI&si=t4bzMZI_JukzPW6c)
- [ ] *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* — Aurélien Géron (book)
- [ ] [Deep Learning Specialization (DeepLearning.AI)](https://www.deeplearning.ai/specializations/deep-learning)
- [ ] [MIT 6.S191: Intro to Deep Learning](https://youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI&si=j3w_289PqUazTxcp)

---

## Module 3 — NLP & Large Language Models

- [ ] [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- [ ] [Natural Language Processing with Deep Learning](https://youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ&si=nccUrGl4oupjXPq0)
- [ ] [Hugging Face Learn](https://huggingface.co/learn)

---

## Module 4 — API Development for AI

- [ ] [Python API Development — Full Course](https://youtu.be/0sOvCWFmrtA)
- [ ] [API: Step by Step — Build, Secure and Deploy](https://youtu.be/Z8zEtb7hHAY)
- [ ] [FastAPI with Python from Scratch (2026)](https://youtu.be/7aKbdpkMVnU)
- [ ] [FastAPI official docs (async)](https://fastapi.tiangolo.com/tutorial/)
- [ ] Function calling / structured output — [Anthropic tool use docs](https://docs.claude.com/en/docs/build-with-claude/tool-use) · [OpenAI function calling guide](https://platform.openai.com/docs/guides/function-calling)

---

## Module 5 — Prompt Engineering

- [ ] [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/courses/chatgpt-prompt-eng)
- [ ] [Functions, Tools & Agents with LangChain](https://www.deeplearning.ai/courses/functions-tools-agents-langchain)
- [ ] [Prompt Engineering Basics to Advanced (Tamil)](https://youtu.be/wNKTBCuuMUU)
- [ ] [Prompt Injection Simplified (Tamil)](https://youtu.be/z0LyQ5HCUFg)

---

## Module 6 — Vector Databases & RAG

- [ ] [Pinecone Learning Center](https://www.pinecone.io/learn/) — best free intro to vector DBs
  - Also worth trying: **Qdrant** and **ChromaDB** (open-source, self-hostable)
- [ ] [Building Agentic RAG with LlamaIndex](https://www.deeplearning.ai/courses/building-agentic-rag-with-llamaindex)
- [ ] [Agentic RAG cookbook (LlamaIndex docs)](https://docs.llamaindex.ai/en/stable/examples/agent/agentic_rag_using_workflows/)
- [ ] [RAG Concepts Explained (Tamil)](https://www.youtube.com/watch?v=OXNnxcTdGZA)
- [ ] [RAG evaluation with Ragas](https://docs.ragas.io/) — measuring faithfulness & relevancy, not just "it seems to work"

---

## Module 7 — LangChain & LangGraph

- [ ] [Agentic AI – Complete Course for Beginners](https://www.youtube.com/watch?v=Zy7EXDONlTY) — solid single course covering LangChain + LangGraph end-to-end (watch after Modules 1–6)
- [ ] [LangChain Fundamentals](https://www.deeplearning.ai/courses/langchain)
- [ ] [LangGraph playlist](https://youtube.com/playlist?list=PLfaIDFEXuae16n2TWUkKq5PgJ0w6Pkwtg&si=RW2BIrO1Z2C4QElM)
- [ ] [LangChain for Beginners (Tamil)](https://youtu.be/p0-eU2MG_Gk)
- [ ] [Complete LangGraph Tutorial (Tamil)](https://youtu.be/vVtzWXTv3vM)

---

## Module 8 — Multi-Agent Systems

- [ ] [Multi AI Agent Systems with CrewAI](https://www.deeplearning.ai/courses/multi-ai-agent-systems-with-crewai)
- [ ] [Build AI Agents with CrewAI (Tamil)](https://youtu.be/16lYmedr7AQ)
- [ ] [AG2 / AutoGen Framework Overview](https://microsoft.github.io/autogen/stable/)
- [ ] [Agent Memory & Planning Strategies — Lilian Weng](https://lilianweng.github.io/posts/2023-06-23-agent/)
- [ ] [LangGraph HITL / Loop Engineering docs](https://docs.langchain.com/oss/python/langgraph/overview) (search "Loop Engineering")

---

## Module 9 — No-Code Agent Automation

- [ ] [n8n official docs](https://docs.n8n.io/)
- [ ] [n8n AI Agent nodes guide](https://docs.n8n.io/advanced-ai/)
  - *Why:* a visual way to wire up agent workflows without building every piece from scratch.

---

## Module 10 — Voice Agents

- [ ] [Vapi docs](https://docs.vapi.ai/)
- [ ] [Retell AI docs](https://www.retellai.com/)

---

## Module 11 — Guardrails & Security

- [ ] [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [ ] [Guardrails AI](https://www.guardrailsai.com/)

---

## Module 12 — Production & Deployment

- [ ] [LangSmith (observability)](https://docs.langchain.com/langsmith/observability)
- [ ] [Arize Phoenix](https://phoenix.arize.com/) — open-source, self-hostable alternative
- [ ] [MCP Course (Tamil)](https://youtu.be/aHD77Fp7X9g)
- [ ] [Model Context Protocol — official docs](https://modelcontextprotocol.io/docs/2026-07-28/getting-started/intro)
- [ ] [Docker Tutorial for Beginners (Full Course)](https://youtu.be/3c-iBn73dDE)
- [ ] Cloud deployment — [Railway docs](https://docs.railway.app/) or [AWS Lambda docs](https://docs.aws.amazon.com/lambda/)

---

## 🔨 Practice Projects

Small builds to actually cement each stage — pick these up as you finish the related module.

| # | Project | Ties to | What it practices |
|---|---------|---------|--------------------|
| 1 | Document Q&A Agent | Module 6 | Basic RAG over a small set of PDFs |
| 2 | Support Agent with Escalation | Module 7 | Tool use, memory, human-in-the-loop |
| 3 | Voice Agent Demo | Module 10 | A basic call-answering agent |
| 4 | Multi-Agent Mini Crew | Module 8 | A few agents completing one task together |

---

## 🤝 Contributing

This is a personal, evolving roadmap — not a finished product. If you spot an outdated resource, a better alternative, or a topic I'm missing, feel free to open an issue or a pull request. Learning in public works better with more eyes on it.

⭐ Star this repo if you're on a similar path — it helps others find it too.
