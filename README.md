# Task 1: Data Foundations — Titanic Dataset

**Intern:** Anchal Patel  
**Program:** DecodeLabs Data Science Internship  

---

## Overview

This project covers the foundational steps of a data science workflow using the classic Titanic dataset (891 passengers, 12 features).

1. **Data Collection & Understanding** — Loaded the dataset, explored shape, data types, and summary statistics.
2. **Data Cleaning & Preprocessing** — Filled missing `Age` values with the median, filled missing `Embarked` with the mode, and dropped columns with too many nulls or no analytical value (`Cabin`, `PassengerId`, `Name`, `Ticket`).
3. **Encoding** — Mapped `Sex` to binary (0/1) and `Embarked` to ordinal (0/1/2).
4. **Exploratory Data Analysis (EDA)** — Visualized survival rates by Sex, Passenger Class, Age distribution, and feature correlations.

## Key Findings

- Overall survival rate: **38.4%**
- Females survived at a significantly higher rate than males.
- 1st class passengers had the highest survival rate compared to 2nd and 3rd class.
- Younger passengers had a slightly better chance of survival.

## Dataset

- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- **File:** `train.csv` (891 rows × 12 columns)

## Files

| File | Description |
|------|-------------|
| `task1_notebook.ipynb` | Main notebook with code, outputs, and visualizations |
| `train.csv` | Titanic training dataset |
| `requirements.txt` | Python dependencies |

## How to Run

1. Install dependencies: `pip install -r requirements.txt`
2. Open `task1_notebook.ipynb` in Jupyter.
3. Run all cells (`Kernel → Restart & Run All`).
