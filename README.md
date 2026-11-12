# Robert Aaron Graham | Applied AI portfolio

Selected work in AI systems engineering, local AI applications, and compute infrastructure.

## Try a project

- **In your browser:** Ask “active listening” for a cited activity, then “weather forecast” to see the demo abstain. [AMIE live demo](https://r-aaron-graham.github.io/Amie-Chatbot-Frontend/)
- **In your terminal:** Run the retrieval benchmark below to compare citation accuracy and context size on a synthetic dataset.
- **For agent governance:** Run an offline demo with a cited answer, a policy denial, and an escalation. [Agent Trust Control Plane quickstart](https://github.com/r-aaron-graham/agent-trust-control-plane#run-the-five-minute-reviewer-demo)

## Start here

Run the Adaptive RAG benchmark with Python 3.11 or later. It uses a synthetic dataset and the Python standard library.

```bash
git clone https://github.com/r-aaron-graham/adaptive-rag-efficiency-lab.git
cd adaptive-rag-efficiency-lab
python -m unittest -q
python benchmark.py
```

The report compares exact citations, abstention, context size, and retrieval latency. In the bundled dataset, the original shortcut scored 9/10 on exact citations. The guarded shortcut and fixed baseline scored 10/10. [Benchmark data and results](https://github.com/r-aaron-graham/adaptive-rag-efficiency-lab#guarded-shortcut-experiment)

## Skills demonstrated

| Skill | Evidence you can inspect |
| --- | --- |
| Python APIs and model routing | [FastAPI gateway and HTTP smoke test](https://github.com/r-aaron-graham/llm-gateway-and-model-router/pull/1) · [Cost and latency selection](https://github.com/r-aaron-graham/cost-aware-model-serving/pull/1) |
| Retrieval evaluation and agent governance | [Policy, trace, and review demo](https://github.com/r-aaron-graham/agent-trust-control-plane/pull/2) · [Evaluation CI and synthetic benchmark](https://github.com/r-aaron-graham/agent-trust-control-plan-evals/pull/2) · [Lexical evaluation baseline](https://github.com/r-aaron-graham/hallucination-detection-lab/pull/1) |
| Prompt lifecycle and agent release controls | [SQLite prompt versioning](https://github.com/r-aaron-graham/prompt-registry-and-versioning/pull/1) · [Agent Release Gate test suite](https://github.com/r-aaron-graham/agent-release-gate-v0.3.0#running-tests) |
| Data quality and reproducible fixtures | [Contract validation and drift](https://github.com/r-aaron-graham/data-contracts-and-quality-engine/pull/1) · [CSV generation and dataset metadata](https://github.com/r-aaron-graham/synthetic-data-generator-with-governance/pull/1) |
| Compute infrastructure modeling | [Site scoring](https://github.com/r-aaron-graham/data-center-site-selection-engine/pull/1) · [Power price scheduling](https://github.com/r-aaron-graham/power-and-load-optimizer/pull/1) · [Capacity simulation](https://github.com/r-aaron-graham/modular-data-center-digital-twin/pull/1) · [Carbon-aware routing simulation](https://github.com/r-aaron-graham/carbon-aware-workload-orchestrator/pull/1) |

## Project demos

| Project | What to try | Evidence |
| --- | --- | --- |
| Agent Trust Control Plane | Run the offline demo to see a cited answer, a policy denial, and an escalation for review. | [Quickstart](https://github.com/r-aaron-graham/agent-trust-control-plane/blob/main/README.md#run-the-five-minute-reviewer-demo) · [Evaluation harness](https://github.com/r-aaron-graham/agent-trust-control-plan-evals#run-benchmarks) |
| Adaptive RAG Efficiency Lab | Compare fixed retrieval with the original and guarded single-identifier shortcuts on synthetic runbooks. | [Released baseline](https://github.com/r-aaron-graham/adaptive-rag-efficiency-lab/releases/tag/v0.1.0) · [Guarded experiment and results](https://github.com/r-aaron-graham/adaptive-rag-efficiency-lab#guarded-shortcut-experiment) |
| Prompt Registry | Add a prompt, create a revision, then retrieve both versions by name from SQLite. | [CLI walkthrough](https://github.com/r-aaron-graham/prompt-registry-and-versioning#version-a-prompt) |
| Agent Release Gate | Use the sample requests to inspect clarification, denial, and review outcomes. | [Quickstart](https://github.com/r-aaron-graham/agent-release-gate-v0.3.0#quick-start) · [Sample requests](https://github.com/r-aaron-graham/agent-release-gate-v0.3.0#step-by-step-beginner-test) |
| RadCopilot Local | Run a synthetic smoke test that serves the UI and exercises the Ollama adapter with a fixture model. | [Reviewer demo](https://github.com/r-aaron-graham/RAD_copilot_test_2.1#reviewer-demo) · [Model code index](https://github.com/r-aaron-graham/RadCopilot-LLM-Models) |
| Mine-water cooling simulation | Compare FIFO and cooling-aware compute scheduling over five synthetic hours. The results are modeled. | [Scheduler and assumptions](https://github.com/r-aaron-graham/geothermal-mine-water-cooling-sim#compute-scheduling-experiment--v010-local-build) · [Raw scenario results](https://github.com/r-aaron-graham/geothermal-mine-water-cooling-sim/blob/main/scheduler-results-v1.json) |
| AMIE | Try “active listening” for a cited classroom activity or “weather forecast” to see the browser demo abstain. The demo uses fictional cards and runs separately from the Python experiments. | [Live demo](https://r-aaron-graham.github.io/Amie-Chatbot-Frontend/) · [Frontend source](https://github.com/r-aaron-graham/Amie-Chatbot-Frontend) · [Python backend experiments](https://github.com/r-aaron-graham/AmieAIBackend) |

## Follow the work

[Follow Robert Aaron Graham on GitHub](https://github.com/r-aaron-graham) for new AI engineering projects. Use the linked repository’s Issues tab to report a reproducible problem or suggest a synthetic example.
