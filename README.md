# Agentic AI Engineering

This is the code repository for *Agentic AI Engineering*, published by Packt.

The book builds production agent systems with the OpenAI Agents SDK: a reference architecture, tools and MCP, memory, orchestration and model routing, multi-agent systems and A2A, evaluation, security and guardrails, observability and cost, deployment, and operations.

## What you need

- Python 3.10 or later
- An OpenAI API key with a payment method attached
- The packages pinned in each chapter's `requirements.txt`

Every chapter is a self-contained project. Create a virtual environment inside the chapter directory, install its requirements, export `OPENAI_API_KEY`, and follow the chapter's `README.md`. The examples call the real API; there are no offline or mock modes.

## Chapters

| Folder | Chapter |
| --- | --- |
| `Chapter02` | From Zero to Agent: Building with the OpenAI Agents SDK |
| `Chapter03` | Giving Agents Hands: Tools, Function Calling, and MCP |
| `Chapter04` | What Agents Remember: Memory, Knowledge, and Context |
| `Chapter05` | Who Runs the Show: Orchestration Patterns and Model Routing |
| `Chapter06` | Agents That Collaborate: Multi-Agent Systems and A2A |
| `Chapter07` | Does It Actually Work? Evaluating and Testing Agent Systems |
| `Chapter08` | Keeping Agents in Line: Security, Guardrails, and Governance |
| `Chapter09` | Watching the Money and the Machines: Observability, Cost, and the ROI Case |
| `Chapter10` | Shipping the Thing: Deployment Patterns and Infrastructure |
| `Chapter11` | After the Launch: Operating, Evolving, and Surviving the Agents You Have Built |

Chapter 1 is conceptual and has no code.

## A note on model names

Model names change faster than books do. Each chapter keeps its model strings in a single registry module (for example `claims_pipeline/settings.py` in Chapter 2). When a model is retired, update the registry and nothing else.
