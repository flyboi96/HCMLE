# 📊 Block 2: Data Manipulation with Pandas

This block focused on exploring, cleaning, transforming, and summarizing real-world data using **Pandas** and **NumPy** — essential tools for every Human-Centered Machine Learning Engineer. Each session tackled real scenarios, from missing values to group-based analysis and visual exploration.

---

## 🧠 Learning Objectives

- Understand Series and DataFrame objects
- Slice, filter, and transform data with Pandas
- Group and aggregate using `.groupby()` and `.agg()`
- Detect and handle missing or inconsistent data
- Save clean, analysis-ready versions of datasets
- Visualize distributions and relationships with Seaborn

---

## 📚 Sessions Completed

| # | Session Title                          | Focus                                           | Status     |
|---|----------------------------------------|--------------------------------------------------|------------|
| 1 | Meet the Data                          | Load and explore Titanic & Iris datasets        | ✅ Complete |
| 2 | Slicing, Dicing, and Filtering         | Subsetting, logic filters, column creation      | ✅ Complete |
| 3 | Grouping and Summarizing               | Multi-level `groupby`, `.agg()` mini-challenges | ✅ Complete |
| 4 | Scrubbing the Mess                     | Missing values, duplicates, cleaning strategies | ✅ Complete |
| 5 | Quick and Dirty Visuals                | Initial distribution plots with Seaborn         | ✅ Complete |
| 6 | Visualizing Relationships              | Scatter plots, hue grouping, comparisons        | ✅ Complete |

---

## 📂 Folder Structure

| Path              | Description                                     |
|-------------------|-------------------------------------------------|
| `notebooks/`      | All exploration, EDA, and visualization work    |
| `data/`           | Raw and cleaned datasets (e.g., Titanic)        |
| `articles/`       | Annotated readings from Python DS Handbook      |
| `plots/`          | Saved visualizations from Sessions 5 and 6      |
| `cleaned_titanic.csv` | Final cleaned dataset (from Session 4)      |
| `iris_clean.csv`      | Cleaned Iris dataset (after simulation)     |

---

## 📝 Key Insights & Deliverables

- **Grouped summaries** revealed survival gaps by gender and class
- **Median imputation per `pclass`** preserved structure in `age`
- **Chained assignment warnings** avoided with best practices
- **Style formatting (`.style.background_gradient`)** improved readability
- **Visualizations** explored class, gender, and feature relationships and were exported to the `plots/` directory

---

## ✅ Status

**Block 2 is complete.**  
Deliverables have been saved, notebooks are cleaned, and all challenges have been documented.

---

## 📈 Example Visualization

![Survival by Class](plots/survival_by_class.png)

---

## 🔍 Visual Insight Preview

<a href="plots/survival_by_class.png">
  <img src="plots/survival_by_class.png" alt="Survival Plot" width="400"/>
</a>

> *Grouped survival rates by class and gender visualized using Seaborn*