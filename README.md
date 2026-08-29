# Project 1

This repository contains a Python environment created for introductory hands-on work in data science, machine learning, and modern large language model workflows.

The environment includes packages for data analysis, notebook development, Hugging Face models and datasets, sentence embeddings, parameter-efficient fine-tuning, retrieval-augmented generation (RAG), and cloud execution with Modal.

## Topics

- Data analysis with NumPy and pandas
- Data visualization with Matplotlib
- Machine learning with scikit-learn
- Interactive notebook development with Jupyter
- Deep learning with PyTorch
- Hugging Face models and datasets
- Sentence embeddings with Sentence Transformers
- Parameter-efficient fine-tuning with PEFT and TRL
- Retrieval-Augmented Generation with LangChain and ChromaDB
- PDF processing with PyPDF
- Cloud execution with Modal

## Setup

### Prerequisites

Before setting up the project, make sure the following are available:

- Git
- Conda, Anaconda, or Miniconda
- Python 3.11
- `pip`
- Internet connection

Clone the repository:

```bash
git clone <your-repository-url>
```

Move into the project directory:

```bash
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

Install the required dependencies:

```bash
python -m pip install -r requirements.txt
```

## Use Jupyter

After activating the environment, launch Jupyter Lab:

```bash
jupyter lab
```

Jupyter Notebook can also be launched using:

```bash
jupyter notebook
```

When creating a notebook, select the Python kernel associated with the `hf_project` environment.

## Dependencies

The full dependency list is maintained in `requirements.txt`.

### General Data Science

```text
numpy
pandas
matplotlib
scikit-learn
```

These packages provide tools for numerical computing, data manipulation, visualization, and machine learning.

### Jupyter

```text
jupyter
ipykernel
```

These packages provide an interactive notebook environment for writing and running Python code.

### Hugging Face

```text
torch
transformers
datasets
huggingface_hub
accelerate
evaluate
```

These packages support deep learning, pretrained Transformer models, Hugging Face datasets, model execution, and evaluation.

### Embeddings

```text
sentence-transformers
```

Sentence Transformers provides tools for creating numerical vector representations of text that can be used for similarity search, semantic search, and other NLP tasks.

### Fine-Tuning

```text
peft
trl
```

PEFT and TRL provide tools that can be used for efficient fine-tuning and training of pretrained language models.

### Retrieval-Augmented Generation

```text
langchain
langchain-community
chromadb
pypdf
```

These packages support basic RAG workflows, including document loading, PDF processing, vector storage, retrieval, and integration with language models.

### Modal

```text
modal
```

Modal provides tools for running Python workloads in a cloud environment.

## requirements.txt

The `requirements.txt` file contains all packages required for the environment.

Whenever the file is updated, the environment can be updated using:

```bash
python -m pip install -r requirements.txt
```

This makes it easier to recreate the same working environment on another computer.

## Environment Verification

Check that the Conda environment exists:

```bash
conda env list
```

The `hf_project` environment should appear in the list.

Activate the environment:

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

These commands can be used to confirm that the environment and dependencies were installed successfully.

## Optional Services

Some tools may require authentication before they can be used.

### Hugging Face

Public models and datasets can usually be accessed without logging in.

For gated models, private repositories, or publishing resources to Hugging Face, authentication may be required:

```bash
huggingface-cli login
```

### Modal

Modal requires authentication before running cloud workloads:

```bash
modal setup
```

## Repository Files

```text
Task-1-Huggin_face/
├── README.md
├── DOCUMENTATION.md
└── requirements.txt
```

- `README.md` contains the project overview, setup instructions, and dependency information.
- `DOCUMENTATION.md` explains the steps followed during the setup task.
- `requirements.txt` contains the Python dependencies required for the environment.

## Purpose

The purpose of this task is to create a clean and reproducible Python environment for future practical work in Special Topics in Data Science.

At this stage, the focus is on environment setup, dependency installation, repository management, and documentation. The installed packages prepare the environment for later exercises involving data analysis, machine learning, Hugging Face models and datasets, embeddings, fine-tuning, RAG, and cloud-based execution.