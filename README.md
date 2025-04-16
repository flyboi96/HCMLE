![Python 3.11](https://img.shields.io/badge/python-3.11-blue)

# 🧠 Human-Centered Machine Learning Engineer (HCMLE)

Welcome to my self-guided journey toward becoming a **Human-Centered Machine Learning Engineer** — a role that blends technical excellence, responsible AI design, and real-world usability.

This repository is structured into focused learning "blocks," each with Jupyter notebooks, hands-on projects, and curated readings. The goal is to build deep technical understanding *and* the human-centered thinking needed to design useful, ethical, and interpretable ML systems.

---

## 🗂️ Project Structure

| Path                      | Description                                      |
|---------------------------|--------------------------------------------------|
| `Block1/`                | Python fundamentals and environment setup        |
| `Block2/`                | Data manipulation with Pandas                    |
| `environment.yml`        | Reproducible Conda environment                   |
| `HCMLE.code-workspace`   | VS Code workspace for auto-loading settings      |
| `README.md`              | Main project overview and setup instructions     |
| `.gitignore`             | Ignore notebooks, data, and system clutter       |

---

## 🧠 Blocks Overview

| Block | Focus                                      | Status        |
|-------|--------------------------------------------|---------------|
| 1     | Python Fundamentals & Environment Setup     | ✅ Completed   |
| 2     | Data Manipulation with Pandas               | 🚧 In Progress |
| 3     | Visualization and Exploratory Analysis      | 🔜 Upcoming    |
| 4     | Human-AI Interaction & Interpretability     | 🔜 Upcoming    |
| 5+    | Modeling, UX, Prototyping, Ethics           | 🔜 Upcoming    |

Each block includes:
- 📓 `notebooks/` – clean and commented Jupyter notebooks  
- 📚 `articles/` – optional readings or references  
- 📊 `data/` – sample datasets (if applicable)  
- 📝 `README.md` – block-specific goals and progress  

---

## ⚙️ Setup Instructions

To run this project locally with **Jupyter + Conda + VS Code**:

### 🔧 1. Clone the repository

```bash
git clone https://github.com/flyboi96/HCMLE.git
cd HCMLE
```

### 🧪 2. Create and activate the environment

Make sure you have [Anaconda](https://www.anaconda.com/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.

```bash
conda env create -f environment.yml
conda activate hcmle-env
```

### 💻 3. Open in VS Code

To launch the project with the correct kernel, folders, and settings:

```bash
code HCMLE.code-workspace
```

> Make sure you have the Python and Jupyter extensions installed in VS Code.

### 🧹 4. Optional: Clean and update the environment

If you add new packages:

```bash
conda env update -f environment.yml --prune
```

To export your environment:

```bash
conda env export --from-history > environment.yml
```

---

## 📈 Progress Tracking

I’m using a [GitHub Project Board](https://github.com/flyboi96/HCMLE/projects) and Issues to track tasks and milestones for each block. This keeps everything visible, organized, and reviewable over time.

---

## 🧰 Tools Used

- Python 3.11
- Pandas, NumPy, Matplotlib, Seaborn
- JupyterLab & VS Code Notebooks
- Git, GitHub, Conda
- Markdown, GitHub Project Boards

---

## 📚 Sample Resources

- *Python Data Science Handbook* by Jake VanderPlas  
- *Designing with the Mind in Mind* by Jeff Johnson  
- Real-world datasets (e.g., Titanic, Iris, UCI ML Repository)

---

## 📝 License

This project is open-source under the MIT License. You’re welcome to explore, fork, or use it as inspiration for your own learning path.
