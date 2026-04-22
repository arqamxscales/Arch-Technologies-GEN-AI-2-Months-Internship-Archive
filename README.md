# Generative AI Tasks Portfolio (Tasks 1–4)

This repository contains my Month 2 deliverables for Tasks 1 to 4, including:
- Python application work
- QLoRA/Unsloth experimentation notebooks
- RAG and speech-to-reasoning notebook pipelines
- Final report documents

## Repository Structure

- **Task 1 & 2/**
  - **Mohammad Arqam Javed _ Tasks 1 & 2/**
    - **1/**
      - `app.py`
      - `README.md`
      - `requirements.txt`
    - **2/**
      - `medical_qlora_unsloth_colab.ipynb`
      - `README.md`
      - `requirements_colab.txt`

- **Task 3 & 4/**
  - **TASK 3-4/**
    - `Mohammad_Arqam_Javed_GenAI_Month2_Report_Template.md`
    - `Mohammad_Arqam_Javed_GenerativeAI_Month2_Task3_Task4_Report.md`
    - `Mohammad_Arqam_Javed_GenerativeAI_Month2_Task3_Task4_Word_Ready.md`
    - `Task3_RAG_Unsloth_4bit.ipynb`
    - `Task4_Speech_to_Reasoning_Whisper_Unsloth.ipynb`

## Highlights

- Clear separation of task-wise deliverables
- Reproducible dependency files for Python and Colab workflows
- Notebook-driven experimentation for model fine-tuning and reasoning pipelines
- Consolidated reporting assets for formal submission

## Getting Started

### 1) Clone the repository

```bash
git clone <your-repository-url>
cd "TASKS (1 2 3 4)"
```

### 2) Run Task 1 app (local)

```bash
cd "Task 1 & 2/Mohammad Arqam Javed _ Tasks 1 & 2/1"
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

### 3) Run notebooks

Open the notebooks in Jupyter/Colab and install required dependencies from:
- `requirements_colab.txt` (for Task 2 notebook)
- any additional packages referenced inside notebooks

## Security and Git Hygiene

A root `.gitignore` is included to prevent committing:
- environment files (`.env`, `.env.*`, `*.env`)
- common API/secret credential files
- local caches, logs, and editor artifacts

## Author

**Mohammad Arqam Javed**

---
If this repository is used for review/submission, please use the latest commit on the default branch.
