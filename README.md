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

---

I'm a **GenAI power-user and prompt/agent engineer** — a tasteful "vibe coder" who ships real, working AI tools with [Claude Code](https://claude.com/claude-code). I'm not a career software engineer and I don't pretend to be one; my edge is **systems thinking, prompt rigor, and taste** — designing agent loops, retrieval pipelines, and human-in-the-loop workflows that actually run.

Everything here is a **personal, AI-assisted project**. The code is real and runnable, the sample data is synthetic, and the READMEs are honest about what's a demo versus a system.

## 🛠️ What I build

**Flagships**

| Project | What it is |
| --- | --- |
| **[operations-knowledge-copilot](https://github.com/schuligan/operations-knowledge-copilot)** ⭐ | A retrieval-augmented team knowledge copilot: ingest docs → embed → **cited** Q&A → **human-reviewed write-back** with an audit log. Runs fully offline in mock mode; Claude-powered with a key. |
| **[prompt-library](https://github.com/schuligan/prompt-library)** ⭐ | A versioned library of system prompts and patterns with a **tiny eval harness** that A/B-scores prompt variants against golden inputs. Prompt engineering with regression tests. |

**Agents &amp; automation**

| Project | What it is |
| --- | --- |
| **[personal-jarvis](https://github.com/schuligan/personal-jarvis)** | A CLI personal assistant with an explicit **plan → tool-call → observe** agent loop, guardrails, and an MCP-style tool layer (calendar, tasks, daily brief, search). |
| **[support-ticket-router](https://github.com/schuligan/support-ticket-router)** | Inbound email/Slack → triage → ticket → **confidence-gated KB auto-resolution** or human handoff with SLA escalation. |
| **[doc-triage-hitl](https://github.com/schuligan/doc-triage-hitl)** | LLM document triage with a **human-in-the-loop queue**: classify into a taxonomy, auto-handle routine items, route exceptions to a human, full audit log. |
| **[agentic-pipeline-starter](https://github.com/schuligan/agentic-pipeline-starter)** | A clone-and-extend **multi-agent scaffold**: orchestrator + specialists, MCP tool wiring, shared memory, safety gates, JSONL run tracing. |

**Knowledge &amp; tooling**

| Project | What it is |
| --- | --- |
| **[second-brain-os](https://github.com/schuligan/second-brain-os)** | A Markdown/Obsidian **second brain** with agentic capture: auto-tag, suggest `[[wikilinks]]`, embeddings search, and daily-note synthesis (approval-gated writes). |
| **[claude-skills-collection](https://github.com/schuligan/claude-skills-collection)** | Reusable **Claude Code skills** for planning, QA, process-flow diagrams, status reports, and comms — drop-in `SKILL.md` files. |

<sub>Every repo runs offline in a labeled mock mode (no API key needed), ships with tests, an implementation plan, and a Mermaid architecture diagram, and uses only synthetic sample data.</sub>

## 🧰 Stack &amp; signals

- **Models:** Anthropic Claude (Opus / Sonnet / Haiku), provider-agnostic config where it's cheap to add
- **Patterns:** RAG (Chroma / pgvector), agentic orchestration, **MCP** tool layers, structured outputs, human-in-the-loop, eval/regression harnesses
- **Languages &amp; tools:** Python, TypeScript where a UI earns it, Mermaid for architecture, synthetic data for safe demos

## 📫 Elsewhere

- 🎛️ YouTube — [Beatoid](https://www.youtube.com/@Beatoid) (generative / creative audio)
- 💼 LinkedIn — <!-- TODO: add your LinkedIn URL here -->
- 🐙 GitHub — you're looking at it

<sub>Built with Claude Code. AI-assisted, personal projects — claims of capability, not enterprise scale.</sub>
