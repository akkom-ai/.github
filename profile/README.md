## akkom-ai

**Open infrastructure for AI-native software and correctness-first AI systems.**

akkom-ai is a technical foundation for building LLM-driven systems that can reason, propose code changes, run tools, and operate inside real software projects — under explicit human-defined control, approval, and audit.

We focus on the missing layer between models and reality: orchestration, memory, patching, validation, execution, and traceability.

akkom-ai prioritizes correctness, auditability, and reversibility over speed or unrestricted autonomy.

## What lives here

Projects under **akkom-ai** are designed to work together as a coherent stack:

| Layer              | Purpose                                             |
| ------------------ | --------------------------------------------------- |
| **Orchestration**  | Coordinate runs, context, tool calls, and decisions |
| **State & Memory** | Track what the model knows, changed, and attempted  |
| **Patching**       | Apply and validate edits to real files              |
| **Execution**      | Run commands, tests, and validations                |
| **Audit**          | Record everything that happened                     |

This is infrastructure for:

* AI software engineers
* autonomous agents
* game AI
* build bots
* research systems
* and anything that needs **models that act, not just talk**

## Flagship projects

### [**llm-orchestrator**](https://github.com/akkom-ai/llm-orchestrator)

The core runtime for AI-driven workflows.

It handles:

* runs
* context
* patch application
* tool execution
* validation
* audit trails

This is the “engine room” of akkom-ai.

### [**git-checkpoint**](https://github.com/akkom-ai/git-checkpoint)

A safety layer for AI-driven code modification.

It provides:

* snapshots
* diffs
* rollback
* history
* controlled patch application

Designed so that models can change code **without destroying it**.

## Design philosophy

akkom-ai follows three rules:

1. **Models must be observable**
   Every action must be logged, inspectable, and reversible.

2. **Patches must be safe**
   No blind writes. Everything is diffed, validated, and merge-aware.

3. **Agents must be grounded**
   Real files, real repos, real tools, real tests — no hallucinated state.

## Not a framework. A foundation.

akkom-ai is not:

* a chatbot
* a prompt library
* a thin wrapper around an API

It is the **substrate** on which real autonomous systems can be built.

## Status

This organization is under active development.
Early repositories are experimental but moving fast toward a cohesive stack.

If you are building:

* autonomous coding agents
* game AI
* research agents
* or LLM-powered infrastructure

you are in the right place.
