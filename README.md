# Project 1

This repository contains a Python environment for introductory work in data science, machine learning, and Hugging Face workflows. The included dependencies support exploratory notebooks, Hugging Face models and datasets, embeddings, fine-tuning, retrieval-augmented generation (RAG), and Modal-based cloud execution.

## Topics

- Data science with NumPy, pandas, matplotlib, and scikit-learn
- Interactive notebook development with Jupyter and IPython kernels
- Model and dataset workflows with PyTorch and Hugging Face
- Sentence embeddings with Sentence Transformers
- Parameter-efficient fine-tuning with PEFT and TRL
- RAG applications with LangChain, ChromaDB, and PDF ingestion
- Cloud execution with Modal

## Setup

Prerequisites: Python 3.11, Conda, Git, and `pip`.

```bash
git clone <your-repository-url>
cd Task-1-Huggin_face
conda create -n hf_project python=3.11 -y
conda activate hf_project
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Use Jupyter

After activating the environment, launch Jupyter Lab:

```bash
jupyter lab
```

When creating a notebook, select the Python kernel associated with the `hf_project` environment.

## Dependencies

The full dependency list is maintained in `requirements.txt`. Install or update the environment whenever that file changes:

```bash
python -m pip install -r requirements.txt
```

The current dependencies are:

```text
# General Data Science
numpy
pandas
matplotlib
scikit-learn

# Jupyter
jupyter
ipykernel

# Hugging Face
torch
transformers
datasets
huggingface_hub
accelerate
evaluate

# Embeddings
sentence-transformers

# Fine-Tuning
peft
trl

# RAG
langchain
langchain-community
chromadb
pypdf

# Modal
modal
```

## Optional Services

Some workflows require their own authentication before use:

- Hugging Face: authenticate with `huggingface-cli login` when accessing gated models, private repositories, or publishing assets.
- Modal: authenticate with `modal setup` before running cloud functions.