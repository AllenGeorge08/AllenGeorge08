## Hi there, I'm Allen.

I build systems across AI, LLMs, and Web3 (Solana).

### What I've built

1. **[LLM Semantic Caching Gateway](https://github.com/AllenGeorge08/LLM-Semantic-Caching-Gateway)**  
   Drop-in gateway that sits between applications and LLM providers. Uses semantic similarity over Redis to serve repeated or paraphrased queries from cache instead of paying for another inference call. Includes latency and threshold benchmarks across multiple models, with measurable speedups on cache hits and explicit precision/recall trade-offs at different similarity thresholds.

2. **[ForgeOps](https://github.com/AllenGeorge08/ForgeOps)**  
   Multi-agent investigation system for engineering and DevOps incidents. Uses LangGraph with a supervisor, specialist agents (GitHub, CI/CD, Slack), guardrails, long-term memory, and structured root-cause analysis. Designed to correlate evidence across systems without manual log hunting.

3. **[SentinelRag](https://github.com/AllenGeorge08/SentinelRag)**  
   Production-style hybrid RAG system for AI security, red-teaming, and governance documentation. Combines dense vector retrieval (Qdrant), BM25 lexical search, and Reciprocal Rank Fusion. Includes asynchronous processing, LangSmith observability, and LLM-as-a-judge evaluation across correctness, relevance, and groundedness.

4. **[Qwen3 Prompt Injection Detector](https://github.com/AllenGeorge08/Qwen3PromptInjectionDetector)**  
   Parameter-efficient fine-tune of Qwen3-1.7B with QLoRA for detecting prompt injection and jailbreak attempts. Classifies inputs by label, attack category, and severity using a labeled dataset and structured evaluation.

### Open Source and Bug Bounties

I contribute to open-source projects and participate in security competitions.

- Merged pull request in [Solana Surfpool](https://github.com/solana-foundation/surfpool) (local Solana development environment with mainnet state forking).
- 4 merged pull requests in [TrenTorch](https://github.com/TrenTorch/TrenTorch) (1k+ stars), an open-source from-scratch machine learning curriculum and framework.
- Security research: [Sherlock profile](https://audits.sherlock.xyz/watson/Allen_George08) — multiple high- and medium-severity findings in DeFi competitions.

![Profile views](https://komarev.com/ghpvc/?username=AllenGeorge08&color=blue&style=flat-square&label=PROFILE+VIEWS&abbreviated=true)
