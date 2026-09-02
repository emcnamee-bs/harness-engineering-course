# Harness Engineering

A free, build-first curriculum for learning **harness engineering** — the loop, tools, context
management, permissions, sub-agent orchestration, memory, and evals that turn a raw LLM into a
working autonomous agent (the same shape of system as Claude Code, Codex CLI, or SWE-agent).

> **Snapshot accurate as of September 1, 2026.** This is a fast-moving field. Treat the named
> tools, frameworks, and links in this course as a starting point, not a permanent map — the
> architectural lessons underneath them (loops, tool design, context budgets, permission gating,
> evals) age much slower than any specific product name.

**[Read the course →](https://emcnamee-bs.github.io/harness-engineering-course/)**

## What it is

Eleven modules, each shipping a working increment of the *same* program — no throwaway snippets.
By the capstone you'll have built a small, real coding agent and scored it against real bugs with
your own eval harness, not just read about how one works.

Every module gives you:
- **What** — the mechanism, concretely (not just the name of it)
- **Why** — why this exists, grounded in a real incident or a real production system
- **Build** — a hands-on exercise with a skeleton, not a full solution — you write it
- **Verify** — a concrete check that tells you whether it actually worked

## Modules

| # | Module |
|---|---|
| 00 | Orientation — what a harness actually is |
| 01 | The bare loop |
| 02 | Tool interfaces (the agent-computer interface) |
| 03 | Eval harness — build this early |
| 04 | Context management (compaction, caching, just-in-time retrieval) |
| 05 | Permissions & sandboxing |
| 06 | Sub-agent fan-out |
| 07 | Persistent memory |
| 08 | Tool ecosystem via MCP |
| 09 | Production hardening (idempotency, circuit breakers, cost ceilings) |
| 10 | Capstone — a coding agent in a box |

A "Field Notes" section at the end points to real open-source systems worth reading alongside
specific modules (Aider's repo-map, SWE-agent's ACI docs, OpenHands' event-stream architecture,
Anthropic's sandbox-runtime, UK AISI's Inspect AI) plus a short core-reading list in build order.

## Using it

Open `index.html` (or the [hosted version](https://emcnamee-bs.github.io/harness-engineering-course/))
and work top to bottom — later modules assume the code from earlier ones exists. Progress
checkboxes persist in your browser via `localStorage`; nothing is sent anywhere.

## Sources

Built from a research pass across Anthropic's and OpenAI's engineering blogs, Martin Fowler's
site (Birgitta Böckeler's harness-engineering framing), Princeton's SWE-agent project, OpenHands,
and UK AISI's Inspect AI, among others. Full citations are in the course's "Field Notes" section.

---

*Generated with the help of Claude Code.*
