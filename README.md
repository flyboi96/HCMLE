![Python 3.11](https://img.shields.io/badge/python-3.11-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

# Human-Centered Machine Learning Engineer (HCMLE)

This is a curated, self-directed journey toward becoming a **Human-Centered Machine Learning Engineer** — a role at the intersection of data science, human factors, and responsible AI. The focus is on developing robust technical skills *and* human-centered intuition for building ML systems that are usable, interpretable, and ethically sound.

This repository is structured into focused learning "blocks," each with Jupyter notebooks, hands-on projects, and curated readings. The goal is to build deep technical understanding *and* the human-centered thinking needed to design useful, ethical, and interpretable ML systems.

---


## Project Structure

| Path                      | Description                                      |
|---------------------------|--------------------------------------------------|
| `Block1/`                 | Python fundamentals and environment setup        |
| `Block2/`                 | Data manipulation with Pandas                    |
| `block3_intro_to_ml/`     | Intro to Machine Learning: Regression & Classification |
| `block4_human_ai/`        | Human-AI Interaction & Interpretability          |
| `block5_mini_project/`        | Mini ML Projects, Modeling, UX, Prototyping, Ethics |
| `block6_intro_to_deep_learning/`     | Neural networks and deep learning fundamentals |
| `block7_deep_learning_tabular_data/`     | Deep learning with tabular data and embedding models |
| `block8_data_visualization/`     | Communicating ML insights through Python visualization and design |
| `block9_human_centered_design/`     | Fundamentals of UX and human-centered design for ML solutions |
| `block12_XAI/`             | Explainable AI techniques: SHAP, LIME, PDP |
| `environment.yml`         | Reproducible Conda environment                   |
| `HCMLE.code-workspace`    | VS Code workspace for auto-loading settings      |
| `README.md`               | Project goals, learning blocks, and setup instructions |
| `.gitignore`              | Ignore notebooks, data, and system clutter       |

---

## Blocks Overview

| Block | Focus                                               | Status        |
|-------|-----------------------------------------------------|---------------|
| 1     | Python Fundamentals & Environment Setup              | Completed   |
| 2     | Data Manipulation with Pandas                        | Completed   |
| 3     | Intro to Machine Learning: Regression & Classification | Completed   |
| 4     | Human-AI Interaction & Interpretability              | Completed   |
| 5    | Mini ML Project                                       | Completed   |
| 6     | Introduction to Deep Learning                        | Completed   |
| 7     | Deep Learning for NLP or Tabular Data                | Completed   |
| 8     | Data Visualization & Communication                   | Completed     |
| 9     | Human-Centered Design Fundamentals                   | In Progress     |
| 12    | Explainable AI Techniques                         | In Progress     |

Each block includes:
- `notebooks/` – clean and commented Jupyter notebooks  
- `data/` – sample datasets (if applicable)  
- `README.md` – block-specific goals and progress  
- `model_card.md` – model transparency summary  
- `project_schedule.md` – daily task plan for hands-on blocks

---

## Setup Instructions

To run this project locally with **Jupyter + Conda + VS Code**:

### 1. Clone the repository

```bash
git clone https://github.com/flyboi96/HCMLE.git
cd HCMLE
```

### 2. Create and activate the environment

Make sure you have [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.

```bash
conda env create -f environment.yml
conda activate hcmle-env
```

### 3. Open in VS Code

To launch the project with the correct kernel, folders, and settings:

```bash
code HCMLE.code-workspace
```

> Make sure you have the Python and Jupyter extensions installed in VS Code.

### 4. Optional: Clean and update the environment

If you add new packages:

```bash
conda env update -f environment.yml --prune
```

To export your environment:

```bash
conda env export --from-history > environment.yml
```

---

## Progress Tracking

I’m using a [GitHub Project Board](https://github.com/flyboi96/HCMLE/projects) and Issues to track tasks and milestones for each block. This keeps everything visible, organized, and reviewable over time.

---

## Tools Used

- Python 3.11
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn
- JupyterLab & VS Code Notebooks
- Git, GitHub, Conda
- Markdown, GitHub Project Boards

---

## Sample Resources

- *Python Data Science Handbook* by Jake VanderPlas  
- *Designing with the Mind in Mind* by Jeff Johnson  
- Real-world datasets (e.g., Titanic, Iris, UCI ML Repository)  
- *People + AI Guidebook* by Google PAIR  
- *Storytelling with Data* by Cole Nussbaumer Knaflic  
- *Interpretable Machine Learning* by Christoph Molnar
- Kaggle & DataCamp tutorials on Explainability (LIME, SHAP)

---

## License

This project is open-source under the MIT License.
Feel free to fork, adapt, or use this project as inspiration for your own ML learning journey.
