# AI Learning Path (ML_git001) — AI Study Project

> *“Do your best (FYE).”*

A collaborative repository for studying and practicing core **Artificial Intelligence** topics — from classic Machine Learning (ML) to **Deep Learning (DL)**, **Computer Vision (CV)**, **Natural Language Processing (NLP)**, **Reinforcement Learning (RL)**, and **Generative AI** — using hands‑on notebooks and a clean Git workflow.

---

## Table of Contents
- [Overview](#overview)
- [Project Goals](#project-goals)
- [Repository Structure & Roadmap](#repository-structure--roadmap)
- [Prerequisites](#prerequisites)
- [Quick Start](#quick-start)
- [Running the Notebooks](#running-the-notebooks)
- [Recommended Git Workflow](#recommended-git-workflow)
- [Contributing](#contributing)
- [Project Members](#project-members)

---

## Overview
This repository contains Jupyter notebooks that explore essential AI topics with concise, well‑commented examples. The focus is on learning by doing, with minimal dependencies and clear results.

> **Why this repo?** Small, focused notebooks; minimal setup; reproducible outcomes.

---

## Project Goals
- Build intuition for common AI/ML workflows (preprocess → train → evaluate → iterate).
- Cover a broad scope: ML (tabular), DL (neural nets), CV, NLP, RL (basics), and Generative AI.
- Encourage good engineering habits (version control, meaningful commits, readable code, lightweight dependencies).

---

## Repository Structure & Roadmap
**Current**
- **`MLproj002/`** — Jupyter notebooks and related assets for learning modules (ML focus).
- **`MLproj003/`** — *Planned/coming soon.*

**Planned Modules (to be added progressively)**
- **`ai/ml/`** — classic ML (scikit‑learn, pipelines, metrics)
- **`ai/dl/`** — deep learning (PyTorch or TensorFlow/Keras)
- **`ai/cv/`** — computer vision (OpenCV, transforms, CNNs)
- **`ai/nlp/`** — natural language processing (tokenization, embeddings, Transformers)
- **`ai/rl/`** — reinforcement learning (intro, basic algorithms)
- **`ai/genai/`** — generative models (LLMs, diffusion — optional)

*(Additional folders like `utils/`, `data/`, and `docs/` may be added as the project grows.)*

---

## Prerequisites
- **Python** ≥ 3.9 (3.10+ recommended)
- **Git** (for version control)
- **Jupyter** (Notebook or Lab)
- **Editor**: VS Code or any IDE you like

### Common Python Packages
**Core (for ML & general work):**
- `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `jupyter`

**Deep Learning (choose a stack):**
- **PyTorch:** `torch`, `torchvision`
- **TensorFlow/Keras:** `tensorflow`, `keras`

**Computer Vision:** `opencv-python`, `scikit-image`, `Pillow`

**NLP:** `nltk`, `spacy`, `transformers`, `datasets`

**RL (optional):** `gymnasium`, `stable-baselines3`

**GenAI (optional):** `transformers`, `diffusers`

> *Note:* Install packages as needed depending on the modules you run.

---

## Quick Start
```bash
# 1) Clone the repository (after rename)
git clone https://github.com/Pooria-Lari/ai-learning-path.git
cd ai-learning-path

# If the repository hasn't been renamed yet, use the old URL:
# git clone https://github.com/Pooria-Lari/ML_git001.git
# cd ML_git001

# 2) (Optional but recommended) Create a virtual environment
python -m venv .venv
# Windows (PowerShell): .venv/Scripts/Activate.ps1
# Windows (cmd.exe): .venv/Scripts/activate.bat
# macOS/Linux: source .venv/bin/activate

# 3) Install core packages (adjust as needed)
pip install --upgrade pip
pip install numpy pandas scikit-learn matplotlib jupyter

# 4) (Optional) Install extras by module, e.g. for DL + CV
# PyTorch stack OR TensorFlow/Keras
# pip install torch torchvision
# pip install tensorflow keras
# CV, NLP, RL, GenAI (install as needed)
# pip install opencv-python scikit-image Pillow
# pip install nltk spacy transformers datasets
# pip install gymnasium stable-baselines3
# pip install diffusers
```

---

## Running the Notebooks
```bash
# From the repository root
jupyter notebook   # or: jupyter lab
```
Open notebooks inside `MLproj002/` (current) or future `ai/*/` module folders as they are added. Run cells top‑to‑bottom and read inline comments for guidance.

---

## Recommended Git Workflow
A simple, clear workflow:

```bash
# Check your status
git status

# Stage changes
git add <modified_file_or_folder>

# Commit with a meaningful message
git commit -m "Describe what changed and why"

# Push your work
git push
```

For larger changes, consider feature branches:
```bash
git checkout -b feature/<short-topic>
# ... make changes ...
git push -u origin feature/<short-topic>
```

Commit message tips:
- Use the imperative mood (e.g., "Add preprocessing step", "Fix accuracy calculation").
- Keep it concise; include *why* when it helps future readers.

---

## Contributing
1. Open an issue or discussion for significant changes.
2. Use small, focused pull requests with clear descriptions and before/after notes if relevant.
3. Keep notebooks tidy: remove unnecessary outputs, prefer deterministic seeds when possible.

---

## Project Members
- **Pooria Lari** — Member #1
- **Reza Sibil** — Member #2
- **Ayda AZ** — Member #3

> *Do your best (FYE).*

---

*Happy learning, and keep iterating!* 🚀
