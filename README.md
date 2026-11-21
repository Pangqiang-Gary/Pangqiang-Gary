# Deqiang Ye · Gary

### Applied AI / ML Engineering

I build retrieval systems, tool-using agents, and evaluation workflows. My work spans source-grounded document applications, agent integration, ML observability, and time-series research.

`Python` · `PyTorch` · `FastAPI` · `LangGraph` · `PostgreSQL` · `Docker` · `TypeScript`

## Selected projects

| Project | Engineering work | Evidence |
| --- | --- | --- |
| [Multi-Source RAG](https://github.com/Pangqiang-Gary/multi_source_rag) | Source-specific ingestion, BM25 and dense retrieval, weighted reciprocal-rank fusion, reranking, and claim-level conflict checks | [Ablations and failure analysis](https://github.com/Pangqiang-Gary/multi_source_rag/blob/main/report.md) |
| [LogSentinel](https://github.com/Pangqiang-Gary/logsentinel) | Streaming log parsing, immutable model versions, atomic activation and rollback, tenant isolation, and anomaly detection | [Verification workflow](https://github.com/Pangqiang-Gary/logsentinel/actions/workflows/ci.yml) |
| [Bank Capability Runner](https://github.com/Pangqiang-Gary/bank-capability-runner) | Computer-use discovery, typed capabilities, deterministic replay, guardrails, and operator handoff | [Implementation and usage](https://github.com/Pangqiang-Gary/bank-capability-runner) |
| [TradingAgents Blind Evaluation](https://github.com/Pangqiang-Gary/tradingagents-blind-eval) | Original evaluation tooling around an upstream agent framework, with frozen candidates, isolated memory and sealed predictions | [Evaluation harness](https://github.com/Pangqiang-Gary/tradingagents-blind-eval) |
| [Qlib US Walk-Forward Study](https://github.com/Pangqiang-Gary/qlib-us-walk-forward) | US-equity data adaptation, expanding-window evaluation, transaction costs and explicit research acceptance gates | [Methods and recorded results](https://github.com/Pangqiang-Gary/qlib-us-walk-forward) |
| [Time-Series Risk Alert](https://github.com/Pangqiang-Gary/time-series-risk-alert) | Chronological evaluation of Transformer and classical risk-alert baselines | [Regime-analysis extension](https://github.com/Pangqiang-Gary/time-series-risk-alert/pull/2) |

## Team contributions

**Emergency-department knowledge retrieval.** Implemented Qdrant-backed knowledge search, an Agent 1 RAG workflow, portable structure-aware ingestion, and integration verification. Five merged pull requests document the progression. The organization repository requires collaborator access.

[Vector store #3](https://github.com/IDEAS-Incubator/Agentic_Triage_System_for_Emergency_Departments/pull/3) · [Agent workflow #6](https://github.com/IDEAS-Incubator/Agentic_Triage_System_for_Emergency_Departments/pull/6) · [Portable ingestion #7](https://github.com/IDEAS-Incubator/Agentic_Triage_System_for_Emergency_Departments/pull/7) · [Integration #9](https://github.com/IDEAS-Incubator/Agentic_Triage_System_for_Emergency_Departments/pull/9) · [Verification #10](https://github.com/IDEAS-Incubator/Agentic_Triage_System_for_Emergency_Departments/pull/10)

**LawGPT.** Submitted four independently installable RAG implementations in their designated directories, with host adapters and documented verification. Graph retrieval uses hierarchical communities, Wiki retrieval navigates compiled Markdown, the retrieval agent selects tools iteratively, and the self-reflective workflow critiques drafts. PR #6 remains open as of November 21, 2026. The repository requires collaborator access.

[Implementation and validation, PR #6](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Lawgpt_CLI/pull/6)

**Native RAG.** Contributed a deterministic Wiki compiler, shared Core integration and a FastAPI adapter through merged pull requests.

[Compiler #1](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG/pull/1) · [Core migration #4](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG/pull/4) · [API adapter #6](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG/pull/6)

## Additional work

My private workspaces include solar-model reproduction and uncertainty experiments, a schema-driven tool dependency graph, contract-review agents, hierarchical configuration services, local prompt-injection experiments, and agent cost/evaluation tooling. Repository documentation records upstream provenance, implementation scope and validation limits.

[MF query generator coursework](https://github.com/Pangqiang-Gary/CS562-final) · [Contribution details](CONTRIBUTIONS.md)

## Engineering practice

- Preserve source IDs and data provenance through retrieval and generation.
- Make failure states, review limits and evaluation assumptions explicit.
- Keep model and data claims linked to reproducible tests or recorded experiments.
- Attribute upstream systems and distinguish original code, adaptations and team contributions.

