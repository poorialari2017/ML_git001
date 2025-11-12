# ai-learning-path (ML_git001) — AI Study Project

> *“Do your best (FYE).”*

A collaborative repository for studying and practicing core Machine Learning (ML) concepts through hands‑on notebooks. The project is organized as a learning path for a small team, with simple, reproducible examples and a clear Git workflow.

---

## Table of Contents
- [Overview](#overview)
- [Project Goals](#project-goals)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [Quick Start](#quick-start)
- [Running the Notebooks](#running-the-notebooks)
- [Recommended Git Workflow](#recommended-git-workflow)
- [Contributing](#contributing)
- [Project Members](#project-members)


---

## Overview
This repository contains Jupyter notebooks that explore essential ML topics such as data preparation, model training, evaluation, and visualization. It is intended for learners who prefer concise, well‑commented examples over large frameworks. The primary language is Python.

> **Why this repo?** To learn by doing: small, focused notebooks; minimal dependencies; clean results.

---

## Project Goals
- Build intuition for common ML workflows (preprocess → train → evaluate → iterate).
- Practice with widely used Python libraries in the ML ecosystem.
- Encourage good engineering habits (version control, clear commits, readable code).

---

## Repository Structure
- **`MLproj002/`** — Jupyter notebooks and related assets for the learning modules.
- **`MLproj003/`** — Soon...

---

## Prerequisites
- **Python** ≥ 3.9 (3.10+ recommended)
- **Git** (for version control)
- **Jupyter** (Notebook or Lab)
- **Editor**: VS Code or any IDE you like

### Common Python Packages
If you are starting from a clean environment, you will likely need:
- `numpy`, `pandas` — numerical computing & data wrangling
- `scikit-learn` — classic ML algorithms
- `matplotlib` — plotting

> *Note:* Exact dependencies depend on the notebooks you run; install as needed.

---

## Quick Start
```bash
# 1) Clone the repository
git clone https://github.com/Pooria-Lari/ML_git001.git
cd ML_git001

# 2) (Optional but recommended) Create a virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate

# 3) Install commonly used ML packages (adjust as needed)
pip install --upgrade pip
pip install numpy pandas scikit-learn matplotlib jupyter
```

---

## Running the Notebooks
```bash
# From the repository root
jupyter notebook   # or: jupyter lab
```
Open the notebooks inside `MLproj002/`, run cells top‑to‑bottom, and read the inline comments for guidance.

---

## Recommended Git Workflow
The project favors a simple, clear workflow:

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

> Motto: *Do your best (FYE).*

---

### Acknowledgments
- The open‑source Python and ML community for tools and tutorials that inspire practical learning.

---

*Happy learning, and keep iterating!* 
