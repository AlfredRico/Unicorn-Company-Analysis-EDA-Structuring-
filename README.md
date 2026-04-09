# Unicorn Companies — EDA & Data Structuring


## Overview

This project analyzes unicorn companies (valued at $1B+) with a focus on structuring time-based data to understand how companies evolve from founding to unicorn status.

---

## Key Insights

* Unicorn formation is concentrated between 2009 and 2016, indicating a period of accelerated startup growth rather than a consistent long-term trend
* Newer companies appear to reach unicorn status faster, though this is likely influenced by time-based bias rather than true acceleration
* Unicorn formation occurs steadily over time without strong seasonal patterns, suggesting timing alone is not a meaningful driver
* Average valuation trends are sensitive to outliers, indicating that median-based analysis would provide a more stable view

---

## Reproducibility

This project uses **UV** for fast, deterministic environment management.

### 🔧 Prerequisites

Install UV (official guide):  
https://docs.astral.sh/uv/getting-started/

---

### ▶️ Run Locally (Step-by-Step)

```bash
# 1. Clone the repository
git clone https://github.com/AlfredRico/Unicorn-Company-Analysis-EDA-Structuring.git
cd Unicorn-Company-Analysis-EDA-Structuring

# 2. Sync environment (installs Python + dependencies)
uv sync

# 3. Launch Jupyter Lab
uv run jupyter lab
```

---

### 📂 Open the Project

Once Jupyter Lab opens in your browser:

1. Navigate to the project root directory  
2. Open the notebook:

   ```
   unicorn_analysis.ipynb
   ```

3. Run all cells from top to bottom  

---

### 🧠 Notes

- The environment is fully defined by:
  - `pyproject.toml`
  - `uv.lock`
- No manual package installation is required  
- Results are fully reproducible across systems  

---


## Project Structure

```
unicorn_pt2/
├── data/Unicorn_Companies.csv
├── .gitignore
├── README.md
├── index.html
├── pyproject.toml
├── unicorn_analysis.ipynb
└── uv.lock
```

---

## Data Source

https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies

---

## Ecosystem

* Portfolio webpage → Project hub and navigation: https://alfredrico.github.io/
* GitHub → Project repositories featuring UV management for reproducibility: https://github.com/AlfredRico
