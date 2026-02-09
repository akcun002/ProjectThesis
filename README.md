### Prerequisites

[**uv**](https://docs.astral.sh/uv/getting-started/installation/) needs to be installed.

---
### Installation 

Create and synchronize the environment
```bash
    uv sync
```

Register the Jupyter kernel
```bash
    uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=projectthesis
```

Launch JupyterLab
```bash
    uv run --with jupyter jupyter lab
```
