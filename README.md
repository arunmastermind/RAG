# Production RAG & Agentic Systems Course Notebooks

A comprehensive repository of interactive Jupyter Notebooks covering LangChain, RAG (Retrieval-Augmented Generation), LangGraph, Multi-Agent Systems, Advanced RAG Techniques, and Production Engineering Patterns.

## 📁 Repository Structure

- `01_langchain_fundamentals/` — Core LangChain abstractions: Prompts, Output Parsers, Chains, LLM initializations, and Memory.
- `02_rag_basics/` — Document loaders, text splitters, embeddings, vector stores, and baseline RAG pipelines.
- `03_langgraph_fundamentals/` — Graph state, nodes, edges, conditional routing, loops/cycles, checkpointing, and human-in-the-loop workflows.
- `04_agents_and_multi_agents/` — Tool-calling agents, supervisor architectures, hierarchical routing, sub-agents, and parallel agents.
- `05_advanced_rag_techniques/` — GraphRAG, ColPali multimodal RAG, late chunking, agentic RAG, and contextual retrieval.
- `06_production_patterns/` — Cost optimization, error handling, security (PII/guardrails), LangSmith tracing, evaluation, and unit testing.

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- [`uv`](https://github.com/astral-sh/uv) fast Python package installer.

### 1. Environment Setup with `uv`

Create and activate a virtual environment using `uv`:

```bash
# Create virtual environment
uv venv

# Activate virtual environment
# On macOS / Linux:
source .venv/bin/activate
# On Windows:
# .venv\Scripts\activate
```

### 2. Install Dependencies

Install all required dependencies into the environment using `uv`:

```bash
uv pip install -r requirements.txt
```

### 3. Configure API Keys

Copy `.env.example` to `.env` and fill in your API keys:

```bash
cp .env.example .env
```

Edit `.env`:
```env
OPENAI_API_KEY=your_openai_api_key_here
ANTHROPIC_API_KEY=your_anthropic_api_key_here
```

### 4. Running the Notebooks

Launch JupyterLab or VS Code to run any notebook:

```bash
uv run jupyter lab
```

Each notebook is structured as a self-contained tutorial with modular cells:
1. **Imports & Setup**
2. **Component Definitions**
3. **Demo Function**
4. **Execution Cell**

## 🌐 Acknowledgements & Credits

This project and its Jupyter Notebook tutorials are inspired by and derived from the course work created by **[Paulo Dichone](https://github.com/pdichone)**.

Special thanks to Paulo Dichone for the original course source repositories:
- [production-course-main-code](https://github.com/pdichone/production-course-main-code)
- [fcc-production-rag-part-6](https://github.com/pdichone/fcc-production-rag-part-6)