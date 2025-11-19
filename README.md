# Custom GPT Prompt Systems

This repository showcases a set of structured, multi-stage prompt systems I use to design and evaluate LLM-powered assistants.

Each sub-project is written as Markdown specifications that can be dropped into:

- Custom GPT / assistant builders
- Internal tooling (prompt registries, eval harnesses)
- Prototypes for domain-specific AI assistants

Across the systems, I focus on:

- **Deterministic structure** — clear sections and ordered steps
- **Rubric-based reasoning** — explicit evaluation criteria
- **Safety boundaries** — what the assistant must not do
- **Auditability** — prompts are readable, editable, and easy to red-team

## What’s Included

- **Boxing Analysis System**
  - Full system prompt for structured fight breakdowns
  - Detailed rubric covering technical, physical, psychological, and stylistic factors
  - Example session showing how the model should reason and format outputs

- **Sigilizer**
  - Phase A: deterministic letter-reduction and number mapping rules
  - Phase B: structural mapping rules for tracing sigils over planetary kameas
  - Worked examples from intention phrase → numbers → structural path

- **Operations Assistants**
  - **Retreat Logistics Assistant** — planning framework for multi-day outdoor retreats
  - **Solar Sales Assistant** — pre-quote assistant for residential solar proposals

None of these systems are production deployments; they are patterns and templates that can be adapted to your own stack.

## How to Use

1. Pick the folder that matches your use case.
2. Use the `system_prompt` / prompt spec file as the base system message.
3. If available, plug the corresponding `rubric` into your eval or review process.
4. Use the example files as reference for tone, structure, and level of detail.
5. Customize constraints, domain details, and failure modes for your environment.

## About

These prompt systems represent how I think about:

- Turning fuzzy requirements into concrete assistant behaviors
- Making reasoning legible to non-technical stakeholders
- Bridging between real-world workflows and LLM capabilities

They are intentionally explicit and verbose so that trade-offs, edge cases, and safety choices are easy to inspect and iterate on.
