# Special Project 1

This repository contains a Python environment created for introductory practical work in data science, machine learning, and Hugging Face workflows. The environment includes commonly used packages for data analysis, notebook development, deep learning, and working with pretrained models and datasets.

## Topics

- Data analysis with NumPy and pandas
- Data visualization with Matplotlib
- Machine learning with scikit-learn
- Interactive notebook development with Jupyter
- Deep learning with PyTorch
- Model and dataset workflows with Hugging Face
- Preparation for future practical work involving modern AI tools

## Setup

### Prerequisites

- Python 3.11
- Conda, Anaconda, or Miniconda
- Git
- `pip`

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

Install the required dependencies:

```bash
python -m pip install -r requirements.txt
```

## Use Jupyter

After activating the environment, launch Jupyter Lab:

```bash
jupyter lab
```

You can also start the classic Jupyter Notebook interface using:

```bash
jupyter notebook
```

When creating a notebook, select the Python kernel associated with the `hf_project` environment.

## Dependencies

The full dependency list is maintained in `requirements.txt`.

The main groups of packages included in the environment are:

### General Data Science

```text
numpy
pandas
matplotlib
scikit-learn
```

These packages support numerical computing, data manipulation, visualization, and basic machine learning.

### Jupyter

```text
jupyter
ipykernel
```

These packages provide an interactive notebook environment for writing and running Python code.

### Deep Learning and Hugging Face

```text
torch
transformers
datasets
huggingface_hub
```

These packages support deep learning, pretrained Transformer models, Hugging Face datasets, and interaction with the Hugging Face Hub.

To install or update the environment whenever `requirements.txt` changes:

```bash
python -m pip install -r requirements.txt
```

## Environment Verification

To confirm that the environment was created successfully:

```bash
conda env list
```

The `hf_project` environment should appear in the list.

Activate it:

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

Some Hugging Face resources may require authentication.

For gated models, private repositories, or publishing assets, authenticate using:

```bash
huggingface-cli login
```

Public Hugging Face models and datasets can usually be accessed without logging in.

## Repository Files

```text
Task-1-Huggin_face/
├── README.md
├── DOCUMENTATION.md
└── requirements.txt
```

- `README.md` contains the project setup and usage instructions.
- `DOCUMENTATION.md` records the steps followed during the task.
- `requirements.txt` contains the Python dependencies for the environment.