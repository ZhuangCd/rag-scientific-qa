# RAG Scientific QA

A Retrieval-Augmented Generation (RAG) system for answering questions based on scientific literature using the TFDS *Scientific Papers* Dataset.

The project implements:
- a **Simple (Naive) RAG** baseline
- an **Advanced RAG** extension
- a **qualitative comparison** against a general-purpose chatbot



## UV Package Manager Setup

This project uses [UV](https://docs.astral.sh/uv/) for Python package management.

### Initial Setup (if starting fresh)

```bash
# Initialize a new UV project
uv init

# Create virtual environment
uv venv
```

### Adding Dependencies

```bash
# Add a library
uv add tensorflow
```

### After Cloning the Repository

If you pulled/cloned this repo, run the following to install all dependencies:

```bash
# Sync all dependencies from pyproject.toml
uv sync
```
