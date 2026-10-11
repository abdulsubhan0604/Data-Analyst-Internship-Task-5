# Task 5 — Exploratory Data Analysis (EDA): Titanic Dataset

## Objective
Explore the Titanic passenger dataset using Python, Pandas, Matplotlib, and Seaborn. Identify data-quality issues, distributions, relationships, and potential anomalies.

## Files
- `Task5_Titanic_EDA.ipynb` — complete notebook with code, charts, observations, and interview answers.
- `EDA_Findings_Report.pdf` — concise report structure and interpretation of the analysis.
- `requirements.txt` — Python packages needed.
- `titanic.csv` — created automatically when you run the notebook for the first time (internet required for initial download).

## How to run
1. Install Python 3.10+ and Jupyter Notebook, or use Google Colab.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Task5_Titanic_EDA.ipynb`.
4. Run all cells from top to bottom. The notebook downloads the public CSV from the seaborn-data GitHub repository if `titanic.csv` is not present.
5. Review the generated outputs and use the figures/metrics from your run in your final submission.

## Main analyses
- Dataset structure and descriptive statistics (`shape`, `info`, `describe`, `value_counts`)
- Missing values and duplicate rows
- Histograms, count plots, and a fare boxplot
- Survival rates by sex, passenger class, and age
- Correlation heatmap and pairplot
- Grouped survival table and conclusion

## Important interpretation note
This is an exploratory analysis. Relationships are associations, not proof of causation. Outliers should be investigated rather than automatically removed. Missing values should be handled based on the downstream objective.

## GitHub submission
Create a new repository named `task-5-titanic-eda`, add the notebook, PDF report, README, and requirements file. After running the notebook, optionally commit the downloaded `titanic.csv` and exported charts if your internship submission expects the dataset and screenshots.
