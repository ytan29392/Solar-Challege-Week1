# Solar Data Discovery – Week 0 (10 Academy)

## Overview

This project is part of the 10 Academy Artificial Intelligence Mastery Program (Week 0 Challenge). The objective is to explore solar energy datasets from three West African countries: **Togo**, **Benin**, and **Sierra Leone**. The challenge is split into two main tasks:

- **Challenge 1**: Environment setup, repository organization, and CI pipeline configuration
- **Challenge 2**: Data profiling, cleaning, and exploratory data analysis (EDA) for each country’s dataset

---

## Challenge 1: Environment Setup & CI/CD

### Goals
- Set up a structured Python project with Git and GitHub
- Install required libraries and manage environment
- Create a meaningful folder structure
- Configure GitHub Actions for CI

### What’s Included
- `requirements.txt`: Project dependencies
- `.gitignore`: Ignores data, virtual environment, and logs
- `.github/workflows/ci.yml`: GitHub Actions CI pipeline
- `notebooks/`: Folder for analysis notebooks
- `scripts/`: Utility scripts (if needed)

---

## Challenge 2: Data Profiling, Cleaning & EDA

### Goals
- Load and inspect each dataset (Benin, Togo, Sierra Leone)
- Handle missing values and outliers
- Perform exploratory data analysis (EDA)
- Save a cleaned version of each dataset for comparison

### Key Steps
- Load data using `pandas`
- Analyze summary statistics and missing values
- Detect and treat outliers using **Z-score**
- Convert timestamps and analyze time series trends
- Explore cleaning impacts (`ModA` / `ModB` vs `Cleaning`)
- Visualize distributions, correlations, and bivariate relationships
- Export cleaned data to the `data/` folder

### Outputs
- `notebooks/togo_eda.ipynb`
- `notebooks/benin_eda.ipynb`
- `notebooks/sierra_leone_eda.ipynb`
- Cleaned CSVs (not committed to GitHub):
  - `data/togo_clean.csv`
  - `data/benin_clean.csv`
  - `data/sierra_leone_clean.csv`

---