# Unicorn Companies — EDA & Data Structuring

View full project walkthrough:
https://alfredrico.github.io/Unicorn-Company-Analysis-EDA-Structuring/

---

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

Run locally using UV:

```bash
uv sync
uv run jupyter lab
```

---

## Project Structure

```
unicorn_pt2/
├── data/Unicorn_Companies.csv
├── unicorn_analysis.ipynb
├── pyproject.toml
├── uv.lock
└── README.md
```

---

## Data Source

https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies

---

## Ecosystem

* Portfolio webpage → Project hub and navigation: https://alfredrico.github.io/
* Project page (HTML) → walkthrough and interpretation
* Notebook → full analysis
* GitHub → reproducibility
