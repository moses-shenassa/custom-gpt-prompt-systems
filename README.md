# Custom GPT Prompt Systems

A collection of structured, multi-stage prompt systems designed for **Custom GPT workflows**, applied reasoning tasks, and domain-specific assistants.

Each system is written as a set of Markdown specifications that can be used:

- As **system prompts** in Custom GPT builders
- As part of an **evaluation / red-teaming harness**
- As reference patterns for designing new LLM workflows

## What’s Included

Each folder typically contains:

- A **system prompt** (core instructions + behavior rules)
- A **rubric** or structural framework for reasoning
- **Examples** showing how the model should respond
- Safety & capability boundaries
- Notes on limitations and failure modes

These examples demonstrate how I design prompts for:

- **Predictive reasoning** – structured, rubric-based analysis of boxing matchups  
- **Symbolic / transformative workflows** – deterministic pipelines for transforming text into symbolic outputs  
- **Operations assistants** – domain-specific helpers for logistics and sales

None of these systems are production deployments; they are **patterns and prototypes** that can be adapted to specific use cases.

## Repository Structure

- `boxing-analysis-system/`  
  Structured fight-analysis system with a detailed rubric and example session.

- `sigilizer/`  
  Two-phase symbolic transformation workflow (Phase A: text reduction, Phase B: structural mapping), with worked examples.

- `operations-assistants/`  
  - `retreat_logistics_assistant.md` – prompt system for planning and stress-testing outdoor retreats.  
  - `solar_sales_assistant.md` – prompt system that helps organize inputs for solar sales proposals.

## How to Use These Files

- In a **Custom GPT / assistant builder**, paste the relevant system prompt and rubric into the system message or tool spec.  
- For **evaluation**, use the rubric files to define grading dimensions and check outputs for completeness.  
- For **design work**, treat these systems as blueprints: copy, adapt, or extend them to match your domain and constraints.

These prompt systems are deliberately explicit and verbose to make reasoning paths and tradeoffs easy to audit.
