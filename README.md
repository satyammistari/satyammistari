## Satyam Mistari
ML/MLOps/LLMOps Engineer, also works in distributed ML systems( feels cool while doing stuff), infrastructure(feels cool to), and inference optimization(also feels cool tooo) . Implementing scalable ML platforms with Rust, Go, Python, and PyTorch.

<p align="center">
  <a href="https://x.com/satyammistari" target="_blank">twitter</a> •
  <a href="https://www.linkedin.com/in/satyammistari" target="_blank">linkedin</a> •
  <a href="https://github.com/satyammistari" target="_blank">github</a>
</p>
![Uploading Animations_sprites - Paulo Dos Reis.gif…]()

---

### currently exploring:
- distributed ML training and inference systems, model serving infrastructure, LLM optimization and cloud-native ML platforms.

### ml systems & infrastructure projects:

#### Distributed ML cli tools & Inference
- [**RUST-CHASH**](https://github.com/satyammistari/RUST-CHASH) —  Rust-based HTTP reverse proxy with a consistent hash ring Inspired by ByteByteGo's system design series — built from scratch in Rust with zero external hashing dependencies.
- [**db-seed-ai**](https://github.com/satyammistari/db-seed-ai) — db-seed-ai reads your SQL schema file and uses a local AI model (Ollama) to generate hundreds of rows of realistic, relationally-correct seed data — then inserts it directly into your database.
- [**log-anonymizer**](https://github.com/satyammistari/Rust-Log) — share logs to debug production issues but those logs contain customer emails, IP addresses, session tokens, and API keys. Manual scrubbing is slow and error-prone. log-anonymizer processes gigabytes in seconds safely.
- [**env-sync-in-go**](https://github.com/satyammistari/env-sync-in-go) — I build this stuff jst for fun, i'm bored by doing Machine learning(feature eng, optimization ) stuff, so i tried this and lock in for 3-4 hrs, doing FAFO with docs and blogs and built in one gooo....

#### ML/MLOps & Platform Engineering
- [**Writer-Flow-Deepseek-r1**](https://github.com/satyammistari/Writer-Flow-Deepseek-r1) — Automated documentation generation for codebases using multi-agent AI (CrewAI + Deepseek-R1) and MCP.
- [**RAG-check**](https://github.com/satyammistari/RAG-check) — rag-check is a terminal tool that ingests documents, stores them in a local vector database, and shows you relevance scores for every chunk your RAG pipeline retrieves. No cloud. No setup. Just clarity.


### end-to-end mlops projects:

- [**ZenML Support Agent**](https://github.com/satyammistari/End-to-End-Support-Agent-MLOps-) — A production-ready agent that can help you with your ZenML questions.
  
### research paper implementations:

- [**Implement-Research-Papers-into-from-scratch Public**](https://github.com/satyammistari/Implement-Research-Papers-into-from-scratch) — 
- [**Diffusion Model**](https://github.com/satyammistari/Implement-Research-Papers-into-from-scratch/tree/main/Diffusion%20Model) — implementation Diffusion Mode from scratch"
- [**LoRA**](https://github.com/satyammistari/Implement-Research-Papers-into-from-scratch/tree/main/LoRA-Low-Rank-Adaptation) —  Implementation of LoRA: Low-Rank Adaptation of Large Language Models.
- [**DDQN-paper-into-code**](https://github.com/satyammistari/DDQN-paper-into-code) — Implementation of the research paper "Deep Reinforcement Learning with Double Q-learning" by Hado van Hasselt, Arthur Guez, and David Silver (DeepMind, 2015).



### Ongoing learning & experimentation:

- [**ml-systems-papers**] — Annotated reading list and summaries of influential ML systems papers with implementation notes.
- [**cuda-kernels-learn**] — Collection of hand-written CUDA kernels for common ML operations: matmul, convolution, attention, normalization.
- [**rust-pytorch-bridge**] — Experiments bridging Rust and PyTorch for zero-copy tensor sharing and FFI optimization.

### My Philosophy

-**Understand before abstracting.** I implement papers and build systems from scratch not because it's always practical, but because it's the only way to know what's actually happening inside the abstraction. When something breaks at 3am, that knowledge is the difference between a 10-minute fix and a 3-hour debugging session.

-**Observability is a first-class concern.** A training run with no metrics is a black box. A serving system with no traces is a liability. I treat instrumentation as part of the implementation, not a follow-up task.

-**Performance claims require benchmarks.** "It's faster" means nothing without a number, a workload, and a baseline. I benchmark against real conditions, report p99 not just mean, and document what I didn't test.

-**Simplicity over cleverness.** The best infrastructure is the kind that a new teammate can understand in 20 minutes. I write code for the engineer who has to debug it at 2am — often that engineer is me.

---

**tech stack:**  
Languages: Rust, Go, Python | Frameworks: PyTorch, FastAPI, gRPC | Infrastructure: Kubernetes, Docker | Storage: S3, PostgreSQL, Redis | Monitoring: Prometheus, Grafana
