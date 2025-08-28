# Project Setup

## Setup with [uv](https://github.com/astral-sh/uv)

1. **Initialize and install packages**

   ```bash
   uv venv
   uv sync
   source .venv/bin/activate
   ```

2. **Create IPython Kernel**

   This registers a named Jupyter kernel for this environment:

   ```bash
   uv run ipython kernel install --user --env VIRTUAL_ENV=$(pwd)/.venv --name=fastbook
   ```
