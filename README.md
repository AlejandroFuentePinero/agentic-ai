# Agentic AI — Foundations from Scratch

The goal is to build a solid, intuitive understanding of how agents work — starting from the simplest possible examples and gradually progressing toward more advanced, multi-agent systems.

This repository supports two parallel goals:
1. **Learning the fundamentals of agent design** through clean, minimal Python examples.
2. **Building a portfolio-ready foundation** that will feed into more advanced Agentic AI projects.

---

## Project Structure

```
01_agentic_basics/
├── notebooks/
│   └── 00_agentic_ai_from_scratch.ipynb    # Core learning notebook
├── src/
│   ├── agents/
│   │   └── basic_agent.py                  # Minimal first agent
│   └── __init__.py
├── data/
│   ├── raw/
│   └── processed/
├── tests/
├── README.md
└── .gitignore
```

---

## Learning Objectives

### Phase 1 — Foundations (Pure Python)
- Understand what an "agent" is (tasks, memory, actions, tools).
- Build a minimal agent from scratch without any external frameworks.
- Learn how reasoning, tool use, and planning fit together.
- Create reusable components for future agent systems.

### Phase 2 — Mini-Projects
- Retrieval agent (queries structured data).
- Planning + worker agent pair.
- Analyst agent for simple ML workflows.
- Optional: Researcher + Writer system.

### Phase 3 — Portfolio Multi-Agent System
A full multi-agent application built with a modern framework (e.g., LangGraph).  
This project will evolve into a professional, public-facing AI system in a later repository.

---

## Why This Project Exists

Most Agentic AI courses start at an advanced level, assuming familiarity with:
- Agent workflows  
- Tool-calling patterns  
- Hierarchical routing  
- Memory/state handling  
- Framework-specific abstractions  

This project fills the missing **beginner-to-intermediate bridge**, building intuition and confidence before jumping into frameworks.

---

## Getting Started

Clone the repository, create a virtual environment, and install dependencies:

```bash
git clone <repo-url>
cd agentic-basics

# (Optional) Create a virtual environment
python3 -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
```

> *The project starts framework-free. Requirements will grow later as complexity increases.*

Open the main notebook:

```bash
jupyter lab notebooks/00_agentic_ai_from_scratch.ipynb
```

---

## Next Steps

The first implementation will be a **simple Python agent** that:

- Accepts a task  
- Reasonably decides what to do  
- Uses a simple “tool” (a Python function)  
- Returns structured output  

No frameworks.  
No complexity.  
Just the core logic of how an agent *thinks* and *acts*.

---

## Status

**Current phase:** Building the foundation (Phase 1)  
This will expand as I learn more about Agentic systems and build confidence in designing and implementing them.

---

## Future Expansion

Future versions of this project will include:
- LangChain / LangGraph agent flows  
- Tool-calling agents  
- Multi-agent collaboration  
- Planner → worker → evaluator systems  
- Domain-specific agents (DS, climate, job intelligence, research)

These will become separate repositories once the foundations are strong.

---

## License

MIT License (optional — will add later if needed)
