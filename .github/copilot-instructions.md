# Copilot Instructions for ML_git001

## Project Overview
This repository is a collaborative machine learning workspace, primarily in Persian, with contributions from multiple members. It is organized for educational and experimental purposes, focusing on hands-on learning with real datasets and practical notebooks.

## Structure & Conventions
- **Data:** All datasets are under `MLproj002/Pooria/00 DATA/` (e.g., `Churn_Modelling.csv`, `titanic.csv`).
- **Notebooks:** Jupyter notebooks are organized by topic and method under `MLproj002/Pooria/01 Preprocessing/` and `MLproj002/Pooria/02 Classification/`, and `MLproj002/Reza/`.
  - Naming: Notebooks use a `00`, `01`, etc. prefix for ordering and clarity.
  - Subfolders group notebooks by library (e.g., `Pandas`, `Matplotlib`) or ML method (e.g., `Regression`, `KNN`).
- **No central Python package or module structure**: This is a collection of independent notebooks and scripts, not a deployable package.

## Developer Workflows
- **No build step required.**
- **Run and edit notebooks directly in Jupyter or VS Code.**
- **Version control:**
  - Use standard Git commands (`git status`, `git add`, `git commit`, `git push`).
  - Commit messages should be concise and meaningful (see README for examples).
- **Data files are not to be modified by scripts.** Treat all CSVs as read-only.

## Patterns & Practices
- **Notebook-centric development:**
  - Each notebook is self-contained. Avoid cross-notebook imports.
  - Use relative paths to access data (e.g., `../00 DATA/titanic.csv`).
  - Document code in both Persian and English where possible.
- **No custom testing or CI/CD.**
- **No requirements.txt or environment.yml:**
  - Assume a standard Python ML stack (numpy, pandas, matplotlib, scikit-learn, etc.).
  - If a notebook needs a special package, install it in the first cell with `!pip install ...`.

## Integration & External Dependencies
- **No external APIs or services integrated.**
- **All data is local.**

## Examples
- To preprocess data: see `MLproj002/Pooria/01 Preprocessing/Pandas/00 pandas doc1.ipynb`.
- For classification: see `MLproj002/Pooria/02 Classification/KNN/00 KNN doc1.ipynb`.

## Summary
- Focus on clear, well-documented, self-contained notebooks.
- Use Git for version control.
- No build, test, or deployment automation.
- Keep all data and code local and organized by topic.

---
If you are unsure about a workflow or convention, check the README or look for similar patterns in existing notebooks.
