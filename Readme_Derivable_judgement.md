# 🎯 Derivable Judgement

> A simple health-data analysis project that uses Python and statistics to compare groups, test hypotheses, and explain results in easy English.

[![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](Derivable_judgement.ipynb) [![Dataset](https://img.shields.io/badge/Dataset-CSV-blue?logo=filezilla)](Health_Dataset_CSV.csv) [![Watch Video](https://img.shields.io/badge/Video-Drive-red?logo=drive)](https://drive.google.com/file/d/1lqMx-kugiRe8OAzzct2R12iyIAX5ZAz1/view?usp=sharing)

---

## 📌 Table of Contents
- [Overview](#overview)
- [Project Files](#project-files)
- [Dataset Details](#dataset-details)
- [Tools & Technologies](#tools--technologies)
- [Project Structure](#project-structure)
- [Project Purpose](#project-purpose)
- [What the Notebook Does](#what-the-notebook-does)
- [Analysis Workflow](#analysis-workflow)
- [Key Results](#key-results)
- [How to Run](#how-to-run)
- [Conclusion](#conclusion)
- [Author](#author)

---

## Overview

This project explores a health dataset using basic statistical analysis.
The main notebook demonstrates how to use Python to:

- load and inspect data,
- form hypotheses,
- calculate confidence intervals,
- perform t-tests, chi-square tests, ANOVA,
- and measure correlation between health variables.

### Project Purpose

The purpose of this project is to learn how to apply statistics to real health data and to explain each result in simple English so that anyone can understand the outcomes.

The goal is to make the analysis easy to understand, especially for GitHub viewers.

---

## Project Files

- `Derivable_judgement.ipynb`
  - Main Jupyter Notebook with code, explanations, and results.
  - Contains statistical computations and interpretation in simple English.

- `Health_Dataset_CSV.csv`
  - CSV dataset used for analysis.
  - Includes health records such as age, BMI, smoking status, blood pressure, diabetes, and cholesterol.

- `Readme_Derivable_judgement.md`
  - This README file.
  - Explains the project and how to run it on GitHub.

---

## Dataset Details

The dataset includes health information for many individuals. Key fields are:

- `record_id` — unique identifier for each record
- `age_group` — age category like `18-25`, `26-35`, `36-45`, `46-60`, `60+`
- `age` — exact age
- `weight` — weight in kilograms
- `gender` — reported gender
- `region` — geographic region
- `smoking_status` — `Smoker`, `Non-Smoker`, or `Former Smoker`
- `exercise_frequency` — frequency of exercise
- `bmi` — body mass index
- `blood_pressure` — measured blood pressure
- `diabetes` — `True` or `False`
- `hypertension` — `True` or `False`
- `cholesterol_level` — cholesterol value
- `glucose_level` — glucose value
- `visit_date` — date of health visit

This dataset is good for comparing groups and checking relationships between health measures.

---

## Tools & Technologies

- Python
- Jupyter Notebook
- pandas
- NumPy
- SciPy
- statsmodels

---

## Project Structure

```text
Derivable_Judgement/
├── Derivable_judgement.ipynb
├── Health_Dataset_CSV.csv
└── Readme_Derivable_judgement.md
```

---

## What the Notebook Does

The notebook performs all main steps of the analysis:

1. Load and show the dataset.
2. Suggest hypotheses from the dataset.
3. Calculate confidence intervals for numeric data like weight.
4. Find critical values and p-values for test results.
5. Compare group means with t-tests and z-tests.
6. Test category relationships with chi-square.
7. Compare age groups with ANOVA.
8. Measure covariance and correlation for continuous variables.

---

## Analysis Workflow

The analysis is structured in a clear workflow:

- Start with data import and inspection.
- Define hypotheses about smoking, exercise, BMI, and disease.
- Estimate values using confidence intervals.
- Compare two groups using hypothesis tests.
- Use chi-square for categorical variables.
- Use ANOVA for more than two groups.
- Measure continuous relationships with correlation.
- Summarize results in plain language.

---

## Key Results

This notebook includes results such as:

- A confidence interval for mean weight.
- BMI comparison between smokers and non-smokers.
- A chi-square test of smoking status vs diabetes.
- ANOVA for age group disease rates.
- Correlation between age and BMI.

These findings help show whether the data supports or rejects the proposed hypotheses.

---

## How to Run

1. Open this folder in VS Code or Jupyter Notebook.
2. Make sure `Derivable_judgement.ipynb` and `Health_Dataset_CSV.csv` are in the same folder.
3. Install packages if needed:

```powershell
pip install pandas numpy scipy statsmodels
```

4. Open `Derivable_judgement.ipynb` in Jupyter.
5. Run cells from top to bottom.
6. Read the output and the English interpretation sections.

---

## Conclusion

This project is a simple and clear example of how to use statistics with health data.
It uses real analysis methods and explains results in a way that is easy to share on GitHub.

---

## Author

**Devanshi Bachhote**

