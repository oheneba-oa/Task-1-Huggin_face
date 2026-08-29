# Data Science and Hugging Face Environment Setup

## Overview

This repository contains my first environment setup for working with Python, data science tools, and the Hugging Face ecosystem.

The purpose of this task is to learn how to create a GitHub repository, set up an isolated Python environment, install the required packages, manage dependencies using a `requirements.txt` file, and document the setup clearly so that it can be recreated on another computer.

The environment created for this project is named `hf_project` and uses Python 3.11.

---

## Objectives

The main objectives of this task are to:

- Create a GitHub repository.
- Create an isolated Python environment.
- Install basic data science and machine learning packages.
- Install Hugging Face-related libraries.
- Store project dependencies in a `requirements.txt` file.
- Document the environment setup and installation process.
- Make the project setup easy to reproduce.

---

## Repository Structure

The repository contains the following files:

```text
Task-1-Huggin_face/
│
├── README.md
├── DOCUMENTATION.md
└── requirements.txt
```

### `README.md`

Provides a detailed description of the project, environment setup, packages used, and instructions for recreating the environment.

### `DOCUMENTATION.md`

Contains additional documentation about the steps followed during the task.

### `requirements.txt`

Contains the Python packages required for the project environment.

---

## Prerequisites

Before recreating this environment, the following should be available on the computer:

- Git
- Conda, Anaconda, or Miniconda
- Python support through Conda
- Visual Studio Code or another code editor
- Internet connection for downloading packages

GitHub Desktop may also be used to manage the repository.

---

## Development Environment

A separate Conda environment was created for this project.

Environment name:

```text
hf_project
```

Python version:

```text
Python 3.11
```

The environment was created using:

```bash
conda create -n hf_project python=3.11 -y
```

The environment can be activated using:

```bash
conda activate hf_project
```

The Python version can be checked using:

```bash
python --version
```

The available Conda environments can be viewed using:

```bash
conda env list
```

When the environment is active, `hf_project` should be marked as the current environment.

---

## Why a Separate Environment Was Used

A separate Python environment helps keep the packages for this project isolated from packages used by other projects.

Different projects may require different Python versions or different versions of the same library. Using an isolated environment reduces the chance of dependency conflicts and makes the setup easier to reproduce.

---

## Package Installation

The packages required for the project are stored in:

```text
requirements.txt
```

All dependencies can be installed using:

```bash
pip install -r requirements.txt
```

After installation, the installed packages can be checked using:

```bash
pip list
```

This helps confirm that the required libraries were installed inside the active `hf_project` environment.

---

## Main Packages

The environment contains packages for data analysis, visualization, machine learning, notebooks, deep learning, and Hugging Face workflows.

| Package | Purpose |
|---|---|
| NumPy | Numerical computing and array operations |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| Scikit-learn | Machine learning and preprocessing tools |
| Jupyter | Interactive notebook environment |
| PyTorch | Deep learning framework |
| Transformers | Access to pretrained Hugging Face Transformer models |
| Datasets | Access to datasets hosted on Hugging Face |
| Hugging Face Hub | Interaction with Hugging Face models and datasets |

---

## Package Descriptions

### NumPy

NumPy is used for numerical computing and working with arrays. It is commonly used as a foundation for data science and machine learning tasks.

### Pandas

Pandas is used for data manipulation and analysis. It provides structures such as DataFrames for working with tabular data.

### Matplotlib

Matplotlib is used for creating plots, charts, and other data visualizations.

### Scikit-learn

Scikit-learn provides tools for machine learning, including preprocessing, data splitting, model evaluation, and traditional machine learning algorithms.

### Jupyter

Jupyter provides an interactive environment for writing and running Python code in notebooks.

### PyTorch

PyTorch is a deep learning framework used for building and running neural networks. It is also commonly used as the underlying framework for Hugging Face Transformer models.

### Transformers

The Hugging Face `transformers` library provides access to pretrained Transformer models.

These models can be used for tasks such as:

- Text classification
- Sentiment analysis
- Question answering
- Text generation
- Translation
- Summarization

### Datasets

The Hugging Face `datasets` library provides tools for downloading, loading, and working with datasets available on the Hugging Face Hub.

### Hugging Face Hub

The `huggingface_hub` package provides tools for interacting with models, datasets, and other resources hosted on Hugging Face.

---

## Hugging Face Preparation

The environment includes the main packages required to begin working with Hugging Face.

These include:

```text
transformers
datasets
huggingface_hub
torch
```

At this stage, the main focus is on preparing the working environment correctly.

The installed Hugging Face packages will support future practical work involving pretrained models and datasets.

---

## Using `requirements.txt`

The `requirements.txt` file is used to record the Python dependencies needed for the project.

Instead of installing each package manually, all required packages can be installed using:

```bash
pip install -r requirements.txt
```

This improves reproducibility because another user can recreate the required package setup using the same file.

The actual Conda environment is not uploaded to GitHub. The `requirements.txt` file and setup instructions provide the information needed to recreate it.

---

## Environment Verification

The environment can be verified using the following commands.

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

The expected result is an active environment named `hf_project` running Python 3.11 with the required packages installed.

---

## Recreating the Environment

The project environment can be recreated on another computer by following these steps.

### Step 1: Clone the Repository

```bash
git clone <repository-url>
```

### Step 2: Move Into the Project Directory

```bash
cd Task-1-Huggin_face
```

### Step 3: Create the Conda Environment

```bash
conda create -n hf_project python=3.11 -y
```

### Step 4: Activate the Environment

```bash
conda activate hf_project
```

### Step 5: Install the Dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Verify the Setup

```bash
python --version
pip list
```

The environment should now be ready for use.

---

## Git and GitHub

Git is used for version control, while GitHub is used to store the repository online.

GitHub Desktop may also be used to manage commits and push changes to the online repository.

A typical Git workflow is:

```bash
git status
git add .
git commit -m "Update project setup"
git push origin main
```

This allows changes to the project files to be tracked and synchronized with GitHub.

---

## Tools Used

The following tools were used for this task:

- Python 3.11
- Conda
- Git
- GitHub
- GitHub Desktop
- Visual Studio Code
- Hugging Face libraries
- PyTorch
- Jupyter

---

## Expected Outcome

After completing the setup, the project should have:

- A working GitHub repository.
- A Conda environment named `hf_project`.
- Python 3.11 installed in the environment.
- The required data science and Hugging Face packages installed.
- A `requirements.txt` file containing the project dependencies.
- Clear documentation explaining how to recreate the setup.

---

## What I Learned

Through this task, I learned how to:

- Create and manage a GitHub repository.
- Create and activate a Conda environment.
- Install Python packages inside an isolated environment.
- Use a `requirements.txt` file.
- Verify installed packages.
- Prepare a Python environment for data science work.
- Install Hugging Face-related libraries.
- Document a project using Markdown.
- Make a project setup reproducible.

---

## Conclusion

This task introduced the basic process of setting up a Python development environment for data science and Hugging Face-related work.

A GitHub repository was created, a dedicated Conda environment named `hf_project` was prepared using Python 3.11, the required packages were installed, and the dependencies were recorded in a `requirements.txt` file.

The completed setup provides a clean foundation for future practical work involving data analysis, machine learning, Hugging Face models, and datasets.