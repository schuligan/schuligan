<h1 align="center">GenAI builder &amp; prompt/agent engineer</h1>
<p align="center"><em>I turn LLMs into working operating systems — real tools that ingest, reason, and act, with a human in the loop where it counts.</em></p>

<p align="center">
  <img alt="Claude" src="https://img.shields.io/badge/Claude-Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white">
  <img alt="MCP" src="https://img.shields.io/badge/MCP-Model_Context_Protocol-1f6feb?style=flat-square">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.11+-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="RAG" src="https://img.shields.io/badge/RAG-Chroma_%2F_pgvector-2ea043?style=flat-square">
  <img alt="Agents" src="https://img.shields.io/badge/Agents-orchestration_%2B_tool_use-8957e5?style=flat-square">
  <img alt="Prompt Engineering" src="https://img.shields.io/badge/Prompt_Engineering-evals_%26_regression-db61a2?style=flat-square">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/prateekjha6/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://www.youtube.com/@Beatoid"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-Beatoid-FF0000?style=flat-square&logo=youtube&logoColor=white"></a>
</p>

---

I'm a **GenAI power-user and prompt/agent engineer** who ships real, working AI tools with [Claude Code](https://claude.com/claude-code). I'm not a career software engineer and I don't pretend to be — my edge is **systems thinking, prompt rigor, and taste**: designing agent loops, retrieval pipelines, and human-in-the-loop workflows that actually run.

> **Start here →** [operations-knowledge-copilot](https://github.com/schuligan/operations-knowledge-copilot) (RAG + cited answers + human-reviewed write-back) and [prompt-library](https://github.com/schuligan/prompt-library) (prompt engineering with an eval harness). They're the fastest read on how I think.

<sub>📦 11 open-source projects · ▶️ every one runs offline with no API key (labeled mock mode) · ✅ tests, a Mermaid architecture diagram, and an implementation plan in each · 🔒 synthetic data only.</sub>

## 🛠️ What I build

**Flagships**

| Project | What it is |
| --- | --- |
| **[operations-knowledge-copilot](https://github.com/schuligan/operations-knowledge-copilot)** ⭐ | A retrieval-augmented team knowledge copilot: ingest docs → embed → **cited** Q&A → **human-reviewed write-back** with an audit log. Runs fully offline in mock mode; Claude-powered with a key. |
| **[prompt-library](https://github.com/schuligan/prompt-library)** ⭐ | A versioned library of system prompts and patterns with a **tiny eval harness** that A/B-scores prompt variants against golden inputs, plus a **prompt-improver** (diagnose → rewrite → explain any weak prompt). Prompt engineering with regression tests. |

**Agents &amp; automation**

| Project | What it is |
| --- | --- |
| **[personal-jarvis](https://github.com/schuligan/personal-jarvis)** | A CLI personal assistant with an explicit **plan → tool-call → observe** agent loop, guardrails, and an MCP-style tool layer (calendar, tasks, daily brief, search). |
| **[support-ticket-router](https://github.com/schuligan/support-ticket-router)** | Inbound email/Slack → triage → ticket → **confidence-gated KB auto-resolution** or human handoff with SLA escalation. |
| **[doc-triage-hitl](https://github.com/schuligan/doc-triage-hitl)** | LLM document triage with a **human-in-the-loop queue**: classify into a taxonomy, auto-handle routine items, route exceptions to a human, full audit log. |
| **[agentic-pipeline-starter](https://github.com/schuligan/agentic-pipeline-starter)** | A clone-and-extend **multi-agent scaffold**: orchestrator + specialists, MCP tool wiring, shared memory, safety gates, JSONL run tracing. |

**Infra &amp; engineering**

| Project | What it is |
| --- | --- |
| **[model-router](https://github.com/schuligan/model-router)** | Pick the right LLM per task: score task signals against a model registry (Claude, GLM, Llama, DeepSeek, GPT) → **select or propose** a model. Provider-agnostic, cost-aware. |
| **[nightshift](https://github.com/schuligan/nightshift)** | A constrained **autonomous agent-loop harness** — run an agent unsupervised inside hard guardrails: allow-list, max iterations, cost cap, time window, dry-run, audit log. |
| **[agentic-test-runner](https://github.com/schuligan/agentic-test-runner)** | Spec → **generated test cases** → tracker tickets → agents execute → report. Provider-agnostic tracker with a Linear adapter. |

**Knowledge &amp; tooling**

| Project | What it is |
| --- | --- |
| **[second-brain-os](https://github.com/schuligan/second-brain-os)** | A Markdown/Obsidian **second brain** with agentic capture: auto-tag, suggest `[[wikilinks]]`, embeddings search, and daily-note synthesis (approval-gated writes). |
| **[claude-skills-collection](https://github.com/schuligan/claude-skills-collection)** | 12 reusable **Claude Code skills** — planning, QA, BRD authoring, process-flow diagrams, Figma mockups, Notion templating, tracker QA, and more. Drop-in `SKILL.md` files. |

## 🧰 How I work

- **Models:** Anthropic Claude (Opus / Sonnet / Haiku), with provider-agnostic config and a [router](https://github.com/schuligan/model-router) that reaches for open models (GLM, Llama, DeepSeek) when they're the right call.
- **Patterns:** RAG (Chroma / pgvector), agentic orchestration, **MCP** tool layers, structured outputs, **human-in-the-loop** gates, and **eval / regression** harnesses for prompts.
- **Defaults:** offline-first (mock mode, no key needed to try anything), guardrails before autonomy, audit logs over trust, synthetic data over real, honest READMEs over hype.

## 📫 Elsewhere

- 💼 LinkedIn — **[in/prateekjha6](https://www.linkedin.com/in/prateekjha6/)**
- 🎛️ YouTube — **[Beatoid](https://www.youtube.com/@Beatoid)** (generative / creative audio)
- 🐙 GitHub — you're looking at it

<sub>Built with Claude Code. AI-assisted, personal projects — claims of capability, not enterprise scale.</sub>
