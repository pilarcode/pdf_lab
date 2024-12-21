
# Docling Lab
A project to explore the library docling. https://ds4sd.github.io/docling/
Docling parses documents and exports them to the desired format with ease and speed.

## Setup

**Step 1**. Navigate to the root directory of the repository and create a new conda environment for development:

```bash
conda create -n <your_env_name> python=3.12 -y && conda activate <your_env_name>
```

**Step 2**. Install poetry

```bash
conda install -c conda-forge poetry
```

**Step 3**. Install  ipywidgets

```bash
conda install -n <your_env_name> ipywidgets
```

**Step 4**. Install all the dependencies

```bash
poetry install --no-root
```

## Usage
Go to the notebook and select your environment to run the cells.