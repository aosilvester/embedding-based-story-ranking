# embedding-based-story-ranking

An Python project for generating stories based on given topics useing a large language model (LLM) and ranking them based on semantic relevance using SentenceTransformers.

This project leverages GPU acceleration when available and is designed for reproducible setups with `uv`.

## Features

- Generate short, three-sentence stories about any topic.
- Rank generated stories based on semantic similarity to the input query.
- GPU-accelerated inference using PyTorch + Transformers.
- Clean, reproducible environment using `uv` and `pyproject.toml`.



## Requirements
 - Python 3.10 or 3.11
 - [UV package manager](https://docs.astral.sh/uv/getting-started/installation/)

## Installation
1. Clone the repository with: `git clone <repo> `
2. Sync dependencies: `cd embedding-based-story-ranking`, then `uv sync`
   - This will install the dependencies defined in `pyproject.toml`
   - Note: GPU acceleration is automatically used if available.
3. Run the main script with `py main.py`
