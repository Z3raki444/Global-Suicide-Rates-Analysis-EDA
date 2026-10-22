# Global Suicide Rates — Exploratory Data Analysis

A descriptive Python/Jupyter analysis of historical suicide-rate records across countries, years, age groups, sex categories, and economic indicators.

> **Scope:** This is an exploratory analysis of the included dataset, not a global census, predictive risk model, or causal study. Aggregated patterns cannot describe any individual's situation.

## Project overview

The notebook explores:
- Changes in recorded suicide rates across years
- Patterns across sex and age groups
- Country comparisons using **rates per 100,000** versus absolute counts
- Relationship between per-capita GDP and recorded rates
- Distributional patterns and correlations

## Stack

Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.

## Reproduce the analysis

```bash
git clone https://github.com/Z3raki444/Global-Suicide-Rates-Analysis-EDA.git
cd Global-Suicide-Rates-Analysis-EDA
python -m pip install -r requirements.txt
jupyter notebook "Notenook.ipynb"
```

The committed notebook is named `Notenook.ipynb` (including the original spelling). Open and run it from the repository root so the CSV files resolve correctly. Inputs include `master.csv`; `Final_data.csv` contains an analysis-ready dataset. Consult notebook cells for preprocessing and derived variables.

## Selected visualizations

| Question | Result |
| --- | --- |
| How do recorded rates change over time? | [Historical trend](Plots/Global%20trend%20of%20sucide%20rate%20per%20100k%20over%20years.png) |
| Do male and female rates differ over time? | [Sex-based trends](Plots/Trend%20of%20Sucide%20rates%20per%20100k%20by%20sex%20Over%20years.png) |
| What role does age group play? | [Age-based trends](Plots/Trend%20of%20suicides%20rate%20per%20100k%20by%20age%20group%20over%20years.png) |
| Which countries have the highest recorded rates? | [Top 10 by average rate](Plots/top%2010%20countries%20by%20average%20suicide%20rate.png) |
| How do GDP and rates compare? | [GDP per capita versus rates](Plots/Gdp%20per%20capita%20vs%20suicide%20rate.png) |

Additional plots are in [`Plots/`](Plots/).

## Data quality and interpretation

- **Counts are not rates.** Cross-country comparisons should use population-normalized rates when appropriate.
- Recording practices, underreporting, age categorization, and coverage differ between countries and years.
- Missing economic data may affect the correlations.
- This is ecological, observational analysis. Associations are not evidence that GDP, age, or sex cause an outcome at the individual level.

**Dataset attribution:** Before presenting results as externally sourced research, add the original dataset publisher, URL, version, license, and collection date. This information is not verified in this repository.

## Repository files

```text
Notenook.ipynb    Analysis notebook
master.csv        Source data used by the notebook
Final_data.csv    Processed data snapshot
Plots/            Exported visualizations
Result.txt        Saved notes/results
requirements.txt  Python packages
```

## Validation

A lightweight GitHub Actions workflow verifies that the notebook is valid JSON and that the expected analysis files exist. It does **not** rerun every notebook cell or certify the scientific conclusions.
