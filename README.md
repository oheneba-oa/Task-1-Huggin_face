# Project 1

This repository contains a Python environment for introductory work in data science, machine learning, and Hugging Face workflows. The environment includes tools for data analysis, notebook development, deep learning, and working with pretrained models and datasets.

## Topics

- Data science with NumPy, pandas, Matplotlib, and scikit-learn
- Interactive notebook development with Jupyter and IPython kernels
- Deep learning with PyTorch
- Hugging Face models and datasets
- Basic environment and dependency management

## Setup

Prerequisites: Python 3.11, Conda, Git, and `pip`.

Clone the repository:

```bash
git clone <your-repository-url>
cd Task-1-Huggin_face
```

Create the Conda environment:

```bash
conda create -n hf_project python=3.11 -y
```

Activate the environment:

```bash
conda activate hf_project
```

Upgrade `pip`:

```bash
python -m pip install --upgrade pip
```

Install the required packages:

```bash
python -m pip install -r requirements.txt
```

## Use Jupyter

After activating the environment, launch Jupyter Lab:

```bash
jupyter lab
```

When creating a notebook, select the Python kernel associated with the `hf_project` environment.

## Dependencies

The full dependency list is maintained in `requirements.txt`.

The environment includes the following main package groups:

### General Data Science

```text
numpy
pandas
matplotlib
scikit-learn
```

### Jupyter

```text
jupyter
ipykernel
```

### Hugging Face

```text
torch
transformers
datasets
huggingface_hub
accelerate
evaluate
```

## Additional Packages

The environment also includes packages that may be used in later practical work.

### Embeddings

```text
sentence-transformers
```

### Fine-Tuning

```text
peft
trl
```

### Retrieval-Augmented Generation

```text
langchain
langchain-community
chromadb
pypdf
```

### Cloud Execution

```text
modal
```

To install or update the environment whenever `requirements.txt` changes:

```bash
python -m pip install -r requirements.txt
```

## Environment Verification

Check the available Conda environments:

```bash
conda env list
```

Activate the project environment:

```bash
conda activate hf_project
```

Check the Python version:

```bash
python --version
```

Check the installed packages:

```bash
pip list
```

## Optional Services

Some services may require authentication before use.

- Hugging Face: use `huggingface-cli login` when accessing gated models, private repositories, or publishing resources.
- Modal: use `modal setup` before running cloud workloads.

## Repository Files

```text
Task-1-Huggin_face/
├── README.md
├── DOCUMENTATION.md
└── requirements.txt
```

- `README.md` contains the project setup and usage instructions.
- `DOCUMENTATION.md` contains the task documentation.
- `requirements.txt` contains the required Python packages.