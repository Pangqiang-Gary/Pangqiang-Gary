# Gary — Applied AI/ML Engineer

I build evaluation-first AI systems: retrieval and ranking pipelines, agent workflows, time-series risk models, and production-minded ML services. I care about reproducibility, provenance, failure analysis, and making model claims testable.

`Python` · `PyTorch` · `FastAPI` · `PostgreSQL` · `Docker` · `GitHub Actions`

## Selected engineering work

| Project | What it demonstrates | Evidence |
|---|---|---|
| [LogSentinel](https://github.com/Pangqiang-Gary/logsentinel) | Streaming log parsing, immutable model versions, atomic activation/rollback, tenant isolation, and online anomaly detection | [CI](https://github.com/Pangqiang-Gary/logsentinel/actions/workflows/ci.yml), 17 tests, 85% coverage, Loghub evaluation, Docker health check |
| [Multi-Source RAG](https://github.com/Pangqiang-Gary/multi_source_rag) | Source-specific ingestion, BM25+dense retrieval, weighted RRF, cross-encoder reranking, and explicit conflict handling | [Ablation report](https://github.com/Pangqiang-Gary/multi_source_rag/blob/main/report.md): reranking improved source-overlap hit rate from 75.0% to 91.7% |
| [TradingAgents Blind Eval](https://github.com/Pangqiang-Gary/tradingagents-blind-eval) | Forward-only evaluation controls around an unchanged upstream agent system | Candidate freezing, clean-commit verification, isolated memory, sealed predictions, post-cutoff scoring |
| [Time-Series Risk Alert](https://github.com/Pangqiang-Gary/time-series-risk-alert) | Chronological financial-ML evaluation with Transformer and classical baselines | Saved datasets, model checkpoint, calibration artifacts, threshold sweeps, and [v2 regime-analysis PR](https://github.com/Pangqiang-Gary/time-series-risk-alert/pull/2) |
| [MF-Structure Query Generator](https://github.com/Pangqiang-Gary/CS562-final) | Parsing declarative MF specifications into executable PostgreSQL query processors | Six reproducible query cases and generated outputs; [extended-cases PR](https://github.com/Pangqiang-Gary/CS562-final/pull/2) |

## Engineering principles

- **Evaluate before claiming.** I keep metrics, ablations, failure cases, and test commands beside the code.
- **Separate evidence from prediction.** Evaluation harnesses freeze inputs and provenance before outcomes are available.
- **Design for rollback and audit.** Versioned state, deterministic artifacts, and explicit boundaries matter as much as model code.

## Ownership and attribution

I label repositories so authorship is unambiguous:

- **Original** — I own the implementation or project design.
- **Collaboration** — team work; I do not present it as solo authorship.
- **Learning / reference** — reproduction, coursework, or unchanged upstream code.

Collaboration includes the [Agentic Triage System for Emergency Departments](https://github.com/IDEAS-Incubator/Agentic_Triage_System_for_Emergency_Departments) and a private multi-agent trading research project. Learning artifacts include [nanoGPT Tiny Shakespeare](https://github.com/Pangqiang-Gary/nanoGPT-TinyShakespeare) and an unchanged [OpenLLMetry fork](https://github.com/Pangqiang-Gary/openllmetry).

## Current focus

Reliable RAG · Agent evaluation · LLM observability · Time-series ML · AI safety

