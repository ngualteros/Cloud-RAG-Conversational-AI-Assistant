
# Cloud RAG — Conversational AI Assistant

## Overview

This repository contains an academic notebook exploring the development of a cloud-based conversational AI assistant using Retrieval-Augmented Generation (RAG).

The notebook is associated with the Cloud Computing Tools for Artificial Intelligence coursework of the Master's in Artificial Intelligence at Universidad Internacional de La Rioja (UNIR).

The project focuses on understanding how retrieval mechanisms and generative AI can be combined to build conversational applications that use external information sources.

## Project Objectives

The learning objectives include:

- Understanding Retrieval-Augmented Generation.
- Exploring cloud-based AI capabilities.
- Examining the relationship between information retrieval and text generation.
- Understanding how external context can support LLM-generated answers.
- Exploring the architecture of conversational AI assistants.

## Technologies

- Python
- Jupyter Notebook
- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Generative AI
- Cloud Computing

The exact cloud provider, SDKs, retrieval services, and language models used in the notebook will be documented after code verification.

## What Is RAG?

Retrieval-Augmented Generation is an architecture that combines information retrieval with language model generation.

A typical RAG workflow includes:

1. Receive a user question.
2. Retrieve relevant information from an external knowledge source.
3. Provide the retrieved information as context to a language model.
4. Generate an answer using the supplied context.

Depending on the implementation, retrieval may use semantic search, embeddings, vector databases, or other search techniques.

This describes the general architecture, not a verified list of components implemented in this notebook.

## Project Structure

```text
cloud-rag-conversational-assistant/
├── README.md
├── requirements.txt
├── .gitignore
└── notebooks/
    └── 01_cloud_rag_assistant.ipynb
```

## Notebook

### 01 — Cloud RAG Conversational Assistant

The notebook is based on an academic laboratory about creating a cloud-based RAG conversational agent.

The implementation details, cloud services, and execution workflow will be documented after reviewing the notebook source code.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ngualteros/Cloud-RAG-Conversational-AI-Assistant.git
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Open the Notebook

```bash
jupyter notebook notebooks/01_cloud_rag_assistant.ipynb
```

### 5. Configure Cloud Services

Cloud authentication, required resources, environment variables, and additional dependencies must be configured according to the actual notebook implementation.

Do not store API keys, access tokens, or other credentials in the repository.

## Results

Implementation results and example outputs will be documented after reproducing and verifying the experiments.

## Future Improvements

Potential improvements include:

- Documenting the complete RAG architecture.
- Adding a reproducible environment configuration.
- Evaluating retrieval quality and answer relevance.
- Introducing automated tests where applicable.
- Exploring deployment and monitoring options.
- Measuring response latency and resource usage.

These items represent possible future work rather than completed functionality.

## Academic Context

Master's in Artificial Intelligence  
Universidad Internacional de La Rioja (UNIR)

Course: Cloud Computing Tools for Artificial Intelligence

This repository is intended to document academic learning and hands-on experimentation. Original authorship and individual contributions should be clarified after reviewing the notebook.

## Author

**Nicolás Gualteros Pérez**

Systems Engineer | Master's in Artificial Intelligence

AI Engineering | Machine Learning | Generative AI | AI Automation

LinkedIn: https://www.linkedin.com/in/nicogualteros
