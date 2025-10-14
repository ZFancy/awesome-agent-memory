# Awesome Agent Memory

A curated collection and reference for memory systems, patterns, research, and implementations used by autonomous agents and conversational assistants.

This repository gathers architectures, libraries, design patterns, benchmarks, and resources that help agents remember, retrieve, summarize, and reason over past interactions and external knowledge. It targets researchers, engineers, and practitioners building memory-enabled agents (chatbots, digital assistants, multi-agent systems).

## Table of Contents

- Overview and motivation
- Memory design patterns and trade-offs
- Benchmarks and evaluation strategies
- Research papers, blog posts, talks
- Best practices and security/privacy considerations

## Why agent memory matters

Modern agents need to maintain state across turns, remember user preferences, and use long-term context to provide consistent, personalized, and safe responses. Good memory systems improve usefulness, reduce repetition, and enable more complex multi-step workflows.

Key challenges:

- Scalability: storing and searching large volumes of past interactions or documents.
- Relevance: selecting what to remember and what to forget.
- Latency: retrieving context fast enough for interactive use.
- Consistency & Safety: avoiding hallucinations and protecting private data.

## Typical memory patterns

- Short-term / working memory: recent conversation turns kept in RAM.
- Episodic memory: snapshots of full interactions stored for later retrieval.
- Semantic memory: embeddings of text/documents for similarity search.
- Procedural memory: learned policies, action histories, or macros.
- Summarization: compressing long interactions into concise notes.
- Forgetting / pruning: TTL, LRU, heuristics, or learned retention.

## Main Content

Research Papers:

- A Survey on the Memory Mechanism of Large Language Model based Agents. [Paper](https://arxiv.org/abs/2404.13501)
- MemGen: Weaving Generative Latent Memory for Self-Evolving Agents. [Paper](https://arxiv.org/abs/2509.24704)
- ReasoningBank: Scaling Agent Self-Evolving with Reasoning Memory. [Paper](https://arxiv.org/abs/2509.25140)
- MemoryBank: Enhancing Large Language Models with Long-Term Memory. [Paper](https://arxiv.org/abs/2305.10250)
- Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory. [Paper](https://arxiv.org/abs/2504.19413)
- Learn to Memorize: Optimizing LLM-based Agents with Adaptive Memory Framework. [Paper](https://arxiv.org/abs/2508.16629)
- Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models. [Paper](https://arxiv.org/abs/2510.04618)
- LEGOMem: Modular Procedural Memory for Multi-agent LLM Systems for Workflow Automation. [Paper](https://arxiv.org/abs/2510.04851)
- Auto-scaling Continuous Memory for GUI Agent. [Paper](https://arxiv.org/abs/2510.09038)

TBD

#### Note: this repo is a starting point — please open issues or PRs with additions, corrections, and links to notable projects.

## Security & privacy

Memory systems commonly store potentially sensitive user data. Follow these practices:

- Minimize retention of sensitive data and provide TTLs.
- Use encryption at rest and in transit.
- Anonymize or redact PII before storing if possible.
- Provide clear user controls and opt-outs.

## Contributing

Contributions are welcome. Please follow these steps:

1. Fork the repository.
2. Add your resource, example, or paper under a descriptive folder.
3. Update this README or add a curated list file where appropriate.
4. Open a PR describing your changes and why the resource is valuable.

Be mindful of licensing when linking third-party code or content.


## Acknowledgements & resources

- Survey papers on memory for dialogue systems
- Major vector DB and embedding providers
- Community contributions
