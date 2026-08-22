# Gary — Applied AI/ML Engineer

I build evaluation-first AI systems: retrieval and ranking pipelines, agent workflows, time-series risk models, and production-minded ML services. I care about reproducibility, provenance, failure analysis, and making model claims testable.

`Python` · `PyTorch` · `FastAPI` · `PostgreSQL` · `Docker` · `GitHub Actions`

## Selected engineering work

| Project | Provenance | What it demonstrates | Evidence |
|---|---|---|---|
| [Multi-Source RAG](https://github.com/Pangqiang-Gary/multi_source_rag) | Original build | Source-specific ingestion, BM25+dense retrieval, weighted RRF, cross-encoder reranking, and explicit conflict handling | [Ablation report](https://github.com/Pangqiang-Gary/multi_source_rag/blob/main/report.md): reranking improved source-overlap hit rate from 75.0% to 91.7% |
| [LogSentinel](https://github.com/Pangqiang-Gary/logsentinel) | Original build | Streaming log parsing, immutable model versions, atomic activation/rollback, tenant isolation, and online anomaly detection | [CI](https://github.com/Pangqiang-Gary/logsentinel/actions/workflows/ci.yml), 17 tests, 85% coverage, Loghub evaluation, Docker health check |
| [Qlib US Walk-Forward Study](https://github.com/Pangqiang-Gary/qlib-us-walk-forward) | Independent research workflow built on [Microsoft Qlib](https://github.com/microsoft/qlib) | US-equity data adaptation, explicit parameter changes, three expanding-window folds, transaction costs, and a fail-closed research gate | The gate returns `RESEARCH_ONLY`: mean IC 0.0069, mean Rank IC -0.0053; attractive backtest returns are rejected as insufficient evidence |
| [Native RAG](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG) | Team contribution | A deterministic Wiki compiler, a shared RAG Core facade, and a local FastAPI adapter in an organization repository | Three merged PRs: [compiler](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG/pull/1), [tested Core migration](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG/pull/4), and [API adapter](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG/pull/6) |
| [TradingAgents Blind Eval](https://github.com/Pangqiang-Gary/tradingagents-blind-eval) | Original tooling around [TradingAgents](https://github.com/TauricResearch/TradingAgents) | Forward-only evaluation controls without claiming authorship of the upstream agent system | Candidate freezing, clean-commit verification, isolated memory, sealed predictions, post-cutoff scoring |
| [Time-Series Risk Alert](https://github.com/Pangqiang-Gary/time-series-risk-alert) | Original research prototype | Chronological financial-ML evaluation with Transformer and classical baselines | Saved datasets, model checkpoint, calibration artifacts, threshold sweeps, and [v2 regime-analysis PR](https://github.com/Pangqiang-Gary/time-series-risk-alert/pull/2) |
| [MF-Structure Query Generator](https://github.com/Pangqiang-Gary/CS562-final) | Team coursework; my implementation is identified in history | Parsing declarative MF specifications into executable PostgreSQL query processors | My [generator and test-case commit](https://github.com/Pangqiang-Gary/CS562-final/commit/82edc7d009d23c098d8fa68efd576f3fab7ceb1d), six reproducible cases, and [extended-cases PR](https://github.com/Pangqiang-Gary/CS562-final/pull/2) |

## Engineering principles

- **Evaluate before claiming.** I keep metrics, ablations, failure cases, and test commands beside the code.
- **Separate evidence from prediction.** Evaluation harnesses freeze inputs and provenance before outcomes are available.
- **Design for rollback and audit.** Versioned state, deterministic artifacts, and explicit boundaries matter as much as model code.

## Ownership and attribution

I label repositories so authorship is unambiguous:

- **Original build** — I own the implementation or project design.
- **Upstream extension / research adaptation** — I name the original project, my changes, their purpose, and the evidence produced.
- **Team contribution** — I link merged pull requests or commits instead of presenting team work as solo authorship.
- **Learning / reference** — unchanged or minimally changed reproductions, tutorials, notes, and source checkouts; these are not presented as portfolio projects.

The public collaboration evidence above comes from merged work in [IDEAS-Incubator/LLM_Bootcamp_Native_RAG](https://github.com/IDEAS-Incubator/LLM_Bootcamp_Native_RAG). A private MATS research branch is an upstream-based OpenAI Agents SDK migration, not a from-scratch system. Learning artifacts include [nanoGPT Tiny Shakespeare](https://github.com/Pangqiang-Gary/nanoGPT-TinyShakespeare) and an unchanged [OpenLLMetry fork](https://github.com/Pangqiang-Gary/openllmetry).

## Current focus

Reliable RAG · Agent evaluation · LLM observability · Quantitative and time-series ML · AI safety

