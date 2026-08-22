# Claude Agentic AI Architecture

> A continuously evolving architecture notebook covering Claude, agentic systems, tool use, orchestration, MCP, and enterprise AI design patterns.

I created this repository while preparing for the **Claude Certified Architect – Foundations** certification.

Rather than keeping certification notes only as handwritten material, I am converting each topic into a practical architecture reference focused on three questions:

**How does it work? Why does it matter? How would I apply it in a real system?**

---

## Current Learning Progress

| Domain            | Focus Area                           | Status             |
| ----------------- | ------------------------------------ | ------------------ |
| Domain 1          | Agentic Architecture & Orchestration | 🟢 Notes Published |
| Domain 2          | Tools, MCP & Claude Code             | 🟢 Notes Published |
| Domain 3          | In Progress                          | ⏳ Learning         |
| Remaining Domains | To be added as I progress            | ⏳ Planned          |

> This repository grows alongside my certification preparation. Topics are added after I study, validate, and summarize them.

---

## Current Knowledge Map

### Domain 1 — Agentic Architecture & Orchestration

Topics currently covered:

* Chatbot vs agent
* Agentic loop
* Tool-use lifecycle
* Loop termination
* `stop_reason`
* Coordinator and subagent architecture
* Task decomposition
* Delegation and aggregation
* Context passing
* Prompt chaining
* Dynamic decomposition
* Human-in-the-loop
* Guidance vs deterministic enforcement
* Agent SDK hooks
* Sessions and forking
* Human handoff patterns

➡️ [Explore Domain 1](docs/01-agentic-architecture-and-orchestration/)

---

### Domain 2 — Tools, MCP & Claude Code

Topics currently covered:

* What tools are
* Tool definitions
* Tool descriptions and schemas
* Tool selection
* `tool_choice`
* Tool distribution
* Structured tool errors
* MCP fundamentals
* MCP tools vs resources
* MCP server connectivity
* Configuration scopes
* Claude Code built-in tools
* Grep vs Glob
* Read / Write / Edit / Bash
* Secret handling

➡️ [Explore Domain 2](docs/02-tools-mcp-and-claude-code/)

---

## How I Structure My Notes

For important concepts I try to capture:

```text
Concept
   ↓
Simple Mental Model
   ↓
How Claude Uses It
   ↓
Architecture Flow
   ↓
Real-World Example
   ↓
Design Considerations
   ↓
Exam Takeaway
```

The objective is not simply to memorize terminology but to understand the underlying architecture.

---

## Repository Philosophy

### Learn → Understand → Architect → Document

Certification preparation is the starting point.

The longer-term objective of this repository is to build a practical reference for designing:

* agentic applications
* tool-enabled AI systems
* multi-agent workflows
* human-in-the-loop processes
* MCP integrations
* governed enterprise AI solutions

---

## Quick Revision

Each completed domain contains a `quick-revision.md` designed for short revision sessions before the certification exam.

---

## Disclaimer

These are personal learning and architecture notes created during my certification preparation. They are not official Anthropic certification documentation.

For production implementations and exam preparation, always validate concepts against current Anthropic documentation.
